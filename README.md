# Cardiovascular Risk Assessment

![Project Image](link_to_project_image.jpg)
![image](https://github.com/Khushalgogia/CardioVascular-Risk-Assesment/assets/43295537/6145acb3-a19f-4941-be80-b20667bf84cf)
https://drive.google.com/file/d/1JAsbtAEE7aZKvFXuyQjBOY6JjqxpgzXI/view?usp=sharing


## Overview

Our project, the Cardiovascular Risk Assessment, leverages the power of data science to predict the risk of cardiovascular disease. Through advanced analytics and machine learning, we've developed a tool that can potentially save lives by identifying risks before they become critical. This project isn't just about numbers and predictions; it's about people and their well-being.

## Data Preprocessing

We've implemented a systematic approach to handle null values in the dataset. Instead of ignoring or blindly filling them, we carefully analyze each column:
- For numerical columns, null values are replaced with their median.
- For categorical and binary columns, we use the mode for handling null values.

Outliers can distort the accuracy of predictive models, so we've adopted a two-step approach to outlier handling for features like [totChol, sysBP, diaBP, BMI, heartRate, glucose].

## Exploratory Data Analysis (EDA)

Key insights from our EDA:
- Non-smokers and heavy smokers are at higher risk of cardiovascular disease.
- Educational background influences the risk; lower education levels correlate with higher risk.
- Old age is a significant factor in cardiovascular disease risk.
- Smokers at risk smoke an average of 11 cigarettes.
- Data collected is biased toward older individuals.

## Model Training

We explored how different data scenarios affect model performance:
- Scenario 1: Balanced training data, imbalanced test data.
- Scenario 2: Balanced training and test data.

Scenario 1 achieved an accuracy score of 87% and a recall score of 50%, while Scenario 2 achieved an accuracy score of 100% and a recall score of 97%. These scores demonstrate the model's robustness in identifying individuals at risk.

## Insights and Recommendations

Based on our findings, here are some insights and recommendations:
- Focus on improving health literacy among individuals with lower education levels.
- Promote regular health check-ups for older adults.
- Develop gender-specific health programs targeting high-risk groups.

Feel free to explore our project and contribute to our mission of preventing cardiovascular disease.

## Getting Started

To run the project, follow these steps:

1. Clone this repository to your local machine.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Run the main script using `python main.py`.

## Contributing

If you would like to contribute to this project, please follow the guidelines in [CONTRIBUTING.md](CONTRIBUTING.md).

## License

This project is licensed under the [MIT License](LICENSE).



## Contact

For questions or feedback, please reach out to khushal.gogia122@gmail.com
