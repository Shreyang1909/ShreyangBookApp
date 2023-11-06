Name: Shreyang Chauhan
ID: W0789989
Course: Asp.Net

2023-10-31
1153
start new project with in ASP.NET Core Web Application and change authentication to individual account type.

1154
Commented out ssl port in launchsettings.json

1155
Created README.txt and README.md
Added description in READMe.txt

1157
In startup.cs ,Commented out options => options.SignIn.RequireConfirmedAccount = true 

1159
Created Github repositery named ShreyangBookApp

1200
Reviewed all files

1202
Added breakpoints in HomeController.cs for Index and Privacy pages.
Tested Application , run perfectly.

1203
download a Superhero theme from Bootswatch website

1204
into wwwroot folder add new file into css folder with the name of Bootstrap.css

1206
replace the site.css file with the given site.css file 
make change into layout.cshtml file with removing .min from 7th line
into layout.cshtml folder change navbar_light with a Navbar_dark and change bg_light to Bg_primary

1208
change footer into _Layout.cshtml folder with text-white 50 bg-primary.

1212
removed a text-dark from line 9,20,23 of loginPartial.cshtml folder
Tested project, ran perfectly

1214
Added styles and scripts in _Layout.cshtml

1216
Added dropdown in _Layout.cshtml 

1220
Added 3 class libraries using .net 5.0 named
ShreyangBook.DataAccess
ShreyangBook.Models
ShreyangBook.Utility

1221
Moved Data folder to .DataAccess

1233
Installed 3 packages
Deleted Migration folder

1236
Modified namespace in ApplicationDbContext.cs
Deleted Class1.cs from 3 projects

1245
Moved Models folder to .Models
Modified Error.cshtml

1247
Renamed Models folder to ViewModels
Modified namespace in ErrorViewModels.cs

1249
Solved 3 errors by added using statement. 
Modified Startup.cs
Changed reference in Error.cshtml
Ran application, worked perfectly

1258
Added SD.cs class in Utility project
Added project referenes Main project and DataAccess

1301
Added new area named Customer
Modified startup.cs , {area=customer}

1303
Moved HomeController.cs to Customer's Controller
Deleted Data and Models

1305
Modified namespace in HomeController.cs 
Moved Home folder to Customer Views

1311
Moved _ViewImport and _ViewStart to customer views
Tested application, ran perfectly

1315
Added New Area Named Admin
Deleted Data and Models folder

1316
Deleted controllers folder from main project
Tested Appliocation, ran successfully

1318
Upldated README.md


2023-11-06

1616
Started Part-2 

1619
Built Project and modified appsettings.json

1622
Added following migrations to .DataAccess
20231106212109_AddDefaultIdentityMigration.Designer.cs
20231106212109_AddDefaultIdentityMigration.cs 

1627
REviewed sql server object explorer

1635
Created new Category class in Models
ran migration AddCategoryToDb


1637
Modified ApplicationDbContext.cs
ran migration AddCategoryToDb2
Updated Database
Reviewed SQL SOE

1645
Created Repository folder ,  created IRepository folder in it.

1648
Created IRepository.cs and added CRUD methods in it.

1654
Created Repository class in Repository folder
Updated using statements

1700
Created CategoryRepository.cs and ICategoryRepository.cs and modified 

1706
Modified ApplicationDbContext.cs

1712
Reviewed and modified class and interface in Repository folders
Removed error by adding using statements
Added remaining code to CategoryRepository.cs and comments in it
