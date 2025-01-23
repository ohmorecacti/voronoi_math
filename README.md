This Github contains the code to the generation of Voronoi diagrams and other equations to predict the prices of condominiums in Singapore. 

condo_predict contains the code used to predict condo prices
condo_voronoi contains the code to gerneate the voronoi diagrams.

Below contains the data tables for the randomly selected points.

Please refer to the "Code" section to view the tables in proper format. 

Test 1
                         Condo  Predicted Price  Actual Price      % diff
0                 SOUTHAVEN II      1235.705747   1210.105263    2.115558
1                FREESIA WOODS      1285.057263   1513.857143   15.113703
2                  THE MADEIRA      1191.072435    863.222222   37.979816
3                  THE MAYFAIR      1112.806144    931.906977   19.411719
4                   SUMMERHILL      1243.015516   1377.833333    9.784770
5                 KISMIS COURT      1288.404503    625.000000  106.144720
6        LAKEPOINT CONDOMINIUM      1105.999197    775.900000   42.544039
7                  MEADOWLODGE      1290.053513   1205.285714    7.033005
8              MAYFAIR GARDENS      1397.601888   1990.833333   29.798147
9           DAINTREE RESIDENCE      1250.841538   1671.861386   25.182701
10             THE BLOSSOMVALE      1411.155812   1656.842105   14.828588
11                    HIGHGATE      1284.315599   1314.631579    2.306044
12                   J GATEWAY      1222.653515   1649.500000   25.877326
13               HILLTOP GROVE      1193.389085    900.241379   32.563234
14            SYMPHONY HEIGHTS      1264.215028   1288.375000    1.875228
15                   THE NEXUS      1664.990895   1799.400000    7.469662
16                THE HILLSIDE      1244.559191   1274.857143    2.376576
17              MAYFAIR MODERN      1400.357736   2062.947368   32.118591
18          HILLVIEW RESIDENCE      1201.241298   1130.500000    6.257523
19                     MI CASA      1152.131755    935.068182   23.213663
20   KINGSFORD . HILLVIEW PEAK      1251.664985   1277.307692    2.007559
21     CASHEW PARK CONDOMINIUM      1220.146209   1109.600000    9.962708
22               HILLVIEW PARK      1262.213559   1245.000000    1.382615
23               PANDAN VALLEY      1317.384132   1425.142857    7.561258
24                     CASPIAN      1189.955284   1176.056338    1.181827
25                   HILLVISTA      1237.171431   1348.181818    8.234081
26                  PINE GROVE      1303.843132    985.222222   32.340004
27                 GUILIN VIEW      1170.920879    909.884615   28.688941
28              HILLVIEW GREEN      1238.621432   1132.088235    9.410326
29                  THE WARREN      1160.036973    916.760870   26.536484
30          1 KING ALBERT PARK      1389.040608   1761.833333   21.159364
31                    THE JADE      1194.613840   1087.241379    9.875678
32                SUNSET LODGE      1283.082543   1027.000000   24.935009
33                 ASTOR GREEN      1306.330959   1179.214286   10.779777
34                THE STERLING      1428.241846   1822.545455   21.634775
35                PALM GARDENS      1163.018015    797.070588   45.911546
36                  HILLBROOKS      1228.695188   1192.448276    3.039705
37                   MERALODGE      1172.743794   1074.166667    9.177079
38                   THE LANAI      1199.944776   1405.461538   14.622724
39              CHANTILLY RISE      1231.470499   1172.000000    5.074275
40                      JARDIN      1393.463303   1692.428571   17.664868
41      SPRINGDALE CONDOMINIUM      1244.074605   1300.176471    4.314942
42                 PARC PALAIS      1241.195202   1263.416667    1.758839
43                     MIDWOOD      1249.998018   1649.603448   24.224333
44                 SOUTHAVEN I      1220.627143   1006.947368   21.220550
45                   MERAWOODS      1190.034185   1173.363636    1.420749
46            HILLVIEW HEIGHTS      1250.202507   1355.615385    7.776017
47           THE CREEK @ BUKIT      1283.459760   1542.090909   16.771459
48            HILLVIEW REGENCY      1162.889742    958.362069   21.341378
49         FORESQUE RESIDENCES      1256.058009   1183.690476    6.113721
50                THE SKYWOODS      1253.528399   1333.228571    5.977983
51                THE CASCADIA      1589.715416   1709.425000    7.002915
52              CASA ESPERANZA      1510.612774   1568.000000    3.659900
53                     HILLSTA      1031.090603   1099.000000    6.179199
54                    MONTROSA      1198.357909   1137.600000    5.340885
55        SHERWOOD CONDOMINIUM      1244.507927   1126.000000   10.524683
56      HAZEL PARK CONDOMINIUM      1194.241407   1200.555556    0.525936
57              CHESTNUT VILLE      1253.898563    965.000000   29.937675
58                 HUME PARK I      1260.858889   1258.333333    0.200706
59                  TREE HOUSE      1261.735498   1180.658537    6.867097
60  KI RESIDENCES AT BROOKVALE      1280.260582   1847.650943   30.708742
61               IVORY HEIGHTS      1216.160932    948.947368   28.158945
62                        ESPA      1218.760955   1288.833333    5.436884
63  CASHEW HEIGHTS CONDOMINIUM      1216.822823   1289.666667    5.648269

