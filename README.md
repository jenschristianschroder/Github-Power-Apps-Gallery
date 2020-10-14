# Github-Power-Apps-Gallery
A Power App to display repositories from Github and allow direct deployment to Power Platform environments

# Solution
The solution consist of two components (both are included in the solution file)
1. Github Power Apps Gallery (Canvas App)
2. Github Custom (Custom Connector)

# Installation
Several ways to install in your own environment
1. Clone, Fork or Download the repository and pack a solution based on the source code and import it into your environment
2. Download the release https://github.com/jenschristianschroder/Github-Power-Apps-Gallery/files/5363134/GithubPowerAppsGallery_1_0_0_0.zip and import into your environment

# Setup
There are a couple of things you need to setup for the solution to work
1. Azure AD App Registration for OAuth authentication in the Custom Connector. See this tutorial https://docs.microsoft.com/en-us/powerapps/developer/common-data-service/walkthrough-register-app-azure-active-directory
2. If you don't have one already you need to create a Github organziation. See the github docs https://docs.github.com/en/enterprise-server@2.21/admin/user-management/creating-organizations
3. Create a repository in your organization and add a topic (app, template, component, control, connector) for the in-app filtering to work
4. Add a workflow to the repository to build the solution deploy it. See this repository for a sample workflow https://github.com/jenschristianschroder/CPAL-Site-Inspection-Canvas-App
