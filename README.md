# E_commerce_replication_package

## abstract:
Selecting an e-commerce platform is a very crucial task when opening an online store.
Diversity of technology stacks has led to dozens of e-commerce platforms with a variety of features. 
While previous studies have shown that developers struggle with various issues during the development of an online business store. 
In this study, we explore 19 e-commerce platforms to understand whether their features correlate with the experience of developers. 
By analyzing the questions that developers ask on the question-and-answer site Stack Overflow, we find that developers ask questions on 17 e-commerce website development related issues that can be grouped into 5 major themes (i.e., database management, payment options, sales features, website design features, and website errors). 
In addition, our analyses also indicate that the technology stack of e-commerce platforms correlates with the development and maintenance experience of an online store by developers.

## Replication package Structure:
```
📁 Package Management project/
├─ 📁 Dataset/
├─ 📁 Scripts/ 
├─ 📁 Results/
─
```
## Contents:
  1. [Dataset](https://github.com/syful-is/E_commerce_replication_package/tree/main/Dataset)- is a folder that contains the dataset for `PM project`.
  2. [Scripts](https://github.com/syful-is/E_commerce_replication_package/tree/main/Scripts)- is a folder that contains the all the codes. 
  3. [Results](https://github.com/syful-is/E_commerce_replication_package/tree/main/Results)- is a folder that contains the results obtained from dataset.

## How to run:
  1. Clone the repository from [here](https://github.com/syful-is/E_commerce_replication_package.git) and the Dataset from [here](https://github.com/syful-is/E_commerce_replication_package/tree/main/Dataset)
  2. Extract the files.
  3. Open `Jupyter Notebook` or `Python Spyder`.
  4. Copy any code and Set your working directory using 
                
                ```
                import os
                
                #Please specify your dataset directory. 
                os.chdir("..../Dataset/")
                ```
  
  4. Example-1: Run the LDA topic modeling **[LDA_Ecommerce.ipynb](https://github.com/syful-is/E_commerce_replication_package/blob/main/Scripts/LDA_Ecommerce.ipynb)** 

## Authors:
1. [Syful Islam](https://syful-is.github.io/), Nara Institute of Science and Technology (NAIST), Nara, Japan.



