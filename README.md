This is the *Git Repository* for Aitken Audio. All the files of the unbuilt site are kept here. You can edit the files directly from here. When *saved*, in git lingo *comitted*, a new build will be triggered on netlify.com where the site is hosted. This build typically takes a fraction of a second to complete. It may take a little longer for the whole process to carry through to the online site, maybe a minute or two.

[![Netlify Status](https://api.netlify.com/api/v1/badges/907dbca7-1dc0-4704-91bf-316ee18bc5e9/deploy-status)](https://app.netlify.com/sites/aitken/deploys)

## Do I need to update to the latest version of Hugo?

With database driven sites like Wordpress it's very important to keep the Wordpress software up to date for security reasons. This is NOT the case with the Hugo static site generator. Static site are secure intrinsically and much harder to hack without access to this git repository. Whilst new versions of Hugo come out periodically their only use is to add new features. But these are of no use unless the site files here are written to use such new features. Furthermore it's possible, but unlikely, that a new version of Hugo *breaks* the site in some way. So it's safer to keep using the current version and not update to a newer version of Hugo.


## Links

1. [Setting up a Hugo site on Netlify](https://www.netlify.com/blog/2016/09/21/a-step-by-step-guide-victor-hugo-on-netlify/)
2. [Netlify CMS](https://www.netlifycms.org/docs/intro/) - this is the official documentation for the CMS used, Netlify CMS.