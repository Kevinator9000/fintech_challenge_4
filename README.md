# risk_return_analysis
This project uses quantitative analysis to determine the most profitable risk-adjusted investment of four portfolios. 

The analysis utilizes variance, stardard deviation, Sharpe's Ratio, and beta to determine the optimal investment.

---
## Technologies
This program utilizes Jupyter Notebook in conjunction with the following libraries:

Pandas, Path from Pathlib, Numpy, and matplotlib.

![](./Resources/screen_shots/import_pic.PNG)

---
## Installation Guide
None

---
## Usage
First the whale_navs.csv file is imported and we display the first 5 rows to verify it is correct.

![](./Resources/screen_shots/pic_1.PNG)

The program then determines the daily return of each portfolio and graphs the data.

![](./Resources/screen_shots/pic_2.PNG)

Then, the application will calculate and visualize the cumulative returns.

![](./Resources/screen_shots/pic_3.PNG)

The program now uses the same daily return values but visualizes the data in a box plot. 

There are two graphs displaying this data, the second excludes the S&P 500 in order to more closely analyze the differences in daily return between the portfolios.

![](./Resources/screen_shots/pic_4.PNG)

![](./Resources/screen_shots/pic_5.PNG)

Then the application calculates and visualizes the 21-day rolling standard deviations for each portfolios and the S&P 500.

The second graph excludes the S&P 500 to help visualize data in a bit more detail.

![](./Resources/screen_shots/pic_6.PNG)

![](./Resources/screen_shots/pic_7.PNG)

Then the Sharpe Ratio of the portfolios and the S&P 500 is displayed as a bar graph.

![](./Resources/screen_shots/pic_8.PNG)


The previous graph showed us that Berkshire Hathaway and Tiger Global Management are the two most promising portfolios.

The program now visualizes the beta of Berkshire Hathaway and Tiger Global Management in order to compare each portfolio's risk-to-reward profile.

![](./Resources/screen_shots/pic_9.PNG)

![](./Resources/screen_shots/pic_10.PNG)

---
## Contributors
Kevin Gross

---
## License
Mit License