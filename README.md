# Dynamic_Attention_Mechanism

This is our project for our NLP module.

This project is about the experimental study on dynamic attention mechanism in Deep Pyramid CNN (DPCNN) for sentiment anaysis.
The experiment has been conducted on 2 datasets namely the financial and tweet datasets. The methodology and results of this project can be found in the report pdf file.

Our codes have been adapted from the following sources:
1) https://www.analyticsvidhya.com/blog/2020/07/transfer-learning-for-nlp-fine-tuning-bert-for-text-classification/
2) https://www.programmersought.com/article/31037125394/


There are sub folders in the SourceCode folder. All the codes are done in colab.

1) Finance:
	Contains 3 notebooks on the training done on financial data.
	Each notebook is for each model.
	1_xxx_xxx : base model
	2_xxx_xxx : global attention
	3_xxx_xx : self attention


2) Tweet
	Contains 3 notebooks on the training done on tweet data.	
	Each notebook is for each model.
	1_xxx_xxx : base model
	2_xxx_xxx : global attention
	3_xxx_xx : self attention


3) Error_Analysis:
	Contains 4 sample notebooks on the error analysis done for 2 types of attention for 2 types of datasets.
	Requires models saved in .pkl files.
