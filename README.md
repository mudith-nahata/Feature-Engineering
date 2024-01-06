**Formal Definition**

---> Feature engineering is the process of using domain knowledge to extract features from raw data to improve the perfomance of Machine Learning Model.

![image](https://github.com/mudith-nahata/Feature-Engineering/assets/96544398/746568bc-c171-4baa-ad74-0d637f3090be)

**Types of Feature Engineering**

---> Feature Engineering are classified into three types 

                       1) feature transformation

                       2) feature construction

                       3) feature selection

                       4) feature extraction

**Techniques of Feature Transformation**

---> We have four types of feature transformation techniques

                        1) missing value imputation

                        2) handling categorical features

                        3) outliers

                        4) feature scaling

  **Missing Value Imputation**

  ---> the missing value is a feature transformatio technique which is used to observe and predict the missing values from the data.

  ---> if we have large amount of missing vaalues in our data so it is a daunting task to fill the missing values in the data.

  **Handling Categorical Features**

  ---> Handling categorical features is a feature transformation technique which is used to encode the entire input column.

  ---> based on every row of an input data  will be transformed as output column and will be encoded based on the input data.

  **Outlier Detection**

  ---> Outlier Detection is a feature transformation technique which is used to detect the deifferent input columns from the data.

  ---> the term outlier means the data which is different from the other data.

  **Feature Scaling**

  ---> Feature scaling is a feature transformation technique which is used to set the range between any two features.

  ---> Feature scaling is done before we train the Machine Learning Model.

  **Feature Construction**

  ---> Feature construction is a technique of feature engineering.

  ---> It is the process of constructing new features from existing features in a data.

  ---> Based on the Constructed or new features we derive the categorical variable.

  ---> And it also varies from data to data and domain to domain.

  **Feature Selection**

  ---> Feature Selection is the technique of feature engineering,

  ---> Feature selection is the process of selecting the features from the Imput data.

  ---> The Best example of working with feature selection is **MNIST** dataset which is famous in Machine Learning and Deep Learning with Convolutional Neural Network. 

  ---> So whatever the image they have given and it will be converted to the tabular form

  ---> where each pixel is represented in each row

  ---> Each categories of pixel are represented in column

  **Feature Extraction**
  
   ---> Feature Extraction is a technique of feature Engineering

   ---> Feature Extraction is used to create the new features by programming.

          Techniques:-

                . Principle Component Analysis(PCA)

                . Linear Discriminant Analysis(LDA)

  **Feature Scaling**

  ---> Feature scaling is a technique  of feature engineering

  ---> feature scaling is done before we train the data to the Machine Learning Model.

  ---> And it is easy to use in feature engineering.

  **Formal Definition of feature Scaling**

    ---> Feature scaling is a technique which is used to standardize the independent features present in a data in a fixed range.

    ---> So whener we get large values that will be dominated and KNN will not perform efficiently.

    ---> if we do not scale the values we will not get good results.

    Types of Feature Scaling

         1) Standardization

         2) Normalization

  **Standardization**

  ---> standardization is a type of feature scaling
  
.
  ---> sometimes in the Machine Learning Literature it is also called as Z-Score Normalization. 

  ---> Standardization technique is used to transform the data and calculate the mean and standard deviation from the input data.
  
  ---> if the Mean is zero and standard deviation is one then the given data is scaled data.

                          Formula to calulate standard deviation=xi'=xi-mean/standard deviation

  **When to use standardization technique:-**

       . K-Means Algorithm

       . k-Nearest-Neigbour(KNN)

       . Principle Component Analysis(PCA)

       . Artifical Neural Network(ANN)

       . Gradient Descent

       
  


  



