# My personal website

Built with Jekyll using [the Akio template](https://jekyllthemes.io/theme/akio-portfolio-jekyll-theme). Hosted by GitHub via GitHub Pages.

## Setup

### Installing Ruby & Jekyll

If this is your first time using Jekyll, please follow the [Jekyll docs](https://jekyllrb.com/docs/installation/) and make sure your local environment (including Ruby) is setup correctly.

### Running locally

To run the theme locally, navigate to the theme directory and run `bundle install` to install the dependencies, then run `jekyll serve` or `bundle exec jekyll serve` to start the Jekyll server. You can then see the website at `localhost:4000`.

To add any job, add .md file into `_works` folder following similar layout. For new projects, add .md file into `_owns` folder with similar layout.  

Layout files:

All major changes: _data/settings.yml

Projects: own/index.html

My Career: work/index.html

Home: index.html, _includes/section-hero.html, section-own.html, section-work.html

