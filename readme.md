Pneumonia associada à ventilação mecânica - Análise de fatores de risco
================

## As análises abaixo relacionam as variáveis com o risco de desenvolvimento de PAV.

    ## [1] "A tabela abaixo diz respeito a análise quanto ao sexo:"

    ##            
    ## d           Não PAV  PAV
    ##   Feminino      771   43
    ##   Masculino    1045   68
    ## 
    ##  Pearson's Chi-squared test with Yates' continuity correction
    ## 
    ## data:  Tabela
    ## X-squared = 0.44987, df = 1, p-value = 0.5024
    ## 
    ## $data
    ##            
    ## d           Não PAV PAV Total
    ##   Feminino      771  43   814
    ##   Masculino    1045  68  1113
    ##   Total        1816 111  1927
    ## 
    ## $measure
    ##            odds ratio with 95% C.I.
    ## d           estimate     lower    upper
    ##   Feminino  1.000000        NA       NA
    ##   Masculino 1.166752 0.7875533 1.728531
    ## 
    ## $p.value
    ##            two-sided
    ## d           midp.exact fisher.exact chi.square
    ##   Feminino          NA           NA         NA
    ##   Masculino  0.4449423    0.4888029  0.4414822
    ## 
    ## $correction
    ## [1] FALSE
    ## 
    ## attr(,"method")
    ## [1] "Unconditional MLE & normal approximation (Wald) CI"

    ##  Feminino Masculino 
    ##       814      1113

    ## [1] "A tabela abaixo diz respeito a análise quanto ao tempo de VM:"

    ##                  
    ## d                 Não PAV  PAV
    ##   Até 10 dias        1312   12
    ##   Mais de 10 dias     504   99
    ## 
    ##  Pearson's Chi-squared test with Yates' continuity correction
    ## 
    ## data:  Tabela
    ## X-squared = 180.79, df = 1, p-value < 2.2e-16
    ## 
    ## $data
    ##                  
    ## d                 Não PAV PAV Total
    ##   Até 10 dias        1312  12  1324
    ##   Mais de 10 dias     504  99   603
    ##   Total              1816 111  1927
    ## 
    ## $measure
    ##                  odds ratio with 95% C.I.
    ## d                 estimate   lower    upper
    ##   Até 10 dias      1.00000      NA       NA
    ##   Mais de 10 dias 21.47619 11.6943 39.44032
    ## 
    ## $p.value
    ##                  two-sided
    ## d                 midp.exact fisher.exact   chi.square
    ##   Até 10 dias             NA           NA           NA
    ##   Mais de 10 dias          0 2.446077e-39 7.787963e-42
    ## 
    ## $correction
    ## [1] FALSE
    ## 
    ## attr(,"method")
    ## [1] "Unconditional MLE & normal approximation (Wald) CI"

    ##     Até 10 dias Mais de 10 dias 
    ##            1324             603

    ## [1] "A tabela abaixo diz respeito a análise quanto a idade (Considera-se idosos pacientes com 60 ou mais anos.):"

    ##             
    ## d            Não PAV  PAV
    ##   1Não Idoso     620   27
    ##   2Idoso        1196   84
    ## 
    ##  Pearson's Chi-squared test with Yates' continuity correction
    ## 
    ## data:  Tabela
    ## X-squared = 4.0905, df = 1, p-value = 0.04313
    ## 
    ## $data
    ##             
    ## d            Não PAV PAV Total
    ##   1Não Idoso     620  27   647
    ##   2Idoso        1196  84  1280
    ##   Total         1816 111  1927
    ## 
    ## $measure
    ##             odds ratio with 95% C.I.
    ## d            estimate    lower    upper
    ##   1Não Idoso 1.000000       NA       NA
    ##   2Idoso     1.612783 1.034219 2.515009
    ## 
    ## $p.value
    ##             two-sided
    ## d            midp.exact fisher.exact chi.square
    ##   1Não Idoso         NA           NA         NA
    ##   2Idoso     0.03099328   0.03799362 0.03350205
    ## 
    ## $correction
    ## [1] FALSE
    ## 
    ## attr(,"method")
    ## [1] "Unconditional MLE & normal approximation (Wald) CI"

    ## 1Não Idoso     2Idoso 
    ##        647       1280

    ## [1] "A tabela abaixo diz respeito a análise quanto a infecção por Covid-19:"

    ##                
    ## d               Não PAV  PAV
    ##   1Não Covid-19    1727   89
    ##   2Covid-19          89   22
    ## 
    ##  Pearson's Chi-squared test with Yates' continuity correction
    ## 
    ## data:  Tabela
    ## X-squared = 40.186, df = 1, p-value = 2.309e-10
    ## 
    ## $data
    ##                
    ## d               Não PAV PAV Total
    ##   1Não Covid-19    1727  89  1816
    ##   2Covid-19          89  22   111
    ##   Total            1816 111  1927
    ## 
    ## $measure
    ##                odds ratio with 95% C.I.
    ## d               estimate    lower  upper
    ##   1Não Covid-19 1.000000       NA     NA
    ##   2Covid-19     4.796617 2.871741 8.0117
    ## 
    ## $p.value
    ##                two-sided
    ## d                 midp.exact fisher.exact   chi.square
    ##   1Não Covid-19           NA           NA           NA
    ##   2Covid-19     1.173299e-07 9.807624e-08 5.790142e-11
    ## 
    ## $correction
    ## [1] FALSE
    ## 
    ## attr(,"method")
    ## [1] "Unconditional MLE & normal approximation (Wald) CI"

    ## 1Não Covid-19     2Covid-19 
    ##          1816           111

    ## [1] "A tabela abaixo diz respeito a análise quanto a DMID:"

    ##      
    ## d     Não PAV  PAV
    ##   Não    1732  106
    ##   Sim      84    5
    ## 
    ##  Pearson's Chi-squared test with Yates' continuity correction
    ## 
    ## data:  Tabela
    ## X-squared = 1.9703e-29, df = 1, p-value = 1
    ## 
    ## $data
    ##        
    ## d       Não PAV PAV Total
    ##   Não      1732 106  1838
    ##   Sim        84   5    89
    ##   Total    1816 111  1927
    ## 
    ## $measure
    ##      odds ratio with 95% C.I.
    ## d      estimate     lower    upper
    ##   Não 1.0000000        NA       NA
    ##   Sim 0.9725966 0.3863216 2.448593
    ## 
    ## $p.value
    ##      two-sided
    ## d     midp.exact fisher.exact chi.square
    ##   Não         NA           NA         NA
    ##   Sim  0.9987558            1  0.9529638
    ## 
    ## $correction
    ## [1] FALSE
    ## 
    ## attr(,"method")
    ## [1] "Unconditional MLE & normal approximation (Wald) CI"

    ##  Não  Sim 
    ## 1838   89

    ## [1] "A tabela abaixo diz respeito a análise quanto a DMNID:"

    ##      
    ## d     Não PAV  PAV
    ##   Não    1555   84
    ##   Sim     261   27
    ## 
    ##  Pearson's Chi-squared test with Yates' continuity correction
    ## 
    ## data:  Tabela
    ## X-squared = 7.3863, df = 1, p-value = 0.006572
    ## 
    ## $data
    ##        
    ## d       Não PAV PAV Total
    ##   Não      1555  84  1639
    ##   Sim       261  27   288
    ##   Total    1816 111  1927
    ## 
    ## $measure
    ##      odds ratio with 95% C.I.
    ## d     estimate    lower    upper
    ##   Não 1.000000       NA       NA
    ##   Sim 1.915025 1.217433 3.012339
    ## 
    ## $p.value
    ##      two-sided
    ## d      midp.exact fisher.exact chi.square
    ##   Não          NA           NA         NA
    ##   Sim 0.007395909  0.008462738 0.00430527
    ## 
    ## $correction
    ## [1] FALSE
    ## 
    ## attr(,"method")
    ## [1] "Unconditional MLE & normal approximation (Wald) CI"

    ##  Não  Sim 
    ## 1639  288

    ## [1] "A tabela abaixo diz respeito a análise quanto a DPOC Não Termial:"

    ##      
    ## d     Não PAV  PAV
    ##   Não    1786  105
    ##   Sim      30    6

    ## Warning in chisq.test(Tabela): Chi-squared approximation may be incorrect

    ## 
    ##  Pearson's Chi-squared test with Yates' continuity correction
    ## 
    ## data:  Tabela
    ## X-squared = 6.1216, df = 1, p-value = 0.01335

    ## Warning in chisq.test(xx, correct = correction): Chi-squared approximation may
    ## be incorrect

    ## $data
    ##        
    ## d       Não PAV PAV Total
    ##   Não      1786 105  1891
    ##   Sim        30   6    36
    ##   Total    1816 111  1927
    ## 
    ## $measure
    ##      odds ratio with 95% C.I.
    ## d     estimate    lower    upper
    ##   Não 1.000000       NA       NA
    ##   Sim 3.401905 1.385399 8.353519
    ## 
    ## $p.value
    ##      two-sided
    ## d     midp.exact fisher.exact  chi.square
    ##   Não         NA           NA          NA
    ##   Sim 0.01864564   0.01503457 0.004579039
    ## 
    ## $correction
    ## [1] FALSE
    ## 
    ## attr(,"method")
    ## [1] "Unconditional MLE & normal approximation (Wald) CI"

    ##  Não  Sim 
    ## 1891   36

    ## [1] "A tabela abaixo diz respeito a análise quanto a Etilismo:"

    ##      
    ## d     Não PAV  PAV
    ##   Não    1680  104
    ##   Sim     136    7
    ## 
    ##  Pearson's Chi-squared test with Yates' continuity correction
    ## 
    ## data:  Tabela
    ## X-squared = 0.075613, df = 1, p-value = 0.7833
    ## 
    ## $data
    ##        
    ## d       Não PAV PAV Total
    ##   Não      1680 104  1784
    ##   Sim       136   7   143
    ##   Total    1816 111  1927
    ## 
    ## $measure
    ##      odds ratio with 95% C.I.
    ## d     estimate     lower    upper
    ##   Não 1.000000        NA       NA
    ##   Sim 0.831448 0.3792339 1.822901
    ## 
    ## $p.value
    ##      two-sided
    ## d     midp.exact fisher.exact chi.square
    ##   Não         NA           NA         NA
    ##   Sim   0.676824    0.8514529  0.6444471
    ## 
    ## $correction
    ## [1] FALSE
    ## 
    ## attr(,"method")
    ## [1] "Unconditional MLE & normal approximation (Wald) CI"

    ##  Não  Sim 
    ## 1784  143

    ## [1] "A tabela abaixo diz respeito a análise quanto a Fibrilação atrial crônica:"

    ##      
    ## d     Não PAV  PAV
    ##   Não    1757  105
    ##   Sim      59    6

    ## Warning in chisq.test(Tabela): Chi-squared approximation may be incorrect

    ## 
    ##  Pearson's Chi-squared test with Yates' continuity correction
    ## 
    ## data:  Tabela
    ## X-squared = 0.90424, df = 1, p-value = 0.3416

    ## Warning in chisq.test(xx, correct = correction): Chi-squared approximation may
    ## be incorrect

    ## $data
    ##        
    ## d       Não PAV PAV Total
    ##   Não      1757 105  1862
    ##   Sim        59   6    65
    ##   Total    1816 111  1927
    ## 
    ## $measure
    ##      odds ratio with 95% C.I.
    ## d     estimate    lower    upper
    ##   Não 1.000000       NA       NA
    ##   Sim 1.701695 0.718204 4.031954
    ## 
    ## $p.value
    ##      two-sided
    ## d     midp.exact fisher.exact chi.square
    ##   Não         NA           NA         NA
    ##   Sim  0.2436193    0.2685895  0.2218211
    ## 
    ## $correction
    ## [1] FALSE
    ## 
    ## attr(,"method")
    ## [1] "Unconditional MLE & normal approximation (Wald) CI"

    ##  Não  Sim 
    ## 1862   65

    ## [1] "A tabela abaixo diz respeito a análise quanto a Hipertensão Arterial Sistêmica:"

    ##      
    ## d     Não PAV PAV
    ##   Não     891  40
    ##   Sim     925  71
    ## 
    ##  Pearson's Chi-squared test with Yates' continuity correction
    ## 
    ## data:  Tabela
    ## X-squared = 6.5976, df = 1, p-value = 0.01021
    ## 
    ## $data
    ##        
    ## d       Não PAV PAV Total
    ##   Não       891  40   931
    ##   Sim       925  71   996
    ##   Total    1816 111  1927
    ## 
    ## $measure
    ##      odds ratio with 95% C.I.
    ## d     estimate    lower    upper
    ##   Não 1.000000       NA       NA
    ##   Sim 1.709757 1.148088 2.546207
    ## 
    ## $p.value
    ##      two-sided
    ## d      midp.exact fisher.exact  chi.square
    ##   Não          NA           NA          NA
    ##   Sim 0.007571197  0.008150692 0.007666436
    ## 
    ## $correction
    ## [1] FALSE
    ## 
    ## attr(,"method")
    ## [1] "Unconditional MLE & normal approximation (Wald) CI"

    ## Não Sim 
    ## 931 996

    ## [1] "A tabela abaixo diz respeito a análise quanto a ICC CF:"

    ##      
    ## d     Não PAV  PAV
    ##   Não    1761  104
    ##   Sim      55    7

    ## Warning in chisq.test(Tabela): Chi-squared approximation may be incorrect

    ## 
    ##  Pearson's Chi-squared test with Yates' continuity correction
    ## 
    ## data:  Tabela
    ## X-squared = 2.6331, df = 1, p-value = 0.1047

    ## Warning in chisq.test(xx, correct = correction): Chi-squared approximation may
    ## be incorrect

    ## $data
    ##        
    ## d       Não PAV PAV Total
    ##   Não      1761 104  1865
    ##   Sim        55   7    62
    ##   Total    1816 111  1927
    ## 
    ## $measure
    ##      odds ratio with 95% C.I.
    ## d     estimate    lower    upper
    ##   Não  1.00000       NA       NA
    ##   Sim  2.15507 0.957729 4.849312
    ## 
    ## $p.value
    ##      two-sided
    ## d     midp.exact fisher.exact chi.square
    ##   Não         NA           NA         NA
    ##   Sim 0.08534199   0.08570593 0.05746936
    ## 
    ## $correction
    ## [1] FALSE
    ## 
    ## attr(,"method")
    ## [1] "Unconditional MLE & normal approximation (Wald) CI"

    ##  Não  Sim 
    ## 1865   62

    ## [1] "A tabela abaixo diz respeito a análise quanto a IRC Não Dialítica:"

    ##      
    ## d     Não PAV  PAV
    ##   Não    1747  100
    ##   Sim      69   11

    ## Warning in chisq.test(Tabela): Chi-squared approximation may be incorrect

    ## 
    ##  Pearson's Chi-squared test with Yates' continuity correction
    ## 
    ## data:  Tabela
    ## X-squared = 8.3396, df = 1, p-value = 0.003879

    ## Warning in chisq.test(xx, correct = correction): Chi-squared approximation may
    ## be incorrect

    ## $data
    ##        
    ## d       Não PAV PAV Total
    ##   Não      1747 100  1847
    ##   Sim        69  11    80
    ##   Total    1816 111  1927
    ## 
    ## $measure
    ##      odds ratio with 95% C.I.
    ## d     estimate    lower    upper
    ##   Não 1.000000       NA       NA
    ##   Sim 2.785072 1.428762 5.428916
    ## 
    ## $p.value
    ##      two-sided
    ## d      midp.exact fisher.exact  chi.square
    ##   Não          NA           NA          NA
    ##   Sim 0.006644578  0.005051608 0.001730824
    ## 
    ## $correction
    ## [1] FALSE
    ## 
    ## attr(,"method")
    ## [1] "Unconditional MLE & normal approximation (Wald) CI"

    ##  Não  Sim 
    ## 1847   80

    ## [1] "A tabela abaixo diz respeito a análise quanto a Obesidade:"

    ##      
    ## d     Não PAV  PAV
    ##   Não    1725   95
    ##   Sim      91   16
    ## 
    ##  Pearson's Chi-squared test with Yates' continuity correction
    ## 
    ## data:  Tabela
    ## X-squared = 15.89, df = 1, p-value = 6.713e-05
    ## 
    ## $data
    ##        
    ## d       Não PAV PAV Total
    ##   Não      1725  95  1820
    ##   Sim        91  16   107
    ##   Total    1816 111  1927
    ## 
    ## $measure
    ##      odds ratio with 95% C.I.
    ## d     estimate    lower    upper
    ##   Não 1.000000       NA       NA
    ##   Sim 3.192597 1.805387 5.645702
    ## 
    ## $p.value
    ##      two-sided
    ## d     midp.exact fisher.exact   chi.square
    ##   Não         NA           NA           NA
    ##   Sim 0.00033768  0.000262531 2.672759e-05
    ## 
    ## $correction
    ## [1] FALSE
    ## 
    ## attr(,"method")
    ## [1] "Unconditional MLE & normal approximation (Wald) CI"

    ##  Não  Sim 
    ## 1820  107

    ## [1] "A tabela abaixo diz respeito a análise quanto a Tabagismo:"

    ##      
    ## d     Não PAV  PAV
    ##   Não    1499   90
    ##   Sim     317   21
    ## 
    ##  Pearson's Chi-squared test with Yates' continuity correction
    ## 
    ## data:  Tabela
    ## X-squared = 0.070168, df = 1, p-value = 0.7911
    ## 
    ## $data
    ##        
    ## d       Não PAV PAV Total
    ##   Não      1499  90  1589
    ##   Sim       317  21   338
    ##   Total    1816 111  1927
    ## 
    ## $measure
    ##      odds ratio with 95% C.I.
    ## d     estimate     lower   upper
    ##   Não 1.000000        NA      NA
    ##   Sim 1.103365 0.6758192 1.80139
    ## 
    ## $p.value
    ##      two-sided
    ## d     midp.exact fisher.exact chi.square
    ##   Não         NA           NA         NA
    ##   Sim  0.6815345    0.6997908  0.6939963
    ## 
    ## $correction
    ## [1] FALSE
    ## 
    ## attr(,"method")
    ## [1] "Unconditional MLE & normal approximation (Wald) CI"

    ##  Não  Sim 
    ## 1589  338

    ## [1] "A tabela abaixo diz respeito a análise quanto a câncer:"

    ##      
    ## d     Não PAV  PAV
    ##   Não    1534  100
    ##   Sim     282   11
    ## 
    ##  Pearson's Chi-squared test with Yates' continuity correction
    ## 
    ## data:  Tabela
    ## X-squared = 2.1441, df = 1, p-value = 0.1431
    ## 
    ## $data
    ##        
    ## d       Não PAV PAV Total
    ##   Não      1534 100  1634
    ##   Sim       282  11   293
    ##   Total    1816 111  1927
    ## 
    ## $measure
    ##      odds ratio with 95% C.I.
    ## d      estimate     lower    upper
    ##   Não 1.0000000        NA       NA
    ##   Sim 0.5983688 0.3169622 1.129615
    ## 
    ## $p.value
    ##      two-sided
    ## d     midp.exact fisher.exact chi.square
    ##   Não         NA           NA         NA
    ##   Sim  0.1016403    0.1331413   0.109502
    ## 
    ## $correction
    ## [1] FALSE
    ## 
    ## attr(,"method")
    ## [1] "Unconditional MLE & normal approximation (Wald) CI"

    ##  Não  Sim 
    ## 1634  293

    ## [1] "A tabela abaixo diz respeito a análise quanto a paciente crônico:"

    ##      
    ## d     Não PAV  PAV
    ##   Não    1616   91
    ##   Sim     200   20
    ## 
    ##  Pearson's Chi-squared test with Yates' continuity correction
    ## 
    ## data:  Tabela
    ## X-squared = 4.4062, df = 1, p-value = 0.03581
    ## 
    ## $data
    ##        
    ## d       Não PAV PAV Total
    ##   Não      1616  91  1707
    ##   Sim       200  20   220
    ##   Total    1816 111  1927
    ## 
    ## $measure
    ##      odds ratio with 95% C.I.
    ## d     estimate    lower    upper
    ##   Não 1.000000       NA       NA
    ##   Sim 1.775824 1.070823 2.944979
    ## 
    ## $p.value
    ##      two-sided
    ## d     midp.exact fisher.exact chi.square
    ##   Não         NA           NA         NA
    ##   Sim 0.03388381   0.03074371 0.02426999
    ## 
    ## $correction
    ## [1] FALSE
    ## 
    ## attr(,"method")
    ## [1] "Unconditional MLE & normal approximation (Wald) CI"

    ##  Não  Sim 
    ## 1707  220

    ## [1] "A tabela abaixo diz respeito a análise quanto a reinternação:"

    ##      
    ## d     Não PAV  PAV
    ##   Não    1654  101
    ##   Sim     162   10
    ## 
    ##  Pearson's Chi-squared test with Yates' continuity correction
    ## 
    ## data:  Tabela
    ## X-squared = 1.4356e-29, df = 1, p-value = 1
    ## 
    ## $data
    ##        
    ## d       Não PAV PAV Total
    ##   Não      1654 101  1755
    ##   Sim       162  10   172
    ##   Total    1816 111  1927
    ## 
    ## $measure
    ##      odds ratio with 95% C.I.
    ## d     estimate     lower    upper
    ##   Não 1.000000        NA       NA
    ##   Sim 1.010879 0.5175398 1.974488
    ## 
    ## $p.value
    ##      two-sided
    ## d     midp.exact fisher.exact chi.square
    ##   Não         NA           NA         NA
    ##   Sim  0.9430844            1  0.9747299
    ## 
    ## $correction
    ## [1] FALSE
    ## 
    ## attr(,"method")
    ## [1] "Unconditional MLE & normal approximation (Wald) CI"

    ##  Não  Sim 
    ## 1755  172
