# Brothers With Christ - Web Application
[![Netlify Status](https://api.netlify.com/api/v1/badges/1bde5310-c34d-494f-9b65-d426970d204f/deploy-status)](https://app.netlify.com/sites/bwc/deploys) &nbsp; &nbsp; &nbsp; ![GitHub issues](https://img.shields.io/github/issues/apmcknight/bwc-org)

# Usage Documentation
## Usage for Admins
If you’re an admin, and need to make changes to the site — please login to the admin at brotherswithchrist.org/admin <br/>
Otherwise you may contact the projects owner, Adam McKnight, by e-mail: adampmcknight@gmail.com or by phone.

## Usage for Developers
If you’re a developer working on this project, here’s documentation for this project.

### Project Deployment
Brothers With Christ’s Web Application is deployed to Netlify through git via GitHub. The CMS is also hosted through a git gateway. To access the admin via the Netlify deployment subdomain go to: www.bwc.netlify.com/admin 

**Note:** You’ll need to have valid credentials to login to the account, please contact the owner to get access.

*Deployment Target*
The deployment target is to the Master branch. A PR must be approved before a new deployment can be merged into production. If you are making changes to the project’s source, please be sure to create and checkout on a new branch to make your changes. 

**Note:** The master branch has write protections attributed to it, and will require 1 PR review by the owner before the request can be merged into the master/production branch.


### Project Dependencies
This Web project was built using Jekyll, as such this project requires various dependencies to run on your local machine as well as on the deployment instance. 

If you don’t have Jekyll installed locally, then you must install it by following their documentation [here](https://jekyllrb.com/docs/). Otherwise, you should edit this projects source files.

Once Jekyll is installed, `cd` into the project file and  run:  `npm i` or `npm install` to install any project-level dependencies. This project does not use yarn — you may use yarn, but please remove the yarn-lock and other associated yarn files before you submit a new pull request.


### Project Data & Content Management System
This project utilizes the Netlify [Content Management System](https://www.netlifycms.org/)
You can review the docs for Jekyll deployments [here](https://www.netlifycms.org/docs/jekyll/).   

As the project data model is still being designed and architected for the project; Documentation will be written once it’s finished.


### Starting a local Copy
Once all dependencies are installed, you can run jekyll serve to spin-up a development server.  /

**Note:** Access to the CMS  will be Unavailable in your local environment


## Contributions
Although this is not an open project, we invite you to suggest changes via the Issue tracker!

## Copyright Notice
Project’s copy, written word, photographs, names, and the like are under Copyright by their respective owners. Code used within project may not be under copyright by the organization, just by the original copyright owner. 

## Project Owner
Adam McKnight <br/>
**GitHub:** www.github.com/apmcknight <br/>
**Site:** www.mcknight.netlify.com <br/>
**Primary Contact:** adampmcknight@gmail.com <br/>

