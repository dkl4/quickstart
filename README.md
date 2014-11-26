This project was initially cloned from branch 
7.x-3.0-beta2 from the project at 
https://www.drupal.org/project/drupalpro

However, the entire project at the above URL
was NOT copied.  Only the drush commands
in the subdirectory ./drush_addons/quickstart
were copied.

In other words, the DrupalPro project included
many items to install a "full" Drupal development
environment into a Ubuntu 12.04 system.  This 
included Apache, MySQL, editors etc.  

This subset of the DrupalPro (formerly Drupal Quickstart')
scripts only included those Drush commands to setup
databases, Apache virtual servers etc.

USAGE
-----
The easiest way to use this, under Drush 7.x (Composer),
is to copy the 'quickstart' directory to your
~/.drush directory.  Then run 'drush cc drush' to
clear your Drush command cache.


