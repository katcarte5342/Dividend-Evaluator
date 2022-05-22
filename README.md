# Group Project - Dividends Evaluator : Juan Bohorquez, Kelvin Le & Ethan Rosenberg

# This was a team collaboration :  We all worked together on writing the code and coming up with solutions.  Every detail were voted by consensus.

### This project aims to analyze the performance of dividends among the top 50 performing stocks to help with decision making.

The dividends in the provided `personal.json` database are the top 50 highest rated stocks currently.

---

## Technologies

This project leverages python 3.9 and Jupyter lab notebook was used to run all analysis.

---

## Installations

Before running the application first import the following libraries and dependencies.

```python
import pandas as pd
from pathlib import Path
%matplotlib inline
import numpy as np
import json 
import requests
import urllib3
from urllib3 import request
import matplotlib.pyplot as plt
import hvplot.pandas
```

---
