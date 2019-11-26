# Exploratory-Analysis-on-AirBnB-Data
An exploratory analysis on AirBnB data 

#The html is the Python notebook, conducting exploratory analysis on the AirBnB data, which is available on Kaggle:https://www.kaggle.com/stevezhenghp/airbnb-price-prediction

#The EDA analysis is done by doing data visuzliation, creating interactive charts(historgram, scatter plot) which can be further
#zoomed in or out to get extra information.

#NLP is also performed to analyzed text data, and world cloud is generated for visualization purpose.

#load packages needed
import pandas as pd 
# Input data files are available in the "../input/" directory.
import os
import matplotlib.pyplot as plt#visualization
from PIL import  Image
%matplotlib inline
import pandas as pd
import seaborn as sns#visualization
import itertools
import warnings
warnings.filterwarnings("ignore")
import io
import plotly.offline as py#visualization
py.init_notebook_mode(connected=True)#visualization
import plotly.graph_objs as go#visualization
import plotly.tools as tls#visualization
import plotly.figure_factory as ff#visualization
import plotly.express as px

from sklearn.feature_extraction.text import CountVectorizer
from PIL import Image
from wordcloud import WordCloud
