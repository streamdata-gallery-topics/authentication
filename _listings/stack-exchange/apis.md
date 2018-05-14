---
name: Stack Exchange
description: Stack Exchange is a network of question and answer websites on diverse
  topics in many different fields, each site covering a specific topic, where questions,
  answers, and users are subject to a reputation award process. The sites are modeled
  after Stack Overflow, a forum for computer programming questions that was the original
  site in this network. The reputation system is designed to allow the sites to be
  self-moderating.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/253_logo.png
x-kinRank: "8"
x-alexaRank: ""
tags:
- Streamrank
- Stack
- Question Answer
- Plug in
- My API Stack
- Media
- Imports
- Content
- Code
- Citations
- Answers
created: "2018-05-12"
modified: "2018-05-12"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/authentication/master/_listings/stack-exchange/apis.md
specificationVersion: "0.14"
apis:
- name: Stack Exchange De-Authenticate Token
  description: "Passing valid access_tokens to this method causes the application
    that created them to be de-authorized by the user associated with each access_token.
    This will remove the application from their apps tab, and cause all other existing
    access_tokens to be destroyed.\n \nThis method is meant for uninstalling applications,
    recovering from access_token leaks, or simply as a stronger form of /access-tokens/{accessTokens}/invalidate.\n
    \nNothing prevents a user from re-authenticate to an application that has de-authenticated
    itself, the user will be prompted to approve the application again however.\n
    \n{accessTokens} can contain up to 20 access tokens. These are obtained by authenticating
    a user using OAuth 2.0.\n \nThis method returns a list of access_tokens."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/253_logo.png
  humanURL: https://stackexchange.com/
  baseURL: https://api.stackexchange.com//2.2
  tags: Authentication
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/authentication/master/_listings/stack-exchange/apps-accesstokens-de-authenticate-get.md
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/authentication/master/_listings/stack-exchange/apps-accesstokens-de-authenticate-get-postman.md
x-common:
- type: x-authentication
  url: https://api.stackexchange.com/docs/authentication
- type: x-base
  url: https://api.stackexchange.com/
- type: x-blog
  url: http://stackexchange.com/blogs
- type: x-blog-rss
  url: http://blog.stackoverflow.com/feed/
- type: x-crunchbase
  url: http://www.crunchbase.com/company/stack-exchange
- type: x-developer
  url: http://api.stackexchange.com/
- type: x-email
  url: team+api@stackexchange.com
- type: x-error-codes
  url: https://api.stackexchange.com/docs/error-handling
- type: x-github
  url: https://github.com/StackExchange
- type: x-javascript-sdk
  url: https://api.stackexchange.com/docs/js-lib
- type: x-privacy
  url: https://stackexchange.com/legal/privacy-policy
- type: x-rate-limits
  url: https://api.stackexchange.com/docs/throttle
- type: x-selfservice-registration
  url: https://stackapps.com/users/login?returnurl=/apps/oauth/register
- type: x-support
  url: https://stackexchange.com/about/contact
- type: x-terms-of-service
  url: http://stackexchange.com/legal/api-terms-of-use
- type: x-twitter
  url: https://twitter.com/StackExchange
- type: x-website
  url: https://stackexchange.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---