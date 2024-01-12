
## Presentation on Tableau 

https://public.tableau.com/app/profile/franziska.ersil/viz/nutritionvshealth/GroceryNutritionDataInsights

## Backstory

### 1. Food Industry Analysis

It's a familiar realization that many foods may not be optimal for our health, yet the clarity on what we can or should consume remains elusive. One intriguing observation is the absence of specific salt quantities in grams on nutrition labels, a standard practice for sugar and protein. This raises a curious question: why does salt, a crucial element in our diet, not receive the same detailed attention on nutritional lists? Unraveling this anomaly may lead to a deeper understanding of dietary choices and the potential impact on our well-being.

### 2. Food Analysis: Salt Content

Introduction

This analysis delves into the salt content in foods, a dimension often overlooked compared to sugar, proteins, and carbohydrates, as salt isn't typically quantified in grams. The focus is on scrutinizing ingredient lists, particularly noting how frequently salt is mentioned and identifying products where salt is notably prevalent.

Methodology

The analysis is grounded in a comprehensive examination of ingredient lists within a dataset encompassing various food items. The primary emphasis is on gauging the frequency of salt mentions in these ingredient lists.

Results

    Frequency of Salt in Ingredient Lists:
    The assessment reveals the prevalence of salt as an ingredient in the examined foods, providing insights into the distribution of salt across different product categories.

    Foods with Elevated Salt Content:
    Special attention is given to identifying types of foods that tend to have higher salt content. This sheds light on dietary habits, enabling consumers to make more informed and conscious decisions.

Conclusion

The analysis aims to raise awareness about salt content in foods, offering consumers informed insights. By pinpointing foods with elevated salt levels, individuals can better manage their dietary preferences, contributing to healthier eating habits.

### 3. Data Source
@misc{GroceryDB, title={GroceryDB: Prevalence of Processed Food in Grocery Stores}, author={Babak Ravandi and Peter Mehler and Albert-László Barabási and Giulia Menichetti}, year={2022}, eprint={medRxiv:2022.04.23.22274217}, url = {https://www.medrxiv.org/content/10.1101/2022.04.23.22274217} }


Linear Regression Reveals a Clear Connection Between Both Variables

In essence, the journey through the data has uncovered a discernible correlation between the two variables, as illuminated by the Linear Regression analysis. The numbers speak, and they tell a story of interdependence, providing a valuable insight into the relationship we sought to understand. The evidence points towards a meaningful connection, adding depth and clarity to our exploration of these variables.

Slope: [[7.93381811]]
Mean squared error:  108.24801034207725
R2 score:  0.5525072795742065

<img width="1460" alt="Bildschirmfoto 2023-12-22 um 06 42 42" src="https://github.com/FE-3-79/python_health_ingredients/assets/145100963/61f752fc-cf34-4fbf-b23a-029f8a33c536">

It is crucial to highlight that there is only a limited number of products where the term appears more than once. The occurrence of this phenomenon is quite unusual and prompts the question of why the manufacturer might not have precise knowledge of their ingredients. A plausible assumption suggests that the manufacturer may be recombining processed products to create a final product. This raises intriguing questions about transparency in the production chain and encourages a closer examination of manufacturing practices.

<img width="1461" alt="Bildschirmfoto 2023-12-22 um 06 45 02" src="https://github.com/FE-3-79/python_health_ingredients/assets/145100963/e112aa45-29a7-479e-b4e5-35b5fa4267fd">

Another striking observation is the prevalence of products with more than 10 ingredients. The quantity of ingredients often serves as a marker for processed food. The notable number of ingredients raises questions about the level of food processing involved and underscores the complexity of these products. This insight prompts further exploration into the nature of these ingredients and their potential impact on the overall nutritional profile of the products.

<img width="1397" alt="Bildschirmfoto 2023-12-22 um 06 53 31" src="https://github.com/FE-3-79/python_health_ingredients/assets/145100963/7fd82187-4b40-455a-89aa-ff4d4a0527e3">

The k-means clustering algorithm has identified two distinct clusters, suggesting that there might not be any latent or hidden structures within the data. This outcome implies that the data points are relatively homogenous and can be effectively grouped into two separate categories based on the features considered. The absence of additional clusters indicates a straightforward and clear organization of data points, simplifying the interpretation of patterns within the dataset.

<img width="1493" alt="Bildschirmfoto 2023-12-22 um 07 02 02" src="https://github.com/FE-3-79/python_health_ingredients/assets/145100963/0c9a4235-468d-41f8-b7da-4570f4da1355">

<img width="1283" alt="Bildschirmfoto 2023-12-22 um 07 08 59" src="https://github.com/FE-3-79/python_health_ingredients/assets/145100963/3dd4d7bb-2bae-40e3-8cf1-2792f9e28a04">

The frequency of salt mentions across different product categories reveals which categories have the highest salt content, offering insights into dietary choices and helping consumers make informed decisions about their food intake.

![sunburst_salt20231222_125114](https://github.com/FE-3-79/python_health_ingredients/assets/145100963/52a96094-56aa-40be-a481-a9115dc14e77)

