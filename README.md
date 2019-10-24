<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Predicting Hospital Readmissions with Machine Learning

## Project Description
Annual hospital data of a country can give us some really big clues as to what is happening all around and can provide us with important points to which we can develop a new strategy around it (e.g. build a concrete strategy to avoid disease outbreaks or any specific health threats).

For instance, it is important to know if a patient will be readmitted in hospital. The reason is that you can change the treatment, in order to avoid a readmission, and therefore costs.
Hospital readmission rates for certain conditions are now considered an indicator of hospital quality, and also affect the cost of care adversely.

In the present dataset there were 3 possible outcomes: not being readmitted, being readmitted in more than 30 days, being readmitted in less than 30 days. There was more than one approach to this but I decided to focus on those "less than 30 days readmissions", as I think these are the problematic ones and that best represent poor hospital management.

Insights:
1) What factors are the strongest predictors of hospital readmission in diabetic patients?
2) How well can we predict hospital readmission in this dataset?

The data I was dealing with was complex and required a lot of medical/pharmaceutical background knowledge for further feature engineering to help the model. A few things I found help on discussions on Kaggle (for example the conversion of the diagnosis codes). But it felt a bit bitter to left behind all the 23 types of medications; I didn't had the time to explore everything I wanted within the given week we had for the project. Would have been lovely to explore interactions between different combinations of medications and see if that was resulting in a new readmission of a patient for example. Nevertheless, I very much enjoy preparing the final presentation and trying to make the information I found perceptible by a non-medical audience.

## Contents
Inside the folder "hospital-readmissions" you will find:
- code (commented)
- data_sets (sources: UCI Machine Learning Repository)
- slides.pdf