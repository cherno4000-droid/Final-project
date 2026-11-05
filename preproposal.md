# Final Project Pre-Proposal

Student:  Barry
**Course:** Intro to Programming and Problem Solving - Python

Project: Swing Trade Planner and Journal

The idea
A Python program that helps a swing trader plan a trade before entering it and keep a record of every trade afterward. I swing trade, and I already use candlesticks and MACD to decide when to get in. This project turns the rules I follow by hand into code I wrote myself: how many shares to buy so a trade only risks a set amount, whether the stock's trend supports the trade, and how my trades have actually turned out.

What the program will do
1. Position sizing:the user enters account size, risk % per trade, entry price, stop price and target price. The program prints the numberg of shares, the dollars at risk, the total cost of the position, and the reward-to-risk ratio.
2. **Trend check:** read a list of daily closing prices for a stock and calculate a 20-day and 50-day moving average. Report whether the price is above or below each one and whether the trend is up, down, or sideways.
3. **MACD signal:** calculate the MACD line and signal line from the closing prices and report whether a bullish or bearish crossover happened recently.
4. **Trade journal:** Save each trade (ticker, entry, stop, exit, shares, and my reason for taking it) to a text file.
5. **Stats:** read the journal back and show win rate, average win vs. average loss, and total profit/loss.
6. Check bad input (negative numbers, a stop above the entry for a long trade, dividing by zero) and ask again instead of crashing.

### Three levels
- **Minimum:** the position size calculator and the moving averages from a list of prices typed into the program. Everything in functions with input validation.
- **Good:** read prices from a CSV file, add the MACD calculation and a menu, and keep the trade journal with stats.
- **Best:** use `turtle` to draw a price chart with the moving averages and the entry and stop lines, or an equity curve of the logged trades.

### New skills I would need
- Reading and writing files (CSV and text)
- Lists and loops for running calculations like moving averages and MACD
- A menu loop that calls different functions
- More `turtle` (for the chart)

### What will be hardest
Getting the moving average and MACD math right, keeping the code organized into small functions, and handling messy or missing data in the file.

### If I have extra time
Add a watchlist that checks several stocks at once and ranks them by trend strength, or add a score for each setup.

 This is an educational tool that uses sample or paper-trading data. It does not make real trades or give financial advice and its for my own personal use first. 
