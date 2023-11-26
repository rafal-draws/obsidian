# **Obsidian**

Data/supervised machine learning decision making system in stock exchange

## target:
nasdaq ~1.5k companies 20trilion$
or
nyse ~2.4k companies 22.6trilion$


## data gathered:
to train the neural network for decisioning, we need stock data

### companiesTable

company's product type

company's resource type

company's resource values

company's location

company's target country

company's scope of product

possibly the companies board members - for news analysis


### newsTable (achievable of 3/6months after the news has been added for neural network training)
dimensions:

company

date

news headline

news sentiment (analysied by LLM on a scale)

to be added

state information (GDP of the state - GPD of last year)

more regional geological information

value of the company when the news struct

value of the company 3months after the news

amount of "dirty articles" in time spans

amount of "applauding articles" in time spans

### stock (3 per company, 7500 requests daily)
each stock value 

at the start of the day 

at the end of the day

at the middle of the day
