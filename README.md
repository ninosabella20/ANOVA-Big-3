# ANOVA Test Comparing Viewership of Big 3 Tennis Players

## Project Overview
This project investigates whether the three most prominent tennis players of the modern era—**Novak Djokovic, Rafael Nadal, and Roger Federer**—have a similar or differing impact on viewership during major tennis finals. The primary analysis is conducted using an **ANOVA (Analysis of Variance) test**.

### Objective
The goal is to determine if Djokovic, Nadal, and Federer attract similar levels of viewership during major finals, or if their impacts are statistically different.

## Data
Initially, we focused on **US Open finals** where one of the Big 3 played against a non-Big 3 player. To enhance the robustness of the results, we expanded the dataset to include:
- **Wimbledon Finals**
- **Roland Garros Finals**
- **Australian Open Finals**

Only matches where **one of the Big 3** played against a non-Big 3 player were included, to avoid the influence of matches where multiple Big 3 players face off (which could artificially increase viewership).

## Hypotheses
- **Null Hypothesis (H0):** The Big 3 players have similar impacts on viewership.
- **Alternate Hypothesis (H1):** The Big 3 players have different impacts on viewership.

## Methodology
1. **ANOVA Test**: To compare the mean viewership for Djokovic, Nadal, and Federer across the selected finals.
2. **Data Expansion**: Adding data from other Grand Slam tournaments (Wimbledon, Roland Garros, and Australian Open) to ensure the results are robust.
3. **Assumptions**: The data must meet ANOVA assumptions such as normality and homogeneity of variances.

## Conclusion
After adding data from other Grand Slams, there is still **no rejection of the null hypothesis**. The variability in viewership (ranging from 1 to 11 million depending on the tournament and year) is high.

Although the Big 3's individual matches may fluctuate in viewership, their overall influence on attracting an audience remains equally strong. However, it is possible that the **high variability within each player's grand slam finals** dilutes the model's ability to detect statistically significant differences in their impact on viewership.

## How to Contribute
You can contribute by:
- **Adding more data**: If you have access to additional relevant matches, feel free to add them.
- **Improving the analysis**: Suggestions for alternative statistical models or methods are welcome.

## Next Steps
Further research could look at refining the dataset, potentially narrowing down by year or event type to reduce within-group variability and potentially reveal more nuanced differences.

---

Feel free to explore the code and data to replicate or extend the analysis.
