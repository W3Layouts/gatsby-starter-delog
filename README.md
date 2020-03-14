[![Netlify Status](https://api.netlify.com/api/v1/badges/8ec719ad-c2f8-4529-b97d-e7561a9eaf33/deploy-status)](https://app.netlify.com/sites/delog-w3layouts/deploys)

# Delog - Blog for Developer and Designer
This simple website built with GatsbyJS and Netlify CMS. Deploys on netlify with single click. This Starter is sponsered by [W3Layouts](https://w3layouts.com).

[![Delog - Gatsby Starter Demo](https://w3layouts.com/wp-content/uploads/2020/03/gatsby-starter.jpg)](https://delog-w3layouts.netlify.com/)

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/W3Layouts/gatsby-starter-delog)

* Once you hit "Deploy to Netlify"
* Connect Github
* Enter Repository Name
* And your site starts build process. After the build process your website is live

## Changing repositary URL for Netlify CMS access
You need to change repo URL to your own `repo` at delog/static/admin/config.yml, for example `username/repo-name`

## Creating Github OAuth Client ID
* Goto Github [Developer Settings](https://github.com/settings/developers)
* **New OAuth** 
* Enter Application name
* Homepage URL as Netlify URL
* And **Authorization callback URL** to `https://api.netlify.com/auth/done`)
* Once Client ID and Secret token is generated configure same in [Netlify Access Control](#accessing-netlify-cms-admin) as described.

## Accessing Netlify CMS Admin
* Goto your Netlify site admin
* Goto **Access Control** > **OAuth** then **Install Provider** you need to select provider as `Github` as add `Client ID` and `Secret` 
* Your Netlify CMS is ready. Goto you netlify site URL and append `/admin/`. for example `example.netlify.com/admin/`, You will see login with Github button.

## Managing Blog Posts in Netlify CMS
* Once logged in you will find all the blog post listed here.
* You can create, edit, update and delete like any CMS

## Editing Meta Data
Goto `gatsby-config.js`. Here you can edit following details
* Title
* Description
* Site URL
* Homepage Title
* Homepage Description
* W3Layouts Contact form domain verification key
* and google analytics tracking id

I hope you build a great website with Delog. If you like it please spread the word, Feel free to contribute and raise a pull request :)

For issues,feedback on enhancement or sharing your new awesome website built with delog. [Create New Issue](https://github.com/W3Layouts/delog/issues/new) Here

### Upcoming Features Roadmap
- [ ] Pagination for Blog
- [ ] Socail Icons
