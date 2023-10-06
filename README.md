# Predictions: Car Mileage (MPG) and Diamond Price

## Project Overview

This project focuses on predicting two key aspects:

**Car Mileage (MPG) Prediction:** We have developed a predictive model that estimates a car's mileage (Miles Per Gallon) based on input features such as horsepower and weight. This assists consumers in assessing a car's fuel efficiency before making a purchase decision.

**Diamond Price Prediction:** Our second model predicts the price of diamonds using characteristics like carat and depth. This prediction empowers both jewelers and buyers to make informed choices regarding diamond purchases.

We provide Python functions for both predictions, along with evaluation metrics like Mean Squared Error (MSE), R-squared (R2) scores, and the predicted values themselves.



This project includes a Python script, `predictor.py`, that contains two functions: `car_mileage_predictor` and `diamond_price_predictor`. These functions are designed to predict car mileage and diamond prices, respectively, based on user-provided input.

## Functions

### car_mileage_predictor

The `car_mileage_predictor` function predicts car mileage (fuel efficiency) based on two input parameters: `horsepower` and `weight`. It provides the following outputs:

- Mean Squared Error (MSE) for the prediction.
- Maximum R-squared (R2) score obtained during prediction.
- Minimum R-squared (R2) score obtained during prediction.
- Average R-squared (R2) score for the prediction.
- Predicted MPG (Miles Per Gallon) based on the input `horsepower` and `weight`.

### diamond_price_predictor

The `diamond_price_predictor` function predicts diamond prices based on two input parameters: `carat` and `depth`. It provides the following outputs:

- Mean Squared Error (MSE) for the prediction.
- Maximum R-squared (R2) score obtained during prediction.
- Minimum R-squared (R2) score obtained during prediction.
- Average R-squared (R2) score for the prediction.
- Predicted price of the diamond based on the input `carat` and `depth`.

## Video Presentation

To see a demonstration of our car mileage (MPG) and diamond price predictions in action, please watch the following video:

[Demo Video](https://drive.google.com/file/d/1BFIkhfqx4cn0M6mx_Oc1Pb3JGqGvDfi4/view?usp=sharing)

In this video, we provide a step-by-step walkthrough of how to use our Python functions for predicting car mileage and diamond prices, as well as an overview of the project's objectives and results.

Feel free to watch the video to get a better understanding of our predictions.

## Dataset

The dataset used for this project is the [Diamond Price Dataset](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-BD0231EN-SkillsNetwork/datasets/diamonds.csv) and [Car Mileage MPG](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-BD0231EN-SkillsNetwork/datasets/mpg.csv), which contains information about diamonds and car.

## Dependencies

This project requires the following Python libraries:

- NumPy
- Pandas
- Scikit-learn
- Matplotlib

You can install these dependencies using pip:

      ```bash
      pip install numpy pandas scikit-learn matplotlib


## Usage

To use this project, follow these steps:

1. Ensure you have Python installed on your machine.
2. Clone the project repository to your local machine:

   ```bash
   git clone https://github.com/mominurr/Predictions-Car-Mileage-and-Diamond-Price.git
   cd Predictions-Car-Mileage-and-Diamond-Price
   python predictor.py

##Author:
[Mominur Rahman](https://github.com/mominurr)
