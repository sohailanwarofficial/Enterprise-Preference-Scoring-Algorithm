# Enterprise Preference Scoring

This project focuses on scoring and ranking enterprises based on multiple indicators to determine their preference. The scoring is done by assigning weights to each indicator and then calculating a preference score for each enterprise. The project also provides a function to calculate the preference score for a given set of indicators.

## Prerequisites

Before running the code, make sure you have the following libraries installed:

- pandas
- Python 3.x

## Dataset

The sample dataset provided in the code is for demonstration purposes. You can replace it with your own dataset containing enterprise information and corresponding indicators.

## Scoring and Ranking

The code calculates preference scores for enterprises based on the following indicators:

- Acquisition Cost (Lower is better)
- Enterprise Value (Higher is better)
- Gearing (Lower is better)
- Internal Rate of Return (IRR) (Higher is better)

You can customize the weights for each indicator according to your preferences by modifying the `weights` dictionary.

The code normalizes the data and calculates a preference score for each enterprise. It then ranks the enterprises based on their preference scores in descending order.

## Calculate Enterprise Score

The code provides a function, `calculate_enterprise_score`, that allows you to calculate the preference score for a specific enterprise based on its acquisition cost, enterprise value, gearing, and IRR. You can input these values, and the function will return the preference score for the given enterprise.

## Example Input

An example input is provided to demonstrate how to use the `calculate_enterprise_score` function. You can replace the example values with your own data to calculate the preference score for a specific enterprise.

## Customization

You can customize this code by:

- Replacing the sample dataset with your own dataset.
- Adjusting the weights assigned to each indicator in the `weights` dictionary.
- Using the `calculate_enterprise_score` function to calculate preference scores for new enterprises.

Feel free to explore and adapt this project to suit your specific needs.

---
