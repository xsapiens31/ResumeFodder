ResumeFodder
============

> NOTE: Primary development has moved over to GitLab:  https://github.com/andrzejressel/ResumeFodder.
> If you're reading this on GitHub, then note that this repo is a mirror which can sometimes be slightly
> out of date.

ResumeFodder is an application for generating Microsoft Word resumes from
[JSON Resume](https://github.com/jsonresume/resume-schema) data files.

https://resumefodder.com

This repository contains the core functionality for parsing JSON Resume data and processing templates.
There are three other related git repositories:

* [ResumeFodder-cli](https://github.com/andrzejressel/ResumeFodder-cli) - A command-line front end that
  compiles to a standalone executable to run on your local machine.

* [ResumeFodder-appengine](https://github.com/andrzejressel/ResumeFodder-appengine) - A web application
  front end, for using ResumeFodder online without having to install any software.  Currently running
  live on Google App Engine at: https://resumefodder.com.

* [ResumeFodder-templates](https://github.com/andrzejressel/ResumeFodder-templates) - All of the Go
  templates available to ResumeFodder.  This repository is imported into all of the others a git submodule.

Copyright 2016 [Steve Perkins](http://steveperkins.com)

[MIT License](https://opensource.org/licenses/MIT)
