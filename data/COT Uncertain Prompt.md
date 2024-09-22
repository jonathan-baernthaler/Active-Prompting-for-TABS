\_**\_ Include: \_\_\_**

Abstract:
Although numerous open-source tools exist for machine learning with tabular data, there is a scarcity of comparable resources tailored specifically for NLP. The lack of transparency in the inner workings of existing AutoNLP tools is a significant obstacle in scientific research. AutoML tools are known for their ability to perform model selection with little human intervention, improving the accuracy and reliability of the results. However, conducting a model space search among pre-trained NLP models can be computationally infeasible, making it challenging to determine the optimal NLP model for a given dataset. This research aims to enhance the performance of NLP model selection. Our approach has resulted in higher accuracy than existing methods on the dataset that was created. In our future work, we plan to benchmark our algorithm against datasets created by other researchers to validate its effectiveness. Additionally, we intend to use the same system to perform model selection among popular large language Transformer models.
Answer:

**Criterion A: Automated Machine Learning (AutoML) or related concepts: MET**
The abstract explicitly mentions "AutoNLP tools" and "AutoML tools," clearly addressing the requirement for Criterion A by discussing automated machine learning specifically tailored for Natural Language Processing (NLP).

**Criterion B: Reproducibility or related concepts: MET**
The abstract identifies the "lack of transparency in the inner workings of existing AutoNLP tools" as a significant issue. Discussing transparency directly addresses Criterion B, which looks for mentions of reproducibility or related concepts such as transparency or explainability in the context of AutoML or related tools.

**Combined Evaluation: INCLUDE**
Criteria A is MET and Criteria B is MET, therefore the Answer is 1 - INCLUDE

Abstract:
To assess the exposure of citizens to pollutants like NOx or particulate matter in urban areas, land use regression (LUR) models are a well established method. LUR models leverage information about environmental and anthropogenic factors such as cars, heating, or industry to predict air pollution in areas where no measurements have been made. However, existing approaches are often not globally applicable and require tedious hyper-parameter tuning to enable high quality predictions. In this work, we tackle these issues by introducing OpenLUR, an off-the-shelf approach for modeling air pollution that (i) works on a set of novel features solely extracted from the globally and openly available data source OpenStreetMap and (ii) is based on state-of-the-art machine learning featuring automated hyper-parameter tuning in order to minimize manual effort. We show that our proposed features are able to outperform their counterparts from local and closed sources, and illustrate how automated hyper parameter tuning can yield competitve results while alleviating the need for expert knowledge in machine learning and manual effort. Importantly, we further demonstrate the potential of the global availability of our features by applying cross-learning across different cities in order to reduce the need for a large amount of training samples. Overall, OpenLUR represents an off-the-shelf approach that facilitates easily reproducible experiments and the development of globally applicable models.
Answer:

**Criterion A: Automated Machine Learning (AutoML) or related concepts: MET**
The abstract explicitly mentions the use of "automated hyper-parameter tuning," which falls under the category of AutoML as it minimizes manual effort and enhances model performance through automation. This satisfies Criterion A.

**Criterion B: Reproducibility or related concepts: MET**
The abstract mentions that OpenLUR "represents an off-the-shelf approach that facilitates easily reproducible experiments." This clearly aligns with Criterion B, as it addresses the reproducibility of experiments within the context of their automated approach.

**Combined Evaluation: INCLUDE**
Criteria A is MET and Criteria B is MET, therefore the Answer is 1 - INCLUDE

Abstract:
Image analysis tasks in computational pathology are commonly solved using convolutional neural networks (CNNs). The selection of a suitable CNN architecture and hyperparameters is usually done through exploratory iterative optimization, which is computationally expensive and requires substantial manual work. The goal of this article is to evaluate how generic tools for neural network architecture search and hyperparameter optimization perform for common use cases in computational pathology. For this purpose, we evaluated one on-premises and one cloud-based tool for three different classification tasks for histological images: tissue classification, mutation prediction, and grading. We found that the default CNN architectures and parameterizations of the evaluated AutoML tools already yielded classification performance on par with the original publications. Hyperparameter optimization for these tasks did not substantially improve performance, despite the additional computational effort. However, performance varied substantially between classifiers obtained from individual AutoML runs due to non-deterministic effects. Generic CNN architectures and AutoML tools could thus be a viable alternative to manually optimizing CNN architectures and parametrizations. This would allow developers of software solutions for computational pathology to focus efforts on harder-to-automate tasks such as data curation.
Answer:

