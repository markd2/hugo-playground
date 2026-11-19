+++
date = '{{ .Date }}'
draft = true
title = 'OMG GREEBLE {{ replace .File.ContentBaseName "-" " " | title }}'
+++
Woo Greeble Template!

```
hugo new content greeble/blah.md
```
