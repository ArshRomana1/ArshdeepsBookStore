﻿Arshdeep Singh
0791162

2023-03-02
1505
Srarted Assignment 2 in-class on the lab computer.
Set up the ASP.NET MVC w/core 1.3 (out of support)
HTTPS enabled , individual account authentication , no razor yet
Reviewd the folders and the content with the professor 

and finally 1507
i made my first change in the project,
in startup.cs file i changed the line 33 , where i removed "options => options.SignIn.RequireConfirmedAccount = true".

1510
Created a Repository on GitHub and updated the Readme file
and I have made my Repo Private


and after saving the file I fired up my project to see if it works fine.

1510
It worked great, and workin fine.
1516
I changed the welcome message on the home page and tested the file by running it again.

1523
Reviewed the route pattern in the startup.cs

1544
I had to make my projectagain because my github was not responding.
I was unable to push my changes through.

2023-03-03
1534
Next day and ruuning the application with no problems.

1540
Change the data in the layout.cshtml ,so it can automatically be updated at the end of the year.

03-09-2023 1438
cloned the reposotory and fired up the project.

1442
Starting to install new bootstrap file by downloading one from bootsswatch.com
first I downloaded the bootstrap theme which I want to implement and the I changed the original bootstraps name in the project and
added the new file to the css folder
the theme is "Sketchy"
by following the instruction in the slides

1450
following the instructions from thye slides Made changes to the two files,
_layout.cshtml and _LoginPartial.cshtml

1500
After Making all the changes , tried running the project.
Running Perfectly fine.
also upadating the navigation bar.
Where Changing the name of "Home" to "Books", for our Future Books Database.

1520
Made Changes to Layout.cshtl because it wasnt Working.

1548
Added a dropdown menu link in the layout.cshtml file
and ran it its working fine.

3/10/2023
1526
Added new projects and About to run now
its running fine
just waiting for the professor to mark it now

3/27/2023
1620
Starting the project again annd still fixing the dependencies from the assignmnet1

1630
Created 3 Dependencies according to the instructions given in the slides and also also Moved the Data folde4r to the "ArshdeepsBooks.DataAccess
"
1635
Installed NuGet Package : identity.entityframeWork Core

1640
Deleted the default class1 in the all projects also modified the NameSpace
\
1645
Moved the Models folder to ArshdeepsBooks.Model, Added Preferences to the project
Lastly we renamed the Models folder to ViewModels

1655
Firstly I modified the startup.cs file and encountered the errors and then resolved them with the given instructions
Went to Error.cshtml and changed the namespace accordingly
now I am gonna fire up the engines and try to run the Project

1700
Ran the project and its running file

1705
Created a new class called SD.cs in the Utility project
and modified the property of the class to public static

Added prefernces to the projects-
DataAcees 
Main project

Added A new Area called Customer and
Modified the pattern of Startup.cs

moved homeController to the contoller folder in the Area "Customer"
and the deleted the folders called Data and Model in the Customer Area

1719
Edited the homeContoller.cs tp explicit define the customer and 
moved the Home folder from views to the view in the "Customer"

1726
Modified the homeconroller's Namespace

1729
Trying to run the Application

1740
Application Running Fine 

1742
Moved two files from Views to Customer called _viewImports.cshtml & _viewsstrat.cshtml

1800
Added A new Area called Admin
Moved two files from Views to Admin called _viewImports.cshtml & _viewsstrat.cshtml
Deleted the folders called Data and Model in the Admin Area
Deleted the Controllers folder from the main project

18.02
Ran the application and working fine
part 1 of the assignmnet is officailly completed.

3/30/2023
19.33
Staarting the part 2 assignmnet,
firstly I have made changes to the appsetting.json file and added the migrations
"20230330233239_AddDefaultIdentityMigration.cs"
"20230331003528_AddCategoryToDb.cs"
And these are the timestamps

19.45
After First step , i encountered 6 errors and solved them later through migrations 
and then updated the database by running 
"update database" command

2000
First we made a class called category.cs 
then added migration and solved error which occured in 
"applicationDbContext.cs"

2040
aDDED Category.cs file and had a lots of errors, it wasnt showing in the table.
so I had to delete the cs file and then add again and after that i ran the migrayion command and also upadated the
database
now its showing the field of category in the table

2045
Part 1 of the assignmnet is completed, now on to the second part.

2052
Added a new interface called "IRepository.cs" in the subfolder "IRepository" of folder "Repository"
which we all made in this step
and the few errors occured in the IRepository.cs file and I solved them with 
"Using" statements

2100
Now according to the Instructions
I added a new class in the repository folder called "Repository.cs"
I made changes according to the slides and then changed the using statements

2112
CategoryRepository.cs and ICategoryRepository.cs files are made as per then instructions
and made the required changes to make it work, followed the instruction givern in the slides

2115
Added a new intrface called "ISP_Call.cs" in IRepository folder and installe4d  the package to 
solve the errors

2119
Added a class in the Repository folder called "SP_Call.cs" and fix the using statements to match my namespaces

2126
pai ek hor interface Bananta called "IunitOfWork.cs" and made changes to it accordingly

2135
Made another class"UnitOfWork.cs "in the Repository folder and
later made changes to the "startup.cs" file accordingly, modified configuration service modifer method

2145
Just finished the final step and ran the application and it is running Smoothly , no errors faced.
Just waiting for the Preofessor to Mark it.
:)