RMSE: 248.63876936906541
T-value: 0.344354853073986
Critical value: 1.998340542520741

Test 2

                         Condo  Predicted Price  Actual Price     % diff
0                    HILLVISTA      1206.650730   1348.181818  10.497923
1                GLENDALE PARK      1210.904884   1363.894737  11.217131
2                 SUNSET LODGE      1278.866544   1027.000000  24.524493
3                    MERALODGE      1163.491992   1074.166667   8.315779
4                     HIGHGATE      1254.345588   1314.631579   4.585771
5                  ASTOR GREEN      1266.248698   1179.214286   7.380712
6                BUKIT REGENCY      1197.733294   1310.916667   8.633911
7                 THE STERLING      1326.568653   1822.545455  27.213412
8   CASHEW HEIGHTS CONDOMINIUM      1185.100976   1289.666667   8.107963
9                  PARC PALAIS      1217.385108   1263.416667   3.643419
10     CASHEW PARK CONDOMINIUM      1184.775293   1109.600000   6.774990
11               HILLTOP GROVE      1165.717767    900.241379  29.489467
12              MAYFAIR MODERN      1365.072996   2062.947368  33.828996
13                     HILLSTA      1150.856224   1099.000000   4.718492
14                THE CASCADIA      1258.773134   1709.425000  26.362775
15                     MIDWOOD      1208.397219   1649.603448  26.746199
16               CLEMENTI PARK      1479.061597   1265.030303  16.919065
17                        ESPA      1189.233363   1288.833333   7.727917
18               THE LAKESHORE      1101.446908   1069.810811   2.957167
19    THE LAKEFRONT RESIDENCES      1027.761599   1298.595238  20.855893
20                 THE MAYFAIR      1070.005119    931.906977  14.818876
21              REGENT HEIGHTS      1163.361123    802.222222  45.017314
22         FORESQUE RESIDENCES      1200.191047   1183.690476   1.393994
23                 MEADOWLODGE      1222.227395   1205.285714   1.405615
24                 PARK NATURA      1213.130319   1261.846154   3.860679
25             THE BLOSSOMVALE      1335.774637   1656.842105  19.378278
26          1 KING ALBERT PARK      1410.208560   1761.833333  19.957891
27                  PINE GROVE      1267.646308    985.222222  28.666029
28      TERRENE AT BUKIT TIMAH      1243.500901   1574.916667  21.043384
29                     CASPIAN      1025.931236   1176.056338  12.765128
30        HIGH OAK CONDOMINIUM      1249.747610   1096.931034  13.931284
31                  HILLBROOKS      1195.953327   1192.448276   0.293937
32      SPRINGDALE CONDOMINIUM      1195.742831   1300.176471   8.032267
33                     LE WOOD      1193.977472    968.000000  23.344780
34                 GARDENVISTA      1407.027103   1472.861111   4.469804
35       LAKEPOINT CONDOMINIUM      1018.577628    775.900000  31.276921
36                REGENT GROVE      1148.820643    733.508475  56.619955
37                   FLORIDIAN      1264.120136   2017.173913  37.332120
38                  THE WARREN      1103.517022    916.760870  20.371305
39                  SUMMERHILL      1216.940113   1377.833333  11.677263
40        SHERWOOD CONDOMINIUM      1207.816021   1126.000000   7.266077
41                THE RAINTREE      1178.950733   1121.361111   5.135689
42             MAYFAIR GARDENS      1390.530011   1990.833333  30.153369
43                 MAPLE WOODS      1271.239859   1845.312500  31.109779
44                SOUTHAVEN II      1131.210480   1210.105263   6.519663
45              CASA ESPERANZA      1290.486614   1568.000000  17.698558
46                   LAKEVILLE      1119.796388   1503.392857  25.515385
47                 LAKE GRANDE      1115.260680   1592.200000  29.954737
48                 THE MADEIRA      1144.711890    863.222222  32.609178
49               PANDAN VALLEY      1257.646902   1425.142857  11.752924
50               ECO SANCTUARY      1197.228805   1289.928571   7.186426
51            HILLVIEW HEIGHTS      1213.361882   1355.615385  10.493648
52              CHANTILLY RISE      1199.270696   1172.000000   2.326851
53          DAINTREE RESIDENCE      1277.720198   1671.861386  23.574992
54               IVORY HEIGHTS      1232.991029    948.947368  29.932499
55               NICON GARDENS      1156.882566    643.000000  79.919528
56                   THE LANAI      1167.069479   1405.461538  16.961834
57                  TREE HOUSE      1198.872384   1180.658537   1.542685
58               HILLVIEW PARK      1211.651901   1245.000000   2.678562
59                   THE NEXUS      1262.450034   1799.400000  29.840501
60               FREESIA WOODS      1280.268032   1513.857143  15.430063
61              ENG KONG GREEN      1212.275701   1313.250000   7.688886
62              HILLVIEW GREEN      1211.714621   1132.088235   7.033585
63            HILLVIEW REGENCY      1171.026419    958.362069  22.190397

