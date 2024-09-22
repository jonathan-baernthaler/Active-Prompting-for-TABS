\_**\_ Include: \_\_\_**

Abstract:
The interplay of machine learning (ML) and deep learning (DL) within the agroclimatic domain is pivotal for addressing the multifaceted challenges posed by climate change on agriculture. This paper embarks on a systematic review to dissect the current utilization of ML and DL in agricultural research, with a pronounced emphasis on agroclimatic impacts and adaptation strategies. Our investigation reveals a dominant reliance on conventional ML models and uncovers a critical gap in the documentation of methodologies. This constrains the replicability, scalability, and adaptability of these technologies in agroclimatic research. In response to these challenges, we advocate for a strategic pivot toward Automated Machine Learning (AutoML) frameworks. AutoML not only simplifies and standardizes the model development process but also democratizes ML expertise, thereby catalyzing the advancement in agroclimatic research. The incorporation of AutoML stands to significantly enhance research scalability, adaptability, and overall performance, ushering in a new era of innovation in agricultural practices tailored to mitigate and adapt to climate change. This paper underscores the untapped potential of AutoML in revolutionizing agroclimatic research, propelling forward the development of sustainable and efficient agricultural solutions that are responsive to the evolving climate dynamics.
Answer:

**Criterion A: Automated Machine Learning (AutoML) or related concepts: MET**
The abstract explicitly mentions "Automated Machine Learning (AutoML)" multiple times and discusses its importance in the context of agroclimatic research. This satisfies the requirement for Criterion A.

**Criterion B: Reproducibility or related concepts: MET**
The abstract highlights the "critical gap in the documentation of methodologies" and how AutoML can tackle the issues of replicability, scalability and adaptability. This aligns with the concepts of reproducibility and transparency in the context of AutoML and satisfies the requirement for Criterion B

**Combined Evaluation: INCLUDE**
Criteria A is MET and Criteria B is MET, therefore the Answer is 1 - INCLUDE

The Abstract:
Due to the concerted efforts to utilize the microbial features to improve disease prediction capabilities, automated machine learning (AutoML) systems aiming to get rid of the tediousness in manually performing ML tasks are in great demand. Here we developed mAML, an ML model-building pipeline, which can automatically and rapidly generate optimized and interpretable models for personalized microbiome-based classification tasks in a reproducible way. The pipeline is deployed on a web-based platform, while the server is user-friendly and flexible and has been designed to be scalable according to the specific requirements. This pipeline exhibits high performance for 13 benchmark datasets including both binary and multi-class classification tasks. In addition, to facilitate the application of mAML and expand the human disease-related microbiome learning repository, we developed GMrepo ML repository (GMrepo Microbiome Learning repository) from the GMrepo database. The repository involves 120 microbiome-based classification tasks for 85 human-disease phenotypes referring to 12 429 metagenomic samples and 38 643 amplicon samples. The mAML pipeline and the GMrepo ML repository are expected to be important resources for researches in microbiology and algorithm developments. Database URL: http://lab.malab.cn/soft/mAML copyright 2020 The Author(s) 2020. Published by Oxford University Press.

**Criterion A: Automated Machine Learning (AutoML) or related concepts: MET**

- The abstract mentions “automated machine learning (AutoML) systems” explicitly.
- It also mentions "an ML model-building pipeline," which aligns with the concept of automated processes in machine learning.

**Criterion B: Reproducibility or related concepts: MET**

- The abstract states that the pipeline can generate "interpretable models," which relates to explainability.
- It also explicitly mentions the pipeline can operate in “a reproducible way.”

**Combined Evaluation: INCLUDE**
Criteria A is MET and Criteria B is MET, therefore the Answer is 1 - INCLUDE

