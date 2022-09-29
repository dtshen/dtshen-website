# dtshen-website

Personal website code forked from jeckyll now
Dependencies
Ruby
Jekyll

Build
```
cd src
jekyll serve
```
Syncing to S3
```
aws s3 sync ./_site/ s3://dtshen.com
```