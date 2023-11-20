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

1722
Added new interface in IRpository folder 
Insalled Dapper package

1740
Added New class in Repository folder
added connections in it

1744
Added IUnitOfWork interface in IRepository

1745
Added UnitOfWork class in Repository
modified the code , solved the errors

1750
Made it accecible in Startup.cs

1808 
Added New controller in Admin Area, added using statements to solve errors

1810
Added New folder in Admin Area 
Added razorview named category in it 
Added code form provied file in Index view

1819
Modified _Layout.cshtml
Changed Privacy navigation to Category
Tested Application, Ran perfectly

1828
Added script in Category.js
Modified Index.cshtml
Tested Application ,ran perfectly

1838
Added IActionresult to the controller and added a View 
Added partial view named _CreateAndBackToListButton and _EditAndBackToListButton

1853
Modified Upsert.cshtml 
Added Model statement in it 
Added asp-action in Index.cshtml
Ran Application , worked good

1904
Modified CategoryController.cs amd added save and editmethods
Added HTTPDELETE in controller
Modified Category.js

1909
Added delete functionality in Category.js
Tested DeLete function ran perfectly.

11-20-2023

1247
Cloned repository ShreyangBookApp from github and going to start Part-3 section - 1

1250
Created new class CoverType in .Models folder

1252
Added CoverTypeRepository class in Repository folder
Added ICoverTypeRepository interface in IRepository folder

1556
Added CoverType to UnitOfWork and IUnitOfWork

1301
Ran migration 20231120180046_addCoverType.cs in .DataAccess project 
Updated databse

1311
Added CoverType to navbar by adding it to _Layout.cshtml 

1313
Created CoverType Controller with all required method

1318
Created CoverType folder in Views in Models Project.
Added Index.cshtml and Upsert.cshtml in it.

1322
Created coverType.cs to add delete method.
Tested application , having error while updating coverType 

1326
Solved error by renaming EditAndBackToListButton.cshtml to _EditAndBackToListButton.cshtml
Tested application , worked perfectly

1328
Added new Product class to .Models project

1330
Added referene of product to ApplicationDbContext.cs file

1333
Ran migration 20231120183215_addProductToDb.cs

1335
opened SOE to review newly created product table. Validation is already required in mentioned columns 

1337
Ran new migration 20231120183648_addValidationToProduct.cs and updated database

1340
Added new Product class .Models project

1343
Added IProductRepository interface to IRepository folder
added ProductRepository class to Repository folder

1346
Added reference to ApplicationDbContext.cs

1349
Added Product to UnitOfWork and IUnitOfWork

