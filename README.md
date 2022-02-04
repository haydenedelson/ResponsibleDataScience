# Responsible Data Science

The notebook `Fairness_Disparate_Impact_Removal.ipynb` contains applications of the [AIF360](https://aif360.mybluemix.net/) library--a library for reducing bias and discrimination in ML models. The notebook includes applications of the [Disparate Impact Removal](https://aif360.readthedocs.io/en/stable/modules/generated/aif360.algorithms.preprocessing.DisparateImpactRemover.html) and [Reject Option Post-Processing](https://aif360.readthedocs.io/en/stable/modules/generated/aif360.algorithms.postprocessing.RejectOptionClassification.html) APIs.

The notebook `Data_Synthesizer.ipynb` contains applications of the [Data Synthesizer](https://github.com/DataResponsibly/DataSynthesizer) library, a toolkit for applying [differential privacy](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/dwork.pdf) techniques to sensitive data sets. The notebook explores the library's three data generation modes: random mode, independent attribute mode, and correlated attribute mode.

The notebook `Explainable_NLP.ipynb` uses the [SHAP](https://shap.readthedocs.io/en/latest/index.html#) library--an explainable AI library--to explore the predictions of some simple ML models trained on the [20 Newsgroups dataset](http://qwone.com/~jason/20Newsgroups/).
