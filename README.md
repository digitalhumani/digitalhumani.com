# digitalhumani.com

The public-facing marketing site for DigitalHumani

## Developing

This site consists of static vanilla HTML and does not need to be compiled or built from source. 

The site is deployed onto Netlify via a continuous deployment process which just requires a push to the `main` git branch to publish new changes.


### Prerequisites

In order to develop locally you will need:

- Git
- Node
- NPM


### Installing dependencies and developing locally

```
# Clone this repository
git clone git@github.com:digitalhumani/digitalhumani.com.git

# Move to the project root
cd digitalhumani.com

# install dependencies
npm install

# start local development server
npm run serve

```

### Adding Changes

When adding changes to the site, first open a pull request. Netlify will automatically deploy a separate site to preview the changes in the PR. Information on preview site, including URL, will be automatically added to the PR as a comment. 