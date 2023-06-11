# MongoDB - Pymongo restaurant project

This project was divided into **3 phases**: **1)** Importing the dataset into MongoDB, creating a pymongo instance connection and checking databases and collections. **2)** Adding a new restaurant and updating its 'BussinessTypeID' and transforming the collection, changing the datatype from string to decimal in geocode latitude and longitude fields. **3)** Exploratory analysis for example, selecting how many restaurants in London have a 'RatingValue' greater than or equal to 4, or which restaurants have a 'RatingValue' of 5 near the new restaurant added on stage one, etc.
# 

## 1 - SETUP

I started importing the dataset into MongoDB by using mongoimport on git bash, and then I am ready to start coding on jupyter notebook:

![image](https://github.com/Daniels2023/nosql-challenge/assets/124798004/acf9ad5c-8323-4aad-9169-048f95fcc913)
# 

## 2 - MongoDB manipulation

I created a variable to store the new restaurant document, then updated the 'BussinessTypeID', I also deleted all restaurants located in 'Dover' and I changed the datatype to decimal in longitude and latitude fields.

![image](https://github.com/Daniels2023/nosql-challenge/assets/124798004/080c331a-6b63-4ad1-a3a6-577ef7543c6a)

![image](https://github.com/Daniels2023/nosql-challenge/assets/124798004/d9f16bda-f7c3-45f0-a68b-c89c06802def)

![image](https://github.com/Daniels2023/nosql-challenge/assets/124798004/0e1e5a35-fba6-45e7-beb4-d6651a897f9b)

![image](https://github.com/Daniels2023/nosql-challenge/assets/124798004/c9e1956a-63c7-439a-9f9e-0201edf4f6c9)
# 

## 3 - Exploratory Analysis

In this stage, I looked for some answers, for example:

**Which establishments in London have a `RatingValue` greater than or equal to 4?**

![image](https://github.com/Daniels2023/nosql-challenge/assets/124798004/bda63c33-0042-43f9-87f0-373717865d61)
# 

**What are the top 5 establishments with a `RatingValue` rating value of '5', sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?**

![image](https://github.com/Daniels2023/nosql-challenge/assets/124798004/31c436a4-7375-4f66-bddd-d2e4a90a39df)
