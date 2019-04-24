# Development Manual

## The Development Environment


### Creating a Blank Azure Database

1. You will need to create your own [Azure](https://azure.microsoft.com/en-us/free/) database. If you don't already have an account, create one and login to create a blank database.      
2. Click **Create a resource** in the upper left-hand corner of the Azure portal.
3. Select **Databases** in the Azure Marketplace section, and then click **SQL Database** in the Featured section.

![alt text](https://github.com/erincloehr/Travel-Content-Management-Editor/blob/master/Documentation/images/create-empty-database.png)  

4. Fill out the SQL Database form with the database name, subscription, and resource group and a blank database for the source.
5. Click **Create a new server** and fill out the form with the server name, admin login, password, and location. Then click **Select**. 

![alt text](https://github.com/erincloehr/Travel-Content-Management-Editor/blob/master/Documentation/images/create-database-server.png)  

6. Select **Create** and wait a few minutes for the deployment process to complete.
7. After the deployment completes, click **SQL databases** from the left-hand menu and then click on *yourDatabase* on the SQL databases page. Finally click on **Set server firewall** on the toolbar.

8. Click **Add client IP** on the toolbar to add your current IP address to a new IP firewall rule then click **Save**. Click **Ok** and then close the page.

![alt text](https://github.com/erincloehr/Travel-Content-Management-Editor/blob/master/Documentation/images/server-firewall-rule.png)


### Connecting Database Through SSMS and Adding Tables.

1. If you do not already have it download, download [SQL Server Management Studio (SSMS)](https://docs.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-2017) and run the application
2. If you have never used SSMS before, proceed to input the server type, server name, authentication, login, and password into the **Connect to Server** form. Otherwise, select the **Connect Object Explorer** button in the toolbar of the Object Explorer Window and the form will pop-up.

![alt text](https://github.com/erincloehr/Travel-Content-Management-Editor/blob/master/Documentation/images/ssms-connect-object-explorer.png)
![alt text](https://github.com/erincloehr/Travel-Content-Management-Editor/blob/master/Documentation/images/connect.png)

3. Click **Options** in the Connect to server dialog box. In the Connect to database section, enter yourDatabase to connect to this database. Then click **Connect**. The Object Explorer window opens in SSMS, and you can now expand Databases and then yourDatabases to view the objects in the database. 

![alt text](https://github.com/erincloehr/Travel-Content-Management-Editor/blob/master/Documentation/images/options-connect-to-db.png)

4. Save this [sql file](https://github.com/erincloehr/Travel-Content-Management-Editor-Database/blob/master/schema.sql) and open it in SSMS by clicking on **File** in the top left of the toolbar, go down to **Open**, then select **File...**. Alternatively, use the keyboard shortcut **Ctrl+o**. 
5. Click the **Execute** button in the SQL editor toolbar. Right-clicking on the database in the Object Explorer window and select **Refresh**. You can now expand the Tables folder to view the new tables.


### Cloning the Project into the IDE
1. If you have not, download [Visual Studios](https://visualstudio.microsoft.com/downloads/) and run the application.
2. You may need to add a GitHub extension if this is your first time using Visual Studios or you have not connected Visual Studios to a GitHub repository. Go to **Extensions and Updates...** under **Tools** in the toolbar. 
3. Find and install the **GitHub extenstion for Visual Studios** then restart Visual Studios.

![alt text](https://github.com/erincloehr/Travel-Content-Management-Editor/blob/master/Documentation/images/open-from-github.png)

4. After reponing the application, go to **File**, **Open**, **Open from GitHub**. and paste the following link into the textbox.
https://github.com/bcrose/TCME-Code.git

![alt text](https://github.com/erincloehr/Travel-Content-Management-Editor/blob/master/Documentation/images/github-extension.png)

5. In the Solution Explorer, double-click on the bottom file **Solution 'Travel-Content-Manager-Editor'**.


### Connecting the Project to the Database
1. Open the server explorer by clicking **Server Explorer** on the left side on the screen and Select the **Connect to Database** button at the top of the window.

![alt text](https://github.com/erincloehr/Travel-Content-Management-Editor/blob/master/Documentation/images/vs-add-database.png)

2. Select the **Connect to Database** button and fill out the form that appears. Then click **OK**
  * Select **Microsoft SQL Server (SqlClient)** for Data Source
  * Input your server name
  * For Authentication, select **SQL Server Authentication** and input your user and password for the server you created
  * Select or input your database name
 

![alt text](https://github.com/erincloehr/Travel-Content-Management-Editor/blob/master/Documentation/images/vs-database-form.png)


