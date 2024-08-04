---
title:  '{{ replace .Name "-" " " | title }}'
date: {{ .Date }}
draft: true
description: ""
ingredients:
  - ""
instructions:
  - ""
prep_time: ""
cook_time: ""
total_time: ""
servings: ""
tags: []
---

## Ingredientes

{{ range .ingredients }}
- {{ . }}
{{ end }}

## Instruções

{{ range .instructions }}
1. {{ . }}
{{ end }}

**Tempo de preparo:** {{ .prep_time }}
**Tempo de cozimento:** {{ .cook_time }}
**Tempo total:** {{ .total_time }}
**Porções:** {{ .servings }}
