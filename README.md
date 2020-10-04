# breast-cancer-detection
This python program uses Logistic regression to predict the Breast cancer Detection.The collective information is been given 
as input based on that the algorithm will be resulting in Malignant or Benign....

the features are:
Data columns (total 33 columns):
id                         569 non-null int64
diagnosis                  569 non-null object
radius_mean                569 non-null float64
texture_mean               569 non-null float64
perimeter_mean             569 non-null float64
area_mean                  569 non-null float64
smoothness_mean            569 non-null float64
compactness_mean           569 non-null float64
concavity_mean             569 non-null float64
concave points_mean        569 non-null float64
symmetry_mean              569 non-null float64
fractal_dimension_mean     569 non-null float64
radius_se                  569 non-null float64
texture_se                 569 non-null float64
perimeter_se               569 non-null float64
area_se                    569 non-null float64
smoothness_se              569 non-null float64
compactness_se             569 non-null float64
concavity_se               569 non-null float64
concave points_se          569 non-null float64
symmetry_se                569 non-null float64
fractal_dimension_se       569 non-null float64
radius_worst               569 non-null float64
texture_worst              569 non-null float64
perimeter_worst            569 non-null float64
area_worst                 569 non-null float64
smoothness_worst           569 non-null float64
compactness_worst          569 non-null float64
concavity_worst            569 non-null float64
concave points_worst       569 non-null float64
symmetry_worst             569 non-null float64
fractal_dimension_worst    569 non-null float64
Unnamed: 32                0 non-null float64


import the dataset and read it with pandas

![p1](https://user-images.githubusercontent.com/60866104/94984994-d8b23b00-056f-11eb-9df2-b01329e6f989.JPG)

visualizing the data in a dataframe with ordered features

![p2](https://user-images.githubusercontent.com/60866104/94984995-db149500-056f-11eb-8374-cb3955ce8030.JPG)

if the input parameters matches with the existiong parameters via logistic regression and returns either 0 or 1
which means 0 is malignant and 1 is begnin.

![p3](https://user-images.githubusercontent.com/60866104/94984996-dbad2b80-056f-11eb-8cf7-861aca8211a1.JPG)

and at the result we can visually check whether it is in malginant stage or begnin stage
if it is in malignant it is in starting stage ,if not it is in last stage

![p4](https://user-images.githubusercontent.com/60866104/94984997-dc45c200-056f-11eb-82fe-73a0eb48cb27.JPG)


https://colab.research.google.com/drive/1HM542jZ1ZdZ7UdBOahyJdH30-q7dcLIP?usp=sharing

