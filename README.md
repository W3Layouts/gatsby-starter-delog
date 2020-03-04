# Delog - Blog for Developer and Designer
This simple website built with GatsbyJS and Netlify CMS. Deploys on netlify with single click.

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=hhttps://github.com/W3Layouts/delog/)

* Once you hit "Deploy to Netlify"
* Connect Github
* Enter Repository Name
* And your site starts build process. After the build process your website is live

[![Netlify Status](https://api.netlify.com/api/v1/badges/8ec719ad-c2f8-4529-b97d-e7561a9eaf33/deploy-status)](https://app.netlify.com/sites/delog-w3layouts/deploys)

## Accessing Netlify CMS Admin
Once the your site is live, Netlify will give you your website address. like example.netlify.com, for this add `/admin/`, You will see login with Github button.
* After clicking on it, you will get error "No Auth Provider Found"
* Goto your Netlify site admin
* Goto **Access Control** > **OAuth** then **Install Provider** you need to select provider as `Github` as add `Client ID` and `Secret` (these you can get from Github [Developer Settings](https://github.com/settings/developers) > **New OAuth**)
