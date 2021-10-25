# Graph of the institutionnal hodlers of Stock Market

### Coding
Here is a notebook that takes a list of tickers as an input and create a graph based on the relationship between institutionnal holders and stocks.

I am using the Yahoo Finance library to retrieve the financial data, Numpy and Pandas to sort and manipulate them and Networkx to draw the graph.

I plan on doing the same graphs for the main stock markets (DOW JONES, NASDAQ, FTSY, CAC40, DAX, ...)

### Networkx

Networkx is a python package that allow to create graph based on large datasets.
I was able to give each Investment Firm a different size based on the percentage of share they hold.

Also the edges are weighted allowing the nodes to space themselves depending on how much shares they hold.

### NASDAQ

This example below is a map of the top 100 stocks in the Nasdaq

We can identify the main investment firms that are in the middle of the map (BlackRock, Vanguard). 
![NASDAQ Inst.Holders](./map_nasdaq.png "Map of institutional holders on the nasdaq")
