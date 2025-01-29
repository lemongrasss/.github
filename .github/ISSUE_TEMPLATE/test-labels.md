---
name: labels test md
about: Use this template for tracking new features.
title: "[Add more labels maybe"
labels: deploy, cd-serverless, invalid
assignees: octocat
---

body:
 - type: dropdown
    id: Product-type
    attributes:
      label: Is this for a net new item?
      options:
       - 'Yes'
       - 'No'
      default: 0
 - type: markdown
    attributes:
     value: |
      ```[tasklist]
      ### Pre-work List
      - [ ] Product in App Inventory
      - [ ] Application Service CI
      - [ ] Application CI: Support Matrix
      - [ ] AIA
      - [ ] AD Groups
      - [ ] ISAM
      - [ ] eSAF
      - [ ] Application User Guide
      - [ ] Knowledge Article/Solution Guide
      - [ ] UAT Coordination
      - [ ] Change Management/Request
      - [ ] Pre-Release Communication
      - [ ] GO LIVE/Deployment
      - [ ] Post - Release Communication
      - [ ] Update App Inventory Request
      - [ ] Update App Inventory Product
      ```
