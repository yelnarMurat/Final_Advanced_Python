# Final_Advanced_Python

Our vision is to reproduce a good dataset to give an opportunity to select different variations of products for those people who want to buy some electronics in Almaty city. The main benefit of this dataset is you can find a proper product which matches your needs. So, it will be given some information about electronic products from different internet stores. And you can specify for yourself which item or from which store you will get most benefits. 
We used three different web-sites:
* www.sulpak.kz
* www.alser.kz
* www.alpha.kz

And collected data from different categories(TVs, Smartphones, Laptops, Tablets).
During the project we used the following libraries:
```python
import requests
from bs4 import BeautifulSoup
import csv
import pandas as pd
import numpy as np
import seaborn as sns
```
Before starting analyze our dataset, we stored all our data in CSV file. For instance:
![alt text](https://github.com/yelnarMurat/Final_Advanced_Python/blob/main/csv.png?raw=true)

Then after cleaning and transformating our dataset using data visualization modules made such kind of plots. Than can show difference between our web-sites.
![alt text](https://github.com/yelnarMurat/Final_Advanced_Python/blob/main/plot1.png?raw=true)

For example, here is the barplot to show the difference between these 2 stores for the same laptop model.

![alt text](https://github.com/yelnarMurat/Final_Advanced_Python/blob/main/plot2.png?raw=true)

