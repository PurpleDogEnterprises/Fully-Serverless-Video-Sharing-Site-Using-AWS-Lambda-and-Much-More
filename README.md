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

NOTE: This project is in progress and all functionality may not yet be included at this time
