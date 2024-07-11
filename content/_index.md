---
title: "Welcome to OTChem"
description: "A website by Davide Crucitti, where I share bits of information I gather while doing my research"
---

## Articles

{{ range .Site.RegularPages }}
- [{{ .Title }}]({{ .Permalink }})
{{ end }}
