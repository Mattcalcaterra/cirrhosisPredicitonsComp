<p align="center">
    <h1 align="center">CIRRHOSIS OUTCOMES PREDICITON KAGGLE COMPETITION</h1>
</p>
<p align="center">
    <em><code>Prediction Model for Cirhosis Outcomes Prediction Competition</code></em>
</p>
<p align="center">
	<img src="https://img.shields.io/github/last-commit/Mattcalcaterra/cirrhosisPredicitonsComp?style=default&color=0080ff" alt="last-commit">
	<img src="https://img.shields.io/github/languages/top/Mattcalcaterra/cirrhosisPredicitonsComp?style=default&color=0080ff" alt="repo-top-language">
	<img src="https://img.shields.io/github/languages/count/Mattcalcaterra/cirrhosisPredicitonsComp?style=default&color=0080ff" alt="repo-language-count">
<p>
<p align="center">
	<!-- default option, no dependency badges. -->
</p>
<hr>

##  Quick Links

> - [ Overview](#-overview)
> - [ Repository Structure](#-repository-structure)
> - [ Modules](#-modules)

---

##  Overview

<code>► This project was created as a submission to the Multi-Class Prediction of Cirrhosis Outcomes Competition as a part of the Kaggle Playground Series. The competition ran from Dec 4th, 2023 to Jan 1st, 2024 and can be found <a href=https://www.kaggle.com/competitions/playground-series-s3e26>here</a></code>

<p> The data for the project was cleaned prior to being downloaded as a part of the kaggle competition. As a results this project does a basic exploritory analysis of the variables in the dataset, and then create a classification model in order to predict outcomes. </p>

<p> The prediction are based off the variable `status` which contains three variables with the following indications:</p>

- **C**: Censored
- **CL**: Consired and liver transplant
- **D**: Death

<p> An ensemble model was tuned and used in order to predict the probability of each of the three classifications for the patients in the testing dataset.</p>

---

##  Repository Structure

```sh
└── cirrhosisPredicitonsComp/
    ├── data
    │   ├── sample_submission.csv
    │   ├── submission.csv
    │   ├── submission2.csv
    │   ├── test.csv
    │   └── train.csv
    ├── cirrhosisAnalysis.ipynb
    ├── .gitignore
    ├── .gitattributes
    └── README.md
```

##  Modules

<details closed><summary>Notebook</summary>

| File                                                                                                                      | Summary                         |
| ---                                                                                                                       | ---                             |
| [cirrhosisAnalysis.ipynb](https://github.com/Mattcalcaterra/cirrhosisPredicitonsComp/blob/master/cirrhosisAnalysis.ipynb) | <code>► All analysis and model building was completed in a single notebook for the competition. Two different submission files are generated from the notebook</code> |

</details>

<details closed><summary>data</summary>

| File                                                                                                                      | Summary                         |
| ---                                                                                                                       | ---                             |
| [cirrhosisAnalysis.ipynb](https://github.com/Mattcalcaterra/cirrhosisPredicitonsComp/blob/master/data) | <code>► The data for this competition was downloadede from kaggle.com. It features a train, test, and sample submission .csv</code> |

</details>

---

##  Acknowledgments

- The <a href=https://www.kaggle.com/competitions/playground-series-s3e26/data>Kaggle Competition Page</a> was used to garner information about the data and competition
- The kaggle page for <a href=https://www.kaggle.com/datasets/joebeachcapital/cirrhosis-patient-survival-prediction>`Cirrhosis Patient Survival`</a> was also used for further insight on the data

[**Return**](#-quick-links)

---
