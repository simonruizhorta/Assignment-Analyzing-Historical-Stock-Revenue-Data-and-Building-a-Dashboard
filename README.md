# Assignment-Analyzing-Historical-Stock-Revenue-Data-and-Building-a-Dashboard

## Question 1: Use yfinance to Extract Stock Data

import yfinance as yf
import pandas as pd
import requests
from bs4 import BeautifulSoup
import plotly.graph_objects as go
from plotly.subplots import make_subplots

import warnings
# Ignore all warnings
warnings.filterwarnings("ignore", category=FutureWarning)
