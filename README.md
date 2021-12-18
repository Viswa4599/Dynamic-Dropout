# Dynamic-Dropout
### Anusha Misra, Viswajit Vinod Nair

Repository for Practical Deep Learning Final Project presentation

- We have devised a dropout policy that varies the dropout at each epoch based on the training and validation loss of previous epochs

  ![image](https://user-images.githubusercontent.com/39920874/146623512-ea4b2de2-c899-425d-8b5a-42d55627dcc0.png)

  ![image](https://user-images.githubusercontent.com/39920874/146623473-dc45ff01-a01a-4bb7-8e19-27675d516123.png)

- The policy has been evaluated on the following datasets:
  - Fashion-MNIST (Image)
  - CIFAR-10 (Image)
  - IMDB Reviews (Text)
  
- Models used were:
  - LeNet-5
  - BERT semantic classifier (derived from: https://www.kaggle.com/atulanandjha/bert-testing-on-imdb-dataset-extensive-tutorial)
 
- Instructions:
  - Each dataset has it's own folder containing the notebook with the code to run and results.
  - The training and testing data is in a '.txt' file in each folder.
  - It is recommended to run the notebooks on a GPU
  - Kaggle link for the BERT notebook (with the dataset): https://www.kaggle.com/viswajitvinodnair/bert-dynamic?scriptVersionId=82629256
 
 - Results:
    - The loss plots and dropout variation plots are given in each folder.
    - The accuracy and f-1 for each dataset is given below:
 ![image](https://user-images.githubusercontent.com/39920874/146623802-36dafdf0-1e21-466d-bf94-9b07035fe6b6.png)

    ![image](https://user-images.githubusercontent.com/39920874/146623810-b63d999b-3496-4f7e-a08c-1e2f27878db1.png)
