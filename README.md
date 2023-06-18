# deep-learning-challenge


## Overview of the Analysis

The analysis uses a dataset of historical funding activity for the nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success 

* The model is design to predict the success of applications by using the "IS_SUCCESSFUL" feature of the dataset.
* The stages of the machine learning process include creating the X and Y elements, seperate the training and test data, standardized the data through Standardscaler, trained the model, and then resampled the data.
* The methods used were multiple `Sequential` model and 'Kesturner' model method.

## Results

The balanced accuracy scores and the model loss for 'Sequential' machine learning models.

* Machine Learning Model 'Sequential' with two models with different cutoff, features and variables:
  *Model 1:
   Loss: 0.5537437796592712, Accuracy: 0.7246647477149963
  *Model 2:
   Loss: 0.5558030009269714, Accuracy: 0.7251312136650085

  * Machine Learning Model 'Kesturner':
   Loss: 0.5558030009269714, Accuracy: 0.7251312136650085

## Summary

Summary the results of the machine learning models, and recommendation none of the model to use:
* The Sequential model was able to prodict the applications sucess to an approximent 72 percent accurary.
* Multiple variations of the features used to create the model as well as multiple attemptes at different cutoffs all resulted in similar results.  No results were able to improve the accuracy but same did result in over fitting the model and a decrease in the results.
* The Kesturner was run to insure that the optimized number of levels and activiation was used and also resulted in similar results.  
* The results found with the available data and created models did not produce statisfactoyry confidence to sucessfully predict the sucess of the applications.

### Technologies used in this project: 
* Google Colab
* Python
* Pandas
* Tensor Flow
* SK Learn

### Files Included
* [Deep Learning, Sequential ML](Deep_learning/Deep_Learning.ipynb)
* [Deep Learning, Sequential 2, model optimizing](Deep_learning/Deep_Learning_optimized.ipynb)
* [Deep Learnig, Keras Tuner](Deep_learning/Optimizing_Model.ipynb)

## Filed Provided
* [Starter Code](Starter_Code/Starter_Code.ipynb)


#### Resources
* [Sample Dataset]("https://static.bc-edx.com/data/dl-1-2/m21/lms/starter/charity_data.csv")

### References
IRS. Tax Exempt Organization Search Bulk Data Downloads. https://www.irs.gov/Links to an external site.
