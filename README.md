# Candidate Matching (NLP)

This project focuses on finding suitable candidates for job positions by utilizing pre-trained BERT for determining the similarity between job descriptions and resumes. The similarity score obtained from BERT is then used as a feature and fed into a CatBoost classifier for the task of classification.

## 📊 Dataset
The dataset used in this project consists of job descriptions and resumes, which were preprocessed to ensure they are clean and formatted appropriately for training the model.

## ⚙️ Training
The pre-trained BERT model was fine-tuned on the dataset to calculate the similarity scores between job descriptions and resumes. These scores were then used as features to train a CatBoost classifier, optimizing its parameters to achieve the best classification results.

## 📈 Evaluation
The performance of the model was evaluated using metrics such as accuracy, precision, recall, and F1 score. Additionally, the model's ability to match candidates with job positions effectively was assessed to ensure its practical utility.

## 🚀 Usage
To use the candidate matching system, input a job description and a resume into the model, which will calculate the similarity score and classify the candidate as suitable or not.

## 🔮 Future Improvements
Future enhancements to the model could involve experimenting with different pre-trained language models, fine-tuning hyperparameters, and exploring additional features to improve the accuracy and efficiency of candidate matching.
