This project aims to predict user preferences between chatbot responses using data from the Chatbot Arena, a platform that evaluates LLMs based on human feedback. A transformer-based model utilizing DeBERTa-v3 is employed to classify chatbot responses into three categories: preferred responses from Model A, Model B, or a tie. The model's performance is assessed using a 5-fold cross-validation approach, with metrics such as log loss guiding the evaluation. Data analysis revealed key insights, including the dominance of GPT models and the influence of prompt and response lengths. While the model performed well during training, validation results highlighted areas for improvement. These findings suggest that hyperparameter tuning, regularization, data augmentation, and the exploration of more advanced architectures could further enhance prediction accuracy.
