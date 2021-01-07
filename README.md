# Dapla Documentation

Documentation website for the Dapla project.

Served here: https://statisticsnorway.github.io/dapla-docs/

The site is built using the [Hugo](https://gohugo.io/) static site generator and the [Learn theme](https://themes.gohugo.io/hugo-theme-learn/).

The [`gh-pages`](https://github.com/statisticsnorway/dapla-docs/tree/gh-pages) branch contains the published content while the `master` branch holds all Hugo internal files, etc 


## Publishing 

Use the `publish.sh` script in order to build and publish a new version of the documentation site, like so:

```sh
  ./publish.sh
```

Notice that only non-draft documents will be included in the built site. This is intentional. If you mean to include drafts, edit the publish script and 

Reference:

https://gohugo.io/hosting-and-deployment/hosting-on-github/#deployment-of-project-pages-from-your-gh-pages-branch


## Contributing

You will need to have hugo installed. Take a look at [this short quick start tutorial](https://gohugo.io/getting-started/quick-start/) to get started.

### Customization

https://learn.netlify.app/en/basics/style-customization/

### Running locally

Start the Hugo server with drafts rendering enabled. Changes to the content should be automatically reloaded.

```sh
hugo server -D
```
