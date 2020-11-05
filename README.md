# Machine learning-based prediction of intraoperative cerebrospinal fluid leakage in endoscopic transsphenoidal pituitary surgery: a pilot study

**ABSTRACT**

**Objective**
Transsphenoidal surgery (TSS) for pituitary adenomas can be complicated by the occurrence of intraoperative CSF leakage (IOL). IOL significantly affects the course of surgery and may predispose to the development of postoperative CSF leakage - a major source of morbidity and mortality in the postoperative period. In this study, the authors present a Random Forest-based prediction model that was trained and internally validated to preoperatively identify patients at high risk for IOL; furthermore, a webapp user interface is designed for the clinical deployment of our random forest model.

**Methods**
The data of 210 patients who underwent TSS were collected: first, risk factors for IOL were identified via conventional statistical methods (multivariable logistic regression). Then, the authors trained and optimized a Random Forest-based prediction model.

**Results**
IOL occurred in 45 patients (21.5%). The recursive feature selection software identified the following variables as the most significant determinants of IOL: Knosp grade, sellar Hardy grade, suprasellar Hardy grade, tumor diameter (on X, Y and Z axis), inter-carotid distance, and secreting status (non-functioning and GH secreting). Leveraging the predictive values of these variables, the Random Forest-based prediction model achieved an AUC of 0.83 (95% CI: 0.78; 0.86), significantly outperforming the multivariable logistic regression prediction model (AUC of 0.63).

**Conclusions**
The authors trained and internally validated a Random Forest-based model that reliably identifies patients at risk for IOL. Machine learning-based prediction models can predict events that were previously judged nearly unpredictable: the use of such prediction models in clinical practice may result in improved patient care and reduced postoperative morbidity and healthcare costs.

<p align="center">
  <img width="1000" src="https://github.com/valerio-mc/ML-fistola-pituitary/blob/main/Fig3.jpg">
</p>
