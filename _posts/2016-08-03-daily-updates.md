---
published: true
layout: post
tags:
  - daily-update
---
Today I Read

1. [Painful journey of painless deployments : Airpair](https://www.airpair.com/docker/posts/the-painful-journey-of-painless-deployments)
2. [Continuous delivery bitbucket pipelines](https://python-programming.courses/testing/continuous-delivery-tox-bitbucket-pipelines/) on git push
3. [Configure deployment script on bitbucket pipelines](https://confluence.atlassian.com/bitbucket/configure-bitbucket-pipelines-yml-792298910.html)

```
bitbucket-pipelines.yml
--------
image: node:5.11.0
pipelines:
  default:
    - step:
        script:
          - echo "This script runs on all branches that don't have any specific pipeline assigned in 'branches'."
  branches:
    master:
      - step:
          script:
            - echo "This script runs only on commit to the master branch."
    feature/*:
      - step:
          image: java:openjdk-9 # This step uses its own image
          script:
            - echo "This script runs only on commit to branches with names that match the feature/* pattern."
```

4. [css tools of 2016 : speckyboy](https://speckyboy.com/2016/07/13/css-libraries-frameworks-tools-2016/?ref=webdesignernews.com)
