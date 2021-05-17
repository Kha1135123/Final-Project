# Final-Project
## Abstract
- This is a Final Project for MachineLearing4AI course hosted by COTAI (Center of talent AI)
- This project is a Food Recommender System using LightFM model from LightFM module to create a Hybrid Recommender System.
- Module used in this Project: 
	- [LightFM](https://making.lyst.com/lightfm/docs/home.html)
	- [Pandas](https://pandas.pydata.org/)
	- [Gradio](https://www.gradio.app/)

## Content
- The data used in this project: https://www.kaggle.com/shuyangli94/food-com-recipes-and-user-interactions
- This dataset consists of 180K+ recipes and 700K+ recipe reviews covering 18 years of user interactions and uploads on Food.com (formerly GeniusKitchen) used in the following paper: 
```
Generating Personalized Recipes from Historical User Preferences
Bodhisattwa Prasad Majumder*, Shuyang Li*, Jianmo Ni, Julian McAuley
EMNLP, 2019
https://www.aclweb.org/anthology/D19-1613/
```

- [Link to Presentation slide](https://hackmd.io/@Kha/BkUvYPqeO#/)

- Codes:
	- [Items Features](): Create a matrix which contains item's weights over features 
	- [Users Features](): Create a matrix which contains user's weights over features
	- [Recommender System](): Make recommends based on predicted scores of LightFM models, Demo by Gradio Interface. (Instruction included)
	- [Full source code used in this Project](): A Jupyter notebooks contains all the codes of the project.




