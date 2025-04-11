# Analysing Housing Crisis in the Netherlands

## Project Overview

This project is inspired by the ongoing housing crisis in the Netherlands. Our goal is to analyze various factors contributing to the crisis and share key findings. A significant part of our research focuses on the impact of immigration on house prices.

## Key Findings

### 1. Discovering shortage

The housing crisis in the Netherlands has been widely acknowledged by various entities, including the United Nations and public opinion. According to research agency ABF, the housing shortage is estimated at approximately 401,000 homes in 2024. The aim of this analysis is to identify the specific characteristics of the housing crisis in the Netherlands.

![image_url](https://github.com/Olulu108/housing-crisis-in-the-netherlands/blob/main/graphs/10_inhabitants%20-%20housing%20numbers.jpg)

Housing shortage can be seen through the imbalance between housing supply and demand. A high population relative to the number of homes could indicate a shortage. However, between 2004 and 2024, the number of residents increased by nearly 1.6 million, while the number of housing units grew by 1.4 million. Theoretically, this provides housing for approximately 1.14 people per new home. Given that the average household size in 2024 is 2.25 people, this suggests that housing construction has outpaced population growth.

![image_url](https://github.com/Olulu108/housing-crisis-in-the-netherlands/blob/main/graphs/11_inhabitants%20per%20home.jpg)

Over the years, the average number of inhabitants per home has been decreasing, which suggests that one contributing factor to the housing shortage is a shift in household composition. Housing demand is growing faster than the population itself, as more people choose to live independently—driven by trends such as young adults moving out, an increase in divorces, and an aging population.

![image_url](https://github.com/Olulu108/housing-crisis-in-the-netherlands/blob/main/graphs/12_1p_householdes.jpg)

The increasing percentage of single-person households is also contributing to greater pressure on the housing market.

Examine the housing situation in selected cities with the highest population density.
![image_url](https://github.com/Olulu108/housing-crisis-in-the-netherlands/blob/main/graphs/13_pop%20density.jpg)

![image_url](https://github.com/Olulu108/housing-crisis-in-the-netherlands/blob/main/graphs/14_the%20hague.jpg)

In The Hague (the most densely populated city in the Netherlands), population density increased by approximately 21.04%, while the number of inhabitants per home remained stable.

![image_url](https://github.com/Olulu108/housing-crisis-in-the-netherlands/blob/main/graphs/15_leiden.jpg)

Population density in Leiden grew by approximately 10.3% while the number of inhabitants per home dropped 8.8%. 

Housing affordability assessment.Price-to-income ratio = Average income / Average house price

![image_url](https://github.com/Olulu108/housing-crisis-in-the-netherlands/blob/main/graphs/16_income_price.jpg)

There are enough houses in terms of quantity, but not enough affordable ones. From 2005 to 2016, houses were getting more affordable. However, starting in 2017, affordability began to decline, and by 2023, homes were 34.3% less affordable than in 2016.

![image_url](https://github.com/Olulu108/housing-crisis-in-the-netherlands/blob/main/graphs/17_rent_own.jpg)

Although affordability—measured by the price-to-income ratio—has significantly declined in recent years, the homeownership rate has remained stable and even shown slight growth. This may indicate a cultural shift toward valuing ownership over renting, along with favorable mortgage conditions that continue to stimulate homeownership despite decreasing affordability.As more people shift to homeownership, especially in high-demand areas, prices could rise, reducing the availability of affordable options for the growing population — leading to potential housing shortages.

### 2. Immigration and House Prices

We began by investigating whether the rising number of immigrants influences house prices. The first two graphs indicate that both house prices and the number of immigrants have been increasing over the years. 

![image_url](https://github.com/Olulu108/housing-crisis-in-the-netherlands/blob/main/graphs/1_house%20price_migration.jpg)

However, when examining the percentage of immigrants within the total population, we see that it remains relatively stable over time.

![image_url](https://github.com/Olulu108/housing-crisis-in-the-netherlands/blob/main/graphs/2_background_pop%20across%20country.jpg)

#### 2.1 Case Study: The Hague

To explore this topic further, we focused on cities with a high percentage of immigrants, including Amsterdam, Rotterdam, and Utrecht. We selected The Hague for a closer examination.

![image_url](https://github.com/Olulu108/housing-crisis-in-the-netherlands/blob/main/graphs/4_background%20graph.jpg)

#### Neighborhood Analysis

The neighborhoods in The Hague are categorized based on the proportion of Dutch-born residents (left) versus people born outside the Netherlands (right).

![image_url](https://github.com/Olulu108/housing-crisis-in-the-netherlands/blob/main/graphs/5_neighbourhoods%20background.jpg)

In areas with a higher percentage of people born outside the Netherlands, most residents live in rented houses. In contrast, neighborhoods with a majority of Dutch-born residents have higher homeownership rates.

![image_url](https://github.com/Olulu108/housing-crisis-in-the-netherlands/blob/main/graphs/6_rented_vs_owned_neigh.jpg)

Additionally, houses in neighborhoods with a dominant Dutch-born population tend to be more expensive.

![image_url](https://github.com/Olulu108/housing-crisis-in-the-netherlands/blob/main/graphs/7_house%20value.jpg)

#### Housing Price Trends

A graph comparing price fluctuations over the years. Orange represents areas with a dominant Dutch-born population. Green represents neighborhoods with a high proportion of immigrants.
The price rise and fluctuation are more significant in neighborhoods with a majority of Dutch-born people.

![image_url](https://github.com/Olulu108/housing-crisis-in-the-netherlands/blob/main/graphs/8_house%20price%20change.jpg)

This analysis suggests that the rising number of immigrants does not drive house price increases. Instead, prices in areas with a high proportion of people born outside the Netherlands remain relatively stable and low.

## Conclusion

Our findings challenge the assumption that immigration directly impacts rising house prices. Instead, ownership patterns and demographic compositions appear to play a more significant role in shaping the housing market.

## Repository Structure
- `data/` - Contains datasets.
- `notebooks/` - Jupyter notebooks.
- `graphs/` - Visualizations.
- `README.md` - This document.

## How to Use

1. Clone the repository:

git clone https://github.com/Olulu108/housing-crisis-in-the-netherlands.git

2. Navigate to the project folder:

cd housing-crisis-nl

3. Explore the data and findings through Jupyter notebooks or graphs.

## Contributors

[Olga Pershina, Lea Lamberti, Helene Lang, Gabriela Villarreal]

## License

This project is licensed under the MIT License.

