---
05 October 2017

Re-examining the cases in Fig 19

junk_plates = [6466, 5059, 4072, 3969]
junk_fibers = [740, 906, 162, 788]
wvoffs = [200., 200., 200., 200.]
zabs = [2.8159, 2.4272, 3.3509, 2.9467]

See Notebook

---

Comparing ML on BOSS vs. Garnett16

---
High NHI, high confidence in ML and in G16
search path but not there otherwise..

71 cases

Many are proximate, but legit

4185   262 3.34463242067 3.25289165067 21.0995353666  0.29 -- DDLA
4235    46 3.05817934665 2.90826792016 21.2279068009  0.21 -- Double DLA
5027   920  2.1460055504 2.08165749295 21.0720525308  99.0 -- Almost Prox
5496   370 2.14984463137 2.03448017445  21.069207854  99.0 -- Legit; not quite prox
6151   560  2.6732948618 2.12596558122 21.0272373694  0.41 -- Might be beyond their path
6964   622 3.47079582444 3.37506338133 21.1436316334  99.0 -- Close to Prox

---
High NHI, high confidence in G16 but not in ML (to a dz=0.015 match)

Spot checking some of the 408
Quite a few with dz just bigger than 0.015
  166 within |dz|<0.05  -- See fig_boss_badz()
  242 not matched at all  -- See fig_boss_missing()
     :: Most are at z<2.5 and mainly z<2.15 with low S/N
Many have z~2.0 [SHOW redshifts]

