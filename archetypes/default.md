---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true
aliases: ["/{{ lower .Name }}"]
---

