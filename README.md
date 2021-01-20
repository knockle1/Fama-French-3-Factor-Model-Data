# Fama-French Three Factor Model Program

This program is a tool to efficiently run the Fama-French Three Factor Model. Normally, one would have to take the following steps to run the model:

1. Go the Ken French's website and download the required CSV file
2. Go to Yahoo Finance and download and individual excel file containing price data for each stock in your portfolio
2. Calculate returns for each stock
3. Calculate weighted returns for each stock and sum them to find the portfolio returns for each period 
4. Merge the portfiolio returns with the data from Ken French's website
5. By hand index the two datasets to make sure the dates line up
6. Run the regression analysis

As you can see, the process is extremely tedious and time consuming, especially trying to analyze a portfolio made up of 25 or 50 stocks. Furthermore, the data on Ken French's website is constantly updated, which requires you to manually go to the website, redownload the required CSV file, and repeat the whole process if you want to know the updated results of the model. The program found here is a way to solve this problem. 

### Using this program to run the Fama-French Model

This program was written using a Jupyter Notebok, so I recommend using the code in the same way. Or, I recommmend using the Jupyter Notebook extension in the VSCode editor. To succesfully use the program, you will need to have the list of stock tickers in your portfolio, and their respective weights. You will input these data points, and the program will automatically fetch the data required for the model. 

If you are simply looking for an automated way to gather the data needed to run the Fama-French regression analysis yourself, this program can easily be adapted to accomplish that goal. Simply comment out the sections that run the regression, and skip to the last line which will download all the data you need to an excel file for you to further analyze. 
