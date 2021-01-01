[![Netlify Status](https://api.netlify.com/api/v1/badges/d7c7e853-0045-4848-99dd-73c6506f0066/deploy-status)](https://app.netlify.com/sites/sorbaathens/deploys)

# Hosted on Github and deploying with Netlify

+ https://sorbaathens.org

## To edit production

+ push changes to master

## To use deploy preview:

+ Make edits
+ Push to a branch
+ Make a pull request - every one yields a unique link which shows up under deploy previews

## Local testing with netlify dev

+ install [Node.js](https://nodejs.org/en/download/)
+ open command prompt and install the netlify CLI with `npm install netlify-cli -g`
+ install hugo extended with `choco install hugo-extended`
+ test that it works with `netlify`
+ login with `netlify login`
+ authorize on the Netlify window that opens
+ cd to the folder of an existing site and `netlify link`
+ copy the site id from Netlify.com > site settings > site details
+ right click the top bar > edit > paste the site id into the command window where it asks for it
+ use `netlify dev` to build a site locally
+ when everything works and you're happy push the changes with git

* * *

## To do:

+ Minutes on the website
+ Add Hart Farms and Morgan County trails pages
+ links in new tab with js:
https://code.luasoftware.com/tutorials/hugo/how-to-create-link-with-target-blanks-in-hugo-markdown/
http://tejasgupta.com/posts/addjstohugo/
+ make pages as outlined below
+ add a description about the committees
+ make a map of our geographic area as defined by the locations of ours and other chapters
+ a crew leaders email list signup in addition to a general list
+ flesh this out and trail forks and Luv Trails pages integrations - https://www.mtbproject.com/club/31736/sorba-athens
+ setup a store page once we have merch - https://snipcart.com/blog/hugo-tutorial-static-site-ecommerce
+ add analytics API somewhere - https://developers.google.com/analytics/devguides/reporting/embed/v1

### Get involved page:

+ Link to wish list
+ add some pictures
+ figure out what happened to the SORBA forum

### Wish list page

+ trail tools - list them
+ soil tac
+ a space - see Coldwater Fat Tire folks outfit as an example
+ mini skid
+ help us provide membership perks and rewards
+ board members who don't have a day job

### Sponsors or supporters page

+ list the folks that have always taken care of us or anyone who has at any point in time.
+ make a splash page using the same template as the trails page?
+ GA League
+ all the long term supporters
+ link to logos like this - 
- [![Alt Text](Image URL)](Link URL)
- [![This is my image](/path/to/image.png)]({{< relref "post/B.md" >}})

* * *

# This Site is built with the Academic theme
**Academic** makes it easy to create a beautiful website for free using Markdown, Jupyter, or RStudio. Customize anything on your site with widgets, themes, and language packs. [Check out the latest demo](https://academic-demo.netlify.com/) of what you'll get in less than 10 minutes, or [view the showcase](https://sourcethemes.com/academic/#expo).

- [**Get Started**](#install)
- [View the documentation](https://sourcethemes.com/academic/docs/)
- [Ask a question](http://discuss.gohugo.io/)
- [Request a feature or report a bug](https://github.com/gcushen/hugo-academic/issues)
- Updating? View the [Update Guide](https://sourcethemes.com/academic/docs/update/) and [Release Notes](https://sourcethemes.com/academic/updates/)

## License

Copyright 2017-present [George Cushen](https://georgecushen.com).

Released under the [MIT](https://github.com/sourcethemes/academic-kickstart/blob/master/LICENSE.md) license.

[![Analytics](https://ga-beacon.appspot.com/UA-78646709-2/academic-kickstart/readme?pixel)](https://github.com/igrigorik/ga-beacon)
