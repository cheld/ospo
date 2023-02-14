# Development

## Setup a Development Environment

* **Codespaces** - No setup required when using Github Codespaces. Just open the project
* **VSCode** - No setup required when using VSCode and Docker. Just open the project in Devcontainer.
* **Local** - Install Ruby and Jekyll following the the instructions from the [Jekyll website](https://jekyllrb.com/docs/installation/).

## Build the Website

Initially all package dependencies of Jekyll must be installed once. Run the command:

```code
bundle install
```

Build the site and serve the content:

```code
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