RMSE: 287.48529122992375
T-value: 2.254838612386918
Critical value: 1.998340542520741

Test 3
                         Condo  Predicted Price  Actual Price      % diff
0                 THE SKYWOODS      1252.726725   1333.228571    6.038113
1               REGENT HEIGHTS      1237.498772    802.222222   54.258850
2       TERRENE AT BUKIT TIMAH      1261.262132   1574.916667   19.915627
3                  MEADOWLODGE      1320.816142   1205.285714    9.585315
4         SHERWOOD CONDOMINIUM      1258.661404   1126.000000   11.781652
5                      HILLSTA      1063.974305   1099.000000    3.187051
6                    J GATEWAY      1174.588010   1649.500000   28.791269
7               HILLVIEW GREEN      1267.481355   1132.088235   11.959591
8                    THE NEXUS      1691.338059   1799.400000    6.005443
9               CHANTILLY RISE      1236.378803   1172.000000    5.493072
10                  THE PETALS      1274.102274   1057.500000   20.482485
11                     CASPIAN      1177.453226   1176.056338    0.118777
12               FREESIA WOODS      1157.384259   1513.857143   23.547326
13                 MAPLE WOODS      1682.574107   1845.312500    8.819015
14            HILLINGTON GREEN      1277.654565   1238.800000    3.136468
15              ENG KONG GREEN      1329.605916   1313.250000    1.245453
16       LAKEPOINT CONDOMINIUM      1182.620164    775.900000   52.419147
17                 GARDENVISTA      1676.812986   1472.861111   13.847326
18                  SUMMERHILL      1270.256581   1377.833333    7.807675
19                   LAKEHOLMZ      1182.827608    937.685714   26.143290
20              CHESTNUT VILLE      1238.627124    965.000000   28.355142
21    THE LAKEFRONT RESIDENCES      1176.260744   1298.595238    9.420525
22  KI RESIDENCES AT BROOKVALE      1309.568612   1847.650943   29.122510
23                 LAKE GRANDE      1154.421433   1592.200000   27.495200
24                   LAKEVILLE      1148.897997   1503.392857   23.579656
25                   MERAWOODS      1269.625520   1173.363636    8.203926
26              CAVENDISH PARK      1208.343603   1296.523810    6.801279
27                    THE JADE      1207.460815   1087.241379   11.057290
28  CASHEW HEIGHTS CONDOMINIUM      1193.566116   1289.666667    7.451581
29                THE HILLSIDE      1282.535736   1274.857143    0.602310
30                 GUILIN VIEW      1194.741086    909.884615   31.306878
31                 HUME PARK I      1290.999919   1258.333333    2.596020
32                KISMIS COURT      1318.050439    625.000000  110.888070
33          DAINTREE RESIDENCE      1230.099022   1671.861386   26.423385
34          HILLVIEW RESIDENCE      1305.238995   1130.500000   15.456789
35                PALM GARDENS      1151.148686    797.070588   44.422427
36                      JARDIN      1699.663891   1692.428571    0.427511
37              THE DAIRY FARM      1246.552210   1297.272727    3.909781
38                    MONTROSA      1271.557003   1137.600000   11.775405
39                  PARC VISTA      1180.100343    876.620000   34.619372
40             THE BLOSSOMVALE      1784.331058   1656.842105    7.694695
41                SOUTHAVEN II      1280.212193   1210.105263    5.793457
42                   HILLVISTA      1260.428066   1348.181818    6.509044
43         FORESQUE RESIDENCES      1249.634216   1183.690476    5.571029
44                 ASTOR GREEN      1211.546139   1179.214286    2.741813
45              CASA ESPERANZA      1650.067094   1568.000000    5.233871
46                  TREE HOUSE      1247.825404   1180.658537    5.688933
47                     MI CASA      1126.572687    935.068182   20.480272
48               ECO SANCTUARY      1244.051176   1289.928571    3.556584
49            HILLVIEW REGENCY      1258.896747    958.362069   31.359200
50                     MIDWOOD      1257.836068   1649.603448   23.749185
51                    HIGHGATE      1300.514730   1314.631579    1.073825
52           THE CREEK @ BUKIT      1277.398851   1542.090909   17.164491
53            SYMPHONY HEIGHTS      1288.519742   1288.375000    0.011234
54               THE LAKESHORE      1162.761258   1069.810811    8.688494
55                THE RAINTREE      1268.929894   1121.361111   13.159791
56               HILLTOP GROVE      1258.451313    900.241379   39.790432
57               CLEMENTI PARK      1299.697424   1265.030303    2.740418
58               PANDAN VALLEY      1292.391079   1425.142857    9.314980
59                   MERALODGE      1288.415933   1074.166667   19.945626
60                 SOUTHAVEN I      1273.244553   1006.947368   26.445988
61               GLENDALE PARK      1262.213352   1363.894737    7.455222
62               BUKIT REGENCY      1284.076126   1310.916667    2.047464
63                THE CASCADIA      1630.208590   1709.425000    4.634097

