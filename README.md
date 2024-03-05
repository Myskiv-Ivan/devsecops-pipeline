Appsec pipeline Gitlab CI/CD

```
include:
  - project: 'ProjectName/appsecscan'
    file: '/.gitlab-ci.yml'
stages:
  - security
```
