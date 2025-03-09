# Predicting which businesses are unlikely to pay their fines

Team: Erle Maido, Kersti Mikkov, Karl Soosalu, Ants Adamson

## The background
All legal entities in Estonia are registered in the Estonian Business Register. While a business is registered, they have the duty to keep their data up to date in the register and submit an annual fiscal report. Failing to do either, can result in the business being fined.

There are thousands of fines issued by the Business Register every year. The levels of fines being paid by legal entities are not good.

Our goal is to find the legal entities that are unlikely to pay their fines and to do so even before the fine is issued. There is a real life use case and a successful project could help improve the Estonian business environment.

## Summary of results
Following the challenge in front of us, we set upon predicting which legal entities are likely to pay and which unlikely to pay fines issued to them by the Estonian Business register.

We set ourselves a target of 75% accuracy to achieve using a Machine Learning model and using the data presented to us.

Following trialling out different approaches and different models, we found that we achieved best results with **XGBoost ML model**. We then set out to work on this model to improve the results to the best possible level.

At default confidence level of 0.5, we achieved:

* 90,3% accuracy
* AUC = 0,951
* AUC PRC = 0,863
* MCC = 0,737

We are happy with the results, as we consider these to be strong results in the light of the unbalanced data we had to work with. Also, we exceeded our own target of 75% accuracy by 15%.
