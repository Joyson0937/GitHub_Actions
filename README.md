# GitHub_Actions

Topics:
 1. What is GitHub Actions
 2. How to use - Step by Step DEMO
 3. A demo workflow file - how to create, run and check results
 4. Terms: Workflows, Events, Jobs, Steps


GitHub Actions
Feature in GitHub to create custom Automated Workflows
automate SDLC workflows
implement CI CD DevOps

 **DEMO**
  Step 1 - Signup and Login to GitHub.com
  Step 2 - Create a new Repository
  Step 3 - In the repo create a folder .github/workflows
  Step 4 - In the folder create a YAML file with .yml extension
  Step 5 - Add the content of the workflow in the file
  Step 6 - Commit and push the changes
  Step 7 - Goto Repo main page and click the “Actions” tab
  Step 8 - Select the workflow from left sidebar and check the logs and results

 **Terms:**
   WORKFLOW: collection of jobs, defined in a YAML file
   name:
   EVENTS: any activity in the repo that can trigger a workflow 
   on:
   JOBS: collection of steps
   jobs:
   STEPS: actions to be taken, commands, scripts
   steps:
   Chain Jobs - :needs

Comparing with Jenkins
Advantages of GitHub Actions over Jenkins
Hosting: Jenkins is self-hosted, meaning it requires its own server to run, while GitHub Actions is hosted by GitHub and runs directly in your GitHub repository.

User interface: Jenkins has a complex and sophisticated user interface, while GitHub Actions has a more streamlined and user-friendly interface that is better suited for simple to moderate automation tasks.

Cost: Jenkins can be expensive to run and maintain, especially for organizations with large and complex automation needs. GitHub Actions, on the other hand, is free for open-source projects and has a tiered pricing model for private repositories, making it more accessible to smaller organizations and individual developers.

Advantages of Jenkins over GitHub Actions
Integration: Jenkins can integrate with a wide range of tools and services, but GitHub Actions is tightly integrated with the GitHub platform, making it easier to automate tasks related to your GitHub workflow.
In conclusion, Jenkins is better suited for complex and large-scale automation tasks, while GitHub Actions is a more cost-effective and user-friendly solution for simple to moderate automation needs.
