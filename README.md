# Hello, Express!

This is a demo Express app for building and deploying an app using AWS CodePipeline.

1. Download the source code on your local machine.
2. Zip the artifact to create ibt-codebuild.zip
3. Create S3 bucket for uploading the input files for build artifact.
4. Create a new build project
a. Enter project name.
b. Enter source provider
c. Enter environment - Amazon Linux 2 x86_64 standard:3.0
https://docs.aws.amazon.com/codebuild/latest/userguide/available-runtimes.html
d. Enter buildspec
e. Enter Artifacts.
5. Build your project.
