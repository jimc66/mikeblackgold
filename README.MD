## Readme for Mike Black Gold site
If you want to update, send me a pull request... 

FYI - I use jekyll (https://jekyllrb.com) for testing my changes locally, so it it's breaks... 


### General setup for those that are interested
- super simple static website using html, css, and bootstrap

- main branch in github is monitored by AWS code deploy

- code deploy will drop the files on an S3 bucket serving the website

- S3 hosted website is then served via cloudfront at https://www.mikeblackgold.com/

- cloudfront is used so that the SSL cert will work with the S3 hosting (but can also help with scale as the word gets out on our MikeBlackGold!!!)




_and this is here under MIT license, not that there is much to it_
