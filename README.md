# Diamond-Price-Prediction
Kaggle Competition to Predict Diamond Price.

![image](https://github.com/EsraaFareha/Diamond-Price-Prediction/assets/112290483/624c1e6b-f454-45b0-a5c8-0054f674f063)

Describtion:
Context
  This classic dataset contains the prices and other attributes of almost 54,000 diamonds. It's a great dataset for beginners learning to work with data analysis and visualization.

Content
  price price in US dollars (\$326--\$18,823)
  carat weight of the diamond (0.2--5.01)
  cut quality of the cut (Fair, Good, Very Good, Premium, Ideal)
  color diamond color, from J (worst) to D (best)
  clarity a measurement of how clear the diamond is (I1 (worst), SI2, SI1, VS2, VS1, VVS2, VVS1, IF (best))
  x length in mm (0--10.74)
  y width in mm (0--58.9)
  z depth in mm (0--31.8)
  depth total depth percentage = z / mean(x, y) = 2 * z / (x + y) (43--79)
  table width of the top of diamond relative to widest point (43--95)

Evaluation:
  Evaluation Metric The evaluation metric for this competition is Root Mean Squared Error (RMSE). The RMSE is a commonly used measure of the differences between predicted values provided by a model and the actual observed values. Submission Format For every diamond (i.e. row) in the test dataset (test.csv), submission files should contain two columns: id and price. id should be an integer and price should be a real value. For each row, these two values should be separated by a comma. The file should contain a header and have the following format ``` Id,price 597,2838 ```
