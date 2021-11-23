# Contributing to Project Delve

Project Delve welcomes file edits, new project additions, and new site features from anyone who wants to contribute.

There are two paths to choose between if you plan to contribute...
* ...and you're **new to GitHub** - Pause here. Go follow the guide I created [**specially for beginners**](https://github.com/punnypenguins/projectdelve/blob/main/documentation/for-beginner-contributers.md) to walk you through everything.
* ...and you **already know GitHub's workflow** - Continue on to the following sections of this doc.


# Style Guidelines

This project is primarily written in [Markdown](https://www.markdownguide.org/basic-syntax/), and its front matter formatting follows [Hugo's](https://gohugo.io/content-management/front-matter/) syntax.


# Getting Started

Before you begin, make sure you've met all of the following requirements:

* You have a GitHub [account](https://github.com/join)
* You have [GitHub Desktop](https://desktop.github.com/) set up
* You have forked and cloned the [Project Delve repository](https://github.com/punnypenguins/projectdelve)
* You know how to create a [branch](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-branches)
* You know how to create a [pull request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests)


# Adding a new project to the site

### To add a new project:
1. Make sure you're in your fork of the Project Delve repository.
2. Create a new **branch**. Name it something that is clear and easy for you to understand, such as "adding-new-project-x" or "[issue number]-project-x".
3. Follow the [template instructions](https://github.com/punnypenguins/projectdelve/tree/main/documentation/templates) for the category the new project falls under.
4. Once the file is ready, save your work and push the changes to GitHub.
5. Open a **pull request** for your work:
  - Give it a simple title, preferrably containing the project name, please!
  - You don't *have* to write a full description/summary for the pull request, but please **DO** type inside that box "Issue #[issue-number-here]". This will connect your pull request with the issue you're addressing and make it easy for me to close issues instead of leaving one open on accident.
    - If there's not already an issue for the project you're adding, please take a minute to open a new issue for it and then connect your pull request to that. Thanks!

Thank you so much for helping all of us find more projects to join!


# Suggesting an edit

### To suggest an edit:
1. Make sure you're in your fork of the Project Delve repository.
2. Create a new **branch**. Name it something that is clear and easy for you to understand, such as "updating-thing-x" or "[issue number]-fixing-x".
3. Make any necessary changes to the file(s) in question.
4. Once you're satisfied with your work, save your edits and push the changes to GitHub.
5. Open a **pull request** for your work:
  - Give it a simple title, clearly stating what kind of change it is (edit, fix, update, etc.).
  - You don't *have* to write a full description/summary for the pull request, but please **DO** type inside that box "Issue #[issue-number-here]". This will connect your pull request with the issue you're addressing and make it easy for me to close issues instead of leaving one open on accident.
    - If there's not already an issue for the project you're adding, please take a minute to open a new issue for it and then connect your pull request to that. Thanks!


# Review process

After your pull request is submitted, I'll review it within a week and request changes if necessary. Once I confirm everything is good to go, your pull request will be accepted and merged into the `master` branch.


# Running the site for local development

To run this site via localhost on your computer, first make sure that you've either cloned the repository or downloaded it via .zip file and unpacked it already.

Once you're sure the site files are all locally on your device, follow the instructions below for installing Hugo on whichever operating system you're using. I've only written instructions for quick installation via package managers; if you want to install Hugo via Tarball or building from the source, you can follow the steps listed in [Hugo's installation guide](https://gohugo.io/getting-started/installing/).

🌟 If you're a fan of using [Docker](https://www.docker.com/), Hugo doesn't have an *official* image but [*does* recommend this one](https://hub.docker.com/r/klakegg/hugo/) if you wish to go the Docker route.

## 1. Install Hugo

### Windows users:

If you use [Chocolatey](https://chocolatey.org/), run `choco install hugo -confirm` in the command line.

If you use [Scoop](https://scoop.sh/), run `choco install hugo -confirm` in the command line.

### Mac users:

If you use [Homebrew](https://brew.sh/), run `brew install hugo` in the command line.

If you use [MacPorts](https://www.macports.org/), run `port install hugo` in the command line.

### Linux users:

If you use [Homebrew on Linux](https://docs.brew.sh/Homebrew-on-Linux), run `brew install hugo` in the command line.

## 2. Set up the local server

Ensure you're currently in the folder that contains the Project Delve site files.
> EXAMPLE: If you're using GitHub Desktop to interface with the repository on a Mac, the default location would be [your user] > `Documents` > `GitHub` > `projectdelve`. In this case, you would open a new Terminal shell and type in `cd Documents/GitHub/projectdelve` to get to the correct folder.

<p align="center">
  <img src="/images/cd-navigate.png" alt="Terminal window showing example navigation"/>
</p>

Once you're sure you're in the correct directory, run `hugo server` in the command line. You should see something similar to the image below as its output. Don't panic if it takes a few seconds to run!

<p align="center">
  <img src="/images/hugo-server.png" alt="Terminal window showing hugo server output"/>
</p>

Until you end this command or quit the shell process, you will now be able to see the Project Delve site at [http://localhost:1313/](http://localhost:1313/) and all changes you make to the local files will be visible there in real time.

🌟 For more information on running Hugo locally, see [hugo server](https://gohugo.io/commands/hugo_server/) in Hugo's documentation.


# Additional resources

* [GitHub documentation](https://docs.github.com/en)
* [Hugo documentation](https://gohugo.io/documentation/)
* [Markdown Guide](https://www.markdownguide.org/)
* My [guide](https://github.com/punnypenguins/writing-samples/blob/main/Assorted/beginner-open-source.md) for beginners to open source
* My [Ko-fi](https://ko-fi.com/punnypenguins) if you feel like helping out with hosting costs or just tipping me as a "Thanks!"

# Questions

If you have any questions that I haven't addressed here, feel free to ask in a [new issue](https://github.com/punnypenguins/projectdelve/issues) (please add the `question` tag to it) or by [shooting me an email](kgeerling@protonmail.com).
