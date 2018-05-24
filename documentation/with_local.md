# Developing Using My Own System
## Install PHP (if you didn't have it already)

```sh
# install php - debian / ubuntu
sudo apt-get install php-cli php-xml
```

## Install Composer (used to install Sculpin)

```sh
# install composer - debian / ubuntu
sudo apt-get install composer
```

## Install Sculpin (requires PHP)

```sh
# from your project directory
composer install
```

## Run a local server via Sculpin

```
# run the app in a local server
sh watch.sh
```

![sculpin dev server screenshot](http://i.imgur.com/ApwpH0H.png)

## View changes in action

Browse to [http://localhost:8000](http://localhost:8000).  There, you did it!  Congratulations.

