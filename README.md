## Memphis Technology Foundation

[http://www.MemphisTechnology.org](http://www.MemphisTechnology.org)

Memphis Technology Foundation is a group interested in getting stuff done. Making stuff happen. Facilitation.

Powered by [Sculpin](http://sculpin.io). =)

## I'd like to contribute!
Great!  We can't wait to see it.  Please read our [contribution guidelines](CONTRIB.md) and get to work.

## I want to set up a local copy of this site for prototyping changes and submissions...
Cool.  You're going to need a few things:

- Local installations of [PHP](http://php.net/manual/en/install.php), [git](http://git-scm.com/book/en/v2/Getting-Started-Installing-Git), and [Sculpin](https://sculpin.io/getstarted/)
- A copy of this codebase

### Step one: grab a local copy of this repository:

```sh
# get a copy of the code
git clone git@github.com:memtech/memphistechnology.org.git
cd memphistechnology.org/
```

### Step two: install sculpin (requires PHP)

```sh
# install sculpin locally (requires PHP install)
curl -O https://download.sculpin.io/sculpin.phar
chmod +x sculpin.phar

# this assumes ~/bin is on your $PATH
mv ~/bin/sculpin.phar ~/bin/sculpin
```

### Step three and a half: install php if you didn't have it already
```sh
# install php5 - ubuntu
sudo apt-get install php5
```

### Step four: Run a local copy of this site that you can see in a browser via Sculpin
```
# run the app in a local server
sculpin generate --watch --server
```

### Step five:  Check out the site in your browser to see your changes in action

Browse to [http://localhost:8000](http://localhost:8000).  There, you did it!  Congratulations.

![sculpin dev server screenshot](http://i.imgur.com/ApwpH0H.png)

## Deployment

Maybe you've got some new content you'd like to see on the page.  What happens after you submit a PR?

TODO: Someone who runs the server (probably @svpernova09) can fill this out.
