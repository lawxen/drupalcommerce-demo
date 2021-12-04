drush si demo_commerce --db-url=mysql://root:password@mariadb:3306/drupalcommercedemo --account-pass=abcd1234 --sites-subdir=default -y


drush si demo_commerce --existing-config --db-url=mysql://root:password@mariadb:3306/drupalcommercedemo --account-pass=abcd1234 --sites-subdir=default -y



## Export default content
drush dcer commerce_product --folder=../content/
drush dcer node --folder=../content/