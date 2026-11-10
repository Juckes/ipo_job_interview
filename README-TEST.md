# Pre Interview Tech Exercise

Please apply even if you have problems with the exercise. Training can be made available for the specific tools.

## Prerequisites 

Use this simple sample app for the pipeline: intellectual-property-office/sample-unit-testing-using-dotnet-test: Sample dotnet app used for onboarding by DevOps Enablement team leads (github.com). · Clone URL here (or fork / download as preferred): https://github.com/intellectual-property-office/sample-unit-testing-using-dotnet-test.git

This exercise should take between 1 – 3 hrs


## Brief

Review the usage information in the sample. The code can be built and tested locally with commands in readme.md.

Create a CI pipeline for the sample application above which was written by a developer and that needs to be automated in a pipeline. The pipeline should include the following parts:

*This means that the CI pipeline needs to build the app, the use of english is not great to me such as 'automated in a pipeline, that means to build it I assume?*

*What exactly is meant by unit test - could this be a thing such as terraform validation or some sort of validation for the App they wnat to be built, should it be security checks, is that a unit test?*

*I assume for task 3, you could simply use bash to write that message as the agent will be using Linux?*

1. Build
2. Test (Unit Test). Ensure the test results for the pre-existing Unit Tests are available in the pipeline GUI
3. Write a message to the Pipeline log that states ‘TODO – Deployment’

## Tech:

· Repo: The sample code should be stored in your own repo, do not reference the example repo directly. Your repo should be stored in Azure DevOps Repos, GitHub or as preferred
· Pipeline: Create pipeline in Azure DevOps YAML Pipelines (preferred) or GitHub
· Scripting: Use a scripting language to complete 1 of the parts above

## Submit Pipeline / Logs to IPO

· The above YAML pipeline you create, and pipeline run raw log .zip should be submitted to IPO as a .zip
· In interview, be ready to share screen to demo if possible (do not need to if not practical)
· There will be an extension to the exercise in the interview (you are free you use any preferred tools), sharing your screen to show your working
