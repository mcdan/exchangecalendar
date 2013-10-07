exchangecalendar
================

Exchange 2007/2010/2013 Calendar, Tasks, Contacts and GAL Provider.



If you would like to use the really latest version of the Exchange Calendar events and tasks add-on for Lightning then checkout a copy of the git repository on GitHub (https://github.com/1stsetup/exchangecalendar).

To clone to your local machine and add the git repository to Thunderbird as the add-on:

Close Thunderbird

$> mkdir ~/git

$> cd ~/git

$> git clone git://github.com/1stsetup/exchangecalendar.git

$> cd exchangecalendar

Remove the exchange add-on files installed by the XPI.

$> rm -r "~/.thunderbird/<profilename>/extensions/exchangecalendar@extensions.1st-setup.nl"

Add the add-on back to Thunderbird but now pointing to the cloned git repository

$> echo `pwd` > "~/.thunderbird/<profilename>/extensions/exchangecalendar@extensions.1st-setup.nl"

If you want to update the local copy of the git repository do:

Close thunderbird

$> cd ~/git/exchangecalendar

$> git pull

Start Thudnerbird

If you want to change to one of the other branches in the git repository:
Close Thunderbird

$> cd ~/git/exchangecalendar

$> git branche

$> git checkout <branchename>

Start Thunderbird

If you want to use one of the existing tags in the git repository:
Close Thunderbird
$> cd ~/git/exchangecalendar
$> git tag
$> git checkout <tagname>
Start Thunderbird
