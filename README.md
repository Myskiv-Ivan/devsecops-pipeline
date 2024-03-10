Appsec pipeline Gitlab CI/CD

Dependency:
1. DefectDojo
2. Gitlab

Add in Gitlab Project stage:

```
include:
  - project: 'ProjectName/appsecscan'
    file: '/.gitlab-ci.yml'
stages:
  - security
```
