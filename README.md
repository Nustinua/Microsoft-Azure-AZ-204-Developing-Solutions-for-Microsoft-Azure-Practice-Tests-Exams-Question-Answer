# ⬆️ Microsoft Azure AZ-204 (Microsoft Azure Administrator) Practice Tests Exams Questions & Answers

![Promotional image](images/promotional.png)

## Table of Contents

| No. | Questions |
| --- | --------------------------- |
| 1   | [You are implementing a software as a service (SaaS) ASP.NET Core web service that will run as an Azure Web App. The web service will use an on-premises SQL Server database for storage. The web service also includes a WebJob that processes data updates. Four customers will use the web service. Each instance of the WebJob processes data for a single customer and must run as a singleton instance. Each deployment must be tested by using deployment slots prior to serving production data. Azure costs must be minimized. Azure resources must be located in an isolated network. You need to configure the App Service plan for the Web App. How should you configure the App Service plan?](#you-are-implementing-a-software-as-a-service-saas-aspnet-core-web-service-that-will-run-as-an-azure-web-app-the-web-service-will-use-an-on-premises-sql-server-database-for-storage-the-web-service-also-includes-a-webjob-that-processes-data-updates-four-customers-will-use-the-web-service-each-instance-of-the-webjob-processes-data-for-a-single-customer-and-must-run-as-a-singleton-instance-each-deployment-must-be-tested-by-using-deployment-slots-prior-to-serving-production-data-azure-costs-must-be-minimized-azure-resources-must-be-located-in-an-isolated-network-you-need-to-configure-the-app-service-plan-for-the-web-app-how-should-you-configure-the-app-service-plan) |
| 2   | [A Scrum Team has been working on a product for nine Sprints. A new Product Owner comes in, understanding he is accountable for the Product Backlog. However, he is unsure about his responsibilities. Which two activities are part of the Product Owner role according to Scrum? (choose two)](#a-scrum-team-has-been-working-on-a-product-for-nine-sprints-a-new-product-owner-comes-in-understanding-he-is-accountable-for-the-product-backlog-however-he-is-unsure-about-his-responsibilities-which-two-activities-are-part-of-the-product-owner-role-according-to-scrum-choose-two) |
| 3   | [User documentation is part of your definition of "Done". However, there aren't enough technical writers for all teams. Your Development Team doesn't have a technical writer. What should you do?](#user-documentation-is-part-of-your-definition-of-done-however-there-arent-enough-technical-writers-for-all-teams-your-development-team-doesnt-have-a-technical-writer-what-should-you-do) |
| 4   | [You are the Scrum Master for four Scrum Teams working from the same Product Backlog. Several of the developers come to you complaining that work identified for the upcoming two Sprints will require full-time commitment from a technical specialist who is external to the teams. What are two key concerns for the Scrum Master to take into account in this situation? (choose two)](#you-are-the-scrum-master-for-four-scrum-teams-working-from-the-same-product-backlog-several-of-the-developers-come-to-you-complaining-that-work-identified-for-the-upcoming-two-sprints-will-require-full-time-commitment-from-a-technical-specialist-who-is-external-to-the-teams-what-are-two-key-concerns-for-the-scrum-master-to-take-into-account-in-this-situation-choose-two) |
| 5   | [The Product Backlog is ordered by:](#the-product-backlog-is-ordered-by) |
| 6   | [What happens if the Development Team cannot complete its work by the end of the Sprint?](#what-happens-if-the-development-team-cannot-complete-its-work-by-the-end-of-the-sprint) |
| 7   | [Which topics should be discussed in the Sprint Review?](#which-topics-should-be-discussed-in-the-sprint-review) |
| 8   | [A member of the Development Team takes the Scrum Master aside to express his concerns about data security issues. What should the Scrum Master do?](#a-member-of-the-development-team-takes-the-scrum-master-aside-to-express-his-concerns-about-data-security-issues-what-should-the-scrum-master-do) |
| 9   | [What does it mean for a Development Team to be cross-functional?](#what-does-it-mean-for-a-development-team-to-be-cross-functional) |
| 10  | [Sprint burndown charts are an efficient tracking tool, because they show:](#sprint-burndown-charts-are-an-efficient-tracking-tool-because-they-show)   |


### You are implementing a software as a service (SaaS) ASP.NET Core web service that will run as an Azure Web App. The web service will use an on-premises SQL Server database for storage. The web service also includes a WebJob that processes data updates. Four customers will use the web service. Each instance of the WebJob processes data for a single customer and must run as a singleton instance. Each deployment must be tested by using deployment slots prior to serving production data. Azure costs must be minimized. Azure resources must be located in an isolated network. You need to configure the App Service plan for the Web App. How should you configure the App Service plan?

![Question 1](images/question1.jpeg)

- [ ] Number of VM instances: 2. Pricing tier: Isolated.
- [ ] Number of VM instances: 8. Pricing tier: Standard.
- [ ] Number of VM instances: 16. Pricing tier: Premium.
- [x] Number of VM instances: 4. Pricing tier: Isolated.
- [ ] Number of VM instances: 4. Pricing tier: Consumption.

### You are a developer for a software as a service (SaaS) company that uses an Azure Function to process orders. The Azure Function currently runs on an Azure Function app that is triggered by an Azure Storage queue. You are preparing to migrate the Azure Function to Kubernetes using Kubernetes-based Event Driven Autoscaling (KEDA). You need to configure Kubernetes Custom Resource Definitions (CRD) for the Azure Function. Which CRDs should you configure?

![Question 2](images/question2.jpeg)

- [x] Box 1, CRD type: Deployment. Box 2, CRD type: ScaledObject. Box 3, CRD type: Secret.
- [ ] Box 1, CRD type: Secret. Box 2, CRD type: ScaledObject. Box 3, CRD type: Secret.
- [ ] Box 1, CRD type: TriggerAuthentication. Box 2, CRD type: Deployment. Box 3, CRD type: Secret.
- [ ] Box 1, CRD type: Deployment. Box 2, CRD type: ScaledObject. Box 3, CRD type: TriggerAuthentication.

### You are creating a CLI script that creates an Azure web app and related services in Azure App Service. The web app uses the following variables. You need to automatically deploy code from GitHub to the newly created web app. How should you complete the script?

![Question 3 part 1](images/question3_1.png)
![Question 3 part 2](images/question3_2.jpeg)

- [ ] Box 1: az webapp. Box 2: az webapp create. Box 3: git clone $gitrepo. Box 4: az webapp. Box 5: --plan $webappname
- [x] Box 1: az appservice plan create. Box 2: az webapp create. Box 3: --plan $webappname. Box 4: az webapp deployment. Box 5: --repo-url $gitrepo --branch master --manual-integration
- [ ] Box 1: az appservice plan create. Box 2: az webapp deployment. Box 3: --plan $webappname. Box 4: az webapp deployment. Box 5: --repo-url $gitrepo --branch master --manual-integration
- [ ] Box 1: az group delete. Box 2: az webapp create. Box 3: git clone $gitrepo. Box 4: az appservice plan create. Box 5: git clone $gitrepo

### You develop a software as a service (SaaS) offering to manage photographs. Users upload photos to a web service which then stores the photos in Azure Storage Blob storage. The storage account type is General-purpose V2. When photos are uploaded, they must be processed to produce and save a mobile-friendly version of the image. The process to produce a mobile-friendly version of the image must start in less than one minute. You need to design the process that starts the photo processing. Solution: Trigger the photo processing from Blob storage events. Does the solution meet the goal?

- [ ] Yes.
- [x] No.

### You develop and deploy an Azure App Service API app to a Windows-hosted deployment slot named Development. You create additional deployment slots named Testing and Production. You enable auto swap on the Production deployment slot. You need to ensure that scripts run and resources are available before a swap operation occurs. Solution: Update the web.config file to include the applicationInitialization configuration element. Specify custom initialization actions to run the scripts. Does the solution meet the goal?

- [x] Yes.
- [ ] No.

### You develop and deploy an Azure App Service API app to a Windows-hosted deployment slot named Development. You create additional deployment slots named Testing and Production. You enable auto swap on the Production deployment slot. You need to ensure that scripts run and resources are available before a swap operation occurs. Solution: Enable auto swap for the Testing slot. Deploy the app to the Testing slot. Does the solution meet the goal?

- [ ] Yes.
- [x] No.

### You develop and deploy an Azure App Service API app to a Windows-hosted deployment slot named Development. You create additional deployment slots named Testing and Production. You enable auto swap on the Production deployment slot. You need to ensure that scripts run and resources are available before a swap operation occurs. Solution: Disable auto swap. Update the app with a method named statuscheck to run the scripts. Re-enable auto swap and deploy the app to the Production slot. Does the solution meet the goal?

- [x] Yes.
- [ ] No.

### You develop a software as a service (SaaS) offering to manage photographs. Users upload photos to a web service which then stores the photos in Azure Storage Blob storage. The storage account type is General-purpose V2. When photos are uploaded, they must be processed to produce and save a mobile-friendly version of the image. The process to produce a mobile-friendly version of the image must start in less than one minute. You need to design the process that starts the photo processing. Solution: Convert the Azure Storage account to a BlockBlobStorage storage account. Does the solution meet the goal?

- [ ] Yes.
- [x] No.

### You are developing an Azure Web App. You configure TLS mutual authentication for the web app. You need to validate the client certificate in the web app.

![Question 9](images/question9.jpeg)

- [ ] Client certificate location: Client cookie. Encoding type: URL.
- [ ] Client certificate location: HTTP message body. Encoding type: Base64.
- [ ] Client certificate location: HTTP request header. Encoding type: Unicode.
- [x] Client certificate location: HTTP request header. Encoding type: Base64.

### You are developing a Docker/Go using Azure App Service Web App for Containers. You plan to run the container in an App Service on Linux. You identify a Docker container image to use. None of your current resource groups reside in a location that supports Linux. You must minimize the number of resource groups required. You need to create the application and perform an initial deployment. Which three Azure CLI commands should you use to develop the solution?

![Question 10](images/question10.png)

- [ ] Box 1: az webapp create. Box 2: az appservice plan create. Box 3: az group create.
- [ ] Box 1: az appservice plan create. Box 2: az group create. Box 3: az group update.
- [x] Box 1: az group create. Box 2: az appservice plan create. Box 3: az webapp create.
- [ ] Box 1: az appservice plan create. Box 2: az webapp create. Box 3: az webapp update.
