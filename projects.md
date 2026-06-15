---
layout: default
permalink: /projects/
title: Projects
---

## Projects

Open-source tools and software I've built alongside my research.

### [icdlookup](https://github.com/yabdulle/icdlookup)

A Python package for looking up ICD codes and mapping them to human-readable descriptions. Ships with a built-in ICD-10-CM 2026 dataset sourced from the official CMS files — useful for annotating clinical datasets, EHR pipelines, and phenotyping workflows.

```bash
pip install icdlookup
```

```python
import icdlookup

icdlookup.lookup("A00.1")
# → "cholera due to vibrio cholerae 01, biovar eltor"

icdlookup.search("cholera")
# → [("A00", "cholera"), ("A00.0", "cholera due to ..."), ...]
```

[GitHub](https://github.com/yabdulle/icdlookup) · [PyPI](https://pypi.org/project/icdlookup/)
