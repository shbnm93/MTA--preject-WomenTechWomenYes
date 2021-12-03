# MTA-preject-WomenTechWomenYes
import pandas as pd
import numpy as np
import matplotlib as mpl
import matplotlib.pyplot as plt
import scipy.stats as st
#import pymc3 as pm
import seaborn as sns
import dateutil.parser
import datetime
from datetime import timedelta
from datetime import date
import calendar

# enables inline plots, without it plots don't show up in the notebook
%matplotlib inline
%config InlineBackend.figure_format = 'svg'
pd.set_option('display.max_rows', 500)
