activetick
==============================================================================
Released: 2014-05-27

A Python module for requesting data via the ActiveTick Feed HTTP Server [1]. 


What is activetick? 
------------------------------------------------------------------------------

**activetick** is a Python module used for requesting historical data from the 
ActiveTick Feed HTTP Server. It currently contains functions that allow the 
user to request the following data: 

  * historical bars (from 1 minute to daily and weekly bars)
  * historical trades (millisecond resolution)
  * historical quotes (millisecond resolution)
  * option chain of a symbol (index and stock options)

Streaming data is not implemented yet. You need a valid subscription to one 
of the Market Data API solutions offered by ActiveTick LLC in order to be 
able to pull data from the server. 

A demo is available [here](http://nbviewer.ipython.org/gist/alexispetit/01fbe2741abb5b017290). 


What else? 
------------------------------------------------------------------------------

**activetick** is not a product of ActiveTick LLC, nor is this project 
affiliated with ActiveTick LLC. 

Any feedback would be greatly appreciated! 

Alexis Petit

[1]: http://activetick.com
