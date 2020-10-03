# breast-cancer-detection
This python program uses Logistic regression to predict the Breast cancer Detection.The collective information is been given 
as input based on that the algorithm will be resulting in Malignant or Benign....

This dataset contains the following features:
id (patientid)

name

radius (the distance from the center to the circumference of the tumor)

texture (standard deviation of gray-scale values)

perimeter (circumference of the tumor, approx. 2*3.14 *radius)

area

smoothness (local variation in radius lengths)

compactness

concavity (severity of concave portions of the contour)

symmetry

fractal_dimension

age

diagnosis: 0 or 1 indicating whether patient has breast cancer or not


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

