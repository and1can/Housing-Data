

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
```

    /usr/local/lib/python2.7/site-packages/matplotlib/font_manager.py:273: UserWarning: Matplotlib is building the font cache using fc-list. This may take a moment.
      warnings.warn('Matplotlib is building the font cache using fc-list. This may take a moment.')



```python
data = pd.read_csv('2013Housingdata.txt')
data.head()
```




<div>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>CONTROL</th>
      <th>AGE1</th>
      <th>METRO3</th>
      <th>REGION</th>
      <th>LMED</th>
      <th>FMR</th>
      <th>L30</th>
      <th>L50</th>
      <th>L80</th>
      <th>IPOV</th>
      <th>...</th>
      <th>FMTINCRELFMRCAT</th>
      <th>FMTCOST06RELAMICAT</th>
      <th>FMTCOST08RELAMICAT</th>
      <th>FMTCOST12RELAMICAT</th>
      <th>FMTCOSTMEDRELAMICAT</th>
      <th>FMTINCRELAMICAT</th>
      <th>FMTASSISTED</th>
      <th>FMTBURDEN</th>
      <th>FMTREGION</th>
      <th>FMTSTATUS</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>'100003130103'</td>
      <td>82</td>
      <td>'3'</td>
      <td>'1'</td>
      <td>73738</td>
      <td>956</td>
      <td>15738</td>
      <td>26213</td>
      <td>40322</td>
      <td>11067</td>
      <td>...</td>
      <td>'1 LTE 50% FMR'</td>
      <td>'2 30 - 50% AMI'</td>
      <td>'2 30 - 50% AMI'</td>
      <td>'2 30 - 50% AMI'</td>
      <td>'2 30 - 50% AMI'</td>
      <td>'2 30 - 50% AMI'</td>
      <td>'.'</td>
      <td>'2 30% to 50%'</td>
      <td>'-5'</td>
      <td>'-5'</td>
    </tr>
    <tr>
      <th>1</th>
      <td>'100006110249'</td>
      <td>50</td>
      <td>'5'</td>
      <td>'3'</td>
      <td>55846</td>
      <td>1100</td>
      <td>17165</td>
      <td>28604</td>
      <td>45744</td>
      <td>24218</td>
      <td>...</td>
      <td>'3 GT FMR'</td>
      <td>'4 60 - 80% AMI'</td>
      <td>'4 60 - 80% AMI'</td>
      <td>'6 100 - 120% AMI'</td>
      <td>'4 60 - 80% AMI'</td>
      <td>'7 120% AMI +'</td>
      <td>'.'</td>
      <td>'1 Less than 30%'</td>
      <td>'-5'</td>
      <td>'-5'</td>
    </tr>
    <tr>
      <th>2</th>
      <td>'100006370140'</td>
      <td>53</td>
      <td>'5'</td>
      <td>'3'</td>
      <td>55846</td>
      <td>1100</td>
      <td>13750</td>
      <td>22897</td>
      <td>36614</td>
      <td>15470</td>
      <td>...</td>
      <td>'2 50.1 - 100% FMR'</td>
      <td>'4 60 - 80% AMI'</td>
      <td>'5 80 - 100% AMI'</td>
      <td>'6 100 - 120% AMI'</td>
      <td>'4 60 - 80% AMI'</td>
      <td>'4 60 - 80% AMI'</td>
      <td>'.'</td>
      <td>'3 50% or More'</td>
      <td>'-5'</td>
      <td>'-5'</td>
    </tr>
    <tr>
      <th>3</th>
      <td>'100006520140'</td>
      <td>67</td>
      <td>'5'</td>
      <td>'3'</td>
      <td>55846</td>
      <td>949</td>
      <td>13750</td>
      <td>22897</td>
      <td>36614</td>
      <td>13964</td>
      <td>...</td>
      <td>'2 50.1 - 100% FMR'</td>
      <td>'6 100 - 120% AMI'</td>
      <td>'7 120% AMI +'</td>
      <td>'7 120% AMI +'</td>
      <td>'5 80 - 100% AMI'</td>
      <td>'4 60 - 80% AMI'</td>
      <td>'.'</td>
      <td>'1 Less than 30%'</td>
      <td>'-5'</td>
      <td>'-5'</td>
    </tr>
    <tr>
      <th>4</th>
      <td>'100007130148'</td>
      <td>26</td>
      <td>'1'</td>
      <td>'3'</td>
      <td>60991</td>
      <td>737</td>
      <td>14801</td>
      <td>24628</td>
      <td>39421</td>
      <td>15492</td>
      <td>...</td>
      <td>'3 GT FMR'</td>
      <td>'3 50 - 60% AMI'</td>
      <td>'3 50 - 60% AMI'</td>
      <td>'3 50 - 60% AMI'</td>
      <td>'3 50 - 60% AMI'</td>
      <td>'7 120% AMI +'</td>
      <td>'0 Not Assisted'</td>
      <td>'1 Less than 30%'</td>
      <td>'-5'</td>
      <td>'-5'</td>
    </tr>
  </tbody>
</table>
<p>5 rows × 99 columns</p>
</div>




```python

```
