<h1>Pharmacy App</h1>
Using .NET Core 3.1 MVC EF Core

<h2>Introduction</h2>
It Contains basic CRUD operations for 3 models, namely:<br/>
1)Medicine-CRUD operations<br/>
2)Prescription-CRD operations<br/>
3)Order- CR operations<br/>

<h2>How to Setup the project?</h2>
Make sure Microsoft SQLServer and EF Core Tools are installed. More importantly, .NET Core 3.1 SDK should be downloaded beforehand.<br/>
1) Run the below command through the terminal in the folder where you want to have all the files:<br/>
    "git clone https://github.com/ManavKalariya/Pharmacy-App.git"<br/>
2) Open solution "Pharmacy.sln"(Visual Studio is required to be installed)<br/>
3) In the appsettings.json, make sure, "DefaultConnection"="Server=(localdb)\\MSSQLLocalDB; Database=PharmacyDb; Trusted_Connection=True;MultipleActiveResultSets=True"<br/>
4) In the View, Open "SQL Server Object Explorer"<br/>
5) If database "PharmacyDb" is not present, then right click on "Databases"(in SQL Server Object Explorer) and add database with name, "PharmacyDb"<br/>
6) In the View, inside "Other Windows", open "Package Manager Console"<br/>
7) Run the command: "App-migration" and enter any name when asked for "Name"<br/>
8) After it is successful, run the command: "update-database"<br/>
9) You are ready to run the project<br/>

<h2>About</h2>
This project was done as part of WAD Termwork.<br/>

<h2>Contributors</h2>
Heet Jambudiya(CE119)<br/>
Manav Kalariya(CE122)<br/>
Tej Kapadia(CE124)
