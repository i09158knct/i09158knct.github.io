---
layout: post
title: "The First post"
date: 2014-03-07 18:32:15 +0900
comments: true
categories: 
---

http://octopress.org/docs/plugins/codeblock/

てすと

**テスト**

h1
==========


h2
--------------



~~aaaaa~~


```ruby
puts 'hello'
```

a|b|c
-|-|-
1|2|3
1|2|3
1|2|3

- a
- b
- c

1. 1
2. 2
3. 3

![image test](https://github.com/favicon.ico)

{% codeblock %}
Awesome code snippet
{% endcodeblock %}

{% codeblock Time to be Awesome - awesome.rb %}
puts "Awesome!" unless lame
{% endcodeblock %}


{% codeblock JavaScript Array Syntax lang:js http://j.mp/pPUUmW MDN Documentation %}
var arr1 = new Array(arrayLength);
var arr2 = new Array(element0, element1, ..., elementN);
{% endcodeblock %}


{% codeblock CoffeeScript Tricks lang:coffeescript start:51 mark:51,54-55 %}
# Given an alphabet:
alphabet = 'abcdefghijklmnopqrstuvwxyz'

# Iterate over part of the alphabet:
console.log letter for letter in alphabet[4..8]
{% endcodeblock %}
