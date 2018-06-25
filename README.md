# Fully-Serverless-Video-Sharing-Site-Using-AWS-Lambda-and-Much-More
Fully serverless video sharing site on AWS using Lambda, API Gateway, S3, Elastic Transcoder, Auth0, Firebase, and Node.js

Features of this project:
* User authentication
* Large file video uploads
* A transcoding pipeline that transcodes uploaded videos to web-friendly 480p mp4 format
* Push-based, event-driven updates to the web-site (users see new videos automatically with no browser refreshes needed)
* The ability to play video files hosted on scalable cloud storage

Steps in this project:
1)  Created a serverless transcoding pipeline in AWS
* Created buckets for uploads and transcoded files in S3
* Created IAM role for Lambda and added permissions
* Set up Elastic Transcoder pipeline
* Created Lambda function
* Established Lambda trigger

2)  Set up the web site & user authentication (Auth0)
* Created application and changed settings on Auth0 website
* Added website files

3)  Created an API in the AWS cloud & authenticate calls
* Created new Lambda function to pull user's profile
* Created API and deployed it
* Set up a custom authorizer between API Gateway and Lambda function
* Updated website JavaScript

4)  Enabled browser-based uploads of video files to S3
* Created IAM user to allow front-end video uploads
* Created new Lambda function to set upload policy
* Established API resource and method to allow function invocation
* Added CORS configuration

5)  Connected Firebase to list videos
* Created Firebase database and changed "Read" rules to true
* Added sample video data 
* Created Firebase service account to allow communication with Lambda
* Updated Lambda function

NOTE: This project is in progress and all functionality may not yet be included at this time
