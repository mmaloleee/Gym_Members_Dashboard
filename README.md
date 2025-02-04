# Gym_Members_Dashboard
The dataset provides various insights about gym members of a particular gym. In this project, specific data such as average water intake, body mass index and workout type popularity have been analyzed. The data has been visualized in an interactive dashboard that allows filtering by gender, age and body mass classification.

## Data used
- <a href="https://www.kaggle.com/datasets/valakhorasani/gym-members-exercise-dataset?resource=download">Dataset</a>

## Questions
- Who drinks more water on average: females or males?
- How does it look in the age overview?
- What are the most and least popular workout types in the gender overview?
- What are the most and least popular workout types in general?
- How does the distribution of particular workout types look according to gender?
- Whose average workout session is longer: females or males? Does it depend on level of advancement?
- How does the distribution of the most popular body mass classifications look like?

## Process
- Imported CSV file into Excel.
- Created a copy of an original data.
- Added a column called "Age_Classification" which contains 4 values: "Young", "Young Adult", "Adult", "Old". The values are based on an "Age" column.
- Added a column called "Body_Mass_Classification". The values are based on a "BMI" column.
- Added a column called "Experience_Level_Classification". The values are based on a "Experience_Level" column.
- Added column "Session_Duration (HH:MM:SS)" with HH:SS:MM time format.
- Removed duplicated values.
- The data was analyzed using pivot tables.
- Created interactive dashboard based on pivot tables

## Dashboard
![Screenshot](https://raw.githubusercontent.com/mmaloleee/Gym_Members_Dashboard/refs/heads/main/dashboard.png?raw=true)

## Conclusions
- Men drink more water on average than women. There are no significant diferences in the age overview.
- Women's favourite workout type is cardio but they don't really like yoga. Men enjoy heavy lifting but the are not into HIIT.
- Strength wrokout and HIIT are the most and least popular in general.
- There are no signifficant differences in workout types popularity. The distribution is approximately equal across gender.
- More experienced members tend to train longer. Beginner and advanced women's have longer average session duration men's, but the differences are not significant.
- Among women, regardless of age, the most popular body mass clasification is normal BMI. Next the most popular classification according to BMI is overweight and underweight. There are very few obese women. Men the most popular BMI classification is also "normal", except young adult men, who are mostly classified as overweight. Older men are extremly obese. The second most popular body mass classification depends on age. For adults it's overweight, olds and young adults have optimal BMI, young men are overweighted. 
