# sqldbrepo

################################################
Sample code 
Sample code 
Sample code 

This code is for demonstration purposes only. 
################################################

SQL DB project in VS 2019

Note that the name "AdventureWorksProject" is a bit misleading. I started off with an Adventureworks database project but deleted it and created a new database project named "Database1".

The pupose of this example is to demonstrate doing db development in one VM, and using a self-hosted GH workflow on a second "SQL Server VM." This second VM has a self-hosted GitHub runner, MSBuild, and the target SQL Server on it. 

Notice the use of the "microsoft/setup-msbuild@v1" action which puts the location of msbuild.exe into the runner's context.

-blizz
