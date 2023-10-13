# sflake


**********************************************************************
 Installing SnowSQL, Snowflake CLI.
**********************************************************************

Specify the directory in which the SnowSQL components will be installed. [~/bin]
Do you want to add /root/bin to PATH in /root/.profile? [y/N] y
Updating /root/.profile to have /root/bin in PATH
Open a new terminal session to make the updated PATH take effect.
**********************************************************************
 Congratulations! Follow the steps to connect to Snowflake DB.
**********************************************************************

1. Open a new terminal window.
2. Execute the following command to test your connection:
      snowsql -a <account_name> -u <login_name>

      Enter your password when prompted. Enter !quit to quit the connection.

3. Add your connection information to the ~/.snowsql/config file:
      accountname = <account_name>
                username = <login_name>
                password = <password>

4. Execute the following command to connect to Snowflake:

      snowsql

See the Snowflake documentation <https://docs.snowflake.net/manuals/user-guide/snowsql.html> for more information.
(venv1) root@LAPTOP-V3O75EIH:~/sflake#