# WebSqlMAilPythonServer

##Script for installation of a complete server system with

Debian or compatible distrobution

###Features
* Update system software.
* Setting hostname
* Creating a user
  * option ssh-key for passwordless connection
* Option Sql server
  * MariaDb
    * Installing
    * Secure Db
  * Postgresql
* Firewall
  * Blocking all trafic except ping and ssh connection as default. Other choices select in start of script may open port for that application
  * Opens ports depending on which options you choose.

##Depends

Linux Debian distrobution.

###TODO
1. Firewall
  * configuration for email
  * configuration for webservices
2. Optinal webserver
  * NGINX
  * APACHE
3. Other
  * SQL (mysql, mariadb, pregresql) Almost done
    * Optimize sql server configuration on memory limitation.
  * Python
  * Django CMS
  * FLASK
