[![](assets/img/screenshot.png)](https://github.com/davehorsfall/jekyll-startbootstrap-agency)

# Jekyllised - Start Bootstrap Agency

[![deploy](https://github.com/davehorsfall/jekyll-startbootstrap-agency/actions/workflows/jekyll.yml/badge.svg)](https://github.com/davehorsfall/jekyll-startbootstrap-agency/actions/workflows/jekyll.yml)
[![license](https://img.shields.io/badge/license-MIT-blue)](LICENSE)
[![demo](https://img.shields.io/badge/demo-view-blue)](https://davehorsfall.github.io/jekyll-startbootstrap-agency/)

**Agency** is one of the most popular HTML themes offered by [Start Bootstrap](https://startbootstrap.com/). I have _**Jekyllised**_ this theme to give web developers and hobbyists a simple and clean implimentation in [Jekyll](https://jekyllrb.com/) for starting new projects. This template is free and open source, released under the [MIT license](LICENSE).

# Description

Agency is a HTML/CSS theme built with Bootstrap 5. This theme is perfect for agencies or small businesses looking to set up a simple website for their company. The theme can also be modified and adjusted to fit just about any purpose! 

## Agency Features

* Responsive top navigation that collapses and restyled when the page is scrolled
* Smooth scrolling navigation to optimize the one page website user experience
* Integration with Font Awesome Icons
* Portfolio grid with modal windows for each item to showcase more detailed content for each portfolio item
* About section with a responsive timeline
* Team member section with profile images and social media links
* Footer with social links, copyright information, and additional page links
* SCSS and Pug files included in the source files on GitHub for deeper customization and development

## Jekyllised

* The Agency HTML template has been natively integrated with the Jekyll framework
* Works with Ruby 2 and 3
* Portfolio collection - just add new Markdown files to add new portfolio items
* Team collection - just add new Markdown files to add new team members

# Getting Started (i.e. setting up things on your own computer)

## Requirements

* You will need [Ruby](https://jekyllrb.com/docs/installation/) to use [Jekyll](https://jekyllrb.com/). Follow [the guides](https://jekyllrb.com/docs/installation/) on the Jekyll website to install the requiremtns for your operating system.
* You will need [Git](https://github.com/git-guides/install-git) installed to deploy your website to Github Pages. Follow [the guide](https://github.com/git-guides/install-git) on the Github website to set setup.

## Installation

1. Create your own copy by forking the repositry. [Click here](https://github.com/davehorsfall/jekyll-startbootstrap-agency/fork) to start a new fork. Afterwards, you will have your own version of the template under your Github username.

> [![create-fork](docs/screenshots/create-fork-thumb.png?raw=true)](docs/screenshots/create-fork.png?raw=true) [![forked-repo](docs/screenshots/forked-repo-thumb.png?raw=true)](docs/screenshots/forked-repo.png?raw=true)

2. Clone your forked repositry. Replace `[USERNAME]` with your own Github username:

```sh
$ git clone git@github.com:[USERNAME]/jekyll-startbootstrap-agency.git
```

2. Change directory into the template:

```sh
$ cd jekyll-startbootstrap-agency
```
3. Install the dependancies in the `Gemfile`:

```sh
$ bundle install 
```

4. Start the development server to serve the Jekyll website:

```sh
$ bundle exec jekyll serve
```

The Jekyll website should now be avaliable for you view in your browser. The default location is http://127.0.0.1:4000/. 

# Deploymemt (i.e. publishing your website online for free using Github Pages)

You can deploy your website for free using features of Github called [Pages](https://pages.github.com/) and [Actions](https://github.com/actions). Follow the instructions below to deploy your forked copy of the template. 

1. In your forked copy of the repo, go to the `Settings` tab at the top, then click the `Pages` link on the left. Here, we see the options for hosting content from your repo. For the `Source` option, make sure **Deploy from a branch** is selected. Then for the `Branch` option, select the **main** branch, as shown in the screenshot below.

> [![github-pages-setup](docs/screenshots/github-pages-setup-thumb.png?raw=true)](docs/screenshots/github-pages-setup.png?raw=true)

2. After you make these changes, Github Pages will be setup. By default, an Action called `pages build and deployment` will be run. You can view this under the `Actions` tab. However, this default Action will not build the website correctly. On the Actions tab, select the `deploy` action on the left, and then select `Run Workflow` and click on the **Run Workflow** button. See screenshots below for clarification.  

> [![github-actions-default-thumb](docs/screenshots/github-actions-default-thumb.png?raw=true)](docs/screenshots/github-actions-default.png?raw=true) [![create-fork](docs/screenshots/github-actions-deploy-thumb.png?raw=true)](docs/screenshots/github-actions-deploy.png?raw=true) [![create-fork](docs/screenshots/github-actions-run-workflow-thumb.png?raw=true)](docs/screenshots/github-actions-run-workflow.png?raw=true)

3. If everything has worked correctly, you will see your `deploy` Action is run successfully. 

> [![github-actions-deploy-success](docs/screenshots/github-actions-deploy-success-thumb.png?raw=true)](docs/screenshots/github-actions-deploy-success.png?raw=true)

4. After the `deploy` Action has successfully complete, you can return to the `Pages` link, to see a confirmation that your Jekyll website is live, along with a link to the website. You can make furhter changes to your Github Pages setup. For example, enforce HTTPS, or setup a custom domain.  See the [Pages documentation](https://docs.github.com/en/pages) for more details. 

> [![github-pages-deploy](docs/screenshots/github-pages-deploy-thumb.png?raw=true)](docs/screenshots/github-pages-deploy.png?raw=true)
