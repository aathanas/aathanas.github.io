# Agissilaos Athanassoulis Homepage

The page is live at [https://aathanas.github.io](https://aathanas.github.io).

## Which files to change to update Gerassimos' info?

### Pages
1. Main page: click [_pages/about.md](https://github.com/aathanas/aathanas.github.io/edit/master/_pages/about.md) to edit the homepage.
1. Short CV information is maintained in [_pages/cv.md](https://github.com/aathanas/aathanas.github.io/blob/master/_pages/cv.md).

### Collections
1. Publications are maintained in [_publications](https://github.com/aathanas/aathanas.github.io/tree/master/_publications).
1. PhD students are maintained in [_students](https://github.com/aathanas/aathanas.github.io/tree/master/_students).
1. Diploma students are maintained in [_students_diploma](https://github.com/aathanas/aathanas.github.io/tree/master/_students_diploma).
1. Teaching information is maintained in [_teaching](https://github.com/aathanas/aathanas.github.io/tree/master/_teaching).

## Disclaimers and other information

This page is a fork from https://academicpages.github.io/, a Github Pages template for academic websites. This was forked (then detached) by [Stuart Geiger](https://github.com/staeiou) from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/), which is © 2016 Michael Rose and released under the MIT License. See LICENSE.md.

#### Note: if you are using this repo and now get a notification about a security vulnerability, delete the Gemfile.lock file. 

### To run locally (not on GitHub Pages, to serve on your own computer)

1. Clone the repository and made updates as detailed above
1. Make sure you have ruby-dev, bundler, and nodejs installed: `sudo apt install ruby-dev ruby-bundler nodejs`
1. Run `bundle clean` to clean up the directory (no need to run `--force`)
1. Run `bundle install` to install ruby dependencies. If you get errors, delete Gemfile.lock and try again.
1. Run `bundle exec jekyll liveserve` to generate the HTML and serve it from `localhost:4000` the local server will automatically rebuild and refresh the pages on change.

