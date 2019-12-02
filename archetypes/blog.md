---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true
author : ""
categories : [""]
featuredpath : ""
type : ""
---








{{ range first 10 ( where .Site.RegularPages "Type" "post" ) }}
* {{ .Title }}
{{ end }}