# Getting Started with Github-actions

## Introduction to CI/CD

In early time when **Git** and **Github-actions** were not present, software engineers manually test their code and then depoly their project on production servers.

Later after if anything happens with the code like code broken or bug in the code then they have to face downtime with their website or app.

So that to get rid of this problem, CI/CD is introduced which means continous inegration and continous delivery. In CI/CD we create a pipline of autonomus tasks for our project like testing, deploying, etc.

There are various tools available in the market to create and deploy CI/CD piplines like `Github actions`, `Jenkins`, `CircleCI`, etc.

## How to start with Github Actions

- Create a `.github` folder in your project folder.
- Create a `workflows` folder in that folder.
- If you create any `.yml` file in that workflows folder then it will be considered as a workflow.
- Let's create `test.yml` file in that folder. This file is now considered as a Github action.
- You can verify it by going to repository's action tab and you will see that new action is listed there.

## YAML - yet another markup language

YAML is a data serialization language that is often used for writing configuaration files. It is much similar like `JSON`, but it is more readable.
You can consider it as a superset of JSON which has easy syntax. There are no usual format symbols like braces, closing tags or sqaure brackets.
It uses `.yml` or `.yaml` extension.

We are going to use YAML for creating and applying logic for Github actions.

