# IOTO-webapp
An overview of a project I contributed to during a work term at IOTO.

## What is the IOTO Webapp?
IOTO focuses on collecting publicly available North American political data to use for data vizualization/manipulation. IOTO has built an API so that customers can access this data to use themselves.

My team built a web application from scratch using our internal API to showoff what IOTO is capable of while also illustrating fun visual analytics and statistics. 

As of writing this, you can:
- View legislator/legislature statistics  
- View data visualizations  
- Compare some statistics/information between legislators 
- Search for a specific politican

![goverlytics_demo](https://media.giphy.com/media/dCPma1n5k6Zo5koisz/giphy.gif)
![goverlytics_demo](https://media.giphy.com/media/Hsu7tfSslO9vliSIcI/giphy.gif)

Try it out live: https://goverlytics.com/

***Disclaimer***: The site is no longer maintained by me or my team. The web application may look or function differently than the images/videos in this readme.

## How did I contribute?
Working in a small team of three students, I was responsible for a multitude of things. I worked on:

- Scraping politcal data for our database and API
- Implemented front-end legistlator/legislation pages
- Designed homepage/dashboard and legislator cards
- Created blog/news pages for team to post public articles
- Implemented geolocation feature to display closest legislators using geolocation API
- Utilized webcaching to improve user experience and decrease API requests
- Developed search feature for quick legislator filtering
- Created code pipline to streamline development pushes and deployments using AWS services

## Things we didn't get to/Could've improved
- Implementing login/registration using AuthO and creating a backend database for tracking user data
- More customizable graphs for more user interaction
- Implementing provincial data (as of now the site uses federal data only)
- Implementing like/dislike/follow feature

## Built with
- Javascript/Typescript
- VueJS
- TailwindCSS
- NestJS
- Python
- AWS Lambda, S3, CloudFront, Beanstalk, CodePipeline, CodeDeploy
