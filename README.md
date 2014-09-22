grunt-init-sopro-app
===========

This grunt init script builds a scaffold for a Society Pro App.

Prerequisites
-------------
Setup grunt and grunt-init:

    $ npm install -g grunt-cli grunt-init

Usage
-----
Be in Git Bash so ~ works:

    $ git clone https://github.com/SocietyPro/grunt-init-sopro-app.git ~/.grunt-init/sopro-app
    $ cd my-sweet-app
    $ grunt-init sopro-app
    $ cd src
    $ npm install

Result
------

    
What it does
------------

0. Check for non-empty directory and warn of overwrites
1. Prompt:
  * app name, human readible title, description
  * repo url (default to SocietyPro/*)
  * wanna add sopro-material?
  * wanna add japi?
  * wanna add Roboto, angular, angular-material, angular-animate?
  * wanna add jquery?
2. Generate custom Gruntfile
3. Copy custom Gruntfile
4. Copy template skeleton
5. Tell the user to run the new Gruntfile for bower