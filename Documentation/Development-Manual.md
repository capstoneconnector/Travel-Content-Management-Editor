# Development Manual

## The Development Environment
### Cloning the Project into the IDE
For development, we suggest using Visual Studios.

### Creating a Blank Azure Database
For the project, you will need to create your own [Azure](https://azure.microsoft.com/en-us/free/) database. 
If you don't already have an account, then create one. Otherwise, login and create a blank database.
      
1. Click **Create a resource** in the upper left-hand corner of the Azure portal.
2. Select **Databases** in the Azure Marketplace section, and then click **SQL Database** in the Featured section.

![alt text](https://github.com/erincloehr/Travel-Content-Management-Editor/blob/master/Documentation/images/create-empty-database.png)  

3. Fill out the SQL Database form with the database name, subscription, and resource group and a blank database for the source.
4. Click **Create a new server** and fill out the form with the server name, admin login, password, and location. Then click **Select**. 

![alt text](https://github.com/erincloehr/Travel-Content-Management-Editor/blob/master/Documentation/images/create-database-server.png)  

5. Select **Create** and wait a few minutes for the deployment process to complete.
6. After the deployment completes, click **SQL databases** from the left-hand menu and then click on *yourDatabase* on the SQL databases page. Finally click on **Set server firewall** on the toolbar.

7. Click **Add client IP** on the toolbar to add your current IP address to a new IP firewall rule then click **Save**. Click **Ok** and then close the page.

![alt text](https://github.com/erincloehr/Travel-Content-Management-Editor/blob/master/Documentation/images/server-firewall-rule.png)

### Connecting Database Through SSMS and Adding Tables.

1. If you do not already have it download, download [SQL Server Management Studio (SSMS)](https://docs.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-2017) and run the application
2. If you have never used SSMS before, proceed to input the server type, server name, authentication, login, and password into the **Connect to Server** form. Otherwise, select the **Connect Object Explorer** button in the toolbar of the Object Explorer Window and the form will pop-up.

![alt text](https://github.com/erincloehr/Travel-Content-Management-Editor/blob/master/Documentation/images/ssms-connect-object-explorer.png)
![alt text](https://github.com/erincloehr/Travel-Content-Management-Editor/blob/master/Documentation/images/connect.png)

3. Click **Options** in the Connect to server dialog box. In the Connect to database section, enter yourDatabase to connect to this database. Then click **Connect**. The Object Explorer window opens in SSMS, and you can now expand Databases and then yourDatabases to view the objects in the database. 

![alt text](https://github.com/erincloehr/Travel-Content-Management-Editor/blob/master/Documentation/images/options-connect-to-db.png)

4. Download the following [sql file](https://github.com/erincloehr/Travel-Content-Management-Editor-Database/blob/master/schema.sql) and open it in SSMS by clicking on **File** in the top left of the toolbar, go down to **Open**, then select **File...**. Alternatively, use the keyboard shortcut **Ctrl+o**



