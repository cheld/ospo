# Development

## Setup Jekyll Development Environment

* **Codespaces** - No setup required when using Github Codespaces. Just open the project
* **VSCode** - No setup required when using VSCode and Docker. Just open the project in the provided Devcontainer.
* **Local** - Follow the instructions from the [Jekyll website](https://jekyllrb.com/docs/installation/) to install Ruby and Jekyll
  
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

* Folder **_layouts** contains html, css and images. In order to keep development and folder structure as simple as possible, the complete layout is contained in only one file (__layout/default.html_).
* Folder **_pages** contains landing page in html
* Folder **_pages/documentation** contains all markdown pages. The folder names align with the menu structure
* File **_config.yml** contains the left-side menu order of the documentation pages

## Design

* The design is aligned to the [Allianz UI framework](https://ngx-ndbx.frameworks.allianz.io/welcome)
* The page is responsive and works on mobile devices