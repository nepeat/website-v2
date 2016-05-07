# website-v2

## Basic info

For now its just plain HTML, CSS and JS. We didn't know who was familiar with what, so we decided to go simple for now since we're on such a tight schedule. After February when we have time for meetings and to talk things through we will put it on a proper platform.

## Setting up development environment
 - Install Node 4.x
 - Install Surge (optional)
 - Make sure you can call npm in a command line and see a response. If you don't, make sure the path to npm is added to the environment variables
 - `npm install` - Run the instalation script
 - `npm run dev` - Run the dev server so that you can see your changes in real time
 - View your changes here: `127.0.0.1:8080`


## Building the site
The site uses [nunjucks](http://mozilla.github.io/nunjucks/) for templating. Pages (HTML files that need to be compiled and uploaded) go in `pages/`, includes, and other non-uploadable HTML files go in `includes/`. Javascript and CSS go in `js/` and `styles/`, respectively, and assets go in `assets/`. To build the site, first make sure you've installed everything with `npm install`, then build it with `npm run build` (this requires node and npm). The `build/` folder will be emptied, `styles/`, `js/`, and `assets/` folders will be recursively copied in to `build/`, and every `.html` file in `pages/` will be templated and copied too. The build directory is *_not_* checked in to git, and is therefore gitignored.

During development, just run `npm run dev`. It will start a server on [localhost:8080](http://localhost:8080), and whenever something changes, re-build and automagically reload the page. Automagically.

If you have questions ask them on Slack #webdev. Apparently I'm (Keksike) running the development at this moment, so you can PM me too.

## npm Commands
`npm run dev` - Run the dev server for automatic template compiling

`npm run build` - Compile the templates into html

`npm run deploy:dev` - Deploy to beta url (assuming you have Surge permission)

`npm run deploy:prod` - Deploy to production url (assuming you have Surge permission)


## Work assignments
These will probably change, and we will work together on some.

### Pages
* Frontpage ("rloop"): Keksike
* Hyperloop (mostly done): -
* Team (mostly done): -
* News: ImAPyromaniac
* Shop: KachanAleksey
* Contact: -

