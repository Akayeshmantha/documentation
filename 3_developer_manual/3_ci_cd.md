#CI/CD

NIMBLE uses Jenkins for CI/CD.

**How to setup and configure Jenkins**
Follow the standard installation of the latest LTS version: [https://www.jenkins.io/download/](https://www.jenkins.io/download/)

**List of required plugins**
NIMBLE is using the GitHub Integration Plugin and GitHub Pull Request Builder in order to trigger builds for every repository in the organization.
Futhermore, SSH Agent Plugin and SSH Build Plugin are required to connect to the according VMs.
Optionally, Email Extension Plugin and Global Slack Notifier Plugin can be used to integrate notifications.

**Explanation of Jenkinsfile settings**
Each repository holds a Jenkinsfile in its root folder.
Usually those are designed in the following manner:
- Trigger a build and deploy to the Staging environments when pushing changes to the staging branch
- Trigger a build when pushing to the master branch
- Trigger a build and deploy to the Production environments when pushing a new tag number (release)