**Criterion A: Automated Machine Learning (AutoML) or related concepts: MET**
The abstract mentions "AutoML tools," "neural network architecture search," and "hyperparameter optimization," which are all related to automated machine learning (AutoML).
**Criterion B: Reproducibility or related concepts: MET**
Although the abstract does not explicitly mention reproducibility, it does refer to "performance varied substantially between classifiers obtained from individual AutoML runs due to non-deterministic effects." This indicates concerns about reproducibility and the non-deterministic nature of AutoML, which can impact the reproducibility of results.

**Combined Evaluation: INCLUDE**
Criteria A is MET and Criteria B is MET, therefore the Answer is 1 - INCLUDE

\_**\_ Exclude: \_\_\_**

Abstract:
Research into clinical applications of speech-based emotion recognition (SER) technologies has been steadily increasing over the past few years. One such potential application is the automatic recognition of expressed emotion (EE) components within family environments. The identification of EE is highly important as they have been linked with a range of adverse life events. Manual coding of these events requires time-consuming specialist training, amplifying the need for automated approaches. Herein we describe an automated machine learning approach for determining the degree of warmth, a key component of EE, from acoustic and text natural language features. Our dataset of 52 recorded interviews is taken from recordings, collected over 20 years ago, from a nationally representative birth cohort of British twin children, and was manually coded for EE by two researchers (inter-rater reliability 0.84--0.90). We demonstrate that the degree of warmth can be predicted with an F1score of 64.7 despite working with audio recordings of highly variable quality. Our highly promising results suggest that machine learning may be able to assist in the coding of EE in the near future.
Answer:

**Criterion A: Automated Machine Learning (AutoML) or related concepts: NOT MET**
While the abstract mentions "an automated machine learning approach," this refers to the automation of the research process using machine learning, not AutoML. The distinction is crucial: the study applies ML techniques in an automated fashion, but does not involve the automatic creation, optimization, or selection of ML models themselves. AutoML specifically refers to the automation of ML pipeline steps like feature selection, algorithm selection, and hyperparameter tuning. Therefore, it does not meet Criterion A

**Criterion B: Reproducibility or related concepts: NOT MET**
The abstract does **not** mention any concepts related to reproducibility, transparency, or explainability. There is no discussion about how the results can be replicated or whether the methodology employed is transparent or explainable. Criterion B requires the mention of reproducibility or related concepts in the context of AutoML or similar tools, which this abstract does not fulfill.

Criteria A is MET but Criteria B is NOT MET, therefore the Answer is 0 - EXCLUDE

Abstract:
Background: Automated analysis of cardiac structure and function using machine learning (ML) has great potential, but is currently hindered by poor generalizability. Comparison is traditionally against clinicians as a reference, ignoring inherent human inter-and intraobserver error, and ensuring that ML cannot demonstrate superiority. Measuring precision (scan:rescan reproducibility) addresses this. We compared precision of ML and humans using a multicenter, multi-disease, scan:rescan cardiovascular magnetic resonance data set. Methods: One hundred ten patients (5 disease categories, 5 institutions, 2 scanner manufacturers, and 2 field strengths) underwent scan:rescan cardiovascular magnetic resonance (96% within one week). After identification of the most precise human technique, left ventricular chamber volumes, mass, and ejection fraction were measured by an expert, a trained junior clinician, and a fully automated convolutional neural network trained on 599 independent multicenter disease cases. Scan:rescan coefficient of variation and 1000 bootstrapped 95% CIs were calculated and compared using mixed linear effects models. Results: Clinicians can be confident in detecting a 9% change in left ventricular ejection fraction, with greater than half of coefficient of variation attributable to intraobserver variation. Expert, trained junior, and automated scan:rescan precision were similar (for left ventricular ejection fraction, coefficient of variation 6.1 [5.2%-7.1%], P=0.2581; 8.3 [5.6%-10.3%], P=0.3653; 8.8 [6.1%-11.1%], P=0.8620). Automated analysis was 186$\times$ faster than humans (0.07 versus 13 minutes). Conclusions: Automated ML analysis is faster with similar precision to the most precise human techniques, even when challenged with real-world scan:rescan data. Assessment of multicenter, multi-vendor, multi-field strength scan:rescan data (available at www.thevolumesresource.com) permits a generalizable assessment of ML precision and may facilitate direct translation of ML to clinical practice. Copyright 2019 American Heart Association, Inc.

