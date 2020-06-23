---
theme : "blood"
transition: 'slide'
highlightTheme: "monokai"
slideNumber: false
title: "VSCode intro"
showNotes: false
---
<!-- .slide: data-transition="fade" data-background="#0066B8" data-background-transition="fade" -->

## Visual Studio Code

### what the _hack_?

_An introduction to VSCode_

note: Clearly explain goal of presentation
note: Enable `Screencast mode` To show shortcuts
note: Explain agenda
note: Only top slides + demo, others as backup

---

<!-- .slide: data-transition="fade" data-background="#0066B8" data-background-transition="fade" -->

## Agenda

- Intro
- Basics
- Usage
- Build & Debug
- Collaboration
- GIT
- Customization
- Extensions

---

<!-- .slide: data-transition="fade" data-background="#0066B8" data-background-transition="fade" -->
# Intro

--

## History

- First announced April 👉 //Build 2015
- Code available GitHub (MIT) 👉 Nov 2015
- Public Review (v1) 👉 //Build 2016
  
note: first announcement => https://youtu.be/Ye4aVpLMZTw?t=2393
--

## What is vscode

- Code editor
- Build on Monaco => _the browser based text editor_
- Electron App
- Build with TypeScript

note: out of the box a code editor. With extensions full IDE. Like a slider.
note: filebased/folderbased

--

## Flavours

- Visual Studio Code
- Visual Studio Code - Insiders
- Visual Studio Codespaces

note: TODO: add logos

--

## Why

It is:

- it's free, for real
- light weight
- build with ❤ for the web
- avaiable on macOS, Linux, and Windows
- highly customizable and extensible
- open source

---

<!-- .slide: data-transition="fade" data-background="#0066B8" data-background-transition="fade" -->
# Basics

--

## Zen Mode

Remove distractions

`CTRL+K, Z`

--

## VSCode Overview

- What is what?

note: panels etc

--

## Code Editing

- Multi-line Editing 
  - `ALT+SHIFT+Drag mouse`
- Commenting Code
  - `CTRL+/`
- Moving blocks 
  - `ALT+UP` 
  - `ALT+DOWN`
- Fold / expand 
  - `CTRL+SHIFT+[` 
  - `CTRL+SHIFT+]`

--

## Split windows

- Creating and switching editor windows
  - `CTRL+1`
  - `CTRL+2`
  - `CTRL+3`
  - etc

- Close current window
  - `CTRL+W`
  - `CTRL+F4`

--

## Last file

- Get back to last file
  - `CTRL+P, CTRL+P`

--

## Navigating through a file

Quick Open:

- `CTRL+P`
  - `@` => Jumping to places
  - `:` => Jumping to Line number
  - `@:` => Jump to places, sorted

note: @ is also in the Explorer

--

## Hot Exit

- Unsaved file indicated by a Dot
- ‘saves’ new files when closing when not saved

note: new file -> kill vscode from process explorer

--

## Minimap

- map of code in scrollbar

note: show in settings


---

<!-- .slide: data-transition="fade" data-background="#0066B8" data-background-transition="fade" -->
# Usage

--

## starting VSCode

From the command line:
- load a folder
  - `code .`
- replace current window:
  -  `code . -r`  

--

## Command palette

executing commands:

- `CTRL+SHIFT+P`
- `CTRL+P + >`

--

## Code Snippets

Adding little snippets of code:

- through extensions
- editing json files

note: demo adding a code snippet
note: " * comment about ${1:functionname}",

--

## Terminal

Integrated commandline

- `CTRL+` `
- `CTRL+J`

--

## Hiding Sensitive files

- When .gitignore is not enough
- Setting per project or global

note: Exclude `**/topsecret.txt`

--

## Emmet

high-speed coding HTML, CSS, and such

- For Angular, vue, react change
  - Emmet.IncludeLanguages

<br/><br/>

Also:

- ImageSize in HTML
- Math

note: demo in html

--

## Playground

Learn VSCode:

- use the interactive playground

---

<!-- .slide: data-transition="fade" data-background="#0066B8" data-background-transition="fade" -->
# Build & Debug

--

## F5

Running your app

--

## Configuring builds

Creating an editing configuration for builds

--

## Breakpoints

- Normal
- Conditional
- Count
- Log

---

<!-- .slide: data-transition="fade" data-background="#0066B8" data-background-transition="fade" -->
## Collaboration

--

## Live share

Remote pair programming from within Visual Studio

_Google Docs of writing code_

note: https://docs.microsoft.com/en-us/visualstudio/liveshare/reference/security
note: LiveShare is available for Code+IDE+Mac. Join in Browser
note: => Pair programming or even Mob programming, education, hackathons, streaming
--

## Visual Studio Codespaces

VSCode online

---

<!-- .slide: data-transition="fade" data-background="#0066B8" data-background-transition="fade" -->
# GIT

--

# Git

Basic Git integration

--

# Git History

Extension for history

note: Exact details on what is git history and lens

--

# Git Lens

Extension for change details

---

<!-- .slide: data-transition="fade" data-background="#0066B8" data-background-transition="fade" -->
## Customization

--

## Themes

Lots of downloable themes

--

## Icons

Extensions to get detailed icons

--

## Font Ligatures

<div style="font-family:'fira code'">
Fira Code:
    =>
    ===
    <=
    !=
</div>

--

## Per Project/workspace

Save or Share per project

---

<!-- .slide: data-transition="fade" data-background="#0066B8" data-background-transition="fade" -->
## Extensions

--

## About

- install extension
- search etc.

--

## Azure

- Azure Account
- Azure Functions
- Azure Storage
- Azure App Service

--

## IntelliCode

AI Driven Intellisense

--

## Peacock

Subtly change the color of your Visual Studio Code workspace

--

## Prettier

Code formatting using Prettier

--

## TODO+

Fancy todo files

---

<!-- .slide: data-transition="fade" data-background="#0066B8" data-background-transition="fade" -->
## Thank you

