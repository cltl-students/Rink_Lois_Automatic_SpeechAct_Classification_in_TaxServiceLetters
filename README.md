This repository contains the code for the thesis project on speech act classification in tax service letters from the tax domain. This thesis project is completed in cooperation with the Belastingdienst. Due to confidentiality reasons, the data used for this project will not be published. 

This repository contains the final thesis and the supporting code in jupyter notebooks. In this way, the coding steps can be followed without revealing too much of the data.

It is adviced to not run the notebooks since the output will disappear.


This repository contain the following files:


-Preprocessing.ipynb: This code is used to prepare the dataset for the annotation experiment. After generating this file, the samples for the annotation experiment are manually assembled

-Annotation_evaluation.ipynb: This code evaluates the samples that were annotated during the annotation experiment. The inter annotator agreement (IAA) is evaluated and the sentences that caused disagreement are saved to a csv so that they can be manually solved.

-Exploratory_data_analysis.ipynb: This code is used to analyze the final dataset that was assembled after manual solving of the disagreement in the annotation experiment. It analyzes the distribution of the data, subdomains of the letters and the labels. 

-RBS.ipynb: This code implements and evaluates the rule based system that uses the occurence of Speech act verbs to determine the speech act.

-SVM_DT.ipynb: This code implements and evaluates the SVM and DT experiments, the SVM+context features experiment and the SVM+ speech act verbs features model.

-Catboost.ipynb: This code shows the implementation and evaluation of the Catboost experiment. 

-BERTje-final.ipynb: This code trains, validates and tests the pipeline that uses the pre-trained language model BERTje for speech act classification.

-requirements.txt: Information about packages used for this project.