---
title: "{{ replace .Name "-" " " | title }}"
summary: "Write a summary"
author: "Анонимен"
date: {{ .Date }}
slug: {{ .Name | urlize }}
type: dict
draft: true
weight: 20
categories:
  - Речник
tags:
  - Речник
  - Термини
---
