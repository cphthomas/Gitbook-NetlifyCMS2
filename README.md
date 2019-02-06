---
title: README
date: 2019-02-06T23:51:43.885Z
---
# Jura på dansk

> Dette er skrevet i editor
### Quick Start

Let's get started with Gitbook-NetlifyCMS in three steps.

### 1.[Fork](https://github.com/DemoMacro/Gitbook-NetlifyCMS/fork) on Github

More info: [GitBook Help Center](https://help.gitbook.com/)

### 2.[Deploy](https://app.netlify.com/start/deploy?repository=https://github.com/DemoMacro/Gitbook-NetlifyCMS) to Netlify
```
Build command: gitbook build
Publish directory: _book
```
More info: [A Step-by-Step Guide: GitBook on Netlify](https://www.netlify.com/blog/2015/12/08/a-step-by-step-guide-gitbook-on-netlify/)

### 3.Add the Netlify Identity Widget

You'll need to add this to the ```<head>``` of your CMS index page at /admin/index.html, as well as the ```<head>``` of your site's main index page.We could include the script in your site using Netlify's Script Injection feature;

```html
<script src="https://identity.netlify.com/v1/netlify-identity-widget.js"></script>
```
 Add the following script before the closing body tag of your site's main index page using Netlify's Script Injection feature.

```html
<script>
  if (window.netlifyIdentity) {
    window.netlifyIdentity.on("init", user => {
      if (!user) {
        window.netlifyIdentity.on("login", () => {
          document.location.href = "/admin/";
        });
      }
    });
  }
</script>
```

> You are finished with Gitbook-NetlifyCMS

> Now you can control site content in https://yoursite.netlify.com/admin/

# Afsnit 2
Her er vi på næste side bla bla

# Afsnit 3

Git Gateway
This feature is in beta.

Netlify’s Git Gateway connects your site to Git provider’s API, allowing tools like Netlify CMS to work with content, branches, and pull requests on your users’ behalf.

For a working example using Git Gateway with Netlify Identity service and Netlify CMS to let users edit site content without having accounts on GitHub or GitLab, or repository write privileges, try deploying this repository:

# Afsnit 4

Git Gateway
This feature is in beta.

Netlify’s Git Gateway connects your site to Git provider’s API, allowing tools like Netlify CMS to work with content, branches, and pull requests on your users’ behalf.

For a working example using Git Gateway with Netlify Identity service and Netlify CMS to let users edit site content without having accounts on GitHub or GitLab, or repository write privileges, try deploying this repository:


## Freestat basisversion
Man kan få beregnet deskriptorerne i et utal af programmer heriblandt Freestat basis et gratis program, der kan hentes ved at [klikke her.](https://www.dropbox.com/s/th8q95lf864npie/FREESTATfin.xlsx?dl=1) Freestat basis, kan gennemføre de mest almindelige statistiske analyser. 

## Freestat fuld version
Har du købt adgang til premium abbonnementet, er der en del ekstra analyser, derfor bør du hente Freestat premium versionen. Seneste version af programmet kan [hentes her.](https://www.dropbox.com/s/a2jztexbxfzcli0/FREESTAT.xlsx?dl=1)

Du kan finde flere resourcer bagerst i bogen under materialer ved at [klikke her.](https://s.tepedu.dk/materialer.html)

# Afsnit 5

Git Gateway
This feature is in beta.

Netlify’s Git Gateway connects your site to Git provider’s API, allowing tools like Netlify CMS to work with content, branches, and pull requests on your users’ behalf.

For a working example using Git Gateway with Netlify Identity service and Netlify CMS to let users edit site content without having accounts on GitHub or GitLab, or repository write privileges, try deploying this repository:


## Freestat basisversion
Man kan få beregnet deskriptorerne i et utal af programmer heriblandt Freestat basis et gratis program, der kan hentes ved at [klikke her.](https://www.dropbox.com/s/th8q95lf864npie/FREESTATfin.xlsx?dl=1) Freestat basis, kan gennemføre de mest almindelige statistiske analyser. 

## Freestat fuld version
Har du købt adgang til premium abbonnementet, er der en del ekstra analyser, derfor bør du hente Freestat premium versionen. Seneste version af programmet kan [hentes her.](https://www.dropbox.com/s/a2jztexbxfzcli0/FREESTAT.xlsx?dl=1)

Du kan finde flere resourcer bagerst i bogen under materialer ved at [klikke her.](https://s.tepedu.dk/materialer.html)

