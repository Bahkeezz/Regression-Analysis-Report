# Predicting Crop Yield

## Introduction
Crop yield is a critical factor in agricultural productivity, and understanding the factors that influence it is essential for optimizing crop production. This study aimed to investigate the relationship between crop yield and five independent variables using regression analysis.

## Methodology
The study employed a multiple linear regression model to analyze the relationship between crop yield and the five independent variables. The data were collected from Kaggle, a reliable source of agricultural datasets. Microsoft Excel was used for data cleaning, analysis, and visualization, leveraging its regression analysis tool and built-in features to calculate key statistics and generate insights.

## Regression Model Overview
The regression model showed a very strong positive linear relationship between the predictors and crop yield, with a Multiple R (Correlation Coefficient) of 0.999998. The R-squared value of 0.999996 indicates that 99.9996% of the variability in crop yield is explained by the independent variables.

![Statistics](https://github.com/user-attachments/assets/b75cde6b-0f69-41cc-ab98-4aacbc2968ba)

## Variables Coefficient and Their Impact on Crop Yield

### Rainfall (mm)
Rainfall positively affects crop yield, with every additional unit of rainfall contributing to a 0.03 unit increase in yield. This indicates that adequate rainfall is essential for crop growth, although its impact is relatively moderate compared to other factors.

### Soil Quality Index
Soil quality has the most significant impact on crop yield among all variables. For every unit increase in the soil quality index, crop yield increases by 2 units. This underscores the importance of maintaining and enhancing soil fertility to maximize agricultural productivity.

### Farm Size (Hectares)
Farm size plays an important role in determining crop yield. Each additional hectare of farmland results in a 0.5 unit increase in yield, indicating that larger farms generally produce higher yields, likely due to economies of scale and increased cultivation area.

### Sunlight Hours
Sunlight has a positive but relatively smaller effect on crop yield, with each additional hour of sunlight increasing yield by 0.09 units. While sufficient sunlight is crucial for crop growth, its influence is less pronounced compared to soil quality and farm size.

### Fertilizer (kg)
Fertilizer contributes positively to crop yield, with each kilogram increasing yield by 0.01 units. However, its impact is the smallest among the variables, suggesting that while fertilizer use is beneficial, other factors such as soil quality and farm size are more critical for achieving higher yields.

## Statistical Significance

### P-Value
All predictors in the model (rainfall, soil quality, farm size, sunlight, and fertilizer) have a P-Value of 0.000. This indicates that their contributions to the model are statistically significant at any conventional significance level (e.g., 0.05). 

### Confidence Intervals
The 95% confidence intervals for all coefficients do not include zero. This further confirms that each predictor has a significant and meaningful effect on crop yield. For example, the confidence interval for rainfall (0.02996, 0.03001) shows that its impact is consistently positive.

### Standard Error of Regression (0.2917)
The standard error represents the average deviation of the observed crop yields from the predicted values. A value of 0.2917 indicates that the model's predictions are highly accurate, with minimal error between the actual and predicted crop yields. This demonstrates the reliability of the model in estimating crop yield based on the predictors.

![chart](https://github.com/user-attachments/assets/30c0ed03-f1c2-4e37-b7ac-68c6e10f6be7)

The chart illustrates the relative importance of each independent variable in predicting crop yield. The soil quality index has the most significant positive impact, followed by farm size and sunlight hours. Rainfall and fertilizer have progressively smaller impacts, aligning with their respective coefficients.

## Discussion
The findings of this study align with the consensus among agricultural experts, who have consistently identified soil quality, farm size, rainfall, sunlight, and fertilizer as crucial factors influencing crop yield.

- **Soil Quality:** Higher soil quality index indicates better fertility, structure, and health, leading to higher yields. 
- **Farm Size:** Larger farms benefit from economies of scale but smaller farms can sometimes outperform due to intensive farming.
- **Rainfall:** Essential for crop growth; irrigation can supplement but not fully replace natural rainfall.
- **Sunlight Hours:** Crucial for photosynthesis and plant growth.
- **Fertilizer:** Provides nutrients but should be used optimally to avoid diminishing returns.

## Conclusion
This study has demonstrated the importance of soil quality, farm size, rainfall, sunlight, and fertilizer in predicting crop yield. The results of this study can be used to inform agricultural policy and practice, with a focus on optimizing crop production and improving agricultural productivity.

## Recommendations
1. **Soil Quality Improvement:** Focus on enhancing soil fertility through better farming practices and soil amendments.
2. **Optimal Resource Allocation:** Prioritize investments in areas with higher soil quality indices and allocate fertilizers efficiently.
3. **Irrigation and Rainfall Management:** Highlight the importance of proper water management systems.
4. **Sunlight Utilization:** Ensure crops are grown in areas with adequate sunlight exposure.
5. **Fertilizer Use Optimization:** Use fertilizer efficiently, considering its marginal benefit.

## Limitations
1. The data used in this study were obtained from a single source on Kaggle, which may not comprehensively represent all agricultural regions or their unique characteristics.
2. Critical factors such as pests, diseases, and the impacts of climate change were not included in the analysis, which could influence the results and insights derived from this study.
