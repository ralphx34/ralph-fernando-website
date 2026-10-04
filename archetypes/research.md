+++
title = "{{ replace .File.ContentBaseName "-" " " | title }}"
authors = []
category = "working-paper"
year = {{ now.Year }}
description = ""
paper = ""
publication = ""
publication_url = ""
code = ""
venue = ""
weight = 10
draft = true

[build]
  render = "never"
  list = "local"
+++