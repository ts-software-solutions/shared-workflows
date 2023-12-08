# shared-workflows
A repository to hold the shared workflows that will run necessary GitHub actions

## How to use

This is a repository to hold all the workflows that will be shared across applications in an organization. The workflows in this repository currently are to support creating a workflow for deploying a MuleSoft application to MuleSoft's CloudHub 1.0. 

To initiate this workflow you would have to clone this repository, add a workflow file in your project's repository to reference this repository's `/github/workflows/main.yml` file with a trigger. 

You can reference the [mule-sample-project](https://github.com/ts-software-solutions/mule-sample-project) in this organization to see how the workflow is referenced. 

## Contact

Tanner Sherman