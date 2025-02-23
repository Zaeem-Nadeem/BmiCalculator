# BMI Calculator

The BMI Calculator is a simple web application that allows users to calculate their Body Mass Index (BMI) based on their height and weight. It provides the BMI value along with an interpretation of the result, helping users understand if they fall into underweight, normal, or overweight categories. 

## Features

- **Calculate BMI**: Users can input their height (in CM) and weight (in KG), and the application will calculate their BMI.
- **BMI Results**: After calculating, the application displays the BMI value along with a weight category (underweight, normal range, or overweight).
- **BMI Weight Guide**: Provides a BMI weight guide to help users understand what their BMI means in terms of health.
- **Responsive Design**: The layout is responsive and works well on different screen sizes.

## How It Works

1. **Height and Weight Input**: Users enter their height (in centimeters) and weight (in kilograms).
2. **BMI Calculation**: The formula used for calculating BMI is:
   \[
   BMI = \frac{{\text{{weight in kg}}}}{{(\text{{height in meters}})^2}}
   \]
3. **Display Results**: After calculation, the BMI value is displayed, and based on the value, users are classified into one of three categories: Underweight, Normal, or Overweight.
4. **Weight Guide**: A BMI weight guide section is included to help users interpret their results.

## Setup Instructions

1. **Clone the repository** or download the files.
2. Open the `index.html` file in your web browser to run the BMI Calculator.
3. Enter your height and weight and press "Calculate" to view your BMI.

## File Structure

```plaintext
├── index.html        # The main HTML file containing the structure of the BMI calculator
├── style.css         # The CSS file that styles the BMI calculator
├── script.js         # The JavaScript file that calculates the BMI and handles user input
└── ../styles.css     # An additional CSS file linked in case it includes shared styles (optional)
