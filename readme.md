# Crafted App landing page


## Firebase commands

firebase deploy

## Commands

aws s3 sync . s3://www.craftedapp.com --acl public-read --exclude "readme.md"
aws cloudfront create-invalidation --distribution-id E3MICJULZ2028G --paths "/*"

## Warnings

Removing a CNAME from CloudFront distribution settings without purging the matching CNAME from your DNS records may expose you to a vulnerability, where an imposter may assume control of the CNAME through a different distribution. Please ensure that your DNS records and your distribution CNAME configurations are kept in sync. [craftedapp.com]

