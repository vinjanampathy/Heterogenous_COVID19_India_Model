## An India-specific compartmental model for Covid19 

### Projections and intervention strategies by incorporating geographical, infrastructural and response heterogeneity

This website is a repository for the code and some results that are available in our [manuscript](https://arxiv.org/abs/2007.14392) posted to the arXiv. The code with the state data is in the [main branch](https://github.com/vinjanampathy/X-SEAIPR) and the district data and simulations are available [here](https://github.com/vinjanampathy/X-SEAIPR/tree/District1). We welcome the _use and modification_ of the code presented here and any comments from the reader.


### Model

The main model is detailed in the manuscript. It is a age-stratified compartmental model, summarized by the two diagrams

![model](/Images/Slide1.jpeg)

![](/Images/Slide2.jpeg)

### Results

The results presented in this manuscript are not (yet) peer reviewed and we urge the requisite caution. We investigate three intervention strategies, corresponding to varying levels of testing and contact. Representative results are presented here.
![res1](/Images/Slide3.jpeg)

![res2](/Images/Slide4.jpeg)

### Features of our Model
- Age-stratified compartmental model.
- District level simulation.
- Health indices of states are incorportated.
- Transport of individuals are incorporated.

### Limitations
```
We note the following limitations of our model

- Compartmental models assume well mixing.
- Age stratified models were consolidated into three catagories: young persons, working age persons and older persons. 
- Health indices derived from Niti Aayog data are assumed to represent overall performance of the states.
- Transport is derived from data derived before Covid-19 crisis. 
- The Kalman filter is discritized and assumed to have additive noise.
- Testing rates are assumed to be numbers as opposed to time series.
```
