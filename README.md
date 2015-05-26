# Memphis Technology Foundation

[http://www.MemphisTechnology.org](http://www.MemphisTechnology.org)

Memphis Technology Foundation is a group interested in getting stuff done. Making stuff happen. Facilitation.

Powered by [Sculpin](http://sculpin.io). =)

# Contributing
## I'd like to contribute!
Great!  We can't wait to see it.  Please read our [contribution guidelines](CONTRIB.md) and get to work.

# Local Development for Prototyping Changes
You're going to need a few things:

- A copy of this codebase
- A working installations of [PHP](http://php.net/manual/en/install.php), [git](http://git-scm.com/book/en/v2/Getting-Started-Installing-Git), and [Sculpin](https://sculpin.io/getstarted/)
or
- Docker

## Step One: Clone the repo
```sh
# get a copy of the code
git clone git@github.com:memtech/memphistechnology.org.git
cd memphistechnology.org/
```

### Using My Own System
#### Step Two: Install php if you didn't have it already

```sh
# install php5 - ubuntu
sudo apt-get install php5-cli
```

#### Step Three: Install sculpin (requires PHP)

```sh
# install sculpin locally (requires PHP install)
curl -O https://download.sculpin.io/sculpin.phar
chmod +x sculpin.phar

# this assumes ~/bin is on your $PATH
mv ~/bin/sculpin.phar ~/bin/sculpin
```

#### Step Four: Run a local copy of this site that you can see in a browser via Sculpin

```
# run the app in a local server
sh watch.sh
```

![sculpin dev server screenshot](http://i.imgur.com/ApwpH0H.png)

#### Step Five: View changes in action

Browse to [http://localhost:8000](http://localhost:8000).  There, you did it!  Congratulations.


### Using Docker
#### Step Two: Install Docker
Follow the apporpriate installation guide provided by [Docker](https://docs.docker.com/installation/#installation) to get setup.

#### Step Three: Run a sculpin contain

```sh
docker run -d -p 8000:8000 -v "$PWD:/data"
```

#### Step Four: View changes in action

Browse to your running docker container.

Linux: [http://localhost:8000](http://localhost:8000)
Mac: prbably [http://192.168.59.103:8000](http://192.168.59.103:8000)

There, you did it!  Congratulations.

## Deployment

Maybe you've got some new content you'd like to see on the pagit sge.  What happens after you submit a PR?

@Svpernova09 handles deployments.

If you don't see your change on the live site and you see your PR merged into master: Please ping ```joepferguson``` in #memtech on Freenode or #memtech Slack.
