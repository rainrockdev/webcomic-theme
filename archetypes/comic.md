---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
image: "img/{{ lower (replace .Name "-" " ")   | comic-image }}.png"
draft: false
---