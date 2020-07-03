# Diary
Simple apllication for making diaries with images

First toolbar to set first image size.  
Second toolbar to set second image size.  
Third toolbar to set number of rows to be shawn.

![awesome image toolbar demo](images/images_view.gif)

## Install

- rename ```db.php.sample``` into ```db.php``` file with own db credentials.
- rename ```config.php.sample``` into ```config.php``` file. 

- add Bingo to project root folder. **Warning!** You must have a Bingo CMS to use this project
- set own mail credentials in ```config.php``` to be able to sync with `mail.ru` cloud.
(syncing not implemented yet)
- run <your_domain>/install and enter password for 'admin' user

to enter 'admin' area use <your_domain>/admin

You cannot register to enter frontend, but have to create a user in admin area.
To do this go to `/admin/app/user-list` and click on `Create new` button in top right corner.

Now you can login with created user
