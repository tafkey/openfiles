2012-Dec-02, tkout
------------------
+ installed drupal 7.17 with sqlite (basic, clean installation)
+ some configuration, added almost all basic modules


- trying to implement workflow with anonymous publishing


$ git clone
(alternatively) 
$ git pull
$ drush sql-drop
$ drush sql-cli
sqlite> .restore db.backup
sqlite> .quit

try chmod -R 777 if you get no response...
