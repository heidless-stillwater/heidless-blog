---
author: Rob Craig
pubDatetime: 2024-06-01T15:57:52.737Z
title: RoR-APP-saas-base-template
postSlug: RoR-APP-saas-base-template
featured: true
ogImage: https://user-images.githubusercontent.com/53733092/215771435-25408246-2309-4f8b-a781-1f3d93bdf0ec.png
tags:
  - alpha-blog
  - ruby-on-rails
  - cloud-run
  - docker
description: Ruby on Rails App - RoR-APP-saas-base-template
---

# RoR-APP-saas-base-template

## <a href="https://alpha-blog-svc-590618864324.europe-west1.run.app/" target="_blank">alpha blog</a>

## Tech Info
- Rails 6
- Google Cloud 
  - Postgres
  - Credentials via Secret Mgr

- ### overview

  - Multi-user blog environment.

- ### link

  - <a href="https://robertlockhart.com/" target="_blank">alpha blog</a>
    - DEMO LOGIN:
    - USERNAME: demo@heidless-app-0.com
    - PASSWORD: password

- ### Bloggers

  - List all Bloggers registerd with the site (including 'Admin')
  - All Users visible including their Articles

- ### Articles

  - create New Articles for current user
  - 'View Articles'
    - List ALL articles for ALL users
  - category
    - choose from list of categories
    - new categories create under 'Catogories' menu

- ### Categories

  - 'Create New Category'
    - ONLY Available to Admin user
    - does what it says on the tin
  - 'View Categories': lists all available categories for selection with Articles
  - All Categories available to All Users

- ### Profile(s)
  - List ALL Users
