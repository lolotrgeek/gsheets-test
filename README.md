# Google Sheets API blog
Uses googlesheets as cms for a javascript single page blog app. Everything is rendered in the browser. 

##Usage
setup google sheets api: make sure write quotas are 0 and key is restricted.

## Notes
Uses localstorage caching to reduce api calls, keeps a copy of the routing table in localstorage. Rebuilds cache when there is a timestamp mis-match.

### TODO
* build - pre-render routes and pages to generate a static site
* tags - routing
* tags - rendering list
* refactor