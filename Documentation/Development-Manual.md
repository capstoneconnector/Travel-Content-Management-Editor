# Development Manual

## The Development Environment
### Cloning the Project into the IDE
For development, we suggest using Visual Studios.

### Setting up the Database
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
