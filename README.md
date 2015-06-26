## My site &nbsp; [![Build Status](https://travis-ci.org/leo/leo.github.io.svg?branch=master)][1]

If you want, you can call this my homepage. This is where I put many of my recent thoughts and works. The reason why I published the site here on GitHub is because they provide a really convenient to deploy.

You're completely free to use parts of my code for one of your projects, as long as you don’t hold me liable. But you can also just contribute to it by creating issues or fixing bugs if you find one.

## Build locally

As you might want to commit something to my site, you should of course be able to build the project locally with Jekyll. So here are some quick steps to accomplish this:

1. Clone this repo: `git@github.com:leo/leo.github.io.git`
2. Download and install Jekyll on your local environment: `gem install jekyll && gem install github-pages`
3. Change to the folder that contains the repo
4. Run Jekyll within the current directory: `jekyll serve --watch`

**Important:** Executing the above comments might take a while because it's downloading a huge amount of files. But if you get something like "You don't have write permissions ..." back, just try the commands with `sudo` on the beginning.

## Forking

You're completely free to fork this repository and use it as starting-point for your own Jekyll-site! Just remember to change all custom variables within ```config.yml``` before continuing to use the setup. 😸

I would also recommend you to make some changes to the theme, of course (if not to completely change it). So that people aren't confused when visiting your site.

[1]: https://travis-ci.org/leo/leo.github.io
