# static-resources
Just a repository to store some of my static resources to get them with CDN.

## What is this?

The idea is to use [jsDelivr](https://www.jsdelivr.com/?docs=gh) content delivery network to get any static file stored in this repository (I know it's not the best idea but it works)

## How does this work?

* Load any GitHub release, commit, or branch ~

`https://cdn.jsdelivr.net/gh/user/repo@version/file`

Load jQuery v3.2.1 ~

`https://cdn.jsdelivr.net/gh/jquery/jquery@3.2.1/dist/jquery.min.js`

* Use a version range instead of a specific version ~

`https://cdn.jsdelivr.net/gh/jquery/jquery@3.2/dist/jquery.min.js`

`https://cdn.jsdelivr.net/gh/jquery/jquery@3/dist/jquery.min.js`

* Omit the version completely to get the latest one ~

> you should NOT use this in production.

`https://cdn.jsdelivr.net/gh/jquery/jquery/dist/jquery.min.js`

* Add ".min" to any JS/CSS file to get a minified version ~

> If one doesn't exist, jsDelivr generate it for you.

`https://cdn.jsdelivr.net/gh/jquery/jquery@3.2.1/src/core.min.js`

* Add / at the end to get a directory listing ~

`https://cdn.jsdelivr.net/gh/jquery/jquery/`
