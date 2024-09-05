# Masters Project
## Summary
Fourth year Masters project using Neural Networks to model defensive football tactics.

The aim of this project was to use tracking data from Premier League football teams to train a time series neural network capable of predicting defensive responses to unseen attacking formations. This process involved building different network architectures in PyTorch, transforming the tracking data into a suitable input format, cleaning the dataset, and interpreting the results to iteratively improve the model.

The latter part of the project focused on integrating convolutional neural networks (CNNs) with the time series model. This involved transforming the coordinate data into a spatial map, which addressed key limitations of the initial approach. Although this method wasn't fully finalized in the reports due to time constraints, the approach is outlined in the conclusion of the second report. Despite this, the new method showed promising results, accurately predicting unseen phases of play with greater accuracy than the original model. These results are showcased in the final slides of the presentation.


## Technical Highlights
* Building Time series (RNN and LSTM) Neural Networks using pytorch
* Building Convolutional Neural Networks in pytorch
* Dataset modification techniques
* Large data filtering techniques such as Principal Component Analysis
* Supervised machine learning
* Interpreting results from machine learning models

## Files
* Masters Project Redacted 1.pdf contains my first semester Masters project report. Note that the experiment was half completed at this point so the results weren't conclusive.
* Masters Project Redacted 2.pdf contains my second semester Masters project report. Note that further work was completed after the report was written that improved results. These are included in the presentation.
* Masters Project Presentation.pptx contains the powerpoint used to present the project. This contains the work done with CNNs that isn't included in the reports. (Slide 19-end).
* Masters Project Notes Redacted 1.pdf contains my handwritten notes on the project from the first semester. This contains methods that were attempted but not included in the final reports.
* Masters Project Notes Redacted 2.pdf contains my typed notes on the project from the second semester. This contains methods that were attempted but not included in the final reports.
