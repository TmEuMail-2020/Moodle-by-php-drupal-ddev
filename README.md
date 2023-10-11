# Code Museum: Moodle via DDEV & GitPod!

This repo will download the newest Moodle source, then configure behat & phpunit all runnable, plus NoVNC to observe!

## How to use

Just simply click gitpod button then enjoy fiddling around runnable code! 

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/TmEuMail-2020/moodle-by-php-drupal-ddev/)

## default password of the app & db

```text
ddev exec 'php public/admin/cli/install.php --non-interactive --agree-license --wwwroot=$DDEV_PRIMARY_URL --dbtype=mariadb --dbhost=db --dbname=db --dbuser=db --dbpass=db --fullname="DDEV Moodle Demo" --shortname=Demo --adminpass=password'
```


## Special thanks 🙏
- [Drupal via DDEV](https://github.com/drud/ddev) 
- [Ofer Shaal](https://github.com/shaal)