RMSE: 235.2167811082915
T-value: 0.8657188980443367
Critical value: 1.998340542520741

Test 4
                         Condo  Predicted Price  Actual Price      % diff
0               CHANTILLY RISE      1234.975306   1172.000000    5.373320
1         SHERWOOD CONDOMINIUM      1256.025074   1126.000000   11.547520
2             HILLVIEW HEIGHTS      1239.703893   1355.615385    8.550470
3                    FLORIDIAN      1376.779568   2017.173913   31.747106
4               REGENT HEIGHTS      1205.738106    802.222222   50.299764
5                    THE NEXUS      1370.613799   1799.400000   23.829399
6                  GARDENVISTA      1355.195819   1472.861111    7.988893
7              THE BLOSSOMVALE      1462.176555   1656.842105   11.749191
8                         ESPA      1233.466063   1288.833333    4.295922
9       TERRENE AT BUKIT TIMAH      1226.009256   1574.916667   22.154024
10               GLENDALE PARK      1241.639666   1363.894737    8.963674
11               CLEMENTI PARK      1274.391162   1265.030303    0.739971
12                    HIGHGATE      1277.897097   1314.631579    2.794280
13    THE LAKEFRONT RESIDENCES      1096.967441   1298.595238   15.526608
14                 THE MAYFAIR      1213.724168    931.906977   30.240914
15                   LAKEHOLMZ       993.132100    937.685714    5.913110
16         FORESQUE RESIDENCES      1256.892072   1183.690476    6.184184
17                   MERALODGE      1172.657424   1074.166667    9.169039
18                KISMIS COURT      1260.295379    625.000000  101.647261
19               THE LAKESHORE      1129.621377   1069.810811    5.590761
20                  HILLBROOKS      1225.398926   1192.448276    2.763277
21                   THE LANAI      1174.556819   1405.461538   16.429103
22              CHESTNUT VILLE      1252.849055    965.000000   29.828918
23                  PINE GROVE      1267.421689    985.222222   28.643230
24                PALM GARDENS      1173.567452    797.070588   47.235072
25     CASHEW PARK CONDOMINIUM      1235.628208   1109.600000   11.357986
26                 LAKE GRANDE      1149.142369   1592.200000   27.826757
27                  SUMMERHILL      1226.523007   1377.833333   10.981758
28                 MAPLE WOODS      1408.111937   1845.312500   23.692495
29                  THE WARREN      1165.152363    916.760870   27.094469
30      SPRINGDALE CONDOMINIUM      1243.875964   1300.176471    4.330220
31                 GUILIN VIEW      1203.589362    909.884615   32.279340
32                     LE WOOD      1239.881129    968.000000   28.086893
33  KI RESIDENCES AT BROOKVALE      1275.756766   1847.650943   30.952501
34                     MIDWOOD      1238.988228   1649.603448   24.891753
35                   MERAWOODS      1129.124399   1173.363636    3.770292
36            HILLINGTON GREEN      1247.228632   1238.800000    0.680387
37                    THE JADE      1227.126124   1087.241379   12.866025
38            HILLVIEW REGENCY      1193.558365    958.362069   24.541486
39  CASHEW HEIGHTS CONDOMINIUM      1234.805946   1289.666667    4.253868
40          DAINTREE RESIDENCE      1202.490500   1671.861386   28.074749
41               NICON GARDENS      1181.629921    643.000000   83.768261
42              MAYFAIR MODERN      1431.927533   2062.947368   30.588266
43                THE SKYWOODS      1250.648060   1333.228571    6.194025
44           THE CREEK @ BUKIT      1242.131117   1542.090909   19.451499
45                 SOUTHAVEN I      1227.788762   1006.947368   21.931771
46                  TREE HOUSE      1262.333728   1180.658537    6.917766
47                 THE MADEIRA      1210.765508    863.222222   40.261161
48      HAZEL PARK CONDOMINIUM      1225.852554   1200.555556    2.107108
49               FREESIA WOODS      1274.170735   1513.857143   15.832829
50                    MONTROSA      1138.232718   1137.600000    0.055619
51                  PARC OASIS      1214.519355    956.960784   26.914224
52               IVORY HEIGHTS      1281.663155    948.947368   35.061564
53              CAVENDISH PARK      1265.389148   1296.523810    2.401395
54                SUNSET LODGE      1273.004782   1027.000000   23.953728
55          1 KING ALBERT PARK      1423.872301   1761.833333   19.182350
56                THE HILLSIDE      1242.201599   1274.857143    2.561506
57                      JARDIN      1381.618761   1692.428571   18.364722
58                THE CASCADIA      1357.670326   1709.425000   20.577368
59                   LAKEVILLE      1157.215512   1503.392857   23.026406
60             MAYFAIR GARDENS      1400.214800   1990.833333   29.666900
61                REGENT GROVE      1201.065934    733.508475   63.742612
62               GRAND CHATEAU      1259.160202   1134.200000   11.017475
63                 HUME PARK I      1255.793790   1258.333333    0.201818

