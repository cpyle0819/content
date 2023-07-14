---
title: "Cloud Journeys: Helping a hotel manager automate here workflow with ML"
description: "The Code Examples team tells the story of how they created a serverless application that uses ML to automate the transcription, translation, and audio synthesis of guest feedback at a fictional hotel."
tags:
  - cdk
  - s3
  - textract
  - translate
  - comprehend 
  - polly
  - ai-ml
authorGithubAlias: ford-at-aws
authorName: Ford Prior
additionalAuthors:
  - authorGithubAlias: cpyle0819 
    authorName: Corey Pyle
  - authorGithubAlias: DavidSouther
    authorName: David Souther
  - authorGithubAlias: scmacdon
    authorName: Scott Macdonald
showInHomeFeed: true
date: 2023-08-01
---

|ToC|
|---|

## 1. Prologue

Hello! Welcome to part 2 of our Cloud Journeys series. If this is your first time here, be sure to check out our first post in the series for more information about our team.

## 2. Starting with a persona

## 3. Choosing our services

## 4. From simple Step Function pipeline to something more robust

## 5. Reducing the number of Lambdas via direct S3 integration

## 6. Moving to a single CDK stack

## 7. Flexibility in our Lambda deployments

## 8. A few notes on the frontend

## 9. The final result

## 10. Epilogue

## Appendix A - Implementations

Most of the application resources for this example are shared. The Lambda functions are implemented in different languages to showcase the use of the AWS SDK in those languages.

- [Front End](https://github.com/awsdocs/aws-doc-sdk-examples/tree/main/applications/feedback-sentiment-analyzer/client)
- [CDK](https://github.com/awsdocs/aws-doc-sdk-examples/tree/main/applications/feedback-sentiment-analyzer/cdk/README.md)
