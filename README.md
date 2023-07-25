# Crop Recommendation Using Machine Learning

Crop recommendation plays a crucial role in precision agriculture, where the goal is to tailor crop selection based on specific site conditions. This process involves considering various factors unique to each location to make accurate recommendations. While the "site-specific" approach has led to better results, it remains important to monitor and assess the outcomes of precision agriculture systems. Not all precision agriculture systems are the same, and the accuracy of the recommendations is of utmost importance in agriculture, as mistakes can lead to substantial losses in resources and investment.



<p align="center">
<img src="[https://media.istockphoto.com/id/543212762/photo/tractor-cultivating-field-at-spring.jpg?s=1024x1024&w=is&k=20&c=yCC31xDwz8uezGmsEWpCcA5QMW95C8f-COaKY4_eJig=](https://static.businessworld.in/article/article_extra_large_image/1595413246_xTzoBr_Agritech_FINAL.jpg)" />
</p>
This application will assist farmers in increasing agricultural productivity, preventing soil degradation in cultivated land, reducing chemical use in crop production, and maximizing water resource efficiency.

# [Dataset]()
This dataset was build by augmenting datasets of rainfall, climate and fertilizer data available for India.

### [Attributes information:]()

* **N** - Ratio of Nitrogen content in soil
* **P** - Ratio of Phosphorous content in soil
* **K** - Ratio of Potassium content in soil
* **Temperature** -  temperature in degree Celsius
* **Humidity** - relative humidity in %
* **ph** - ph value of the soil
* **Rainfall** - rainfall in mm 

### [Experiment Results:]()
* **Data Analysis**
    * All columns contain outliers except for N.
 * **Performance Evaluation**
    * Splitting the dataset by 80 % for training set and 20 % validation set.
 * **Training and Validation**
    * GausianNB gets a higher accuracy score than other classification models.
    * GaussianNB ( 99 % accuracy score )
 * **Performance Results**
    * Training Score: 99.5%
    * Validation Score: 99.3%

 
# Demo
Live Demo: https://ai-crop-recommender.herokuapp.com/

![](https://i.imgur.com/TnsSPQy.png)

# References
* https://www.prolim.com/crop-recommendation-system-using-machine-learning-for-digital-farming/
* https://www.irjet.net/archives/V4/i12/IRJET-V4I12179.pdf
* http://sersc.org/journals/index.php/IJAST/article/view/30399
* https://www.researchgate.net/publication/345247916_Crop_Plantation_Recommendation_using_Feature_Extraction_and_Machine_Learning_Techniques
* https://ieeexplore.ieee.org/document/8768790
* https://towardsdatascience.com/farmeasy-crop-recommendation-portal-for-farmers-48a8809b421c
* http://agri.ckcest.cn/ass/8185d605-6c4d-4d8a-b280-c867c2304d42.pdf
* https://www.kaggle.com/atharvaingle/crop-recommendation-dataset
