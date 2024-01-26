# Metalhead Robot Wiki - Configuration

| [Home](../README.md) | [Architecture](../architecture/README.md) | [Git](../git/README.md) | Configuration | [Mockups](../mockups/README.md) | [Database](../database/README.md) | [Project Management](../project-management/README.md) | [Quality](../quality/README.md) |
| :------------------: | :---------------------------------------: | :---------------------: | :-----------: | :-----------------------------: | :-------------------------------: | :---------------------------------------------------: | :-----------------------------: |

- [Metalhead Robot Wiki - Configuration](#metalhead-robot-wiki---configuration)
  - [Configuration](#configuration)
    - [UI](#ui)
    - [Rest API](#rest-api)
    - [Scavenger](#scavenger)
    - [Database](#database)

## Configuration

This document only contains the steps for Windows environment.

Start by setting up the development environment. To run any project, the tools below needs to be installed.

- Node.js - To run Javascript code on your machine. Download the Windows Installer from the [official website](https://nodejs.org/en/download/current).
- Git - To have source code versioning support with Git. Download the Git SCM from the [official website](https://git-scm.com/downloads).
- Visual Studio Code - Suggested IDE, but you can use one of your preference. Download the Windows Installer from the [official website](https://code.visualstudio.com/download).

### UI

UI is a Next.js project. In order to have your project running, start by cloning the repository.

```bash
$ git clone <metalhead_robot_repository_url>
```

Go to the cloned repository and install all dependencies.

```bash
$ cd metalhead-robot-ui
$ npm install
```

You can now build, run and test the UI project.

```bash
$ npm run build
$ npm run dev
$ npm test
$ npm test:e2e
```

### Rest API

TBD.

### Scavenger

TBD.

### Database

TBD.
