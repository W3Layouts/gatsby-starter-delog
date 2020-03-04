# Delog - Blog for Developer and Designer
This simple website built with GatsbyJS and Netlify CMS. Deploys on netlify with single click.

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=hhttps://github.com/W3Layouts/delog/)

* Once you hit "Deploy to Netlify"
* Connect Github
* Enter Repository Name
* And your site starts build process. After the build process your website is live

[![Netlify Status](https://api.netlify.com/api/v1/badges/8ec719ad-c2f8-4529-b97d-e7561a9eaf33/deploy-status)](https://app.netlify.com/sites/delog-w3layouts/deploys)

## Accessing Netlify CMS Admin
Once the your site is live, Netlify will give you your website URL. like example.netlify.com, for this add `/admin/`, You will see login with Github button.
* After clicking on it, you will get error "No Auth Provider Found"
* Goto your Netlify site admin
* Goto **Access Control** > **OAuth** then **Install Provider** you need to select provider as `Github` as add `Client ID` and `Secret` 

## Creating Github OAuth Client ID
* Goto Github [Developer Settings](https://github.com/settings/developers)
* **New OAuth** 
* Enter Application name
* Homepage URL as Netlify URL
* And **Authorization callback URL** to `https://api.netlify.com/auth/done`)
* Once Client ID and Secret token is generated configure same in [Netlify Access Control](#accessing-netlify-cms-admin) as described earlier. Now go back to `example.netlify.com/admin` and connect with github and Authorize. Now you will be redirected to Netlify CMS

## Managing Blog Posts in Netlify CMS
* Once logged in you will find all the blog post listed here.
* You can create, edit, update and delete like any CMS

I hope you build a great website with Delog. This Starter is sponsered by [W3Layouts](https://w3layouts.com).

For issues,feedback on enhancement or sharing your new awesome website built with delog here. [Create New Issue](https://github.com/W3Layouts/delog/issues/new)
