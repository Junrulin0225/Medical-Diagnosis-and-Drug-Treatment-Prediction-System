**Introduction**

Welcome to the **Medical Diagnosis & Drug Treatment Prediction System 🩺**!

This is a big project that combines 5 disease types and 1 drug classification data. After analyzing 6 datasets, I decided to put them all together for an interactive project for users. 

5 disease types:

🧋 Diabetes

🍺 Liver Disease

👩 Breast Cancer

🫀 Heart Disease

🫘 Chronic Kidney Disease

and 
💊 Drug data.

This big project aims to **predict which disease type or drug it is after the users enter the data**. The model we use to predict here is SVM, since it has the best performance among 6 datasets.

Dataset explained (👉 **Drug Treatment.csv**)
- Na_to_K ratio: Sodium to Potassium ratio in the human body. The recommended Sodium to Potassium ratio for humans is 1:3. That is Potassium intake should be 3 times higher than Sodium intake.
- BP: Blood pressure levels



**Workflow**

- Step 1: I cleaned and visualized all 6 datasets by removing missing values and skew, applying EDA.

- Step 2: The data preprocessing here is to convert categorical data into numeric form. Both useful tools, LabelEncoder and Lambda were used. 

- Step 3: After data cleaning preprocessing, here comes the step where we fitted and predicted the model. Since every dataset requires the same steps to split, standardize, fit, train, and predict, this is where 'function' comes in handy.


- Step 4: The most fun part of this project is to build something interactive. I want users to enter all the data, later on, the predict outcome will tell you whether **this patient potentially has disease ABC** or **this patient should take drug XYZ**.

**Result and Discussion**

This project took me a lot of time to build but it feels great after seeing the product. I know if the prediction is accurate enough, it can help medical professionals save lots of time and effort! 
