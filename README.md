Quick and dirty PHP script to work around http://bugs.mysql.com/73894  
"Can't easily change DEFINER on existing views, stored routines, triggers, events"

Rename config.php.sample to config.php and fill it with your data.  
Usage: ./change_mysql_definer.php old_definer_user old_definer_host new_definer_user new_definer_host [for_real=false] [verbose=true]

* Master branch is for PHP5.6
* For PHP7 look into php7 branch
