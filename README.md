# POC MkDocs Technical Reference Guide

This project is a proof of concept experiment to see if docs as code can work for a particular set of technical reference material.
This is one of a handful experiments to identify authoring tools and source content management system (SCM) for this content.

**The experiment** prototype the content in the tooling, and then evaluate (score) the results against prioritized (weighted) requirements.

## Project description

This is a real draft material so I can evaluate the feasibility of using the [MkDocs ↗](http://www.mkdocs.org/) Markdown and Python static site generator and [Material for MkDocs ↗](https://squidfunk.github.io/mkdocs-material/) theme for my technical documentation.

With this project, I can understand if markdown and ssg meets my authoring, source code management, and deliverable generation requirements.

## Who this project is for

This project is intended for me (technical writer) and is likely not useful for others.

## Project dependencies

Before using POC MkDocs Technical Reference Guide, ensure you have:

* Python
* Git
* Visual Studio Code (VSCode) with extensions: Python (MS), Code Spell checker, DevSkim (security analyzer), Markdown All in One, markdownlint, YAML (redhat)
* [Material for MkDocs ↗](https://squidfunk.github.io/mkdocs-material/getting-started/) (use Python/pip) with plugins: glightbox

## Instructions for using this project

Use [Material for Makedocs Getting Started ↗](https://squidfunk.github.io/mkdocs-material/getting-started/)
Install and configure plugins:

* [Lightbox ↗](https://squidfunk.github.io/mkdocs-material/reference/images/#lightbox)
* Others tbd

Recommend using a Python virtual environment.

To create a virtual env (one time task):

* In Powershell or VS Code Terminal from the local repo folder, `python -m venv venv`
* Then `venv\Scripts\activate`
* You will see prompt now includes "venv" i.e. `(venv)C:\ProjectDir\gitreponame>`
* Confirm you are running virtual env by checking pip version `pip --version` the response should show pip from repo venv\Lib location.

With each VSCode session, activate virtual env. Type `venv\Scripts\activate`

Use live preview server. In Terminal, type `mkdocs serve` use the localhost:8000 port in the message.

Build the site. Type `mkdocs build`

## Additional documentation

For more information:

* [Markdown cheat sheet ↗](https://www.markdownguide.org/cheat-sheet/)
* [MkDocs User Guide ↗](https://www.mkdocs.org/user-guide/)
* [Material for MkDocs Reference Guide ↗](https://squidfunk.github.io/mkdocs-material/reference/)

## Terms of use

POC MkDocs Technical Reference Guide is licensed under [CC0 1.0](LICENSE) for this doc project only and provides no licensing provisions for the software it documents.
