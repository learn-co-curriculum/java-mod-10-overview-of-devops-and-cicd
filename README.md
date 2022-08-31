# Overview of DevOps and CI/CD

## Learning Goals

- Overview of DevOps principals
- Overview of CI/CD processes


## Introduction

We've been exposed so far to some concepts that fall in the DevOps space. The most beneficial ones we've been making use of would be Docker and Docker Compose.
So far we have been using these tools to automate systems locally in a development environment. Once we start considering production environments however, these tools aren't necessarily
applicable on their own for solving the unique challenges for production environments.

Additional DevOps processes and tooling starts becoming more prevalent once needing to automate the full scope of a production environment. From creating and maintaining the production
hosting infrastructure environment, to configuring individual Virtual Machines, configuring individual physical servers, building and Orchestrating Containers, and building pipelines
that support automated processes from an initial code commit to eventual deployment in production.


## DevOps Overview

DevOps itself can be considered just as much of a collaboration style between Developers and Operations, as it can be considered a specific set of technical problems to be solved with those relevant tools.
There are many ways in which this collaboration can manifest. Some patterns are good, and some are best to avoid or move away from.
Take a look at some well described patterns.

- [DevOps Structure](https://web.devopstopologies.com/)

While a main point of DevOps is these organizational structures, the actual problem space addressed and processes used are just as important.
While every organization or environment may take a different approach here, there are some high level concepts that tend to be addressed similarly.
There is a good quick primer by GitHub that encapsulates these ideas well.

- [Defining DevOps](https://resources.github.com/devops/)


## CI/CD Overview

Most of the DevOps platform and tooling management will tend to fall under the responsibility of dedicated DevOps engineers.
However, developers do have high visibility on the CI/CD pipeline definitions that are created for a given application, so this is something that commonly is owned by a given application team.
GitHub has a good overview of this topic as well.
		
- [CI/CD Explained](https://resources.github.com/ci-cd/)
