# Sea Cloud Consulting site

This is the production repository. It serves **https://seacloudconsulting.com**,
live since August 2026. The `main` branch is both the repository default and the
GitHub Pages source, and Pages publishes the repository root.

## This repository is generated

The HTML here is build output. It is produced by the generator at
`C:\Users\mikeb\AI projects\website\site-generator` and is overwritten by the
next build, so editing a page in this repo will not survive. Change `pages.py`
or `build_site.py` there instead, rebuild, and deploy with
`python deploy.py production`.

A plain `python pages.py` now produces the live configuration: indexable, an
open `robots.txt`, and the `CNAME` file that claims the domain. `PRECUTOVER=1`
produces the hidden variant, which is only for the sandbox.

Changes are made and reviewed in the sandbox repository first, then promoted
here: https://github.com/mikeblakeduncan/SeaCloudConsultingSandbox

The `legacy-single-page` branch contains the retired single-page build and is
not the source of the published site.
