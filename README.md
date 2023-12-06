# ChestXRay Classification and Caption Generation
project for course EE_475

Steps:
* Dataset:
  * Load Data
  * Filter the Dataframe: remove captions that cannot be used and drop the lateral view, the models consider the frontal view
  * prepare the split the dataframes into train, validate, and test with a total of 600 samples (300 from each class (normal/abnormal))
* EDA: plot the distribution of classes between the train, validate, and test sets, calculate the average height and width for the images, plot the histogram of the pixel values of a sample of images
* Modelling:
  * Classification: implement a simple CNN, train and evaluate
  * Caption Generation: fine-tune a caption generation model and evaluate
