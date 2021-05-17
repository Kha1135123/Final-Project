# Final-Project
## Abstract
- This is a Final Project for MachineLearing4AI course hosted by COTAI (Center of talent AI)
- This project is a Food Recommender System using LightFM model from LightFM module to create a Hybrid Food Recommender System.
- Module used in this Project: 
	- [LightFM](https://making.lyst.com/lightfm/docs/home.html)
	- [Pandas](https://pandas.pydata.org/)
	- [Gradio](https://www.gradio.app/)
	- [SciPy](https://www.scipy.org/)
- We have created a model which can bring out recommendations for users, but can only handle cold-start to a low degree.

## Content
### Data
- The data used in this project: https://www.kaggle.com/shuyangli94/food-com-recipes-and-user-interactions
- This dataset consists of 180K+ recipes and 700K+ recipe reviews covering 18 years of user interactions and uploads on Food.com (formerly GeniusKitchen) used in the following paper: 
```
Generating Personalized Recipes from Historical User Preferences
Bodhisattwa Prasad Majumder*, Shuyang Li*, Jianmo Ni, Julian McAuley
EMNLP, 2019
https://www.aclweb.org/anthology/D19-1613/
```
- Train-Test-Validation interactions of the dataset were merged to one interactions. The full merged interactions was first split to train and test sets for demonstration purpose, but The Recommender System use the whole merged interactions for training. 
- We created a [Demo Data](https://github.com/Kha1135123/FoodRecommenderSystem_FinalProject/blob/main/Demo_file.csv) for demonstration.

### Code and Presentation
- [Link to Presentation slide](https://hackmd.io/@Kha/BkUvYPqeO#/)

- Codes:
	- [Create Items Features](https://github.com/Kha1135123/Final-Project/blob/main/create_item_features.py): Create a matrix which contains item's weights over features 
	- [Create Users Features](https://github.com/Kha1135123/Final-Project/blob/main/create_user_features.py): Create a matrix which contains user's weights over features
	- [Recommender System](https://github.com/Kha1135123/Final-Project/blob/main/create_recsys.py): Make recommends based on predicted scores of LightFM models.
	- [Full source code used in this Project](https://github.com/Kha1135123/FoodRecommenderSystem_FinalProject/blob/main/FinalProject.ipynb): A Jupyter notebooks contains all the codes of the project with a Gradio UI to demo the results (Instruction included).

- Exported Files: 
	- [Item Features](https://drive.google.com/file/d/1-2NHRb9oGlH7_3bWAeLoKcZ5xpbp0O0m/view?usp=sharing)
	- [User Features](https://drive.google.com/file/d/1-1yw5LwCm8ryhPZKkmJRNicLKNiVHdE0/view?usp=sharing)

### Note: 
- **References:** 
 	- https://github.com/aayushmnit/cookbook/blob/master/recsys.py, line 33-62, line 81-123
	- https://www.kaggle.com/shuyangli94/food-com-recipes-and-user-interactions
- For time-saving purpose, you can import item and user features used in this notebooks using Pandas:
	```
	df = pd.read('file name.csv')
	```
- Go to [Kaggle](https://www.kaggle.com/shuyangli94/food-com-recipes-and-user-interactions) to download the zip dataset file and unzip in the Jupyter Notebook by: 
	```
	!unzip 'file name.zip'
	```
### Author of this Project
- Tran Thien Phu (also known as Paul Tran) - Class 11CTRN - Le Hong Phong High School for the Gifted - Ho Chi Minh City, Vietnam.
- Nguyen Manh Kha - Class 11CTRN - Le Hong Phong High School for the Gifted - Ho Chi Minh City, Vietnam.

