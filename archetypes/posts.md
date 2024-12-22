---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
slug: {{ .Name | urlize }}
type: posts
draft: true
weight: 10
categories:
  - default
tags:
  - default
---