|  6183 |   530 | 2.6358 |  2.068 | 21.0465 |            99.0 | BAL
|  6874 |   828 |  2.489 | 2.1682 | 21.3834 |            99.0 | Lots of strange flux; but strong metals
|  4532 |   720 | 2.7762 | 2.3778 | 21.8559 |            99.0 | Strong high ions; weak low; lots of flux
|  7057 |   612 | 3.7416 | 3.5283 | 21.2567 | 0.0815245334877 | Bad z; 3.46 [ML agrees]; pair of DLAs
|  7053 |   190 | 2.7356 | 2.2542 | 22.0805 |  0.314288563662 | JUNK  SHOW
|  6782 |   956 |   2.39 | 2.1875 | 22.4319 |  0.361323481856 | Low S/N; probably junk
|  4501 |   848 | 3.7387 | 2.9994 | 21.1716 |            99.0 | BAL; JUNK
|  3806 |   596 | 2.7434 | 2.4422 |  21.987 | 0.0330352676405 | No metals; Probably junk
|  3758 |   234 |  2.221 | 2.0233 | 21.7263 |            99.0 | Low S/N; legit, but z=2.033; Metals
|  4478 |   886 |   2.38 | 2.1956 | 21.4855 |            99.0 | Legit absorber; lower S/N; NHI lower
|  6396 |   583 |  3.997 | 3.7561 | 22.7261 |  0.637171095954 | Poor data reduction; but strong metals: 1.6A of SiII 1808!! SHOW
|  5780 |   594 | 2.6028 | 2.3845 | 22.1137 | 0.0778807591698 | Not 10^22; metals but z offset
|  4688 |   620 |  3.261 | 2.7995 | 21.8397 | 0.0198047127561 | Pair of DLAs; SHOW
|  4605 |   229 |    4.1 |  3.422 | 21.9409 | 0.0262005357642 | Junk; I think
|  5735 |    62 | 3.2944 | 2.9122 | 22.2046 |  0.192703208879 | Very low S/N; 
|  5769 |   963 |   3.65 | 3.5445 | 22.1422 |  0.743412783563 | BAL
|  5733 |   720 | 3.1361 | 2.9286 | 21.8652 | 0.0739559784676 | Junk data; metals at 2.932; Plausible
|  5768 |   826 | 2.3185 | 2.0132 | 21.5161 |            99.0 | Junk
|  5309 |   362 |  3.166 | 3.0266 | 22.2216 | 0.0309795133291 | Solid; ML offset dz
|  5315 |   820 | 2.5588 | 2.1033 | 21.7094 |            99.0 | Likely junk; SHOW?
|  4799 |   729 |  2.208 | 2.0767 | 22.2131 |            99.0 | z way off (metals); SHOW
|  6466 |   740 | 3.2766 | 2.8738 |  21.969 |  0.605782117821 | Bad data; SHOW
|  4876 |   782 | 3.1748 | 2.8159 | 21.3343 |            99.0 | Low S/N
|  6465 |   720 |  3.223 | 3.0408 | 21.0443 |            99.0 | SHOW (no data) 
|  6662 |   500 |   4.44 | 4.2527 | 22.0265 | 0.0156790503899 | Solid; z offset
|  7381 |    47 |  2.361 | 2.1754 | 22.6336 |            99.0 | Terrible S/N; SHOW
|  5345 |   358 | 2.4358 | 2.0841 | 22.2329 | 0.0398220278992 | SHOW
|  5349 |   740 | 3.4343 | 2.7431 | 21.6204 | 0.0295935076953 | ML redshift is better; NHI is lower?
|  7096 |   820 |  2.355 | 2.0995 | 21.8972 |            99.0 | Bad z; metals; Much lower NHI; SHOW
|  4685 |   294 | 2.4571 |  2.308 | 21.9306 | 0.0269106903241 | Double DLA; SHOW?; Lower S/N
|  5371 |   356 | 3.1171 | 2.8143 | 22.1463 | 0.0595217385783 | Very low S/N
|  5381 |   600 | 2.5928 | 2.2742 | 21.6751 |            99.0 | Very low S/N; possible
|  5386 |   637 |  2.571 | 2.3098 | 21.5656 | 0.0918123994767 | Solid (metals); SHOW
|  4697 |   782 | 2.6164 | 2.0926 | 21.9295 |            99.0 | SHOW; no metals; JUNK
|  6972 |   446 | 2.8347 | 2.5271 | 21.8907 | 0.0821391579335 | Low S/N; unlikely metals
|  4749 |   768 |  2.505 | 2.3825 | 21.4418 |            99.0 | Low S/N; no metals, but plausible
|  6972 |   982 | 2.3959 | 2.1457 | 21.6788 |            99.0 | z offset (metals) but good DLA; SHOW
|  7419 |   480 | 2.2435 | 2.1333 | 22.0818 | 0.0629752334232 | Very low S/N
|  3969 |   788 |  3.222 | 2.9467 | 21.7833 |  0.500152214751 | SHOW; residual flux; no metals
|  6482 |   308 |  2.301 | 2.0296 | 22.4095 |            99.0 | Ok (metals); HI seems unlikely (dust? fluxing?)
|  5986 |   876 |  3.105 | 2.7658 |  21.786 |  0.323217363599 | Plausible, but low S/N
|  6487 |   496 | 2.6715 | 2.2909 | 21.6172 | 0.0221304184627 | G16 better z; SHOW
|  5425 |   384 | 2.8725 | 2.5597 |  22.414 |            99.0 | SHOW; Double DLA; ML got neither!
|  6489 |   680 | 2.5656 | 2.0306 | 22.0494 |            99.0 | SHOW?; metals confirm, but NHI too high
|  7409 |   118 |   2.31 | 2.1079 |  22.074 |            99.0 | SHOW; z off, but metals
|  7406 |   236 | 2.9434 | 2.3557 | 21.9979 |  0.355243123185 | Low S/N; Junk; Show?
|  5868 |   896 | 3.2082 | 2.9464 | 21.1252 |            99.0 | Legit metals; probable; SHOW?
|  4863 |   276 |  2.888 | 2.3696 |  22.043 |  0.259377166398 | Absyml S/N; SHOW
|  4713 |   868 |  3.952 | 3.8515 | 21.8864 |  0.170008774997 | JUNK
|  5463 |    52 | 2.5241 | 2.3351 | 21.9619 |            99.0 | Metals; high NHI?; SHOW
|  6806 |   212 | 2.5933 | 2.3182 |  21.391 |            99.0 | JUNK; show
|  6048 |   548 | 4.1263 |  3.626 | 22.3902 |  0.330604755505 | Solid; SHOW
|  6730 |   936 |  2.698 | 2.6323 | 21.8337 |            99.0 | BAL
|  3928 |   439 |  3.781 |  3.491 | 22.4707 |  0.099757517588 | Low S/N; improbable
|  4072 |   162 |  3.786 | 3.3509 | 22.3474 |  0.043805664289 | Double DLA (z=3.28, 3.40; ML got it); SHOW 
|  5202 |   564 |  2.386 | 2.1415 | 21.8437 |            99.0 | SHOW; metals but offset (z=2.17)
|  4983 |   492 |  2.517 |  2.327 | 22.7626 |            99.0 | Super low S/N; SHOW
|  4983 |   272 | 2.6552 | 2.2473 | 22.4977 |  0.256057218267 | Low S/N; metals nearby
|  4194 |   342 | 2.6539 | 2.3327 | 22.2515 |  0.113971946488 | Low S/N; no metals; SHOW?
|  4198 |   278 | 3.0011 | 2.7773 | 22.3873 | 0.0942441028661 | Low S/N; legit metals; SHOW?
|  5059 |   645 | 2.6926 | 2.4217 | 21.8377 | 0.0279153643927 | JUNK (I think); SHOW
|  5059 |   906 |  2.556 | 2.4272 | 22.0779 | 0.0280890265759 | SHOW; junk; maybe weak CIV
|  6114 |   266 |  3.091 | 3.0796 | 22.1573 | 0.0153139960629 | Solid
|  4210 |   906 | 2.9692 | 2.3656 | 21.9607 |  0.204532542009 | v. low S/N
|  6165 |   922 | 2.6689 | 2.4053 | 21.6923 |            99.0 | Double DLA; SHOW 
|  6124 |   444 | 2.3397 |  2.114 |  21.401 |            99.0 | Low S/N
|  4208 |   954 | 2.9936 | 2.7469 | 21.8056 | 0.0286844481592 | Double but somewhat legit; SHOW


---
High NHI, high confidence in G16 matched to ML (dz=0.015 match)

Higher S/N cases show good agreement

Lower S/N at z~2 have ML with *much* lower NHI

Many of the bigger differences are close to Lya emission
where G16 should perform better (ML not trained for that)

|  7237 |   979 |  2.558 |  0.7334 | 2.1956 | 22.1962 | 20.5570709517 | No clue
|  4500 |   286 |   2.24 |  1.8113 | 2.2028 | 22.2074 | 20.9861275418 | Proximate
|  6701 |   768 | 2.5005 |  8.2437 | 2.0677 | 21.8161 | 21.1994721515 | Pair of DLAs
|  6829 |   688 | 2.5003 | 10.0003 | 2.0233 | 21.8621 | 20.6343630127 | G16 looks better
|  6139 |   598 | 2.1617 |  6.0428 | 2.0807 | 21.8056 | 21.3372004439 | G16 probably better
|  4374 |   401 |  2.479 |  4.2521 | 2.3393 | 22.2688 | 21.7156481506 | Prox; G16 better
|  7137 |   194 |  2.515 |  9.7582 | 2.2095 | 22.1286 | 21.6877189841 | ML is better




