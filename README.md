# Birdstrike Analysis (Aircraft Wildlife Strikes 1990-2015)

## Overview
This repository contains Python code for analyzing bird strikes on aircraft from 1990 to 2015. The purpose of this analysis is to gain insights into birdstrike incidents and practice Python coding skills.

## Questions Explored
1. **Which part of the aircraft is struck?**
    - Analysis of the 'Aircraft Damage' column to identify affected parts.

2. **Which species of bird are struck the most?**
    - Examination of the 'Species Name' column to determine the most common species involved in strikes.
    - Visualizations such as bar plots or pie charts may be used.

3. **During which phase are these birds being struck?**
    - Analysis of the 'Phase of Flight' column to identify when strikes occur most frequently.

4. **Is there a relationship between state and operator?**
    - Use Heatmap to look at the relationship
    - Use chi-square tests

5. **Is there a relationship between the Bird species struck and the year of the accident?**
    - Use Boxplots and Violin plot
    - Use Kruskal-Wallis test
   
## Statistics
### The chi-square statistic and the p-value obtained suggest that there is a statistically significant association between the 'Operator' and 'State' variables.

- The chi-square statistic (9586.26) is a measure of the strength of the association between the variables.

- The p-value (0.0) is the probability of observing such extreme results if the variables were independent.

- With such a low p-value (close to zero), we typically reject the null hypothesis that the variables are independent.

- This implies that there is a significant relationship between the 'Operator' and 'State' variables in the context of the incidents data.

- This result indicates that the choice of operator and the state where incidents occur are not independent; they are associated with each other in a statistically significant manner.

### The Kruskal-Wallis statistic and the obtained p-value suggest that there is a statistically significant relationship between the year of the accident ('Incident Year') and the species of the bird ('Species Name').

- The Kruskal-Wallis statistic (15087.49) is a measure of the strength of the relationship between the two variables.

- The p-value (0.0) indicates the probability of observing such extreme results if the variables were not related. With such a low p-value (close to zero), we typically reject the null hypothesis that the distributions of 'Incident Year' across different species are the same. This suggests that there is a significant relationship between the year of the accident and the species of the bird.

- In practical terms, this result indicates that the distribution of accident years varies significantly across different bird species, implying that certain species might be involved in incidents more frequently in certain years compared to others.

![violin](https://github.com/BarendBester/AviationData/assets/121133689/a7e41d87-0c68-4558-834b-2b119bb219c6)


![fd8bb67546bb2a5b106ca87efcd666951882de20e2164166b9e289907fe5144e_1](https://github.com/BarendBester/AviationData/assets/121133689/ba81bf8f-15d9-4c74-862b-e20c2e1fdcc1)
<img src="https://github.com/BarendBester/AviationData/assets/121133689/ba81bf8f-15d9-4c74-862b-e20c2e1fdcc1" alt="Image" width="400">

- Find a link to kaggle here https://www.kaggle.com/datasets/faa/wildlife-strikes/data
