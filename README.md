# LendingClub

##Challenge

In the resample file, the data was analysed by performing a random oversampling instance, a SMOTE oversampling, undersampling and a combination using SMOTEENN. 

The accuracy score for the SMOTE oversampling tells us its that it is pretty significant and that the model is precise for low risk loan status but pretty insignificant for high risk loan status. The recall for both of these is about 0.7, in comparison with the undersampling where the recall for the high risk loan status is high and the low risk
was found to be very low. In contrast the SMOTEENN gave the best resultin recall as it determined the high risk to be 0.71 and the low risk to be 0.68. 

None of the models really have a good model for high risk loan status but have really good models for low risk status. When taking into consideration the F1 score that accounts for a true positive weight and precision the SMOTE oversampling and combination techniques serve as better models of prediction, though all models show a variation of the same results across the board. The exception to this would be the amount of predicted yes responses that were actual "yes" amongst the models. SMOTE oversampling had the largest quantity of these with the combination model falling behind. If one model is to be recommended for further analysis or refining, it would be the combination model given the mentioned reasons. 

In the ensemble file, we can see that the AdaBoost Classifier model was the best out of all the models in comparison to the resampling. We see this in the correct predictions performed and the fact that it has the highest high risk precision and balanced accuracy score out of all of the models by a significant margin. 
