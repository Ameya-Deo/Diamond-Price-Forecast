# Diamond Price Forecast

## Introduction
Building a regression model to predict the price of diamonds.

## Purpose
The purpose of this project is to perform Data Analysis on 'Diamond Price' dataset and compute the probability of attrition using various algorithms. After applying all the models XGBClassifier appears to be the model with the best scoring on negative root mean square error.

## Dataset
This classic dataset contains the prices and other attributes of almost 54,000 diamonds. There are 10 attributes included in the dataset including the target ie. price.

## Dataset details:
Price: price in US dollars ($326--$18,823)This is the target column containing tags for the features. 

### The 4 Cs of Diamonds:-

Carat (0.2--5.01): The carat is the diamond’s physical weight measured in metric carats.  One carat equals 1/5 gram and is subdivided into 100 points. Carat weight is the most objective grade of the 4Cs. 

Cut (Fair, Good, Very Good, Premium, Ideal): In determining the quality of the cut, the diamond grader evaluates the cutter’s skill in the fashioning of the diamond. The more precise the diamond is cut, the more captivating the diamond is to the eye.  

Color, from J (worst) to D (best): The colour of gem-quality diamonds occurs in many hues. In the range from colourless to light yellow or light brown. Colourless diamonds are the rarest. Other natural colours (blue, red, pink for example) are known as "fancy,” and their colour grading is different than from white colorless diamonds.  

Clarity (I1 (worst), SI2, SI1, VS2, VS1, VVS2, VVS1, IF (best)): Diamonds can have internal characteristics known as inclusions or external characteristics known as blemishes. Diamonds without inclusions or blemishes are rare; however, most characteristics can only be seen with magnification.  

### Dimensions

x length in mm (0--10.74)
y width in mm (0--58.9)
z depth in mm (0--31.8)

depth total depth percentage = z / mean(x, y) = 2 * z / (x + y) (43--79)
table width of top of diamond relative to widest point (43--95)

## Conclusion
On the basis of negative root mean square error, XGBClassifier appears to be the best model.
