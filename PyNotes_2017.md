# PyNotes 2017

## Tel Aviv Meetup

**Fraud detection challenges and data skepticism using LIME** (_Shir Meir Lador_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=HcaAKI1tVGM
<br/>&nbsp;&nbsp;https://github.com/marcotcr/lime

- To view a random sample of dataframe: `df.sample(frac=1).head()`


## PyData London 2017

**Bayesian optimisation with scikit-learn** (_Thomas Huijskens_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=jtRPxRnOXnk

- Bayesian Optimization increases computational overhead, so only makes sense to use when the number of hyperparameters is very high, or it is computationally very expensive to evaluate the out of sample performance.
- GPs are the generalization of a Gaussian distribution to a distribution over _functions_, instead of random variables.
- Packages: Spearming, Hyperopt, MOE, Hyperband (model-free), SMAC (model-free)

**Ten Steps to Keras** (_Valerio Maggio_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=FrkYu2zVUyM
<br/>&nbsp;&nbsp;

**Bayesian Deep Learning with Edward (and a trick using Dropout)** (_Andrew Rowan_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=I09QVNrUS3Q


**Next generation of word embeddings in Gensim** (_Lev Konstantinovskiy_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=7530Tn2J0Mc


**Dimension Reduction and Extracting Topics - A Gentle Introduction** (_Tariq Rashid_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=Bxlzbck51SU
<br/>&nbsp;&nbsp;http://makeyourowntextminingtoolkit.blogspot.co.uk/


**Make your research interactive with Jupyter Dashboards** (_Pavlo Andriychenko_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=qQaBv7gw8vw


## Add the previous videos for this conference (e.g., Using RFs.)



## PyCon 2017

**Kubernetes for Pythonistas** (_Kelsey Hightower_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=u_iAXzy3xBA

- (Really fun Tetris example of scheduling)

**Probabilistic Programming with PyMC3** (_Christopher Fonnesbeck_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=5TyvJ6jXHYE

**The Python Visualization Landscape** (_Jake VanderPlas_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=FytuB8nFHPQ

**Optimizing Pandas Code for Speed and Efficiency** (_Sofia Heisler_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=HN5d490_KKk

**Keynote** (_Jake Vanderplas_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=ZyjCqQEUa8o

**The Fastest FizzBuzz in the West** (_Dustin Ingram_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=ApgUrtCrmV8

```python
def fizzbuzz(n):
  for i in range(n):
    print(i%3//2*'fizz'+i%5//4*'buzz' or i+1)
```

**An Introduction to Reinforcement Learning** (_Jessica Forde_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=k1UuTyW2uFc

**Human Machine Collaboration for Improved Analytical Processes** (_Tony Ojeda_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=s0u_UkVecx0

**The Dictionary Even Mightier** (_Brandon Rhodes_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=66P5FMkWoVU

**Modern Python Dictionaries -- A confluence of a dozen great ideas** (_Raymond Hettinger_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=npw4s1QTmPg

**What's new in Python 3.6** (_Brett Cannon_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=c2rEbbGLPQc

**Readability Counts** (_Trey Hunner_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=knMg6G9_XCg

**The Wild West of Data Wrangling** (_Sarah Guido_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=xn9sTXR3Cp8

**Dask: A Pythonic Distributed Data Science Framework** (_Matthew Rocklin_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=RA_2qdipVng

**Factory Automation with Python Stories about Robots, Serial Ports, and Barcode Readers** (_Jonas Neubert_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=cEyVfiix1Lw

**Snakes on a Hyperplane Python Machine Learning in Production** (_Jessica Lundin_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=oV-cm0Loefg

**A gentle introduction to deep learning with TensorFlow** (_Michelle Fullwood_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=5e0TbyCkbCY

**Looping Like a Pro in Python** (_David DB Baumgold_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=u8g9scXeAcI

**Instagram Filters in 15 Lines of Python** (_Michele Pratusevich_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=otLGDpBglEA

**Passing Exceptions 101 Paradigms in Error Handling** (_Amandine Lee_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=BMtJbrvwlmo

**Python Epiphanies [Tutorial]** (_Stuart Williams_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=oQca6eDcjA8

**Intro to Bayesian Machine Learning with PyMC3 and Edward [Tutorial]** (_Torsten Scholak, Diego Maniloff_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=fR5Wvb86-IU
<br/>&nbsp;&nbsp;http://tscholak.github.io/assets/PyConEdward/#/

**Parallel Data Analysis [Tutorial]** (_Ben Zaitlen, Matthew Rocklin, Min Ragan Kelley, Olivier Grisel_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=KIXACCJHtDg

**Build a data pipeline with Luigi [Tutorial]** (_Aaron Knight_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=jpkZGXrhZJ8

**Faster Python Programs Measure, don't Guess [Tutorial]** (_Mike Müller_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=xmuEsYut9Pc

**Python and Jupyter in Depth: High productivity, interactive Python [Tutorial]** (_Matthias Bussonnier, Mike Bright, Min Ragan-Kelley_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=VQBZ2MqWBZI

**Introduction to Digital Signal Processing [Tutorial]** (_Allen Downey_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=UOIllEyajGs

**Deploy and scale containers with Docker native, open source orchestration [Tutorial]** (_Jerome Petazzoni, AJ Bowen_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=EuzoEaE6Cqs

**Hands On Intro to Python for New Programmers [Tutorial]** (_Trey Hunner_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=6zu8lrYn6t8

**Time Series Analysis** (_Aileen Nielsen_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=zmfe2RaX-14

**Decorators and descriptors decoded** (_Luciano Ramalho_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=81S01c9zytE

**Fantastic Data and Where To Find Them: An introduction to APIs, RSS, and Scraping** (_Nicole Donnelly, Tony Ojeda, Will Voorhees_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=A42voDYkFZw

**Introduction to Statistical Modeling with Python** (_Christopher Fonnesbeck_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=TMmSESkhRtI

**bokeh: Data Visualization in Python** (_Chalmer Lowe_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=xId9B1BVusA

**Exploratory data analysis in pytho** (_Chloe Mawer, Jonathan Whitmore_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=W5WE9Db2RLU
<br/>&nbsp;&nbsp;https://github.com/cmawer/pycon-2017-eda-tutorial/

**Using Functional Programming for efficient Data Processing and Analysis** (_Reuben Cummings_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=9kDUTJahXBM
<br/>&nbsp;&nbsp;https://speakerdeck.com/reubano/using-functional-programming-for-efficient-data-processing-and-analysis
<br/>&nbsp;&nbsp;https://github.com/reubano/pycon17-tute


## PyData London

**SaaaS - Sampling as an Algorithm Service** (_Vincent D. Warmerdam_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=8g6oF8vUqTU
<br/>&nbsp;&nbsp;http://koaning.io/switching-to-sampling-in-order-to-switch.html
<br/>&nbsp;&nbsp;http://koaning.io/elimination-via-inference.html

- _(Approachable introduction to MCMC)_ 
- Uses the Kaggle [Santa's Uncertain Bags Competition](https://www.kaggle.com/c/santas-uncertain-bags) as an example


## Misc

**Use Python to Load & Prepare Data Analytics** (_Raymond Hettinger_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=nO78ECRighw

```python
from collections import defaultdict
from pprint import pprint

d = defaultdict(list)
d['a'].append('apple')
d = dict(d) # to convert to regular dict
pprint(d)

# start @ 11:52

```



## ...

**The Secret Life Of Rolling Pandas** (_Jaime Fernandez del Rio_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=XM_r5La-1tA
<br/>&nbsp;&nbsp;

**Keynote** (_Travis Oliphant_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=NBliyFXnWeo
<br/>&nbsp;&nbsp;

**A Beginners Guide to Weather & Climate Data** (_Margriet Groenendijk_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=U_Aq2cPxwss
<br/>&nbsp;&nbsp;

**NASA Space APPS Challenge: Asteroid prediction impact** (_Gema Parreño_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=8h3uyQfiMNc
<br/>&nbsp;&nbsp;

**Security for Data Scientists** (_David Arcos_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=aicyYd8MZWo
<br/>&nbsp;&nbsp;

**Web Scraping with Python** (_Carles Illa_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=aTwvQZjEZhk
<br/>&nbsp;&nbsp;

**Marketing Data Science** (_Joaquin Pais_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=jzuQJg3bFy8
<br/>&nbsp;&nbsp;

**Python for visualization of HPC applications** (_Miguel Zavala-Ake_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=0ni90h8EErQ
<br/>&nbsp;&nbsp;

**TensorFlow Wide & Deep: Advanced Classification the easy way** (_Yufeng Guo_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=WKgNNC0VLhM
<br/>&nbsp;&nbsp;

**Feature Importance and Ensemble Methods : a new perspective** (_Constant Bridon_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=qdEhJ0uT7wk
<br/>&nbsp;&nbsp;

**Extending Jupyter with Google Cloud Storage file system backend** (_Egor Bulychev_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=uLC0t5JZBZs
<br/>&nbsp;&nbsp;

**xxx** (_xxx_)
<br/>&nbsp;&nbsp;
<br/>&nbsp;&nbsp;

**xxx** (_xxx_)
<br/>&nbsp;&nbsp;
<br/>&nbsp;&nbsp;

**xxx** (_xxx_)
<br/>&nbsp;&nbsp;
<br/>&nbsp;&nbsp;



## PyData Seattle

**Tutorial: Web Scraping with Python** (_Lingqiang Kong_)
<br/>&nbsp;&nbsp;
<br/>&nbsp;&nbsp;https://github.com/klq/python-webscrapes

**Tutorial: D’oh! Unevenly spaced time series analysis of The Simpsons in Pandas** (_Joe McCarthy_)
<br/>&nbsp;&nbsp;
<br/>&nbsp;&nbsp;https://pydata.org/seattle2017/schedule/presentation/104/

**Tutorial: From Novice to Data Ninja** (_Valentina Staneva_)
<br/>&nbsp;&nbsp;
<br/>&nbsp;&nbsp;

**Tutorial: So you want to be a Python expert?** (_James Powell_)
<br/>&nbsp;&nbsp;
<br/>&nbsp;&nbsp;

**Tutorial: Introduction to data analytics with pandas** (_Quentin Caudron_)
<br/>&nbsp;&nbsp;
<br/>&nbsp;&nbsp;

**Tutorial: pomegranate, fast and flexible probabilistic modeling in python** (_Maxwell W Libbrecht_)
<br/>&nbsp;&nbsp;
<br/>&nbsp;&nbsp;http://noble.gs.washington.edu/~maxwl/2017-07-05%20pydata%20pomegranate.pdf

**Tutorial: Data Visualization and Exploration with Python** (_Stephen Elston_)
<br/>&nbsp;&nbsp;
<br/>&nbsp;&nbsp;https://github.com/StephenElston/ExploringDataWithPython

**Tutorial: Vocabulary Analysis of Job Descriptions** (_Alex Thomas_)
<br/>&nbsp;&nbsp;
<br/>&nbsp;&nbsp;

**Keynote 1** (_Katrina Riehl_)
<br/>&nbsp;&nbsp;
<br/>&nbsp;&nbsp;

**Provenance for Reproducible Data Science** (_Andreas Schreiber_)
<br/>&nbsp;&nbsp;
<br/>&nbsp;&nbsp;

**Monitoring Displacement Crises with Python** (_George Richardson_)
<br/>&nbsp;&nbsp;
<br/>&nbsp;&nbsp;

**Designing for Guidance in Machine Learning** (_Olivia Gunton_)
<br/>&nbsp;&nbsp;
<br/>&nbsp;&nbsp;

**Automatic Citation generation with Natural Language Processing** (_Claire Kelley, Sarah Kelley_)
<br/>&nbsp;&nbsp;
<br/>&nbsp;&nbsp;

**Practical Optimization for Stats Nerds** (_Ryan J. O'Neil_)
<br/>&nbsp;&nbsp;
<br/>&nbsp;&nbsp;

**Pandas, Pipelines, and Custom Transformers** (_Julie Michelman_)
<br/>&nbsp;&nbsp;
<br/>&nbsp;&nbsp;

**Robust Automated Forecasting in Python and R** (_Pranav Bahl, Jonathan Stacks_)
<br/>&nbsp;&nbsp;
<br/>&nbsp;&nbsp;

**How to be a 10x Data Scientist** (_Stephanie Kim_)
<br/>&nbsp;&nbsp;
<br/>&nbsp;&nbsp;

 - Code Stubs
 - Exception handling
 - Unit Tests

**Learning Neural Nets Through Implementation and Examples** (_Kyle Shaffer_)
<br/>&nbsp;&nbsp;
<br/>&nbsp;&nbsp;

**Forecasting Time Series Data at scale with the TICK stack** (_Nathaniel Cook_)
<br/>&nbsp;&nbsp;
<br/>&nbsp;&nbsp;

**Sirbarksalot: Bark Detection in Python** (_Nicholas Kridler_)
<br/>&nbsp;&nbsp;
<br/>&nbsp;&nbsp;

**High Fidelity Web Crawling in Python** (_Josh Weissbock_)
<br/>&nbsp;&nbsp;
<br/>&nbsp;&nbsp;

**Implementing and Training Predictive Customer Lifetime Value Models in Python** (_Jean-Rene Gauthier, Ben Van Dyke_)
<br/>&nbsp;&nbsp;
<br/>&nbsp;&nbsp;

**Learn to be a painter using Neural Style Painting** (_Pramit Choudhary_)
<br/>&nbsp;&nbsp;
<br/>&nbsp;&nbsp;

**Scaling Scikit-Learn** (_Stephen Hoover_)
<br/>&nbsp;&nbsp;
<br/>&nbsp;&nbsp;

**Interactive Data Analysis** (_Jeffrey Heer_)
<br/>&nbsp;&nbsp;
<br/>&nbsp;&nbsp;

**JupyterLab+Real Time Collaboration** (_Brian Granger, Chris Colbert & Ian Rose_)
<br/>&nbsp;&nbsp;
<br/>&nbsp;&nbsp;

**We came, we saw, we hacked. How to win a Big Data hackathon** (_Eloisa Tran_)
<br/>&nbsp;&nbsp;
<br/>&nbsp;&nbsp;

**Bokeh and Friends** (_Bryan Van de ven_)
<br/>&nbsp;&nbsp;
<br/>&nbsp;&nbsp;

**Using Machine Learning and Brain Waves to Detect Errors in Human Problem Solving** (_Katie Porterfield_)
<br/>&nbsp;&nbsp;
<br/>&nbsp;&nbsp;

**Robust Algorithms for Machine Learning** (_Tom Radcliffe_)
<br/>&nbsp;&nbsp;
<br/>&nbsp;&nbsp;

**xxx** (_xxx_)
<br/>&nbsp;&nbsp;
<br/>&nbsp;&nbsp;

**xxx** (_xxx_)
<br/>&nbsp;&nbsp;
<br/>&nbsp;&nbsp;

**PyData Seattle Diversity Panel - How diversity drives excellence in our data driven tech world** (_Lingqiang Kong, Andrea Brice, Charlotte Flanagan, Tina-Marie Gulley, James Powell_)
<br/>&nbsp;&nbsp;https://www.youtube.com/watch?v=xOcbLqnFUa8

 - **Ling**: First PyData conference, noticed there were lines at the men's restroom but not the women's.
 - What obstacles have you encountered in building a diverse community?
     - **Ling**: 1) Building a diverse community not always a priority (especially when hiring one at a time). 2) Really hard to find diverse candidates. Why? Not building from scratch; building from an already established tech community. So, general lack of role models. Work on building mentorships and role models.
 - What lessons can you share about overcoming these obstackes?
     - **Andrea:** Find people who are adaptable, not try to use some objective measure of competency.
 - What actionalble advice do you have someone trying to increase undersatanding the value of diversity?
     - **Tina:** Show up for people who don't look like you. Understand unconscious bias. Change mindset so it is a business issue as well as a human issue. As we create job descriptions, challenge the list of "must haves". 
 - What examples have you encountered where a project was improved by having a diverse team?
     - **James:** (Handed off to Brett Cannon, CPython Core Contributor) - After the first two female core core contributors made it much easier to get momentum. 
 - In the wake of high profile HR scandals in tech, how can we as a tech community build more inclusive workplaces?
     - **James*:* We all know the overt discrimination is wrong, we need to scrutinize the unconscious biases.
     - **Charlotte:** The Atlantic - [Why Silicon Valley So Awful To Women](https://www.theatlantic.com/magazine/archive/2017/04/why-is-silicon-valley-so-awful-to-women/517788/)
- What tips do you have for diversity candidates when they're trying to find a job
 - **Charlotte:** I don't know if my advice would be that different to anyone. Network like crazy. Don't limit yourself by what is listed on the job discription.


## ...

**xxx** (_xxx_)
<br/>&nbsp;&nbsp;
<br/>&nbsp;&nbsp;
<br/>&nbsp;&nbsp;


