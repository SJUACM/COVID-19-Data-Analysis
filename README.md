# COVID-19-Data-Analysis

Interactive Data Visualizations on Worldwide COVID-19 Data

## Lab Instructions
  - Click [here](https://colab.research.google.com/notebooks/intro.ipynb#recent=true) to open up Google Colab
  
  - Click [here](https://covid.ourworldindata.org/data/owid-covid-data.csv) to download the COVID-19 Dataset
  
  - Upload the downloaded dataset into Google Colab by clicking the File icon on the top left then click "Upload to session storage"
  
  - Copy all the code below and paste it in the first cell in Google Colab
  ```python
  # Necessary imports

  import math
  import pandas as pd
  import matplotlib
  import matplotlib.pyplot as plt
  from matplotlib.pyplot import figure

  from datetime import datetime
  import plotly.graph_objects as go
  import plotly.express as px
  import numpy as np
  from ipywidgets import interactive
  import ipywidgets as widgets
  from IPython.display import display, clear_output
  from ipywidgets import interact, Layout
  from bokeh.io import output_notebook
  from prettytable import PrettyTable
  import locale
  import warnings

  warnings.filterwarnings('ignore')

  # For number formatting 
  locale.setlocale(locale.LC_ALL, '') 

  # Call once to configure Bokeh to display plots inline in the notebook
  output_notebook()

  # Style of plots
  matplotlib.style.use('seaborn')
  ```


### Example Visualization
  - Plot and compare any set of COVID-19 metrics for any set of countries  
    <br>
![Data-Viz](https://github.com/SJUACM/COVID-19-Data-Analysis/blob/main/Interactive%20Plotting%20Example.gif?raw=true)
