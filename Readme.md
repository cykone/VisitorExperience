# Visitor Experience - Visitor Overview

This project is a quick and dirty POC for the Visitor Overview concept. Through our research at TCS London, we found that our receptionist are not able to see an overview of expected guests. This is due to the fact, that currently they only forward emails to the DMG reception and that there is no common process in place for inviting and announcing visitors to the NCH. 

The purpose of this POC is to have something to test with real users and to show how a solution could look like.

## Architecture
The frontend of the POC is based on angular-cli and the backend is an Asp.Net Core 2 WebApi project. You can find the Frontend in 
```
VisitorExperience.web
```
the backend in
```
VisitorExperience.Api
```

### Frontend
You can find more details, information and documentation here
```
* Get started with angular cli https://cli.angular.io/
* Find a general Documentation about angular https://angular.io/docs
```

### Backend
You can find more details, information and documentation here
```
Get started: https://blogs.msdn.microsoft.com/webdev/2017/08/14/announcing-asp-net-core-2-0/
```

#### Database
The current solution uses Entity Framework as Database Wrapper and due to restrictions on the local dev system (can't install software- no admin rights) a sqlite provider and database. This should be replaced by a proper database serve like sqlserver as soons as the dev environment is open for installing software or an online solution on AWS can be provided. 

More information about Entity Framework Core
```
Get started: https://docs.microsoft.com/en-us/ef/core/
```


## Getting started

This document will help you to get this project up and running on your local machine. Therefore you need to install the following frameworks and tools:

Install Node and follow the steps descibed here:
```
https://nodejs.org/en/download/
```

Install dotnet core following the steps described here:
```
https://www.microsoft.com/net/download/core
```
## Running the application



