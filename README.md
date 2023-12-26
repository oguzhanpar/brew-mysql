# brew-mysql-install

# Installation process:
1. Now simply run the below command in your terminal

$ brew install mysql
2. Start the MySQL service

$ brew services start mysql
3. Set root MySQL password

$ mysqladmin -u root password 'secretpassword'
4. Access MySQL on mac

$ mysql -u root -p

Once you have ran brew update you can then upgrade all formulas/packages using:

# brew-mysql-upgrade-update

brew upgrade
To upgrade a particular package you can use the brew upgrade command like:

brew upgrade mysql
Before running an upgrade you may want to know what can be or is going to be upgraded using the command:

brew outdated
NOTE always remember to read the post install/upgrade notes that are output. Some packages require manual steps post install/upgrade like major database version upgrades often require data upgrade/migration procedures to be run.
