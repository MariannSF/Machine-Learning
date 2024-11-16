Assignment 1

1.	Data Preprocessing:

		Categorical data was mapped to numerical values.
		Continuous features (e.g., age, fnlwgt) were bucketed into discrete bins, but this impacted model performance slightly.
		The dataset was scaled using StandardScaler for normalization.
		
2.	Model Comparisons:

		Decision Tree (DT):
			Initial results: ~79% accuracy.
			Post-tuning with a max depth of 9: ~83% accuracy and an F1 score of ~84.8%.
			
		Random Forest:
			Accuracy: ~82%.
			Log loss and feature importance analysis revealed key influential features.
			
		AdaBoost:
			Performed well with an accuracy of ~82.4% and an F1 score of ~81.2%.
			
		Neural Networks:
			Achieved ~82.3% accuracy and an F1 score of ~81.8%.
			
		SVM:
			Linear kernel: ~81.7% accuracy.
			Polynomial kernel outperformed others with ~82.4% accuracy.
			
		KNN:
			Optimal neighbors = 36, yielding ~83% accuracy.
			
		Feature Importance:
			Top features identified include workclass, education_num, marital_status, and occupation.
			Some features like capital_loss and native_country had minimal impact.
			
		Learning Curves:
			Visualizations showed evidence of overfitting in some models like DT without depth pruning.
			AdaBoost and Random Forest models showed balanced performance.
