# _wampindexer
Template is using :
- _h5ai : https://larsjung.de/h5ai/ 
a sweet folder indexer 

- Material Design : https://material.io/ 
a simple google material theme for the design inspiration

- Search Replace DB : https://github.com/interconnectit/Search-Replace-DB/
This script was made to aid the process of migrating PHP and MySQL based websites. It has additional features for WordPress and Drupal but works for most other similar CMSes.

# Template & dependencies for Data :
- Title of the repository : name of the folder from your git or local project inside `www`
- Thumbnail : `screenshot.png` to put inside each project folder
- Description : `README.md` from your git project folder or other

## Screenshot
![Image of Yaktocat](http://goomie.fr/img/screen.png)

## Installation
1. Donwload and copy the folder `_wampindexer` in `www`
2. Export `index.php` present in `_wampindexer` to `www`
3. Left click on wamp -> Apache -> Edite httpd.conf and replace the DirectoryIndex by :
`DirectoryIndex  index.html  index.php  /_wampindexer/public/index.php`
4. Restart wamp and enjoy !

## Informations
By default all of my git folder are named with the domain : `mydomain.com` cus i'm using it to test the serveur status.
If you work on a simple folder with subfolders inside; `_h5ai` will take over the _wampindexer theme.

## Default setup
the ` _wampindexer` folder inside your `www` is hidden with CSS in order to not be count and displayed as a repository.
- The profile picture modifications is in `_wampindexer\web\img\profil.png`.
- The style modifications are in `_wampindexer\web\css\style.css`.
- The Javascript modifications are in `_wampindexer\web\js\app.js`.
- The Php modifications are in `_wampindexer\src\app.php`.
