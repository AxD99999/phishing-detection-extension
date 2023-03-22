# Phishing Site Detector Plugin 
This lite chrome plugin aims to detect phishing websites and warn the user. It is built with a objective of privacy, so that the user browsing data need not collected for classification. The classification is done on the client side with one-time download of classifier model.

![License](https://img.shields.io/github/license/mashape/apistatus.svg?style=popout) ![Beta](https://img.shields.io/badge/beta-v1.0.01-blue.svg)

**Dataset:** [UCI Repository](https://archive.ics.uci.edu/ml/datasets/phishing+websites)  

## Requirements
```
Python3.7
sklearn==0.19.2
numpy==1.15.0
liac-arff==2.2.2
```

## Documentation
* [Prepare the dataset](backend/dataset/)
* [Train and Export the model](backend/classifier/)
* [Install plugin](frontend/)

Links to few phishing sites: [PDF](artifacts/url_list.pdf), [PhishTank](https://www.phishtank.com/)