# NodeJs, helloworld API for test propouses.

This is a simple API that returns a welcome message.

## Run your local environment

### Clone the repository
```bash
git clone https://github.com/yosoyfunes/nodejs-helloworld-api.git
```

### Install dependencies
```bash
npm install
```

### Run the tests
```bash
npm test
```

### Start the server
```bash
npm start
```

### Make a request
```bash
curl http://localhost:3000
```
# Test job

To run this pipeline in Jenkins, follow these steps:

## Create a new pipeline job:

Open your Jenkins instance and select "New Item".
Choose "Pipeline" as the project type and enter a name.

## Configure the repository:

In the job configuration, add the URL of this Git repository under the "Source Code Management" section.

## Define the Jenkinsfile:

Ensure Jenkins uses the Jenkinsfile from this repository.
Verify that the Node.js tool is configured in Jenkins under "Global Tool Configuration" with the name nodejs.

## Run the Pipeline:

Once configured, run the job in Jenkins.
Check the console output to ensure that dependencies are installed correctly and that tests run without errors.

## Expected Outcome

When you run the pipeline, Jenkins should successfully complete the Build and Test stages.
If everything is configured correctly, you should see success messages in the Jenkins console output, confirming that dependencies were installed and tests passed.