# PingDirectoryConfiguration
PingDirectory configuration explained from scratch
### 2 Open cmd promt and navigate the ping-directory folder
- Run setup.bat cmd
### 3 Accept License
### 4 Provide lincense file path
### 5 Enter Fully Qualified hostname
### 6 Create Initial root user DN
- use default cn=Directory Manager
- just give enter
### 7 Provide a password
- Give yes even if prompt says password is too short
### 8 Enable Directory Server Services
- default option yes is displayed in [yes] - just give enter
### 9 Choose the port
- just press enter to choose the default port 443
### 10 unencrypted LDAP connections
- Choose default option [3]. Just press enter
### 11  Port for LDAP Clients
- choose default [389], just press enter
### 12 Self Signed certificate
### 13 Data Encrytion options
- Choose default option [1] by pressing enter
### 14 Enter encryption passphrase
- Enter a password as encryption passphrase
- weak password prompt , give confirmation as yes
- re-confirm the password again when asked
### 15 select base DN
- choose default option shown [dc=example, dc=com]
- options for populating database - select option 3 and enter the path for the .lidf file we have
### 16 Select minimum memery size for the server
- Choose option [3]
### 17 Automatically prime the database
- choose yes
### 18 choose location name
- give any city name
### 19 instance name
- enter as dev env
### 20 option to start server after configuration
### 21  choose option for config\tools.properties file
- choose default option
### 22 Setup Summary
### 23 Asks you if you want to setup with above configuration
- choose default
- after clicking enter - pingdirectory installation starts and it will take 2 mins
- after installation is completed

  # Run Ping Directory as windows Service

### 1 Navigate to bat folder
- stop the server
- run register-windows-service.bat -e option
