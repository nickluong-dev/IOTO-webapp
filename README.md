# IOTO-webapp
An overview of a project I contributed to during a work term at IOTO.

## What is the IOTO Webapp?
IOTO focuses on collecting publicly available North American political data to use for data vizualization/manipulation. IOTO has built an API so that customers can access this data to use themselves.

My team built a web application from scratch using our internal API to showoff what IOTO is capable of while also illustrating fun visual analytics and statistics. As of writing this, you can view legislator/legislature statistics, view data visualizations, compare some statistcs between legislators, search for a specific politican, and view bill statistics/information.

![goverlytics_demo](https://media.giphy.com/media/dCPma1n5k6Zo5koisz/giphy.gif)
![goverlytics_demo](https://media.giphy.com/media/Hsu7tfSslO9vliSIcI/giphy.gif)

Try it out live: https://goverlytics.com/

***Disclaimer***: The site is no longer maintained by me or my team. The web application may look or function differently than the images/videos in this readme.

## How did I contribute?
Working in a small team of three students, I was responsible for a multitude of things. I worked on:

- Scraping politcal data for our database and API
- Implementing legistlator/legislation pages
- Implementing homepage/dashboard
- Implementing news blog to display posts from medium.com
- Implementing geolocation feature to display close by legislators
- Implementing webcaching to improve user experience and decrease API requests
- Implementing search feature
- Implemented Codepipeline to streamline development pushes and deployments

## Things we didn't get to/Could've improved
- Implementing login/registration using AuthO and creating a backend database for tracking user data
- More customizable graphs for more user interaction
- Implementing provincial data (as of now the site uses federal data only)

## Built with
- Javascript/Typescript
- VueJS
- TailwindCSS
- NestJS
- Python
- AWS Lambda, S3, CloudFront, Beanstalk, CodePipeline
