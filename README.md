# ML-GC

The aim of this study was to develop a quantitative feature-based model from histopathologic images to assess the prognosis of patients with gastric cancer.
Methods.
Whole slide image (WSI) images of H&E-stained histologic specimens of gastric cancer patients from The Cancer Genome Atlas were included and randomly assigned to training and test groups in a 7:3 ratio. A systematic preprocessing approach was employed as well as a non-overlapping segmentation method that combined patch-level prediction with a multi-instance learning approach to integrate features across the slide images. Subjects were categorized into high- or low-risk groups based on the median risk score derived from the model, and the significance of this stratification was assessed using a log-rank test. In addition, combining transcriptomic data from patients and data from other large cohort studies, we further searched for genes associated with pathological features and their prognostic value.
Results.
A total of 165 gastric cancer patients were included for model training, and a total of 26 features were integrated through multi-instance learning, with each process generating 11 probabilistic features and 2 predictive labeling features. We applied a 10-fold Lasso-Cox regression model to achieve dimensionality reduction of these features. The predictive accuracy of the model was verified using Kaplan-Meyer (KM) curves for stratification with a consistency index of 0.741 for the training set and 0.585 for the test set.
Conclusion.
Deep learning-based resultant supervised pathohistological features have the potential for superior prognostic stratification of gastric cancer patients, transforming image pixels into an effective and labor-saving tool to optimize the clinical management of gastric cancer patients. Also, SLITRK4 was identified as a prognostic marker for gastric cancer.

[Power by OnekeyAI](http://medai.icu/)

