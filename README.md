# fl-course-templates
A set of templates for EdX courses

# How to build the site

## Install the pre-requisites

Open a command prompt / terminal and run:

```bash
pip3 install mkdocs mkdocs-nav-enhancements mkdocs-material mkdocs-autozip
```

## Test and view the site

Run mkdocs and *serve* the site:

```bash
mkdocs serve
```

Open a browser and visit [http://127.0.0.1:8000/](http://127.0.0.1:8000/)

## Deploy the site

Use mkdocs to deploy the site to the `gh-pages` branch.

```bash
mkdocs gh-deploy
```
