# Project 2 - Ames Housing Data and Kaggle Challenge
by ([*Chalermchon Wongsopa*](https://github.com/Chalermchon1993)) & ([*Kantaphon Vareekasem*](https://github.com/Tatadektep)) 

Welcome to Ames! 

Time to learn from the best price predictive model by the reigning champions!

### [Presentation Deck](https://docs.google.com/presentation/d/1UlCZofn6LABNTLjEg3tArpQSQw4D-kPKwfdj8tL_tSE/edit?usp=sharing)

### Dataset and Competition
[Ames Iowa Housing Dataset and Competition](https://www.kaggle.com/competitions/dsi-tda-02-project-2/data)

### Problem Statement

1. How much should you pay for the price of a house in Ames?
2. Which features appear to add the most value to a home?
3. What neighbourhoods seem like they might be a good investment?

### EDA
1. Fill Missing data to 0 from the Top 15 numerical features
2. Remove 3 Outlier from Ground Living Area (Square Feet)\gr_liv_area variable

### Final Model
1. Top 15 numerical features
2. dummy_normal = ['bldg_type', 'lot_shape', 'land_contour', 'exter_qual', 'sale_condition', 'functional', 'fireplace_qu', 'central_air', "paved_drive", 'neighborhood']

3. dummy_group = ['ms_zoning', 'condition_1', 'sale_type', 'exterior_1st', 'bsmt_qual', 'exterior_2nd', 'garage_qual', 'garage_cond', 'heating_qc', 'kitchen_qual', 'misc_feature']

4. Log Y (Log Sale Price)

5. Interaction term: X['overall_qual'] * X['fireplaces']

6. Log X (Log lot area)

### Business Recommendation
Valuable Features 
    - Numeric value: Overall Quality, Ground Living Area (Square feet), Total square feet of basement area, Garage and Year Built.
    - Categorical value: Neighborhood, Type of Dwelling, Kitchen Quality, Basement Quality.

Northridge and Stone Brook seem to be valuable neighbourhoods.

The model could generalise to other cities. Yet, there might a significant difference between cities such as air conditioning for hotter cities and central heating for colder cities.

### Contributors:
Special thanks to all the contributors who have contributed to this project. We are heartily thankful to you all.

And a special thanks to *James Larkin*, *Yamada Nozomi*, and *Apiwat Jaroonpol* for their support.