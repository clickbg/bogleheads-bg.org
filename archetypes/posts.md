---
title: "{{ replace .Name "-" " " | title }}"
author: "Анонимен"
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
