# stock_analysis
  #The purpose of this project was twofold. The first goal was to take refactor our old code for stock analysis.
 We did this partially for the experience of working with some already realized code that didn't work at the onset.
 The reason was to have us work through what worked and what didn't work with the code that we had so that we could figure
 out how to fix the code for our purposes. The second purpose was to create loops that would work past the original 12 tickers.
 Very rarely will we be dealing with a situation where only a handful of subjects are at the heart of our analysis.
 This new code will allow us to quickly get analysis for a much larger group of stocks.
 #2017 vs 2018 Analysis
  #We learned three things in the analysis of 2017 vs 2018. First, there appeared to be an overall market correction or at the
 very least a downturn in the industry we were looking at in 2018. While all but one stock saw a positive return in 2017;
 the almost complete inverse happened in 2018 where all but two stocks had a negative return. A wider analysis of the stock market
 between 2017 and 2018 would show whether it was the overall market or the industry of these stocks that saw this decline.
 The second thing we learned is that ENPHENPH and RUNRUN were the only stocks to see positive returns in both years. 
 I would recommend ENPHENPH if the client was looking for a single stock to invest in as it saw at least an 80% increase in both years.
 The third piece of information is not as concrete from the data. But we did learn that the higher the volume of trading of
 a particular stock, for the most part, the higher the yearly return. This is not nearly as concrete and applies more to the
 2018 numbers than the 2017 numbers.
 #Refactoring Code
  #The advantages of refactoring code is mostly time related. Having already existing code that serves a function cuts down
 on development time. If you have a subroutine that will do most of what you need done all you should need to do are 
 minor adjustments to get the code to serve your new purpose. The disadvantage was evident in how long it took me to get
 my code to work. While having code that serves most of your function is helpful, there are issues when trying to modify it to 
 complete your task. In my case, I didn't run the subroutine as given to us to see if it worked properly. There were issues
 where it wasn't producing anything to begin with. I began writing my code to add onto it without realizing I needed to fix existing
 issues to begin with. Also modifying existing code can mean you can ruin the original function of the code as you add on to it.
 #Application
  #In my case two issues came up. One, as stated above, was the fact that the code was not producing what our practcice code did.
  I should have read through it and run it to make sure before refactoring. Second, I had major issues with my tickerIndex at first because
  I put it in the wrong spot at first. Once I started reading the comments it was placed in the right spot but in real life
  I'll need to understand where in loops my refactored code needs to go.
