Native XGBoost just dominated everything.

1) 0.0171364
$ python classify-xgb-native.py # 990r depth6
0.0155765992602
0.019516592639
0.00988590074655
0.0141124661651
0.014303086534
Results: [0.015576599260152162, 0.019516592638969554, 0.0098859007465472819, 0.014112466165067009, 0.014303086534016464]
Mean: 0.014678929069

2) 0.0172253
$ python classify-xgb-native.py # 180r
0.0157726389016
0.0201645979107
0.0095532522597
0.013888759618
0.0139117869773
Results: [0.01577263890161577, 0.020164597910677044, 0.0095532522596954699, 0.013888759618006124, 0.013911786977273863]
Mean: 0.0146582071335

3) 0.0171475
$ python classify-xgb-native.py #added age_gender, rm a bunch of features
0.015551655811
0.019148557532
0.00965389534226
0.0139233429833
0.0139280448029
Results: [0.015551655810998924, 0.019148557531997155, 0.0096538953422591212, 0.013923342983307932, 0.013928044802880669]
Mean: 0.0144410992943