Answer:
**Criterion A: Automated Machine Learning (AutoML) or related concepts: NOT MET**
The abstract mentions a "fully automated convolutional neural network" for cardiac analysis, but this refers to the application of a pre-trained model rather than AutoML, low-code/no-code ML tools, or neural architecture search. While the process is automated, it does not involve the automatic creation, optimization, or selection of ML models. The focus is on the automated application of ML to cardiac imaging, not on automating the ML development process itself

**Criterion B: Reproducibility or related concepts: NOT MET**
The abstract mentions reproducibility, but it refers to scan-rescan reproducibility of cardiac measurements, not the reproducibility of AutoML processes or explainability of machine learning models. While the study compares the precision of ML and human analysis, it does not address transparency or explainability of the AutoML process itself. Therefore, it does not meet Criterion B

**Combined Evaluation: EXCLUDE**
Criteria A is NOT MET and Criteria B is NOT MET, therefore the Answer is 0 - EXCLUDE

Abstract:
Purpose: It is vital to appropriately power clinical trials towards discovery of novel disease-modifying therapies for Parkinson's disease (PD). Thus, it is critical to improve prediction of outcome in PD patients. Methods: We systematically probed a range of robust predictor algorithms, aiming to find best combinations of features for significantly improved prediction of motor outcome (MDS-UPDRS-III) in PD. We analyzed 204 PD patients with 18 features (clinical measures; dopamine-transporter (DAT) SPECT imaging measures), performing different randomized arrangements and utilizing data from 64%/6%/30% of patients in each arrangement for training/training validation/final testing. We pursued 3 approaches: i) 10 predictor algorithms (accompanied with automated machine learning hyperparameter tuning) were first applied on 32 experimentally created combinations of 18 features, ii) we utilized Feature Subset Selector Algorithms (FSSAs) for more systematic initial feature selection, and iii) considered all possible combinations between 18 features (262,143 states) to assess contributions of individual features. Results: A specific set (set 18) applied to the LOLIMOT (Local Linear Model Trees) predictor machine resulted in the lowest absolute error 4.32 $\pm$ 0.19, when we firstly experimentally created 32 combinations of 18 features. Subsequently, 2 FSSAs (Genetic Algorithm (GA) and Ant Colony Optimization (ACO)) selecting 5 features, combined with LOLIMOT, reached an error of 4.15 $\pm$ 0.46. Our final analysis indicated that longitudinal motor measures (MDS-UPDRS-III years 0 and 1) were highly significant predictors of motor outcome. Conclusions: We demonstrate excellent prediction of motor outcome in PD patients by employing automated hyperparameter tuning and optimal utilization of FSSAs and predictor algorithms. copyright 2019 Associazione Italiana di Fisica Medica
Answer:

**Criterion A: Automated Machine Learning (AutoML) or related concepts** MET:
The abstract mentions "automated machine learning hyperparameter tuning," which is a core component of AutoML.
**Criterion B: Reproducibility or related concepts: NOT MET**
This criterion is not met. The abstract does not mention reproducibility, transparency, or explainability, either in general or in the context of AutoML or its related concepts.
**Combined Evaluation: EXCLUDE**
Criteria A is MET but Criteria B is NOT MET, therefore the Answer is 0 - EXCLUDE
