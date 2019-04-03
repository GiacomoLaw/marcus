---
layout: post
title:  "Marcus theme - features"
image: assets/images/posts/sunrise.jpg
---

The Marcus theme is a simple, but beautiful theme for those wanting a Jekyll theme. It has the following features:

- Search
- Post images
- Syntax highlighting
- Embedded images
- Pages folder

![Welcome!]({{ site.baseurl }}/assets/images/posts/sunrise.jpg)

```python
def bubbleSort(alist):
    for passnum in range(len(alist)-1,0,-1):
        for i in range(passnum):
            if alist[i]>alist[i+1]:
                temp = alist[i]
                alist[i] = alist[i+1]
                alist[i+1] = temp

alist = [54,26,93,17,77,31,44,55,20]
bubbleSort(alist)
print(alist)
```