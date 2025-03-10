# Yuxin-Guo-Thesis_Project

This thesis project is created by Yuxin Guo, student ID is 23009014.

This project is about correctly identifying the emotions and scenario in user chats in WeChat, and polishing and generating negative content. Improve conflicts caused by text communication between users on instant messaging devices.

Due to the large amount of data used in this project and the complexity of the model, a GPU is required. Therefore, Kaggle’s GPU T4*2 was borrowed to ensure the operation and training of the project. All code is completed in Kaggle, so it can only be run in the Kaggle environment and cannot be run locally.

In the database, the two csv files "cleaned_data" and "data_processing" were too large, so they were uploaded to Google Drive. These two data sets are the data generated by the preliminary cleaning part and Lemmatization, Stemming, and machine learning of the data, and were re-saved.

“clean_data” Google Drive link: https://drive.google.com/file/d/1FV34i5fwTbe8lXk208INJOLTQazekkVQ/view?usp=sharing
"data_processing" Google Drive link: https://drive.google.com/file/d/1VP-u0WUiBhcZG5etWbZcRmoSlc-4kffW/view?usp=sharing

This trained model was originally in the roberta_saved_model folder. Since my trained sentiment classification model also was too big, I uploaded the RoBERTa model to Google Drive with the link：https://drive.google.com/file/d/1qgSaqUgZ6d74v99ELrv4Rv5FiFSylX8i/view?usp=sharing. This link can download model, and the code can use this model.
