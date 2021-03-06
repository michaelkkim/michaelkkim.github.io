---
title: "How to setup github.io portfolio (not my work)"
date: 2019-07-23
tags: [howto, github, github.io]
header:
  image:
excerpt: "howto, github, github.io"
mathjax: "true"
---

[See this youtube video!](https://www.youtube.com/watch?v=qWrcgHwSG8M)

**Everything below is just replication from video:**

# H1 Heading

## H2 Heading

### H3 Heading

Here's some basic text.

And here's some *italics*

Here's some **bold** test.

What about a [link](https://github.com/michaelkkim)

Here's a bulleted list:
* First item
+ Second item
- Third item

Here's a numbered list:
1. First
2. Second
3. Third

Python code block:
```python
    import numpy as np

    def test_function(x,y):
      z = np.sum(x, y)
      return z
```

R code block:
```r
library(tidyverse)
df <- read_csv("some_file.csv")
head(df)
```

Here's some inline code `x+y`.

Here's an image:
<img src="{{site.url}}{{ site.baseurl }}/images/bayes_rule.jpg" alt="bayes rule formula">

Here's another image using Kramdown:
![alt]({{ site.url }}{{ site.baseurl }}/images/bayes_rule.jpg)

Here's some math:
$$z=x+y$$

You can also put it inline $$z=x+y$$
