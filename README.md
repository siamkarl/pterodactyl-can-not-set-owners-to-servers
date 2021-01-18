# pterodactyl-error
pterodactyl error help


root@vmi482662:~# cd /var/www/pterodactyl
root@vmi482662:/var/www/pterodactyl# php artisan migrate --force
Migrating: 2020_01_19_12375_add_backup_folder_to_nodes_table

In Connection.php line 664:

  SQLSTATE[42000]: Syntax error or access violation: 1101 BLOB/TEXT column 'backup_folder' can't have a default va
  lue (SQL: alter table `nodes` add `backup_folder` text not null default 'backup' after `daemonBase`)


In PDOConnection.php line 82:

  SQLSTATE[42000]: Syntax error or access violation: 1101 BLOB/TEXT column 'backup_folder' can't have a default va
  lue


In PDOConnection.php line 80:

  SQLSTATE[42000]: Syntax error or access violation: 1101 BLOB/TEXT column 'backup_folder' can't have a default va
  lue

