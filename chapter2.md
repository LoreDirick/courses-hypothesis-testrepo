---
title       : One sample hypothesis testing
description : 



--- type:NormalExercise lang:python xp:100 skills:2 key:13e65f0ce8
## CHAPTER 2: Exercise 1

```yaml
type: NormalExercise
lang: python
xp: 100
skills: 1
key: 7942f6cb9a
```

*** =instructions

New York City has an open access dataset containing all 311 service calls requesting service or registering a complaint. The data has been preloaded in `complaints` dataframe. 

*** =hint

*** =pre_exercise_code
```{python}

import numpy as np
import pandas as pd
import scipy.stats as stats
import urllib.request

filename = 'https://s3.amazonaws.com/assets.datacamp.com/production/course_6777/datasets/Chicago_violent_crimes.csv.gz.csv'
urllib.request.urlretrieve(filename, "nyc_complaints_311.csv.gz")

complaints = pd.read_csv('nyc_complaints_311.csv.gz')
```

*** =sample_code
```{python}

```

*** =solution
```{python}

```

*** =sct
```{python}

```

--- type:NormalExercise lang:python xp:100 skills:2 key:a387ec52f7
## CHAPTER 2: Exercise 2

```yaml
type: NormalExercise
lang: python
xp: 100
skills: 1
key: a8b5042fc1
```

*** =instructions

Till now we have used t-statistics for hypothesis testing. However, for large data (n > 30) and with known variance the usage of z-test is appropriate. 

*** =hint

*** =pre_exercise_code
```{python}

```

*** =sample_code
```{python}

```

*** =solution
```{python}

```

*** =sct
```{python}

```

