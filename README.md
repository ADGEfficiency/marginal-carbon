# Todo

## Adam

- aws (invite link sent)
- papers / read (done)
- code snippets (done)
- provide dataset for the MMSDM data (done)

## Bastian

- repo (done)
- reading
- working with NEMDE price setter XML locally
- scraping of NEMDE

# References & reading

- [A hackers guide to AEMO data](https://adgefficiency.com/hackers-aemo/)
- https://medium.com/electricitymap/marginal-emissions-what-they-are-and-when-to-use-them-ecd050ab0962
- https://medium.com/electricitymap/using-machine-learning-to-estimate-the-hourly-marginal-carbon-intensity-of-electricity-49eade43b421
- Li Thesis, Winds of Change & 2018_Dungey_stragetic_bidding_NEM.pdf (all of which I will put into a reference folder in the repo)

# Timetable

## Week 1

Reading

## Week 2

Last week of teaching

Time series analysis
- visualivation
- auto correlation
- decomposition (seasonal & trend)

## Week 3

Monday 2nd

Scraping & cleaning of target

model 1 - xgboost
- target
- demand (MW), datetime (feature)

## Week 4

2 models - Conv
- interconnectors (MW)

Price verus intensity

Seasonality / trend

## Week 5

3 models - SARIMA
- generators (DUIDs - MW)

## Week 6

demo day

# Time series

What metric
- see [Hyndman & Koehler (2005) Another look at measures of forecast accuracy](https://robjhyndman.com/papers/mase.pdf)
- mae, mape, mase
- is mase differentiable?
- using linear programming - optimizing using battery model & measuring in either $ or tC

Lagging & horizioning

Trend, seasonality

sklearn.TimeSeriesSplit

Model candidates
- SARIMA
- random forest, xgboost
- convolution (1 or 2D)
- lstm or gru
- [Facebook's Prophet](https://github.com/facebook/prophet)
- [Amazon's Forecast](https://aws.amazon.com/forecast/)