The Abstract:
In the last 10 years, various automated machine learning (AutoML) systems have been proposed to build end-to-end machine learning (ML) pipelines with minimal human interaction. Even though such automatically synthesized ML pipelines are able to achieve competitive performance, recent studies have shown that users do not trust models constructed by AutoML due to missing transparency of AutoML systems and missing explanations for the constructed ML pipelines. In a requirements analysis study with 36 domain experts, data scientists, and AutoML researchers from different professions with vastly different expertise in ML, we collect detailed informational needs for AutoML. We propose XAutoML, an interactive visual analytics tool for explaining arbitrary AutoML optimization procedures and ML pipelines constructed by AutoML. XAutoML combines interactive visualizations with established techniques from explainable artificial intelligence (XAI) to make the complete AutoML procedure transparent and explainable. By integrating XAutoML with JupyterLab, experienced users can extend the visual analytics with ad-hoc visualizations based on information extracted from XAutoML. We validate our approach in a user study with the same diverse user group from the requirements analysis. All participants were able to extract useful information from XAutoML, leading to a significantly increased understanding of ML pipelines produced by AutoML and the AutoML optimization itself. copyright 2023 Copyright held by the owner/author(s)

**Criterion A: Automated Machine Learning (AutoML) or related concepts: MET**

- The abstract mentions "automated machine learning (AutoML) systems" more than once.
  **Criterion B: Reproducibility or related concepts: MET**
- The abstract repeatedly addresses the issue of "transparency" with regard to AutoML systems.
- It also discusses the "explanations for the constructed ML pipelines," and describes XAutoML as a tool that makes the AutoML procedure "transparent and explainable."
  **Combined Evaluation: INCLUDE**
  Criteria A is MET and Criteria B is MET, therefore the Answer is 1 - INCLUDE

**\_Exclude\_\_**

Abstract:
Background: Unfractionated heparin (UFH) is an anticoagulant drug that is considered a high-risk medication because an excessive dose can cause bleeding, whereas an insufficient dose can lead to a recurrent embolic event. Therapeutic response to the initiation of intravenous UFH is monitored using activated partial thromboplastin time (aPTT) as a measure of blood clotting time. Clinicians iteratively adjust the dose of UFH toward a target, indication-defined therapeutic aPTT range using nomograms, but this process can be imprecise and can take = 36 hours to achieve the target range. Thus, a more efficient approach is required.Objective: In this study, we aimed to develop and validate a machine learning (ML) algorithm to predict aPTT within 12 hours after a specified bolus and maintenance dose of UFH.Methods: This was a retrospective cohort study of 3019 patient episodes of care from January 2017 to August 2020 using data collected from electronic health records of 5 hospitals in Queensland, Australia. Data from 4 hospitals were used to build and test ensemble models using cross-validation, whereas data from the fifth hospital were used for external validation. We built 2 ML models: a regression model to predict the aPTT value after a UFH bolus dose and a multiclass model to predict the aPTT, classified as subtherapeutic (aPTT 70 seconds), therapeutic (aPTT 70-100 seconds), or supratherapeutic (aPTT 100 seconds). Modeling was performed using Driverless AI (H2O), an automated ML tool, and 17 different experiments were iteratively conducted to optimize model accuracy.Results: In predicting aPTT, the best performing model was an ensemble with 4x LightGBM models with a root mean square error of 31.35 (SD 1.37). In predicting the aPTT class using a repurposed data set, the best performing ensemble model achieved an accuracy of 0.599 (SD 0.0289) and an area under the receiver operating characteristic curve of 0.735. External validation yielded similar results: root mean square error of 30.52 (SD 1.29) for the aPTT prediction model, and accuracy of 0.568 (SD 0.0315) and area under the receiver operating characteristic curve of 0.724 for the aPTT multiclassification model.Conclusions: To the best of our knowledge, this is the first ML model applied to intravenous UFH dosing that has been developed and externally validated in a multisite adult general medical and surgical inpatient setting. We present the processes of data collection, preparation, and feature engineering for replication.

1. **Criterion A: Automated Machine Learning (AutoML) or related concepts: MET**

- The abstract mentions "Driverless AI (H2O), an automated ML tool," which satisfies the requirement for Criterion A as it discusses the use of an AutoML tool for modeling.

2. **Criterion B: Reproducibility or related concepts: NOT MET**

- Although the abstract states that the article discusses, the process of data collection, preparation, and feature engineering for replication, it does _not_ explicitly mention reproducibility, transparency, or explainability in the context of AutoML or related concepts. Criterion B requires that these concepts be explicitly mentioned, which is not done in the abstract. The focus on external validation and model accuracy does not equate to an explicit discussion about reproducibility or transparency.
  **Combined Evaluation: EXCLUDE**
  Criterion A is MET, But Critereon B is NOT MET, therefore the final decision is EXCLUDE (0)

