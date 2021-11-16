[![MLOps with Github Actions](https://github.com/balajivenky06/ML_Deployment/actions/workflows/main.yml/badge.svg)](https://github.com/balajivenky06/ML_Deployment/actions/workflows/main.yml)
[![AWS Code Build](https://codebuild.us-east-1.amazonaws.com/badges?uuid=eyJlbmNyeXB0ZWREYXRhIjoiQlVCZGtZUEdSRUZvWS8xS0dLT0tzSktXYWdaT2s3MXVjTmk5RjJvU24rUlRzTjRhUWtWTHB0TkhVekd5dWlhSVArWGFBYXFxUnMyVUttWFRpeldOQU53PSIsIml2UGFyYW1ldGVyU3BlYyI6IlpuYkZTMDF6Nm5QVTJ5dnYiLCJtYXRlcmlhbFNldFNlcmlhbCI6MX0%3D&branch=main)

# ML_Deployment
contains workflow for creating ML model CI/CD Deployment using Git Actions, AWS Code Commit &amp; App Runner

To create Virtual Environment:
  1) python3 -m pip install virtualenv  --> incase virtualenv package not available then install it
  2) virtualenv ~/.venv  --> create hidden virtualenv venv
  2) source ~/.venv/bin/activate --> activate virtualenv
  3) vim ~/.venv/bin/activate
  4) vim ~/.bashrc --> shift+g --> source ~/.venv/bin/activate --> permenantly adding virtualenv to bash
  5) deactivate --> to deactivate virtualenv


To Authorize AWS cloud Shell to connect with this Github Repo:
  1) can clone through https -> but need to specify username & pwd, else we can opt for ssh
  2) ssh-keygen --> press enter for default filename & passphrase to generate ssh key
  3) note: id_rsa file generated and location where saved will be displayed
  4) cat /home/cloudshell-user/.ssh/id_rsa.pub --> to see the rsa token
  5) go back to github account --> settings --> SSH & GPG keys --> New ssh key --> save the ssh

