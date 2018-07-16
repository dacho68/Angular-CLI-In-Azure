# Setup Angular CLI with Git on Azure

## Create Angular 2 with  CLI

- npm i -g @angular/cli
- ng new myApp
- cd myApp
- ng server
## Create New Git repos
- Goto the new project folder
- git init
- git add .
- git commit . -m "Init"
- git remote add origin [Git repos]
- git push -u origin master 

## Create the Kudu script for compiling code on azure
- npm i -g kuduscript
- kuduscript -y --node


https://passos.com.au/build-and-deploy-an-angular-app-from-github-to-azure-website/
