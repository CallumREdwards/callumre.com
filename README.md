#  https://callumre.com ![](https://api.netlify.com/api/v1/badges/4bb0de62-4d8e-49a8-8f24-f4cafe52a70a/deploy-status)

This is the repository for my blog. For information on how this website was created visit [this post](https://callumre.com/posts/welcome/).

## Deployment

1.  Make site changes locally
2.  Run `quarto render src` if you'd like to change the output of any embedded computations
3.  Push changes to GitHub

This website is deployed with [netlify](https://www.netlify.com/). It is configured with the [quarto plugin](https://github.com/quarto-dev/netlify-plugin-quarto?tab=readme-ov-file) [here](netifly.toml) (version is specified [here](package.json#L3)) and so it will automatically build and deploy the site remotely on new commits.

## Local Usage

Preview site with `quarto preview src`

Render site with `quarto render src`

-   Rendered output generated at `_site`

-   Results of computations will be re-run and added to `_freeze` for version control

Manual publish `quarto publish src`

-   Options: Quarto Pub, GitHub Pages, Posit Connect, Netlify & Confluence  
