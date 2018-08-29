---
layout: post
title: Commonly used methods in Ruby
date:   2018-08-30 12:36:00 +0530
categories: jekyll update
---
1. Array#Compact:
The _Array_ class provides an object method _compact_ which returns a new array with all nil objects removed from the array on which it operates.

Ex:
arr = [1,2,3,nil,4,nil]
arr.compact // _will_ _return_ _[1,2,3,4]_