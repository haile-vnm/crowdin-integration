## Read me

To achieve this, you can set up a process that periodically fetches changes from a third-party repository, such as GitHub, and then creates pull requests in AWS CodeCommit. You can use AWS Lambda along with Amazon CloudWatch Events to trigger the Lambda function every 2 minutes. Here's a high-level overview of how you can implement this:

1. **Set up an AWS Lambda Function**:
   - Create a new AWS Lambda function using the AWS Management Console or AWS CLI.
   - Configure the function to be triggered periodically using Amazon CloudWatch Events.
   - In the Lambda function code, write logic to fetch changes from the third-party repository and create pull requests in CodeCommit.
