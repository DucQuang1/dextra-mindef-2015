Native XGBoost just dominated everything.

1) Public Leader Board 0.0171364
$ python classify-xgb-native.py # 990r depth6
0.0155765992602
0.019516592639
0.00988590074655
0.0141124661651
0.014303086534
Results: [0.015576599260152162, 0.019516592638969554, 0.0098859007465472819, 0.014112466165067009, 0.014303086534016464]
Mean: 0.014678929069 (Local Score)

2) Public Leader Board 0.0172253
$ python classify-xgb-native.py # 180r
0.0157726389016
0.0201645979107
0.0095532522597
0.013888759618
0.0139117869773
Results: [0.01577263890161577, 0.020164597910677044, 0.0095532522596954699, 0.013888759618006124, 0.013911786977273863]
Mean: 0.0146582071335 (Local Score)

3) Public Leader Board 0.0171475
$ python classify-xgb-native.py #added age_gender, rm a bunch of features
0.015551655811
0.019148557532
0.00965389534226
0.0139233429833
0.0139280448029
Results: [0.015551655810998924, 0.019148557531997155, 0.0096538953422591212, 0.013923342983307932, 0.013928044802880669]
Mean: 0.0144410992943 (Local Score)

4) Public Leader Board 0.0171112
$ python classify-xgb-native.py # promo - gender
0.0155083548415
0.0189263516813
0.00951782504063
0.0140093232169
0.014178032663
Results: [0.015508354841467287, 0.018926351681337099, 0.0095178250406324112, 0.01400932321688471, 0.014178032663031151]
Mean: 0.0144279774887 (Local Score)

5) Public Leader Board 0.0170703
$ python classify-xgb-native.py # cap salary 101%
0.0153414063482
0.0189991328711
0.00959486331913
0.0139794582592
0.0140253377611
Results: [0.01534140634816232, 0.018999132871067075, 0.0095948633191300595, 0.013979458259173684, 0.014025337761100839]
Mean: 0.0143880397117 (Local Score)

6) Public Leader Board 0.0170369
$ python classify-xgb-native.py # INJURY TYPE as String
0.0153022751895
0.0189944794534
0.00957494483944
0.0139220394066
0.014069437855
Results: [0.015302275189484418, 0.018994479453434174, 0.0095749448394401911, 0.013922039406634879, 0.014069437855035585]
Mean: 0.0143726353488 (Local Score)

7) Public Leader Board 0.0169515
$ python classify-xgb-native.py # better minchildage # treat as str
0.0152455036731
0.0189285563506
0.00961418416464
0.0139189502782
0.0139664367926
Results: [0.015245503673132394, 0.018928556350630326, 0.0096141841646366355, 0.01391895027824846, 0.013966436792574888]
Mean: 0.0143347262518 (Local Score)