The Abstract:
The widespread abuse of legal high psychoactive plants continues to be of global concern because of their negative impacts on public health and safety. In forensic science, a major challenge in controlling these substances is the paucity of methods to rapidly identify them. We report the development of the Database of Psychoactive Plants (DoPP), a new user-friendly tool featuring an architecture for the identification of plant unknowns, and the necessary regression statistics for the development and validation of psychoactive compound quantification. The application relies on the knowledge that terrestrial plants exhibit species-specific chemical signatures that can be revealed by direct analysis in real time─high-resolution mass spectrometry (DART-HRMS). Subsequent automated machine learning processing of libraries of these spectra enables rapid discrimination and species identification. The chemical signature database includes 57 available plant species. The rapid acquisition of mass spectra and the ability to sample the materials in their native form enabled the generation of the vast amounts of spectral replicates required for database construction. For the identification of sample unknowns, a data analysis workflow was developed and implemented using the DoPP tool. It utilizes a hierarchical classification tree that integrates three machine learning methods, namely, random forest, k-nearest neighbors, and support vector machine, all of which were fused using posterior probabilities. The results show accuracies of 98 and 99% for 10-fold cross-validation and external validation, respectively, which make the classification model suitable for identity prediction of real samples. copyright 2022 American Chemical Society.

**Criterion A: Automated Machine Learning (AutoML) or related concepts: NOT MET**
The abstract mentions "automated machine learning processing," but upon closer examination, this refers to the automation of data analysis rather than AutoML, low-code/no-code ML tools, or neural architecture search. Therefore, it does not meet Criterion A's requirement for explicit mention of AutoML or related concepts.

**Criterion B: Reproducibility or related concepts: NOT MET**

- The abstract does not mention reproducibility, transparency, explainability, or any related concepts directly in the context of AutoML or the applied machine learning methods.

**Combined Evaluation: EXCLUDE**
Criteria A is partially MET but Criteria B is NOT MET, therefore the Answer is EXCLUDE (0)

Sequence-based analysis and prediction are fundamental bioinformatic tasks that facilitate understanding of the sequence(-structure)-function paradigm for DNAs, RNAs and proteins. Rapid accumulation of sequences requires equally pervasive development of new predictive models, which depends on the availability of effective tools that support these efforts. We introduce iLearnPlus, the first machine-learning platform with graphical-and web-based interfaces for the construction of machine-learning pipelines for analysis and predictions using nucleic acid and protein sequences. iLearnPlus provides a comprehensive set of algorithms and automates sequence-based feature extraction and analysis, construction and deployment of models, assessment of predictive performance, statistical analysis, and data visualization; all without programming. iLearnPlus includes a wide range of feature sets which encode information from the input sequences and over twenty machine-learning algorithms that cover several deep-learning approaches, outnumbering the current solutions by a wide margin. Our solution caters to experienced bioinformaticians, given the broad range of options, and biologists with no programming background, given the point-and-click interface and easy-to-follow design process. We showcase iLearnPlus with two case studies concerning prediction of long noncoding RNAs (lncRNAs) from RNA transcripts and prediction of crotonylation sites in protein chains. iLearnPlus is an open-source platform available at https://github.com/Superzchen/iLearnPlus/with the webserver at http://ilearnplus.erc.monash.edu/. copyright 2021 The Author(s). Published by Oxford University Press on behalf of Nucleic Acids Research.

**Criterion A: Automated Machine Learning (AutoML) or related concepts: MET**

- The abstract mentions "iLearnPlus, the first machine-learning platform with graphical-and web-based interfaces for the construction of machine-learning pipelines." This aligns closely with the concept of low-code/no-code machine learning tools.
- It describes the automation of various tasks such as feature extraction, model construction, deployment, and performance assessment, which are core aspects of AutoML.

**Criterion B: Reproducibility or related concepts: NOT MET**

- The abstract does not explicitly mention reproducibility, transparency, or explainability in the context of iLearnPlus or the machine learning models it helps create.
- It focuses on the features, capabilities, and user interface of the iLearnPlus platform without addressing how the results or processes are made reproducible, transparent, or explainable.
  **Combined Evaluation: EXCLUDE**
  Criteria A is MET but Criteria B is NOT MET, therefore the Answer is 0 - EXCLUDE
