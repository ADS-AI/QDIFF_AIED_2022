# DATASET: <br />
train_qdiff_dataset_2.csv -  Qa-data training set. <br />
val_qdiff_dataset_2.csv - Qa-data validation set. <br />
test_qdiff_dataset_2.csv - Qa-data testing set  <br />
# CODE: <br />
bloom_predicted_qdiff_interactive__attention_difficulty_ensemble_with_statistical_significance.ipynb  -  Constructs an ensemble of models trained on QC-Science and performs statistical significance tests. <br />
difficulty_ensemble_statistical_significance_data_2.ipynb - Ensemble construction of models trained on QA-data dataset and performs statistical significance tests. <br />
multi_task_qdiff_interactive_attention_BERT_data_2_final.ipynb - notebook implementing IA_BERT, the core method discussed in the paper. In this notebook it is trained on QA-data. This notebook contains both training and inference scripts for QA-data. <br />
multi_task_qdiff_interactive_attention_BERT_final.ipynb - notebook implementing IA_BERT, the core method discussed in the paper. In this notebook it is trained on QC-Science. This notebook contains both training and inference scripts for QC-Science. <br />
multi_task_qdiff_interactive_attention_bloom_label_given_data_2.ipynb - notebook implementing a variation of IA_BERT where the bloom level instead of being jointly predicted with difficulty label is actually considered as given ground truth. Notebook performs training and inference on QA-data. <br />
multi_task_qdiff_interactive_attention_bloom_label_given_final.ipynb - notebook implementing a variation of IA_BERT where the bloom level instead of being jointly predicted with difficulty label is actually considered as given ground truth. Notebook performs training and inference on QC-Science. <br />
BERT_difficult_name_cascade_data_2.ipynb - notebook to implement difficulty prediction in a cascade setting where a model is first trained to predict the bloom’s taxonomy level. Then the model is fine-tuned to predict the difficulty level. <br />
multi_task_qdiff_interactive_attention_pre_trained_skill_bert.ipynb - notebook where bloom level is not jointly predicted but rather a pre-trained skill prediction BERT model is used. Contains training and inference scripts for QC-Science data. <br />
skill_prediction_multi_task_qdiff_interactive_attention_difficulty_label_given.ipynb - notebook where bloom level is predicted using a variant of IA_BERT with the difficulty label considered as an input instead of being jointly predicted. <br />
multi_task_qdiff_interactive_attention_pre_trained_skill_bert_data_2.ipynb - notebook where bloom level is not jointly predicted but rather a pre-trained skill prediction BERT model is used. Contains training and inference scripts for QA-data dataset. <br />

