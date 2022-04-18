# Titanic(Machine Learning from Disaster)

## Workflow for Project
  1. Problem definition
  2. Tools used
  3. Data used
  4. Wrangle, prepare, cleanse the data
  5. EDA (Exploratory Data Analysis) - Analyze, identify patterns, and explore the data
  6. Acquire training and testing data
  7. Model, predict and solve the problem
  8. Visualize, report, and present the problem solving steps and final solution


### Problem definition
* Use the Titanic passenger data (name, age, price of ticket, etc) to try to predict who will survive and who will die.


### Tools used
* python language
* Libs: Numpy, pandas, sklearn, seaborn, matplotlib
* algorithms: decision tree, random forest 

### Wrangle, prepare, cleanse the data
   1. Name, Ticket, Cabin ... I will Drop these columns because they are of no use to me in this notebook
   2. null for Survived because this column is not on test data
   3. I will fill nall of Age col. by mean
   5. convert Pclass, Survived to categorical
   6. create a new column for combine two column SibSp, Parch and then drop it


### EDA
  1. Survived rate
![EDA_1](https://user-images.githubusercontent.com/49419507/163881622-ccb422c5-d293-4f6b-a7db-8484d9723ad1.png)
![EDA_2](https://user-images.githubusercontent.com/49419507/163881623-6c7bd605-5d35-4a33-8baf-3350aad0e000.png)
![EDA_3](https://user-images.githubusercontent.com/49419507/163881626-6bacc6ff-2a97-4008-b7d4-73f2c296a94f.png)
![EDA_4](https://user-images.githubusercontent.com/49419507/163881597-770fab1a-3fe5-46af-b133-081fa57015de.png)
![EDA_5](https://user-images.githubusercontent.com/49419507/163881603-0076f666-d4c3-4db1-bbcf-8df30dd74d16.png)
![EDA_6](https://user-images.githubusercontent.com/49419507/163881606-8c56aa9f-8986-4202-956e-f37113c0e5f9.png)
![EDA_7](https://user-images.githubusercontent.com/49419507/163881607-9af3cd31-dcd0-4e04-ac29-cc7f5ea4ab11.png)
![EDA_8](https://user-images.githubusercontent.com/49419507/163881612-a15eec58-1c7e-46d8-a811-a4078a62fa63.png)
![EDA_9](https://user-images.githubusercontent.com/49419507/163881613-25e92dfe-e5fd-4982-9288-12f61a00ea5e.png)
![EDA_10](https://user-images.githubusercontent.com/49419507/163881615-bf780143-21b8-4bd9-95f6-a4d8cfe603a8.png)
![EDA_11](https://user-images.githubusercontent.com/49419507/163881621-25a809bc-7dd0-4dbe-b565-6d79078e849b.png)


