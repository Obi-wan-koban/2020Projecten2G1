# 2020Projecten2G1
2019-2020 Hogent Informatics group project

## Database info
| Database information |  |
| - | - |
| Username | i97bEE0fyV |
| Database name | i97bEE0fyV |
| Server | remotemysql.com |
| Port | 3306 |
| password | see keepass |

All database scripts in the Scripts folder please!

### How to add

#### For general use, use MySQL workbench
Install MySQL workbench, add a new connection
copy/paste data from above, use the password from the keepass attached.
![MySQLWorkbench](/images/mysqlWorkbench.png)

Once added just doubleclick the connection to manipulate databas.

#### dotnet (Visual Studio)
Requirements: 
 - Visual Studio
 - [MySQL for Visual Studio](https://dev.mysql.com/downloads/windows/visualstudio/)

In server explorer > add database
fill in data and add the following data

![add MySQL connection](/images/add_server_visual_studio.png)

(this step is optional, allows you to see database directly)

Mandatory is to install the package EntityFramework (Project > Manage NuGet Packages)

#### java (Eclipse/Intellij)
(incoming

