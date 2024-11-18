---
title: Background Check
description: Notifies maintainers when new contributors who have been toxic in
  the past join the project
slug: background-check
screenshots:
  - https://raw.githubusercontent.com/probot/background-check/master/assets/demonstration.png
authors:
  - itaditya
repository: probot/background-check
host: https://probot-background-check.herokuapp.com
stars: 28
updated: 2023-12-16 00:54:12 UTC
organizations:
  - kartik-v
  - probot
  - theme-next
  - publiclab
  - debugger22
  - cherrypy
  - fvcproductions
  - Richienb
  - campus-experts
  - techqueria
---

When a new contributor comments on your repository, sentiment analysis is run on their recent public comments. If 5 or more comments stand out as toxic, then an issue is opened for this user in `probot-background-check/{your-github-username}-discussions` private repository so that you and other maintainers can review these toxic comments and discuss whether or not you all want to allow this hostile user to participate in the community.

## Setup the app

* Install the app from [here](https://github.com/apps/background-check) in your repos.
* You'll receive an invitation to join a repo in `probot-background-check` org. Accept it.

Simple as that. No config needed.
