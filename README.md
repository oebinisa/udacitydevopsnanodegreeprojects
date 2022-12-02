# Udacity DevOps Engineer Nanodegree Projects

# Project 1
- Description:
    - Deploy Static Website on AWS 
    
- Steps:
    - Create a public S3 bucket and upload the website files to your bucket.
    - Configure the bucket for website hosting and secure it using IAM policies.
    - Speed up content delivery using AWS’s content distribution network service, CloudFront.
    - Access your website in a browser using the unique CloudFront endpoint.

- Dependencies:
    - Cloud Services
        - Amazon Web Services S3 - Resource hosting and deployments
        - AWS CloudFront - CDN for SPA
        - AWS EKS - Backend API
        - AWS DynamoDB - Persistent Datastore
        - AWS Cognito - User Authentication
    - Performance Tracking and DevOps Tools:
        - AWS CloudWatch - Performance and Health checks
        - Sentry - Bug Reporting
            - Alternates:
            - TBD
        - Google Analytics - Usage Reporting
            - Alternates:
            - Mixpanel
        - Travis (CI/CD)
    - Frameworks:
        - Ionic (Javascript) (Frontend)
        - Node.js (Javascript) (Backend)
