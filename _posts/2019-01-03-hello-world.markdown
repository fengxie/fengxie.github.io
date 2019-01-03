---
layout: post
title:  "My first blog on github"
subtitle: "Hello world"
author: FX
catalog: yes
date:   2019-01-03 15:21:03 +0800
tags:
 - note
---

## Hey
>这是我的第一篇博客。

{% highlight python %}
import numpy as np
import matplotlib.pyplot as plt

theta = np.arange(0, 2.0 * np.pi, 0.001)
r = np.sin(2 * theta) + np.sin(6 * theta) / 4.0

plt.polar(theta, np.abs(r))
plt.polar(theta, 0.5 * np.abs(r))

plt.show()
{% endhighlight %}
