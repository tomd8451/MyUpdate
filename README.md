# Static Site
This repository is a static site consisting of a template from [W3Schools](https://www.w3schools.com/w3css/w3css_templates.asp).

## Getting the code
1) Fork the repo (for the sake of this, assume your github username is jdoe)
2) `git clone https://github.com/jdoe/staticsite.git`
3) `cd staticsite`

## Setting up heroku
1) Create an account https://heroku.com
2) Click the new button in the top right corner, and select "Create new app"
3) Give your app a name (this has to be unique) and click create app
4) Under deployment method, click the "Connect to Github" link
5) Search for staticsite, then click connect for "jdoe/staticsite"
6) Click the "Deploy Branch" at the bottom of the page
7) Open a new tab and navigate to https://{appname}.herokuapp.com

### Making changes
When you edit files locally, to see your changes, run the following commands on the command line:
1) `git add *`
2) `git commit -m "message about what I changed"`
3) `git push`
4) On your heroku dashboard https://dashboard.heroku.com/apps/{appname}/deploy/github, click the "Deploy" button again.
