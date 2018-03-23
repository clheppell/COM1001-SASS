# clheppell/COM1001-SASS for COM1001-ComputerScience-Sheffield/team-33
Sassy CSS for team-33's Pied Piper Project for COM1001: Introduction to Software Engineering.

## Using our Sass CSS
We're using [the Bootstrap framework](https://www.getbootstrap.com) in this project to deal with all the CSS that is not a top priority for us. It also provides with a fully responsive site, straight out of the box.

The repo with the Sass in is separate to the main one because otherwise it would fill it up with unnecessary crap.

[This repo](https://github.com/clheppell/COM1001-SASS) is on Chris' personal GitHub (but is a private repo), so ask for access first by [contacting clheppell1@shef.ac.uk](mailto:clheppell1@sheffield.ac.uk).

To install Sass on your system, which is needed to build (compile) the CSS from source, run
```
gem install sass
```

When you have made a change, run
```
sass pies.scss:pies.css
```
and Sass will build `pies.css` and `pies.css.map`. Copy both to the public/css directory in this repo. When we're ready to hand in, we'll use Autoprefixer to prefix our CSS and at this point will stop using this `pies.css.map` file

Don't forget to commit changes to the Sass Repo and the [main Repo](https://github.com/COM1001-ComputerScience-Sheffield/team-33).

## Acknowledgements
The Bootstrap Framework is [licensed under the MIT License](https://github.com/twbs/bootstrap/blob/v4.0.0/LICENSE)
- Copyright (c) 2011-2018 Twitter, Inc.
- Copyright (c) 2011-2018 The Bootstrap Authors
