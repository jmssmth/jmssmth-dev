---
title: pandas snippets
date: '2020-02-12T12:35:08.000Z'
layout: post
draft: false
path: '/posts/pandas/'
category: 'Design Inspiration'
tags:
  - 'python'
  - 'pandas'
  - 'cheatsheet'
# description: ''
---

## pandas setup

```python
import numpy as np  # convention
import pandas as pd # convention
import platform, sys
import pathlib as pl # my habit
print(F'System:  {platform.platform()[:10]}')
print(F'Python:  {sys.version[:5]}')
print(F'Pandas:  {pd.__version__}')
pd.options.display.max_columns=100
pd.options.display.max_rows=100
```

<!-- include and image... -->
<!-- ![Nulla faucibus vestibulum eros in tempus. Vestibulum tempor imperdiet velit nec dapibus](./1.jpg) -->

## dataframe creation
