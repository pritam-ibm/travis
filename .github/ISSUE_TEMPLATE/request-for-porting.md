---
name: Request for porting
about: Request for porting.
title: ''
labels: ''
assignees: ''

---

body:
  - type: markdown
    attributes:
      value: >
        Github is reserved for bug reports and feature requests; it is
        not the place for general questions. 

        Please fill in the following details to request Currency for a package:
  - type: input
    id: pkg_name
    attributes:
      label: Package Name
      description: >-
        The package name you want to be supported on power e.g. redis, elasticsearch
    validations:
      required: true
  - type: input
    id: version 
    attributes:
      label: Package Version
      description: Specific version of package want to be supported on power
    validations:
      required: false
  - type: input
    id: github_repo
    attributes:
      label: GitHub Repo url
      description: The GitHub source url of package
    validations:
      required: true
