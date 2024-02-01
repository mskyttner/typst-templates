# Typst IEEE Format

Based on the IEE template published by the Typst team at <https://github.com/typst/templates/tree/main/ieee>.

**NOTE**: This format requires the pre-release version of Quarto v1.4, which you can download here: <https://quarto.org/docs/download/prerelease>.

## Installing

```bash
quarto use template quarto-ext/typst-templates/ieee
```

This will install the extension and create an example qmd file that you can use as a starting place for your document.

## Using

The example qmd demonstrates the document options supported by the IEE format (`title`, `authorsgit p`, `abstract`, `index-terms`, etc.). For example, your document options might look something like this:

```yaml
---
title: "A typesetting system to untangle the scientific writing process"
authors:
  - name: Martin Haug
    email: "haug@typst.app"
    affiliations:
      - name: Typst GmbH
        department: Co-Founder
        city: Berlin
        country: Germany
  - name: Laurenz Mädje
    email: "maedje@typst.app"
    affiliations:
      - name: Typst GmbH
        department: Co-Founder
        city: Berlin
        country: Germany
abstract: |
  (Abstract Contents)
format:
  ieee-typst: default
bibliography: refs.bib
---
```

This document would be rendered as:

![](ieee.png)
