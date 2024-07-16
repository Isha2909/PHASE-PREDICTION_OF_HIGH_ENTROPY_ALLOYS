# PHASE-PREDICTION_OF_HIGH_ENTROPY_ALLOYS
- ### Project Overview
 High Entropy Alloys (HEAs) are composed of five or more principal elements mixed in near-equal proportions. Predicting the phases of HEAs is crucial for understanding their properties and 
 potential applications. This project utilizes advanced machine learning algorithms to predict the phase formation of HEAs based on their elemental composition.
## Key Features

- **Data Cleaning and Preprocessing**: Compilation of a comprehensive dataset of HEA compositions and their corresponding phases. Data preprocessing includes normalization and feature engineering to enhance predictive accuracy .
  
  ![image](https://github.com/user-attachments/assets/064a2603-e44f-4cb2-b772-c93825e87951)

  ![image](https://github.com/user-attachments/assets/9d93532e-0700-4539-a791-95a319d9fae3)
  
 **Introducing some new features** :
  
  ![image](https://github.com/user-attachments/assets/4f4661ea-9ecb-44b7-b90f-9e12d91b9d2d)

  ![image](https://github.com/user-attachments/assets/52431e07-6dea-408c-a143-359c714a3328)
- **Data Visualization** :

   ![image](https://github.com/user-attachments/assets/9533fdb8-a14d-49d7-bdc7-6c4dd1e63750)

  ![image](https://github.com/user-attachments/assets/90e62bb1-dea8-4af2-a336-973f62c32b92)

 ![image](https://github.com/user-attachments/assets/cfded6c8-1f59-4fc1-90f1-f56cef841713)

  ![image](https://github.com/user-attachments/assets/5dd54936-b844-46b3-a414-8343eea3b60f)
- **Correlation Plot** :
  
   ![image](https://github.com/user-attachments/assets/44b6f267-1a16-4975-8861-f28f65be406d)
   ![image](https://github.com/user-attachments/assets/9d2eadd8-9d7d-4490-8926-4ad5451c1b20)


- **Machine Learning Models**: Implementation of Decseion Tree, XG Boost and Random Forest for phase prediction.
  
   ![image](https://github.com/user-attachments/assets/76267da1-e7a0-4952-a559-1136b69a87a4)
  
   - Using deceseion tree accuarcy was so low so we treid Random Forest and XGboost but performance didnot improve much .
   - So we performed Hyperparamter tuning using optuna .
     Still not much improvement
    - So we used Smote to balance the imbalanced phases data .

      ![image](https://github.com/user-attachments/assets/6023a3d1-4f73-42ec-9dcc-a9c0e1722005)
  - Now we predicted the phases using smoted data and random forest :

    ![image](https://github.com/user-attachments/assets/a7ef512c-d80f-4877-a1fe-830dfece31ad)


- **Model Evaluation**: Comprehensively evaluated  model performance using metrics sucha as  accuracy, precision, recall, and F1-score. Cross-validation is employed to ensure robustness and generalizability of the models.
  
   ![image](https://github.com/user-attachments/assets/da8269d6-d50a-41cb-aa04-4546884f5fdb)



