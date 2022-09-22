# Project 2 - Ames Housing Data and Kaggle Challenge
by ([*Chalermchon Wongsopa*](https://github.com/Chalermchon1993)) & ([*Kantaphon Vareekasem*](https://github.com/Tatadektep)) 

Welcome to Ames! 
### [Presentation Deck](https://docs.google.com/presentation/d/1UlCZofn6LABNTLjEg3tArpQSQw4D-kPKwfdj8tL_tSE/edit?usp=sharing)

### Problem Statement

1. How much should you pay for the price of a house in Ames?
2. What are the important features on sale price?

### EDA
1. Fill Missing data to 0 from Top 15 numerical features
2. Remove 3 Outlier from Ground Living Area (Square Feet)\gr_liv_area variable

### Final Model
1. Top 15 numerical features
2. dummy_normal = ['bldg_type', 'lot_shape', 'land_contour', 'exter_qual', 'sale_condition', 'functional', 'fireplace_qu', 'central_air', "paved_drive", 'neighborhood']

3. dummy_group = ['ms_zoning', 'condition_1', 'sale_type', 'exterior_1st', 'bsmt_qual', 'exterior_2nd', 'garage_qual', 'garage_cond', 'heating_qc', 'kitchen_qual', 'misc_feature']

4. Log Y (Log Sale Price)

5. Interaction term: X['overall_qual'] * X['fireplaces']

6. Log X (Log lot area)


### Data
[Ames Iowa Housing dataset](https://www.kaggle.com/competitions/dsi-tda-02-project-2/data)


### Special Thanks
[*James Larkin*], [*Yamada Nozomi*], [*Apiwat Jaroonpol*]
