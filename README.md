# brew-mysql-update

Installation process:
1. Now simply run the below command in your terminal

$ brew install mysql
2. Start the MySQL service

$ brew services start mysql
3. Set root MySQL password

$ mysqladmin -u root password 'secretpassword'
4. Access MySQL on mac

$ mysql -u root -p