RMSE: 296.6397320054015
T-value: 0.6850977701363099
Critical value: 1.998340542520741

Test 5
                         Condo  Predicted Price  Actual Price     % diff
0     THE LAKEFRONT RESIDENCES      1162.253337   1298.595238  10.499184
1                NICON GARDENS      1197.285859    643.000000  86.203089
2                    MERALODGE      1194.912346   1074.166667  11.240870
3                THE LAKESHORE      1329.446805   1069.810811  24.269337
4                  SOUTHAVEN I      1312.674485   1006.947368  30.361777
5         HIGH OAK CONDOMINIUM      1406.797090   1096.931034  28.248454
6                  GARDENVISTA      1639.599869   1472.861111  11.320739
7                    J GATEWAY      1253.698482   1649.500000  23.995242
8                 THE HILLSIDE      1263.641121   1274.857143   0.879787
9               CAVENDISH PARK      1378.158037   1296.523810   6.296392
10                THE RAINTREE      1313.169954   1121.361111  17.105002
11  KI RESIDENCES AT BROOKVALE      1321.114723   1847.650943  28.497602
12          HILLVIEW RESIDENCE      1174.075558   1130.500000   3.854539
13                     HILLSTA      1189.091082   1099.000000   8.197551
14                THE STERLING      1628.014309   1822.545455  10.673596
15                   FLORIDIAN      1613.171252   2017.173913  20.028152
16              SIGNATURE PARK      1290.598358   1402.721311   7.993245
17                 THE MAYFAIR      1248.375870    931.906977  33.959279
18                  PARC OASIS      1249.517618    956.960784  30.571455
19                        ESPA      1219.610196   1288.833333   5.370992
20                     MIDWOOD      1238.981993   1649.603448  24.892131
21                SOUTHAVEN II      1308.958222   1210.105263   8.168955
22                  HILLBROOKS      1223.566271   1192.448276   2.609589
23                  THE PETALS      1196.870123   1057.500000  13.179208
24   KINGSFORD . HILLVIEW PEAK      1237.631020   1277.307692   3.106274
25      HAZEL PARK CONDOMINIUM      1215.641537   1200.555556   1.256583
26  CASHEW HEIGHTS CONDOMINIUM      1198.312785   1289.666667   7.083527
27               CLEMENTI PARK      1321.034542   1265.030303   4.427107
28                  PARC VISTA      1153.462133    876.620000  31.580632
29            HILLVIEW REGENCY      1171.787749    958.362069  22.269838
30               IVORY HEIGHTS      1252.087424    948.947368  31.944876
31           THE CREEK @ BUKIT      1356.572689   1542.090909  12.030304
32      SPRINGDALE CONDOMINIUM      1292.922372   1300.176471   0.557932
33                     LE WOOD      1336.505963    968.000000  38.068798
34              CHANTILLY RISE      1228.378725   1172.000000   4.810471
35                 ASTOR GREEN      1389.872161   1179.214286  17.864257
36                REGENT GROVE      1208.802604    733.508475  64.797360
37                 MAPLE WOODS      1592.254637   1845.312500  13.713551
38                 PARC PALAIS      1248.660078   1263.416667   1.167991
39                   LAKEHOLMZ      1053.275750    937.685714  12.327162
40                   HILLVISTA      1238.946777   1348.181818   8.102397
41              ENG KONG GREEN      1264.463629   1313.250000   3.714934
42          1 KING ALBERT PARK      1624.713962   1761.833333   7.782766
43                 THE MADEIRA      1161.679475    863.222222  34.574788
44                  PINE GROVE      1381.529736    985.222222  40.225190
45                   MERAWOODS      1122.975399   1173.363636   4.294341
46              CHESTNUT VILLE      1242.127344    965.000000  28.717859
47      TERRENE AT BUKIT TIMAH      1331.438351   1574.916667  15.459759
48              THE DAIRY FARM      1248.783221   1297.272727   3.737804
49                   THE LANAI      1189.970021   1405.461538  15.332438
50               FREESIA WOODS      1335.888707   1513.857143  11.755960
51                  TREE HOUSE      1274.818212   1180.658537   7.975183
52                THE SKYWOODS      1257.391003   1333.228571   5.688265
53               BUKIT REGENCY      1291.543560   1310.916667   1.477829
54        SHERWOOD CONDOMINIUM      1256.378199   1126.000000  11.578881
55                      JARDIN      1649.168634   1692.428571   2.556086
56            SYMPHONY HEIGHTS      1271.156186   1288.375000   1.336475
57         FORESQUE RESIDENCES      1272.110298   1183.690476   7.469843
58                SUNSET LODGE      1332.406817   1027.000000  29.737762
59                   LAKEVILLE      1407.161743   1503.392857   6.400929
60                  THE WARREN      1145.282395    916.760870  24.927059
61                    THE JADE      1192.947525   1087.241379   9.722417
62               GLENDALE PARK      1252.398590   1363.894737   8.174835
63               HILLVIEW PARK      1243.533655   1245.000000   0.117779

RMSE: 223.00925064525072
T-value: 1.5703244736550985
Critical value: 1.998340542520741

