# Poverty Prediction by Satellite Images and Deep Learning
### Capstone Project 2 (Springboard - Data Science Career Track)
Chiyuan Cheng (08/2020)

### Summary
- This project uses transfer learning to predict poverty (Wealth index) of a sub-Saharan African country, Burundi, in 2010. 
- Regression models are used to predict Wealth index from luminosity of nighttime satellite images, with r-squared of 0.54.
- Gaussian Mixture Model is used to classify the daytime satellite imagery into three classes, based on the luminosity.
- Transfer learning (VGG16, ResNet50, Inception C3) to capture features from daytime satellite imagery and predict poverty, with the 80% accuracy from the best model.

![image](/figures/Fig1.png)

### Report
- [Presentation slide](https://docs.google.com/presentation/d/13KgTJkdyjjubUSS5dwITZT3ruCCU9iCJ3A_uSp24nT8/edit?usp=sharing)
- [Final report](https://drive.google.com/file/d/1ZdsWbX4VsiD6wMjic_lAjuNo_9WTPhTL/view?usp=sharing)


### Jupyter Notebook
1) [Data Access](https://nbviewer.jupyter.org/github/cyuancheng/Predicting_Poverty/blob/master/01_DHS_prep.ipynb)
2) [Data Prep (Nightlight Satellite Image)](https://nbviewer.jupyter.org/github/cyuancheng/Predicting_Poverty/blob/master/02_Satellite_Image_Prep.ipynb)
3) [Machine Learning (Nightlight)](https://nbviewer.jupyter.org/github/cyuancheng/Predicting_Poverty/blob/master/03_Satellite_Image_nighttime_ML.ipynb)
4) [Data Processing (Daylight Satellite Image)](https://nbviewer.jupyter.org/github/cyuancheng/Predicting_Poverty/blob/master/04_Satellite_Image_process.ipynb)
5) [Data Analysis (Simularity](https://github.com/cyuancheng/Predicting_Poverty/blob/master/05_Satellite_Image_similarity.ipynb)
6) [Deep Learnining](https://github.com/cyuancheng/Predicting_Poverty/blob/master/06_Satellite_Image_TL.ipynb)


