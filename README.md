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

+ links in new tab with js:
https://code.luasoftware.com/tutorials/hugo/how-to-create-link-with-target-blanks-in-hugo-markdown/
http://tejasgupta.com/posts/addjstohugo/
+ make pages as outlined below
+ add a subheading for the board section 'volunteer board' or something or some more description
+ make a map of our geographic area as defined by the locations of ours and other chapters
+ a crew leaders email list signup in addition to a general list
+ flesh this out and trail forks and Luv Trails pages integrations - https://www.mtbproject.com/club/31736/sorba-athens
+ setup a store page once we have merch - https://codeburst.io/how-to-build-host-a-very-fast-hugo-static-e-commerce-site-3554ba0eb802
+ add analytics API somewhere - https://developers.google.com/analytics/devguides/reporting/embed/v1

### Join / Membership page

+ make a Join page with more membership info and remove the auto renew details from get involved

### Get involved page:

+ <iframe src="https://widget.goldenvolunteer.com/#list/3aac45ac80d726cbaf8aee2ac53fa20d603e5e968a01727c9dc4b780339b1e5b&showAllTimeslots=true" frameborder="0" width="600" height="400"></iframe>
+ Link to wish list
+ add some pictures
+ figure out what happened to the SORBA forum

### Wish list page

+ trail tools - list them
+ soil tac
+ a space for a club house - see Coldwater Fat Tire folks outfit as an example
+ mini skid
+ help us provide membership perks and rewards
+ board members who don't have a day job

### Sponsors or supporters page

+ list the folks that have always taken care of us or anyone who has at any point in time.
+ where could we feature sponsor logos? probably on a splash page
+ GA League

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
