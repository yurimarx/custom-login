## custom-login

 [![Gitter](https://img.shields.io/badge/Available%20on-Intersystems%20Open%20Exchange-00b2a9.svg)](https://openexchange.intersystems.com/package/custom-login)
 [![Quality Gate Status](https://community.objectscriptquality.com/api/project_badges/measure?project=intersystems_iris_community%2Firis-rest-api-template&metric=alert_status)](https://community.objectscriptquality.com/dashboard?id=intersystems_iris_community%2Fcustom-login)
 <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/intersystems-community/custom-login">

## Description
This is an application sample to show how to develop custom login pages and custom authentication login.

## Installation with ZPM

zpm:USER>install custom-login

## Installation for development

Create your repository from template.

Clone/git pull the repo into any local directory e.g. like it is shown below (here I show all the examples related to this repository, but I assume you have your own derived from the template):

```
$ git clone https://github.com/yurimarx/custom-login.git
```

Open the terminal in this directory and run:

```
$ docker-compose up -d --build
```

## How to Work With it

1. Open the Manament Portal on http://localhost:52773/csp/sys/UtilHome.csp.
2. Check the title of the login page (text "Custom Login") to see the custom login page in action.
3. Login with a user on superusers.csv (for example username yuri and password SYS).
4. Ready! You login with a user defined into a csv file (it is an example of custom authentication logic).

## Thanks to
1. [passwordless application](https://openexchange.intersystems.com/package/passwordless) 
2. [Google social login application](https://openexchange.intersystems.com/package/Google-IRIS-Login)