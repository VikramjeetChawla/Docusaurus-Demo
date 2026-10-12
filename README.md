# Website

This website is built using [Docusaurus](https://docusaurus.io/), a modern static website generator.

## Installation

```bash
npm install
```

**Note**: feel free to use the package manager of your choice.

## Local Development

```bash
npm run start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

## Build

```bash
npm run build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

## Deployment

Using SSH:

```bash
USE_SSH=true npm run deploy
```

Not using SSH:

```bash
GIT_USER=<Your GitHub username> npm run deploy
```

If you are using GitHub Pages for hosting, this command is a convenient way to build the website and push to the `gh-pages` branch.


```bash

```mermaid
%%{init: {"flowchart": {"htmlLabels": true, "nodeSpacing": 65, "rankSpacing": 90, "useMaxWidth": false}, "themeVariables": {"fontSize": "16px"}}}%%

flowchart TB
    ROOT["Product Release Documentation<br/>Project overview and release index"]

    ROOT ~~~ OVERVIEW
    ROOT ~~~ CHANGES
    ROOT ~~~ SUPPORT

    subgraph OVERVIEW["RELEASE OVERVIEW"]
        direction LR
        A["<b>1. What's New in Version 2.0</b><br/><span>Release highlights and summary</span>"]
        B["<b>7. Previous Releases</b><br/><span>Release history and links to earlier versions</span>"]
    end

    subgraph CHANGES["PRODUCT CHANGES"]
        direction LR
        C["<b>2.&nbsp;New&nbsp;Features</b><br/><span>New functionality and how to use it</span>"]
        D["<b>3.&nbsp;Improvements</b><br/><span>Enhancements to existing features</span>"]
        E["<b>4.&nbsp;Bug Fixes</b><br/><span>Resolved issues and their user impact</span>"]
    end

    subgraph SUPPORT["UPGRADE & SUPPORT"]
        direction LR
        F["<b>6.&nbsp;Upgrade Notes</b><br/><span>Compatibility, prerequisites, and upgrade guidance</span>"]
        G["<b>5.&nbsp;Known Issues and Workarounds</b><br/><span>Current limitations and temporary solutions</span>"]
    end

    ROOT --> A
    ROOT --> C
    ROOT --> F

    A ~~~ B
    C ~~~ D
    D ~~~ E
    F ~~~ G

    A --> B
    C --> D
    D --> E
    F --> G

    style ROOT fill:none,stroke:#333,stroke-width:2px
    style OVERVIEW fill:none,stroke:#999,stroke-dasharray:4 4
    style CHANGES fill:none,stroke:#999,stroke-dasharray:4 4
    style SUPPORT fill:none,stroke:#999,stroke-dasharray:4 4
```

```
