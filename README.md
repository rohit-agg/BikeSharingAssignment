# Bike Sharing Assignment
> A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

## Table of Contents
* [General Information](#general-information)
* [Approach](#approach)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)
* [License](#license)

## General Information

BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

#### Objective

They want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:
1. Which variables are significant in predicting the demand for shared bikes.
1. How well those variables describe the bike demands

#### Dataset

Complete data for bike rentals along with weather parameters for the year 2018 and 2019

## Approach

Following is the step-by-step approach followed to solve the given problem statement:
1. Data Understanding
1. Data Visualisation (EDA)
1. Data Preparation
1. Building Linear Model
1. Residual Analysis
1. Predictions and Evaluation

## Conclusions
- Final Model = 0.19 + 0.47\*temp + 0.23\*yr - 0.3\*lightrain - 0.1\*holiday - 0.1\*spring - 0.08\*cloudysky - 0.07\*july + 0.06\*september + 0.05\*winter
- Temperature is a clear factor driving bike rentals evident from highest coefficient in the formula
- As per business, there is a year-on-year increase in the bike rental service which is again visible from the coefficient
- Light Rain or Light Thunderstorm would discourage people from opting for bike rental
- Holiday and Spring season also reduces the number of bike rentals

## Technologies Used
- Python (ver 3.11.7)
- NumPy (ver 1.26.4)
- Pandas (ver 2.1.4)
- MatplotLib (ver 3.8.0)
- Seaborn (ver 0.13.2)
- StatsModel (ver 0.14.0)
- SciKitLearn (ver 1.2.2)

## Acknowledgements
- PI Session on Linear Regression conducted by Shubham Gupta on 14th September 2024
- Session on Linear Regression conducted by Darshan Ingle on 15th September 2024
- [Seaborn Documentation](https://seaborn.pydata.org/api.html)
- [StatsModel Documentation](https://www.statsmodels.org/stable/api.html)
- [SciKitLearn Documentation](https://scikit-learn.org/stable/api/index.html)

## Contact
Created by [@rohit-agg](https://github.com/rohit-agg) - feel free to contact us!

## License
This project is open source and available under the [MIT License](LICENSE.md)
