# Sea Cloud Consulting site

This is the production repository. The canonical site is the multi-page build
on the `main` branch, which is both the repository default and the GitHub Pages
source. Pages publishes the repository root to:

https://mikeblakeduncan.github.io/SeaCloudConsultingSite/

Before editing or previewing the site, confirm the working tree is on `main`
and compare the relevant page with the live URL.

Changes are made and reviewed in the sandbox repository first, then promoted
here:

https://github.com/mikeblakeduncan/SeaCloudConsultingSandbox

The site is not on the live domain yet. Every page carries `noindex` and
`robots.txt` disallows crawling until the DNS cutover, at which point
`CNAME.at-cutover` is renamed to `CNAME` and both of those are reversed.

The `legacy-single-page` branch contains the retired single-page build and is
not the source of the published site.
