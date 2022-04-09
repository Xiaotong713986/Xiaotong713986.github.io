---
title: "{{ with slicestr .Name 7 }}{{replace . "-" " "  | strings.TrimLeft " " | title }}{{end}}"
date: {{ .Date }}
Newdate: "{{ slicestr .Name 0 7 }}"
Description: ""
Tags: []
Categories: []
featureImg: "news-example"
---
- One paper was accepted to 