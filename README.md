# ReusingViewsRepro

## Description

When referencing another ASP.NET Core Web Application and trying to use its Views, it only works on the first build. 
If you change something in the referencing project and hit the run button again you get a 404 error.

The only working solution is to rebuild the referencing project and **then** hit run. 

## Steps to reproduce

1. Using .NET Core 3.0 preview6 (I dont know if the bug exists in lower versions)
1. Clone this Repo
1. Run **ReusingViewsRepro**
