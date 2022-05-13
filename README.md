
# Detection of 13 Thoracic Disease from Chest Xray

Objectives and background: The chest X-ray is among the most widely used diagnostic imaging for screening and diagnosing many lung and bone-related diseases. Recent advances in deep learning have shown many good performances in disease identification from chest X-rays. However, deep network stability and class imbalance problems were not addressed with high accuracy for disease detection and classification from chest X-rays.  

Method: In this study, we proposed a CX-Ultra net (Chest X-Ray Ultranet) to classify and identify thirteen thoracic lung diseases from chest X-rays. The network utilises a multiclass cross-entropy loss function on a compound scaling framework using EfficientNet as a baseline. Channel shuffling is performed in various stages of the network creating reduction cells and more skip connections. The loss function algorithm; and Adam optimisers stabilise and facilitate the model to keep learning over time from new data.

Results and Discussion: The CX-Ultra net achieves 88% average prediction accuracy on NIH Chest X-Ray Dataset. The proposed CX-Ultra net is compared against current best-performing methods and performs 5% -15%(ranging across different diseases) better. It takes ≈30% less time than pre-existing state-of-the-art models in the same environment and data.  

Conclusion: The proposed CX-Ultra net gives higher average accuracy and efficiently handles the dataset’s class imbalance. It also has a significantly less network training time in terms of FLOPS, therefore creating a new benchmark in disease detection from chest X-Rays



## Authors

- [@Anwesh Kabiraj](https://www.github.com/octokatherine)

