# Creating a New User in Oracle Database

**Step 1: Login as SYSTEM**

To create a new user in Oracle, you need administrative privileges. You can log in as the SYSTEM user to perform administrative tasks.

Open the 'Run SQL Command Line' and the following command :

```sql
Connect SYSTEM
```
When prompted, enter the following information:

- **Enter Password:** [Your_SYSTEM_Password]


Replace `[Your_SYSTEM_Password]` with the password you provided while installing oracle.


**Step 2: Create User: **

```sql

CREATE USER [username] IDENTIFIED BY [password];
```
Replace [username] with the desired username for the new user and [password] with the desired password.


**Step 3: Grant 'CONNECT' role: **

```sql

GRANT CONNECT TO [username];
```
Replace [username] with the selected username
