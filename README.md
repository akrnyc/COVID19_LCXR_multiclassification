# COVID19_LCXR_multiclassification
## In-line Image Transformations on Lung Chest X-Rays for Multiclass Classification

The following is a computer vision study using lung chest x-ray data to assess the impact of multiclass classification based on imbalanced transformed image datasets. Data were transformed to 1. correct for class imbalance and 2. enhance edge features.

<img width="1175" alt="Fig3" src="https://user-images.githubusercontent.com/43153538/113652747-5f042280-9662-11eb-8426-a83e77a723fa.png">

### Data Sources:
* COVID-19 Image Data Collection: Prospective Predictions Are the Future. Joseph Paul Cohen and Paul Morrison and Lan Dao and Karsten Roth and Tim Q Duong and Marzyeh Ghassemi. arXiv:2006.11988, https://github.com/ieee8023/covid-chestxray-dataset, 2020
* Kermany, D. S., Goldbaum, M., Cai, W., Valentim, C. C., Liang, H., Baxter, S. L., ... Zhang, K. (2018). Identifying Medical Diagnoses and Treatable Diseases by Image-Based Deep Learning. Cell, 172(5). https://doi.org/10.1016/j.cell.2018.02.010
* https://github.com/agchung

Downloaded from https://www.kaggle.com/prashant268/chest-xray-covid19-pneumonia

### Labels:
* 0 - No disease diagnosis
* 1 - COVID-19 diagnosis
* 2 - Non-COVID Pneumonia diagnosis

### What's Available:

Balanced training and test datasets available as zip files; these are before applied image transformations by graphical filter but after image transformations by rotation.

The trained *TensorFlow* models are available as zip files. Model summaries are found as output of the jupyter notebook.

- - - 

**DISCLAIMER:** This study does not make any clinical observations or recommendations for any diseases, especially those mentioned in the study related to lung disease pathology. Research conducted is for artificial intelligence computer vision and makes no claims in regards to medicine, biology, health, or any related discipline of the aforementioned. There is no diagnostic or clinical value in this study.

Remember that clinical value comes from rigorous, blinded, randomized, controlled clinical studies ethically performed with participant consent and approval from Internal Review Boards.
