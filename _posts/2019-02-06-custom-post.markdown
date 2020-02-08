---
layout: post
title:  "first post"
date:   2020-02-01
categories: orbital_mechanics
tags: [science]

# Author
author: Jorge M.G.
---
![picture](https://placehold.it/250x150)

My custom post

{% highlight python %}
def bubbleSort(arr):
    n = len(arr)
 
    # Traverse through all array elements
    for i in range(n):
 
        # Last i elements are already in place
        for j in range(0, n-i-1):
 
            # traverse the array from 0 to n-i-1
            # Swap if the element found is greater
            # than the next element
            if arr[j] > arr[j+1] :
                arr[j], arr[j+1] = arr[j+1], arr[j]
{% endhighlight %}
