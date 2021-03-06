---
layout: index
title: Home
published: true
---

# Welcome to exVim

exVim is a project to turn Vim into a nice programming environment. exVim introduce the project file concept (.exvim) in Vim. By editing this project file (.exvim) through Vim, the exVim plugins will be invoked. In this way, it makes you possible to apply different Vim settings, plugin settings and even loading plugins on demand by different projects. In general, it makes Vim become the best IDE in the world!

**EVEN COOL IS --- WE USE EXVIM DEVELOP EXVIM! (\\(-_-)/)**

- [Downloads](downloads)
- [Install](docs/install)

## Features

- Manage your project with a `.exvim` setting file.
- Update your project files with a single command. (tags, cscope-db, search-index, makefile, ...)
- Project files are stored in one place (in the folder `./.exvim.your_project_name/` under your project).
- Load Vim plugins on demand for different projects based on your `.exvim` settings.
- Better management of plugin windows in Vim. (avoid getting multiple plugin windows messed up)
- Browse and work on your project files and folders in the project window.
- Class, variable, and function tag jumping.
- Global search in project scope.
- Global search engine customization (user can choose grep, idutils, or even his own)
- A powerful way to filter your global search results.
- Generate class hierarchy pictures.
- Enhanced quick-fix window.
- Popular Vim plugin integrated.

## How does it work?

By editing and saving your project settings in a `your_project_name.exvim` file and opening it with Vim, the exVim plugins
will be loaded.  exVim will parse the `your_project_name.exvim` file and apply the settings for your project after Vim
has started.

The settings include:

exVim also makes sure project files are stored in one place (in the folder `./.exvim.your_project_name/` under your project).
This makes your project clean and much better to work with external tools. These project files can be:

- global search index and results (idutils)
- tags
- cscope files
- hierarchy graph pictures
- error messages
- temporary files
- ...

After Vim has loaded `your_project_name.exvim` and started, exVim helps you update your project files so you
can use your favorite plugins with these files.

## Community

- [Chinese] QQ群: 319248144
- [Chinese] Tower讨论群: 请发我Email KarasAya@gmail.com 申请加入
- [English] Comming Soon...
