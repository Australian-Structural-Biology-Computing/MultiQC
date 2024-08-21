---
name: pbmarkdup
urls: ["https://github.com/PacificBiosciences/pbmarkdup"]
summary: >
  Takes one or multiple sequencing chips of an amplified libray as HiFi reads and marks or removes duplicates
---

<!--
~~~~~ DO NOT EDIT ~~~~~
This file is autogenerated from the MultiQC module python docstring.
Do not edit the markdown, it will be overwritten.

File path for the source of this content: multiqc/modules/pbmarkdup/pbmarkdup.py
~~~~~~~~~~~~~~~~~~~~~~~
-->

The module adds the **% Unique Molecules** and **%Duplicate Reads** (hidden) to the General Statistics
table.

### File search patterns

```yaml
pbmarkdup:
  contents_re: LIBRARY +READS +UNIQUE MOLECULES +DUPLICATE READS
  num_lines: 5
```