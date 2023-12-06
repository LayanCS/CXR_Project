# ChestXRay Classification and Caption Generation
project for course EE_475

Steps:
* Dataset:
  * Load Data
  * Filter the Dataframe: remove captions that cannot be used and drop the lateral view, the models consider the frontal view
  * prepare the split the dataframes into train, validate, and test with a total of 600 samples (300 from each class (normal/abnormal))
* Modelling:
  * Classification: implement a simple CNN, train and evaluate
  * Caption Generation: fine-tune a caption generation model and evaluate
