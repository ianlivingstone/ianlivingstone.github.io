# Ian Livingstone's Blog

This repository contains the source for Ian Livingstone's site which is powered
by Jekyll and hosted on GitHub pages.

### Requirements

* Docker 1.7+
* Boot2Docker (if you're on Mac OS X or Windows)

### Running and Development

Once you have docker setup, getting up and running is really simple. Just start
a docker container using the following command:

```
./_bin/blog dev
```

This will start a docker container with the light-weight jekyll server running
inside. You will be able to access this server by navigating to
`http://localhost:4000`.

*NOTE*: If you are running on Mac OS X you'll need to use `boot2docker ip` to
retrieve the IP Address of the VM that the docker server is running on.

Now you're off to the races!

### Deployment

Simply push your changes to master and everything else is taken care of for
you!
