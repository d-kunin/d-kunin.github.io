---
layout: post
title: "Formatting json using command line tools"
date: 2016-02-26 15:45:41 -0800
comments: true
categories: [short, cli tricks]
---

Validate and format clipboard content and then copy the result:
```bash
pbpaste | python -m json.tool | pbcopy
```

To provide an input from a file:
```bash
cat <filename> | python -m json.tool
```


