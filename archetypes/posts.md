---
title: "{{ replace .Name "-" " " | title }}"
author: "Анонимен"
date: {{ .Date }}
slug: {{ .Name | urlize }}
type: posts
draft: true
weight: 20
categories:
  - Наръчници
tags:
  - Наръчници
---
