# Memphis Technology Foundation

[![Netlify Status](https://api.netlify.com/api/v1/badges/db842e29-26d0-429d-a7bf-2bfd8f05d228/deploy-status)](https://app.netlify.com/sites/cranky-shockley-26311d/deploys)

[http://www.MemphisTechnology.org](http://www.MemphisTechnology.org)

Memphis Technology Foundation is a group interested in getting stuff done. Making stuff happen. Facilitation.

Powered by [Sculpin](http://sculpin.io). =)

# Contributing
## I'd like to contribute!
Great!  We can't wait to see it.  Please read our [contribution guidelines](CONTRIB.md) and get to work.

# Local Development for Prototyping Changes
You're going to need a few things:

- A copy of this codebase
- One of the recommended deving systems listed below to cover the following resources
    - [PHP](http://php.net/manual/en/install.php)
    - [git](http://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
    - [Sculpin](https://sculpin.io/getstarted/)

## Clone the repo

```sh
# get a copy of the code
git clone git@github.com:memtech/memphistechnology.org.git
cd memphistechnology.org/
```

## Follow one of the local dev methods
- Using your [local system](documentation/with_local.md)
- Using [Docker](documentation/with_docker.md)

# Deployment

Deployment is handled by Netlify whenever a commit or PR is merged to `master`

## How to contribute blog posts

* Blog posts are stored in the `source/_posts/` folder in Markdown format
* Create a new markdown file in the folder with the appropriate front matter (Variables at the top, use an existing file as an example)
* Write blog post (HTML is OK after the front matter)
* Save your changes and commit to version control
* Open a pull request and await someone to review your changes
