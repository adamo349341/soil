Hello, this repository contains a model that predicts the erosion risk and the recommended biofertilizer for the inputed soil.

The model is based on deeplearning tensorflow keras, you will find 3 notes on the model code: first one is for the training of the model which outputs the accuracy of erosion risk and biofertilizer's trainings,validations and their losses. Second one shows the R2 of the both targets.Finally, the input of the code.

On the dataset, it contains many and various samples, for the feature "erosion risk" is represented by numbers 0-4 which refer to:
-0: No risk
-1: Low risk
-2: Moderate risk
-3: High risk
-4: Very high risk

Same as for " Biofertilizer Formulation":
-0: Formulation A
-1: Formulation B
-2: Formulation C
-3: Formulation D
-4: Formulation E

Formulations are just assumptions so they can be modified.

