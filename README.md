# aws-lambda_cd

This is an AWS CloudFormation template that creates a CodePipeline that pulls changes from a CodeCommit repository and deploys it as a Lambda function. Upon every new commit to the repository, the pipeline will update the code in the target Lambda function.

After the Stack is built, clone the CodeCommit repository and place a file with the same name as the repo (\<repo name\>.py) to its root. Then push the changes back to it to initialise the process.
