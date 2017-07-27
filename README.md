# TensorFlow Mammogram Image Classifier
By using convolutional neural networks (CNNs) this classifies microcalcifications and masses in a mammogram as either *benign* or *malevolent*. If there are no masses present in the breast tissue then the mammogram will be classified as *normal*. The biggest challenge in this project was that the amount of mammogram images without any segmentation or overlay available online (publicly) was scarce and not feasible to train a CNN on, thus why I trained the network on pre-segmented image data. The .gitignore contains files that are installed via the retrain.py script that is pulled from TensorFlow.
![Left](/results/A_1105_1.LEFT_MLO.LJPEG.1_highpass.png) ![Right](/results/A_1363_1.RIGHT_MLO.LJPEG.1_highpass.png)

## Tools & Resources
- [TensorFlow for Poets](https://codelabs.developers.google.com/codelabs/tensorflow-for-poets/#0)
- [Docker](https://www.docker.com/)
- [Digital Database for Screening Mammography (DDSM)](http://marathon.csee.usf.edu/Mammography/Database.html)

## Results
#### Normal mammogram image test
![Normal Test](/results/normal.png)

#### Benign mammogram image test
![Benign Test](/results/benign.png)

#### Malevolent mammogram image test
![Malevolent Test](/results/malevolent.png)

## Accuracy
![Final Test](/results/final.png)