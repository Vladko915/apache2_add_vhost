*********************************************************************************
!!! REMEMBER, this code is available under license Apache-2.0 License. 
You are responsible for all the changes youmake to your operating system.No guarantees. 
Be careful.
*********************************************************************************


The repository contains scripts for  add virtual host of Apache2 in Debian 9.
There are different versions of scripts:

1) apache2_add_vhost                    #default script
2) apache2_add_vhost_check_php          #default script + check php of index-page
3) apache2_add_vhost_check_php_browser  #default script + show index-page of browser, suitable for PC

Choose the one you like best.

For run scripts you need to put them in folders:

/usr/bin
OR
/usr/local/bin

And set the scripts as executed.

Then you can to run them from anywhere from the terminal.
Just write the name of the script in terminal.

Alternatively, you can to copy them to any folder and run as root in console as:
***********************
bash apache2_add_vhost 

OR

bash apache2_add_vhost_check_php 

OR

bash apache2_add_vhost_check_php_browser 
***********************

It is also necessary to have such packages as installed in Debian:

1) packages: coreutils, apache2( for apache2_add_vhost).
OR 
2) packages: coreutils, apache2, php ( for apache2_add_vhost_check_php ).
OR 
3) packages: coreutils, apache2, php, google-chrome ( for apache2_add_vhost_check_php_browser ).

Enjoy!
