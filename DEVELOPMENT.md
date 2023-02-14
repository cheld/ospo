# Development

## Setup in Codespaces

Using Github Codespaces no setup required. Just open the project.

## Setup in Local DevContainer

Using VSCode and Docker no setup required. Just open the project.

## Setup in Local Environment

Using your PC environment, you must install Ruby and Jekyll. Follow the the installation instructions from the Jekyll website.

## Build the Website

Initially all package dependencies of Jekyll must be installed once. Run the command:

```sh
bundle install
```

Build the site and serve the content:

```sh
bundle exec jekyll serve
```

## Jekyll Structure

* Folder __layouts_ contains html, css and images. In order to keep development and folder structure as simple as possible, the complete layout is contained in only one file (__layout/default.html_).
* Folder __pages_ contains landing page in html
* Folder __pages/documentation_ contains all markdown pages. The folder names align with the menu structure
* File __config.yml_ contains the top-level menu order of the documentation pages

## Design

* The design is aligned to the [Allianz UI framework](https://ngx-ndbx.frameworks.allianz.io/welcome)
* The page is responsive and works on mobile devices