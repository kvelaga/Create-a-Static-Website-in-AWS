# Create-a-Static-Website-in-1-2-3

The cloud is perfect for hosting static websites that only include HTML, CSS, and JavaScript files that require no server-side processing.
In this project, a static website has been deployed to AWS. create a S3 bucket and upload the website files to your bucket.

### Steps to setup:
1. An S3 bucket is created and configured the bucket for website hosting and secured it using IAM policies.
2. Next, content delivery is sped up using AWS’ content distribution network service, CloudFront.
3. Lastly, you will be able to access the website in a browser using the unique CloudFront endpoint.

Services and Tools used:

### Cloud Services
* Amazon Web Services S3 - Resource hosting and deployments
* AWS CloudFront - CDN for SPA
* AWS EKS - Backend API
* AWS DynamoDB - Persistent Datastore
* AWS Cognito - User Authentication
### Performance Tracking and DevOps Tools:
* AWS CloudWatch - Performance and Health checks
* Sentry - Bug Reporting

* Google Analytics - Usage Reporting
### Alternates:
* Mixpanel
* Travis (CI/CD)

### Frameworks:
* Ionic (Javascript) (Frontend)
* Node.js (Javascript) (Backend)
