# PEUGIC Framework

[GitHub Repo](https://github.com/AlexSeferidis/FYP-Code)

## Synopsis

For my final-year MEng project, I designed and evaluated a machine-learning framework for predicting a patient's Post-Endoscopy Upper Gastrointestinal Cancer (PEUGIC) risk from endoscopic photodocumentation. PEUGIC describes upper gastrointestinal cancers diagnosed following a recent endoscopy that did not identify cancer, representing a potential missed opportunity for earlier detection.

The framework included a pathology-classification system for identifying Barrett's oesophagus, healthy/normal anatomy and oesophagitis, and an object-detection system for identifying image artefacts and indicators of photodocumentation quality. The classification system evaluated single-model, ensemble and two-stage CNN architectures alongside a custom contrast-enhancement pipeline, while the artefact detector compared modern YOLO and transformer-based models.

The final implementation combined classification probabilities, confidence summaries, hard-predicted class fractions and artefact-detection features using a regularised logistic-regression model. Using a dataset of 70 PEUGIC cases containing 134 images, the final framework achieved an AUROC of 0.959 and an AUPRC of 0.877, providing promising evidence that PEUGIC-related risk information can be extracted from endoscopic images.

## Skills

Below are the skills and experiences gained from the project:

* Designing CNN ensembles, two-stage classifiers and object-detection systems
* Developing an end-to-end framework combining image classification, artefact detection and patient-level risk modelling
* Working with de-identified NHS clinical data and limited, imbalanced medical-image datasets
* Applying transfer learning, data augmentation, custom image preprocessing and model explainability techniques
* Evaluating model calibration, robustness, class imbalance and source-domain confounding
* Competency with Python, PyTorch, scikit-learn, OpenCV, pandas, NumPy, Matplotlib and Ultralytics
* Developing domain knowledge in gastroenterology, endoscopy quality and clinical risk stratification

---

![alt](images/Design-Diagram.png 'title')

---