# ome-ngff

Next-generation file format (NGFF) specifications for storing bioimaging data in the cloud.

## Editing

Specifications are written in markdown, or technically
[bikeshed](https://github.com/tabatkins/bikeshed) -- a markdown document, with
special extensions understood by the bikeshed tool. The bikeshed tool is run
on-commit via the [spec-prod github action](https://github.com/w3c/spec-prod),
generating the familiar "spec looking" ReSpec format. ReSpec is just html with
a javascript ReSpec library.

Specification files end with the .bs file extension. The github action runs on
commit to automatically convert to respec/html, via bikeshed. 

[Learn more about bikeshed](https://w3c-ccg.github.io/bikeshed_instructions.html)

## Citing

Next-generation file format (NGFF) specifications for storing bioimaging data
in the cloud. Josh Moore, et al. Editors. Open Microscopy Environment
Consortium, 20 November 2020. This edition of the specification (0.1) is
https://ngff.openmicroscopy.org/0.1. The latest edition of NGFF is available at
https://ngff.openmicroscopy.org. (edited)
