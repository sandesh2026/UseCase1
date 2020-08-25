# ADO-GITHUB PIPELINE Library

This is a sample library used for demonstrating a use case of build/release pipeline using Azure DevOps.
Check out the azure-pipelines.yml file.

The pipeline is set up to execute the following scenarios:

- Commits are pushed: Build & Test only
- Tags are pushed: Build, Test and Release (push to nuget repository)
- Pull requests: Build & Test only
- Daily builds: Build & Test only
