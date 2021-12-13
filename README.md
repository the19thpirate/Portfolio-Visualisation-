# Portfolio Visualisation
An application made for visualizing stock portfolios.
(Note : This is made only for personal use and for learning GUI design. The Stock Details which are being showcased in this project are random stocks and  **SHOULD NOT BE TAKEN AS INVESTMENT ADVICE**)

### Problem Statement:
- Manually searching for stocks and being up-to-date with the stock prices and other metrics every day is a difficult measure for anyone who is working each day and invests in stocks.

#### Tools Used:
- Yahoo Finance API, Tkinter, Plotly, Sci-kit Learn, Numpy and Pandas

### Solution:

- An active internet connection is required
- This application takes the buying position of the stocks and quantity owned by the user. These values can be input in a excel file as follows:

     ![Input](https://github.com/the19thpirate/Portfolio-Visualisation-/blob/main/Input%20Details.JPG)

- The stock name, quantity and price mentioned in the previous table are dummy values.

- Once this is filled/updated for future updates the application can be run and the following can be seen:

     ![Interface](https://github.com/the19thpirate/Portfolio-Visualisation-/blob/main/Opening%20Interface.JPG)

#### About the Interface:
  - The Stock Names have been edited, since this is not a recommendation and is solely meant for personal use.
  - The Interface includes 4 columns, The Name of the Stock, the CAGR of the stock, its Beta Value and the Current Market Price.
  - The user can look for any stock price with a period of 1 year by searching the stock name in the top search bar.
    For Eg: For looking at Wipro ltd. price chart input will by WIPRO ( similar to that of the Yahoo Finance SCRIP Name ).
   - The Three Buttons on the bottom will showcase the Invested Value of the portfolio.

#### Portfolio Distribution:

- This button will open a Pie Chart on the Browser showing the invested value in each of the stocks and the current value of the same.
- The following will look as such:

     ![Pie Chart](https://github.com/the19thpirate/Portfolio-Visualisation-/blob/main/newplot.png)
     
#### Portfolio Growth Comparison

- This Button will open a line chart on the browser which compares the variance of the portfolio value with respect to the NIFTY 50 Chart. 
- The following chart is as such:

    ![Growth](https://github.com/the19thpirate/Portfolio-Visualisation-/blob/main/Portfolio%20Growth%20Adjusted.png)

## Conclusion:

- This application has come in handy for managing my personal investments in the market and is continuing to be effective each day for understanding which stock is making losses and which stock gives better gains.
- Based on these findings, I was able to manage and allocate the funds in a better way. 

