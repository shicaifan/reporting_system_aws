# Antra SEP java evaluation project
## 1. Setup the environment and make it run.
seted up AWS SNS/SQS/S3 in order to use the async API.
updated <i>application.properties</i> file with AWS IAM account secrets and region.
 
## 2. Understand the structure and details
Look at the [ReportingSystemArchitecture.pdf](./ReportingSystemArchitecture.pdf)

## 3. Make improvement in the code/system level.

0. Add new features like update/delete/report.
1. Improve sync API performance by using multithreading and sending request concurrently to both services.


