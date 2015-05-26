# Developing Using My Own System
## Install PHP (if you didn't have it already)

```sh
# install php5 - ubuntu
sudo apt-get install php5-cli
```

## Install Sculpin (requires PHP)

```sh
# install sculpin locally (requires PHP install)
curl -O https://download.sculpin.io/sculpin.phar
chmod +x sculpin.phar

# this assumes ~/bin is on your $PATH
mv ~/bin/sculpin.phar ~/bin/sculpin
```

## Run a local server via Sculpin

```
# run the app in a local server
sh watch.sh
```

![sculpin dev server screenshot](http://i.imgur.com/ApwpH0H.png)

## View changes in action

Browse to [http://localhost:8000](http://localhost:8000).  There, you did it!  Congratulations.

