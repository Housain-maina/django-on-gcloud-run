# Django on Google Cloud Run

Step by step guide for deploying a django web app on Google Cloud Run.

This guide includes the following:
1. Setting up Terraform for automated resources provisioning on the Google Cloud Platform
2. Docker for containerizing your django app
3. Google Cloud Build for continuous integration / continuous deployment (CI/CD).

## Pre-requisites

1. A google cloud account
2. Google Cloud command-line tool installed on your machine
3. An existing django project
4. A requirements.txt file

Take the following steps to get started with the deployment process:

1. Create a new terraform file `main.tf`
2.
