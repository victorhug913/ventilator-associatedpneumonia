Untitled
================

## As análises abaixo relacionam as variáveis com o risco de desenvolvimento de PAV.

    ##    Min. 1st Qu.  Median    Mean 3rd Qu.    Max. 
    ##   13.00   55.00   65.00   63.34   74.00  104.00

    ## Warning in summary(as.numeric(df$Score.SAPS)): NAs introduzidos por coerção

    ##    Min. 1st Qu.  Median    Mean 3rd Qu.    Max.    NA's 
    ##   25.00   45.00   54.00   56.08   65.00  118.00       4

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
    ##                    OR   2.5 % 97.5 %      p
    ## Fisher's test 1.16665 0.77523  1.772 0.4888
    ## [1] "Abaixo, há um resumo quanto ao tema acima como fator"

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
    ##                   OR  2.5 % 97.5 %         p    
    ## Fisher's test 21.445 11.614 43.241 < 2.2e-16 ***
    ## ---
    ## Signif. codes:  0 '***' 0.001 '**' 0.01 '*' 0.05 '.' 0.1 ' ' 1
    ## [1] "Abaixo, há um resumo quanto ao tema acima como fator"

    ##     Até 10 dias Mais de 10 dias 
    ##            1324             603

    ## [1] "A tabela abaixo diz respeito a análise quanto a idade:"

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
    ##                   OR  2.5 % 97.5 %       p  
    ## Fisher's test 1.6124 1.0215 2.6174 0.03799 *
    ## ---
    ## Signif. codes:  0 '***' 0.001 '**' 0.01 '*' 0.05 '.' 0.1 ' ' 1
    ## [1] "Abaixo, há um resumo quanto ao tema acima como fator"

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
    ##                   OR  2.5 % 97.5 %         p    
    ## Fisher's test 4.7890 2.7266 8.1474 9.808e-08 ***
    ## ---
    ## Signif. codes:  0 '***' 0.001 '**' 0.01 '*' 0.05 '.' 0.1 ' ' 1
    ## [1] "Abaixo, há um resumo quanto ao tema acima como fator"

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
    ##                    OR   2.5 % 97.5 % p
    ## Fisher's test 0.97261 0.30145 2.4354 1
    ## [1] "Abaixo, há um resumo quanto ao tema acima como fator"

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
    ##                   OR  2.5 % 97.5 %        p   
    ## Fisher's test 1.9143 1.1688 3.0523 0.008463 **
    ## ---
    ## Signif. codes:  0 '***' 0.001 '**' 0.01 '*' 0.05 '.' 0.1 ' ' 1
    ## [1] "Abaixo, há um resumo quanto ao tema acima como fator"

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
    ## 
    ##                   OR  2.5 % 97.5 %       p  
    ## Fisher's test 3.3983 1.1312 8.5448 0.01503 *
    ## ---
    ## Signif. codes:  0 '***' 0.001 '**' 0.01 '*' 0.05 '.' 0.1 ' ' 1
    ## [1] "Abaixo, há um resumo quanto ao tema acima como fator"

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
    ##                    OR   2.5 % 97.5 %      p
    ## Fisher's test 0.83155 0.31986 1.8242 0.8515
    ## [1] "Abaixo, há um resumo quanto ao tema acima como fator"

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
    ## 
    ##                    OR   2.5 % 97.5 %      p
    ## Fisher's test 1.70111 0.58657 4.0551 0.2686
    ## [1] "Abaixo, há um resumo quanto ao tema acima como fator"

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
    ##                   OR  2.5 % 97.5 %        p   
    ## Fisher's test 1.7093 1.1308 2.6145 0.008151 **
    ## ---
    ## Signif. codes:  0 '***' 0.001 '**' 0.01 '*' 0.05 '.' 0.1 ' ' 1
    ## [1] "Abaixo, há um resumo quanto ao tema acima como fator"

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
    ## 
    ##                    OR   2.5 % 97.5 %       p  
    ## Fisher's test 2.15391 0.80734 4.9029 0.08571 .
    ## ---
    ## Signif. codes:  0 '***' 0.001 '**' 0.01 '*' 0.05 '.' 0.1 ' ' 1
    ## [1] "Abaixo, há um resumo quanto ao tema acima como fator"

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
    ## 
    ##                   OR  2.5 % 97.5 %        p   
    ## Fisher's test 2.7829 1.2865 5.5114 0.005052 **
    ## ---
    ## Signif. codes:  0 '***' 0.001 '**' 0.01 '*' 0.05 '.' 0.1 ' ' 1
    ## [1] "Abaixo, há um resumo quanto ao tema acima como fator"

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
    ##                   OR  2.5 % 97.5 %         p    
    ## Fisher's test 3.1896 1.6819 5.7322 0.0002625 ***
    ## ---
    ## Signif. codes:  0 '***' 0.001 '**' 0.01 '*' 0.05 '.' 0.1 ' ' 1
    ## [1] "Abaixo, há um resumo quanto ao tema acima como fator"

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
    ##                   OR  2.5 % 97.5 %      p
    ## Fisher's test 1.1033 0.6414 1.8221 0.6998
    ## [1] "Abaixo, há um resumo quanto ao tema acima como fator"

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
    ##                    OR   2.5 % 97.5 %      p
    ## Fisher's test 0.59851 0.28575 1.1362 0.1331
    ## [1] "Abaixo, há um resumo quanto ao tema acima como fator"

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
    ##                   OR  2.5 % 97.5 %       p  
    ## Fisher's test 1.7752 1.0130 2.9809 0.03074 *
    ## ---
    ## Signif. codes:  0 '***' 0.001 '**' 0.01 '*' 0.05 '.' 0.1 ' ' 1
    ## [1] "Abaixo, há um resumo quanto ao tema acima como fator"

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
    ##                    OR   2.5 % 97.5 % p
    ## Fisher's test 1.01087 0.46119 1.9875 1
    ## [1] "Abaixo, há um resumo quanto ao tema acima como fator"

    ##  Não  Sim 
    ## 1755  172
