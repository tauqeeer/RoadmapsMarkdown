# Data Visualization

Data Visualization enables analysts to understand and make sense of data patterns. It helps to tell stories into a form easier to understand, highlighting the trends and outliers. Some people understand better through visualization rather than what is written in front of them. Data visualization helps in grabbing reader's attention and help them understand the stories in depth as it is not language specific.

# Python Libraries For Data Visualization

## Matplotlib

It is the most popular and widely-used plotting library in the Python community. It can be used to create plots, bar charts, pie charts, histograms, scatterplots, error charts, power spectra, stemplots, and much more.

```python
import numpy as np`</br>
from matplotlib import pyplot as plt

ys = 200 + np.random.randn(100)
x = [x for x in range(len(ys))]

plt.plot(x, ys, '-')`</br>
plt.fill_between(x, ys, 195, where=(ys > 195), facecolor='g', alpha=0.6)

plt.title("Sample Visualization")
plt.show()
```

The above lines of code gives the following output:

![image](https://github.com/tauqeeer/RoadmapsMarkdown/assets/96877527/ef97eb7b-3ff7-4dc6-acd0-81806988cf64)

</br>
</br>
</br>
</br>

## Seaborn

This library is an extended version of Matplotlib and it provides a high-level interface for drawing attractive and informative statistical graphics. 

```python
import seaborn as sns
data = [1, 2, 2, 3, 3, 3, 4, 4, 4, 4]
sns.histplot(data)
```

The above lines of code gives the following output:

![image](https://github.com/tauqeeer/RoadmapsMarkdown/assets/96877527/c4714147-4aeb-4778-a56a-0885f4685016)

</br>
</br>
</br>
</br>

## Plotly

Plotly is a free open-source graphing library that can be used to form data visualizations. Plotly provides more than 40 unique chart types.

```python
import plotly.express as px
df = px.data.iris()`</br>
fig = px.scatter(df, x="petal_width", y="petal_length", color="species")
fig.show()
```

The above lines of code gives the following output:

![image](https://github.com/tauqeeer/RoadmapsMarkdown/assets/96877527/245e72e9-3b72-4c81-8276-eff439333ee4)

</br>
</br>

## Bokeh

This library is great for creating interactive and scalable visualizations in Python. 

```python
import numpy as np
import pandas as pd

from bokeh.palettes import tol
from bokeh.plotting import figure, show

N = 10
df = pd.DataFrame(np.random.randint(10, 100, size=(15, N))).add_prefix('y')

p = figure(x_range=(0, len(df)-1), y_range=(0, 800))
p.grid.minor_grid_line_color = '#eeeeee'

names = [f"y{i}" for i in range(N)]
p.varea_stack(stackers=names, x='index', color=tol['Sunset'][N], legend_label=names, source=df)

p.legend.orientation = "horizontal"
p.legend.background_fill_color = "#fafafa"

show(p)
```

The above lines of code gives the following output:

![image](https://github.com/tauqeeer/RoadmapsMarkdown/assets/96877527/790722cc-6318-4591-ac62-d1d22f6ee262)

</br>
</br>
</br>
</br>

## ggplot

ggplot is a data visualization module in the plotnine library. ggplot operates differently than Matplotlib it let's you layer components to create a complete plot.

```python
from plotnine.data import economics
from plotnine import ggplot, aes, geom_line
 
(
    ggplot(economics)  
    + aes(x="date", y="pop")  
    + geom_line()  
)
```
The above lines of code gives the following output:

![image](https://github.com/tauqeeer/RoadmapsMarkdown/assets/96877527/1c7b7a14-d198-47a4-bf25-12422b536c3d)

---
These were some of the data visualization libraries for python which you can use to enhance your stories and present the data ina much pleasing way.

</br>
</br>

# Softwares For Data Visualization

## Power BI

Power BI is a self-service business intelligence tool from Microsoft with versatile data visualization capabilities. It provides an user friendly interface to see and understand trends, outliers, and patterns in data. Power BI can connect to local or remote data in different formats and can also convert live data into up-to-date visualizations. 

Power BI can be used to connect different data sources such as cloud, remote or local data and gain insights to conclude a summary of the story you want to present.

Power BI can be downloaded from [their website](https://powerbi.microsoft.com/en-us/downloads/).

<br>


## Tableau

Tableau is used to manage and present data to gain and discover insights. The distinctive feature of Tableau is it's ease of use, which can be observed by simple drag and drop features on the software. This tool is free and flexible for data analytics, whatever you are trying to think in your head, Tableau can visualize it.



Tableau can be downloaded from [their website](https://www.tableau.com/products/desktop).

