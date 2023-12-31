# Crop Recommender System

Crop recommendation plays a crucial role in precision agriculture, where the goal is to tailor crop selection based on specific site conditions. This process involves considering various factors unique to each location to make accurate recommendations. While the "site-specific" approach has led to better results, it remains important to monitor and assess the outcomes of precision agriculture systems. Not all precision agriculture systems are the same, and the accuracy of the recommendations is of utmost importance in agriculture, as mistakes can lead to substantial losses in resources and investment.

<p align="center">
<img src="https://static.businessworld.in/article/article_extra_large_image/1595413246_xTzoBr_Agritech_FINAL.jpg" />
</p>

This application will assist farmers in increasing agricultural productivity, preventing soil degradation in cultivated land, reducing chemical use in crop production, and maximizing water resource efficiency.

# [Dataset]()
The data was obtained from Kaggle

### [Features information:]()

* **N** - Ratio of Nitrogen content in soil
* **P** - Ratio of Phosphorous content in soil
* **K** - Ratio of Potassium content in soil
* **Temperature** -  temperature in degree Celsius
* **Humidity** - relative humidity in %
* **ph** - ph value of the soil
* **Rainfall** - rainfall in mm 

### [Experiment Results:]()
* **Data Analysis**
    * All columns contain outliers except for N. Removed them using IQR. 
 * **Performance Evaluation**
    * 80 % training set and 20 % validation set.
 * **Training and Validation**
    * GausianNB had the highest accuracy score (99%) than other classification models.
 * **Performance Results**
    * Training Score: 99.5%
    * Validation Score: 99.3%

# References
* https://www.prolim.com/crop-recommendation-system-using-machine-learning-for-digital-farming/
* http://sersc.org/journals/index.php/IJAST/article/view/30399
* https://www.researchgate.net/publication/345247916_Crop_Plantation_Recommendation_using_Feature_Extraction_and_Machine_Learning_Techniques
* https://towardsdatascience.com/farmeasy-crop-recommendation-portal-for-farmers-48a8809b421c
* https://www.kaggle.com/atharvaingle/crop-recommendation-dataset
