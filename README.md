# A decision support tool for surgeons to predict post surgery complications of elective surgery patients using pre-operative clinical risk factors

## Datathon_Team_01

SINGAPORE HEALTHCARE AI DATATHON & EXPO: SHADE'22

## Table of Contents

+ [About](#about)
    + [Code Locations](#codeloc)
    + [Contributors](#contributor)
    + [Information About The Dataset](#datasetinfo)

## About <a name = "about"></a>

Each year, there are approximately [300 million surgeries](https://doi.org/10.1016/S0140-6736(15)60806-6) performed worldwide and this number is rapidly increasing. With improved access to surgery, the number of patients with postoperative complications will also increase. To address this, it is important to predict surgical risk preoperatively to aid in clinical decision making and resource planning, such as ICU beds.

In Singapore, public hospitals have approximately [163 adult ICU beds for non-COVID-19 patients with an average occupancy rate of 80%](https://www.straitstimes.com/singapore/politics/about-60-of-singapores-219-covid-19-icu-beds-occupied-janil-puthucheary#:~:text=Singapore's%20public%20hospitals%20currently%20operate,rate%20of%2063%20per%20cent). By using Electronic Health Records (EHR) and integrated data science techniques, early surgical risk prediction can be achieved. This allows for preoperative counseling for the patient regarding the risks of postoperative mortality and critical care needs after surgery.

In this project, we have developed predictors using routinely available preoperative clinical and laboratory variables found in the [VitalDB Asian dataset](https://doi.org/10.1038/s41597-022-01411-5). These predictors will be valuable to both surgeons and patients as they aid in shared decision making.

## Contributors <a name = "contributor"></a>
- Mukkesh Kumar
- Joshua Yeo
- Varsha Singh
- Divakar K N
- Sharifah
- Maisie
- Estella
- Leon Tjandra

### Information About The Dataset <a name = "datasetinfo"></a>

The [VitalDB Asian dataset](https://doi.org/10.1038/s41597-022-01411-5) is an open dataset created specifically to facilitate machine learning studies related to monitoring vital signs in surgical patients. This dataset contains high-resolution multi-parameter data from 6,388 cases, including 486,451 waveform and numeric data tracks of 196 intraoperative monitoring parameters, 73 perioperative clinical parameters, and 34 time-series laboratory result parameters.
The features of the dataset are the following:

- **Measurement(s)**: vital signs of patients during surgery • perioperative patient information
- **Technology Type(s)**: Vital Signs Measurement • Electronic Medical Record
- **Factor Type(s)**: vital signs data including various numeric and waveform data acquired from multiple patient monitors • perioperative patient information acquired from the electronic medical record system
- **Sample Characteristic - Organism**: Homo sapiens
- **Sample Characteristic - Environment**: hospital
- **Sample Characteristic - Location**: South Korea