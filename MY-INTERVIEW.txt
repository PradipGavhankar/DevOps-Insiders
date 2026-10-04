Introduce yourself
How you will create Docker File
Terraform Modules
how terrform modules communicates with each other
Kubernetes Deployment Strategies
How you will integrate Github and one more tool with Kubernetes
How you can make CI/CD pipeline light weight
Which is better Amazon RDBMS or Mongo DB(Nosql)
How you will scale up and scale down traffic
===========================================================================================

Insight Interview: 20-05-2026

1.Any major activity you have performed recently(based on creating azure resource).
2. Any knowledge of AVD
3. Diff between domain admin and enterprise admin role
4. have you done any migration from on-premises to cloud
5. Suppose VM i need to migrate. what is process to migrate it.
6. Azure Sql Server, DB, azure vault. Client want to automate a billing count and get the data automated so that they can get the data in form of report every month.
7. client want to monitor azure VM
8. state lock, no one able to run anything. what you will do . command to do it
9. suppose someone has change the nsg rule from azure portal which was created from terraform , terraform shows drift. what you will do?
10. and what you will do to prevent this to happen in future?
11. after deployment, new release there is application gateway error 502 or 503. what will you do to troubleshoot and fix?
12. you have to design blue-green deployment pipeline on AKS with safe traffic switching. How will you do?
13. azure configured and getting noisy false -positive alerts for list of applications in prod using azure monitor. the first positive alert you have to rectify and get it corrected. what steps you will follow? ALERT FINE-TUNING
14. can you share your screen and write a web application deployment code using terraform
15. Write a DOCKER file to build any application
16. Difference b/w subnet and a gateway subnet
17. establish connection between two VNET. Is it possible to peer a vent across different subscription?
18. I want to restrict a inbound and out bound traffic for all the n/w which we have under my tenant. suitable way to implement it?
19. diff b/w load balancer and application gateway?
20. diff b/w vertical abd horizontal scaling
21. we have a vm i want to access it securely. different method to do it?
22. implement a solution , i want to have all my employees access the client env securely as they are working remotely. best solution?
23. site to site and point to site?
24. MS entra id? Diff b/w static group and dynamic group?
25. i have couple of user. I have implemented MFA and want to exclude some of the user's MFA . How i can do it?
26. have you worked on On-premises active directory/legacy AD?
27. AVD. difference between Pooled and Personal Host Pools?

==============================================================================================

MultiCloudForU-28-05-2026

1. Explain your experience with Azure Devops YAML Pipelines?
2. How would you deploy react application to Azure Static Web Apps?
3. Difference between Azure Static Web Apps and Azure app Service?
4. How do you secure Secrets in CI/CD pipelines?
5. What are managed identities in Azure?
6. How would you implement PR validation?
7. Explain Multi-Stage Deployment pipeline.
8. How do you implement rollback strategies?
9. What is IAC?
10. How do you monitor Azure application?
11. What quality gates would you implement?
12. Explain Azure Container Apps?

================================================================================================================

MCCAIN Interview 29-05-2026

1. What is your understanding of Landing Zone? And how we implement it within the overall architecture. What is the role of LZ?
2. What services, tools and technologies we provision through landing zone? 
3. Describe Landing Zone based on your current architecture?
4. What do you understand by terraform workflows?
5. What is state file in terraform?
6. What is diff between root modules and child module?
7. Have you used terraform Cloud or Terraform Vanilla?
8. You are maintaining state file in Azure or Terraform cloud?
9.  Have you created any private modules based on your need?
10. What all major resources you have created in terraform?
11. What best practices you follow or what all things you include(strategies) while creating a firewall? 
12. Lifecycle Block?
13. Meta-Arguments?
14. Exposure onto Kubernetes?
15. Application hosted on Kubernetes or monolithic, users hitting and getting 503. Steps you will take to troubleshoot? If backend is fine then what will you check ? How and what things you will check on Application gateway for this issue ?
16. what all we need to check in backend for 503?
17. What CI/CD tool used in your deployment?
18. have you ever worked on workflows on GITHUB Actions ?
19. Basic flow of CI/CD workflows and pipeline you have created using security and other checks ?
20. Have you worked with any monitoring tool?
21. Do you know how to set-up end to end implementation of any monitoring tool?
22. How the new-relic or any other monitoring tool got the access to your application log?
23. Where we are storing the logs on monitoring tools, so that someone wants to check logs for 3 days back?
24. Elaborate how we are storing that data from the log side and what exactly we call it as ?

=====================================================================================================================

MultiCloudForU Second Round 01-06-2026
* How do you ensure or insist that developers do not bypass security scans as a DevSecOps engineer?
* What are the most common project issues you have handled?
* Walk me through the P1 and P2 (Priority 1 & 2) incidents you have gone through.
* What strategies do you use for environment-specific variables and secrets?
* What versioning strategies do you implement in your project?
* Which tools did you use for system monitoring?
* How do you integrate OpenCost for cost reduction?
* How do you design a disaster recovery strategy for a multi-tier application?
* What is the current CI/CD pipeline flow used in your project?
* Explain reusable modules and how you handle their versioning and sharing across environments.
* How do you isolate development, staging, and production environments in Terraform?
* What are the risks associated with production isolation strategies in Terraform?
* How do you handle secrets in your Terraform state file to ensure they are not exposed?
* Describe your experience with Terratest.
* Can you explain the "zero public architecture" mentioned in your CV?
* How do you secure communication and connectivity for an Azure App Service?
* What is the difference between Azure Application Gateway and Azure Front Door?
* Explain the Git branching strategies you follow.
* Have you used Azure Managed Identities in your deployment pipelines?
* When setting up an Azure Landing Zone, what are the core governance policies?
* How do you integrate tools like tfsec and tflint into your workflow?


======================================================================================================================

Cognizant 03-06-2026

1. New Relic setup you did on your now? What was it for APM or log management. Where logs were storing? 
2. Security tools you used? Apart from terraform security tool any other security tool for vulnerability check like SAST and DAST? Difference between SAST and DAST?
3. How backup and DR works in your environment? 
4. What kind of technologies you have deployed using Azure pipeline. (Like java .net etc)
5. Explain high level of the pipeline of the java app or any other app you deployed ?
6. Do you have used SONARQUBE or similar kind of tool.
7. What can we achieve from SONARQUBE ?
8. Is there any implementation of SAST and DAST in your pipeline?
9. If you have any secret inside your code you will be using Keyvault? How will you manage those secret like do you have any expiry of password and how you manage those?
10. Explain with one example of what kind of secret you stored in azure key vault and how did you manage to rotate it with affecting the functionality or application.
11. Suppose you have stored VM password as you said so how you will use that in your code?
12. What kind of PAAS services you have experienced in AZURE Cloud?
13. What kind of Database you used in your project?
14. You have experience with Azure front door? What it does? 
15. You have experience in Azure Gateway. Integration between the component your network?
16. Why you are going with Hub and Spoke ? Is there in any advantage ?
17. Do you have experience in K8s? 
18. You mentioned in your CICD you cut the deployment release cycle to 70%. How did you manage to do it?
19. You mentioned using terraform you cut the infra creation time to 2 to 3 days? How did you do it?
20. Let take example of 1 use case I have to build new environment and what will be the best approach to maintain these module in the resource or components can be used in all the environment like pre, prod, uat etc?
21. Explain the terraform workflow in detail for the above scenario, what files and all you will be keeping in root and child module?
22. How did you use Open Cost tool? Explain the use case.
23. Can you tell me what all resource, for which you reduced the cost as per the use case for open cost you explained?
24. Apart from VM did you do any other cost optimisation on other Azure resource?
25. As you said you have a Kubernetes team separate? Why ? Application you are supporting but separate team for kubernetes?
26. You have mention you have written docker multiple state file? What are the stages involved?
27. What is your application architecture?
28. How many micro services you have in your project?
29. What is the team size you have ?
30. In Docker file we will be using a BASE image in FROM instruction, I have 100 mircoservices based on java application. How will you you manage the BASE image for these 100 micro services?
31. I am using idk 11 for 100 Microservices. I want to upgrade the the version to 17 . What will be your approach to do this change using docker file?
32. You did a POC and compatibility is ok, you now want to roll it out to 100 Microservices, the same change , the base image change ? What will be your approach? Will you do it individually or will you do it a single place and refer that ?
33. You mention you have 5 VM and in all the 5 VM if you want to update the version of ubuntu version ? How will you you do it?
34. How will you refer the VM inventory in you for each loop for the above update?

=======================================================================================================================================================

Resources publicist group - interview

1. Management has mandated removing all public IPs from your Azure environment — how do you maintain access and outbound traffic?
2. You have a storage account behind a private endpoint and a VM on the same VNET — but DNS is still resolving the public IP. What might be wrong in that environment?
3. An application is running behind an Application Gateway and you're getting 502 errors — how would you troubleshoot that?
4. Walk me through configuring Azure Front Door for a web application — what are the key things you need to configure?
5. When would you use a NAT Gateway and what is it used for?
6. A client shuts down his dev VM every night to save money but is still getting charged — what is he doing wrong?
7. A Linux VM's root slice is running out of space — walk me through the entire process of adding a disk and extending the root slice.
8. A VM in Azure is showing high CPU usage — what Azure native tools would you use to diagnose it?
9. You have 10 VMs and want to update all of them without touching each one manually — what would you use in Azure?
10. Are you familiar with Azure Automation Accounts and Azure Update Manager?
11. You have Contributor access on a subscription but are getting access denied on Blob Storage — why could this happen and how would you fix it?
12. You have an environment variable that's an API key — is it a secret or not? If it's a secret, is it a build-time or runtime secret? Where would you store it on GitHub?
13. How would you design a high availability environment in Azure — what resources would you use?
14. Which CI/CD tools have you used besides Azure DevOps?
15. What is a workflow file and what is it used for?
16. If you need to create a CI/CD pipeline, which file would you edit and where?
17. Do you have experience configuring Web Apps?Have you configured web applications? Used web applications?

===================================================================================================================

IBM
1. Could you please tell me, suppose there is an Android application and you need to perform security tool integration into the existing pipeline. What would be your approach?

2. What would be the approach to integrate security tools into the existing pipeline for 100 applications or a large number of applications?

3. What security tools have you integrated in your current or past job?

4. Have you worked on scripting such as YAML or Groovy scripts?

5. Can you explain the YAML code/configuration that was shared with you?
security_tools:
  vulnerability_scanner:
    enabled: true
    tool: "Nessus"
    server: "https://scanner.internal.local"
    username: "admin"
    password: "HardcodedPassword123"
  static_code_analysis:
    enabled: true
    tool: "SonarQube"
    url: "https://sonarqube.internal.local"
    token: "hardcoded-api-token"
  dependency_scanner:
    enabled: true
    tool: "OWASP Dependency-Check"
    report_path: "/reports/dependency-check"
  secrets_scanner:
    enabled: true
    tool: "Gitleaks"
    config_file: "/etc/gitleaks/config.toml"
  container_scanner:
    enabled: true
    tool: "Trivy"
    severity: ["HIGH", "CRITICAL"]

6. What security issues do you identify in that YAML configuration?

7. In the container scanning configuration, what does the severity field mean?

8. Have you performed Checkmarx integration?

9. If you are writing Terraform code to provision resources for a CI/CD pipeline, what security considerations would you take care of?

10. Suppose a pipeline policy gate fails a build because critical/high vulnerabilities are detected before a release. How would you:

* Verify whether the vulnerabilities are true positives or false positives?
* Ensure developers fix them?
* Handle the failed build situation?

11. Suppose you are a DevOps engineer and someone has modified the pipeline without authorization. How would you investigate the incident?

12. What logs, audit trails, or checks would you review to identify unauthorized pipeline changes?

13. Suppose someone deploys code to production from a feature branch. What controls would you implement to prevent direct deployment from feature branches to production?

14. A repository contains 10 applications in different folders, and every commit triggers security scans. Multiple scans start simultaneously and increase execution time. What approaches would you suggest to reduce scan time while maintaining security requirements?

15. Apart from CI/CD, what other DevOps/DevSecOps-related activities have you worked on?

16. Can security tools/packages be executed directly on a Linux server without CI/CD integration?

17. Have you implemented any AI-driven automation in DevOps or DevSecOps? If yes, explain.
18. Do you have experience in Python scripting?
19. Do you know Shell Scripting?
20. Can you explain what SBOM (Software Bill of Materials) is and what is its use in CI/CD?
21. Do you know what SQL Injection is?
22. How do you prevent SQL Injection attacks?
23. Do you know what OWASP Top 10 is?
24. What is OWASP and how is it used in application security?

====================================

Cognizant 9th July 2026

1. Tell me about yourself, your experience, technical expertise, and roles & responsibilities.
2. Have you been part of creating an Azure Landing Zone?
3. What are the steps to create an Azure Landing Zone from scratch?
4. Explain Azure Landing Zone briefly.
5. Apart from Hub-and-Spoke networking, what other components are part of a Landing Zone?
6. What governance controls do you implement in a Landing Zone?
7. How do you implement IAM and RBAC in a Landing Zone?
8. How do you approach networking when a client has hundreds or thousands of VNets?
9. Hub-and-Spoke has peering limits. How will you overcome that limitation?
10. Which Azure service helps overcome Hub-and-Spoke scaling limitations?
11. How do you implement firewall architecture in Azure?
12. How do you ensure all outbound traffic passes through Azure Firewall?
13. How do you design centralized egress traffic through Azure Firewall?
14. What is the role of User Defined Routes (UDRs)?
15. Where do you associate UDRs?
16. Explain the complete packet flow when traffic is forced through Azure Firewall.
17. How do you make sure Azure uses your custom routes instead of system routes?
18. Which CI/CD tools have you worked on besides Azure DevOps?
19. How do you fetch secrets from Azure Key Vault in Azure DevOps Pipeline?
20. How is the connection established between Azure DevOps and Azure Key Vault?
21. Explain the Service Connection authentication flow.
22. Explain your complete CI/CD architecture.
23. Explain every step in your Azure DevOps Pipeline.
24. Where do you deploy your .NET application?
25. What are the stages in your application deployment pipeline?
26. What SAST tools have you implemented?
27. Explain how SonarQube works in your pipeline.
28. What is DAST?
29. How do you perform DAST testing?
30. Which OWASP Top 10 vulnerabilities does your DAST tool detect?
31. If code coverage is below 80%, how will you fail the pipeline?
32. How do you enforce Quality Gates in Azure DevOps?
33. Which agent do you use—Microsoft Hosted Agent or Self Hosted Agent?
34. Why are you using Microsoft Hosted Agent?
35. Why Ubuntu agent instead of Windows agent?
36. Your Azure Key Vault is behind a Private Endpoint. How will a Microsoft Hosted Agent access it?
37. Will a Microsoft Hosted Agent be able to access a Private Endpoint directly?
38. How do you securely communicate from Microsoft Hosted Agent to private Azure resources?
39. How did you implement this architecture in your project?
40. Rate yourself on Terraform.
41. What is the difference between the Terraform block (`required_providers`) and the Provider block?
42. What is the difference between AzureRM Provider and AzAPI Provider?
43. When should you use the AzAPI Provider?
44. Suppose a resource was created manually in Azure. How will you manage it using Terraform?
45. Explain the Terraform Import process.
46. Which files are required while importing existing resources into Terraform?
47. Have you worked with Terraform Modules?
48. How do you pass values from one module (e.g., VNet) to another module (e.g., VM)?
49. Explain the complete Azure Firewall routing design.
50. Design a scalable Azure network architecture for thousands of VNets.
51. Explain the complete CI/CD flow from code commit to deployment.
52. Design a secure pipeline that accesses Azure Key Vault over a Private Endpoint.
53. How would you migrate manually created Azure resources into Terraform?
54. How do multiple Terraform modules communicate with each other using outputs, variables, and dependencies?

=====================================

TCS 9th July

1. Brief me about yourself, your skill set, and your current project.
2. Explain your recent project end-to-end.
3. How would you design an Azure Landing Zone from scratch?
4. Explain Azure Landing Zone step by step.
5. What are the different types of Azure Landing Zones?
6. Why is Azure Landing Zone important?
7. Explain Hub-and-Spoke architecture in detail.
8. How would you design a Multi-Region Azure Landing Zone?
9. How would you handle Identity, Networking, and Disaster Recovery in a Multi-Region Landing Zone?
10. Where would you associate User Defined Routes (UDRs) in a Landing Zone?
11. How would you implement Azure Firewall?
12. How would you define and control traffic flow in Azure?
13. How do you ensure all traffic passes through Azure Firewall?
14. Have you worked on Multi-Region deployments and onboarding pipelines?
15. Explain your Multi-Region deployment experience.
16. Production deployment succeeded, but the application is unavailable. How would you troubleshoot it?
17. What would be your rollback strategy after a failed production deployment?
18. How would you communicate with users/business during a production outage?
19. Explain your real-time rollback strategy with an example.
20. Have you worked on Bash, PowerShell, or other scripting?
21. Explain an automation you implemented using scripting.
22. Explain an Azure DevOps automation you implemented using PowerShell/Bash.
23. Explain your PowerShell automation experience.
24. Explain an RBAC scenario you implemented in your CI/CD pipeline.
25. How would you implement RBAC in an Azure DevOps Pipeline?
26. How would you use RBAC to mitigate deployment failures?
27. Explain your RBAC strategy in Azure DevOps.
28. Have you worked on multi-stage CI/CD pipelines (Build, Test, Deploy)?
29. Explain SAST and DAST implementation in your CI/CD pipeline.
30. What monitoring and alerting tools have you used?
31. Which monitoring tool are you currently using?
32. What KPIs and thresholds do you monitor?
33. Deployment works in Dev but consistently fails in QA. How would you troubleshoot it?
34. How would you compare configurations across environments?
35. How would you standardize Dev, QA, and Production environments?
36. How do you monitor Terraform deployment failures?
37. Explain a real-time Terraform deployment failure you resolved.
38. What challenges have you faced during Terraform upgrades or deployments?
39. How do you manage Terraform across Dev, QA, and Production?
40. What kinds of Terraform drift have you encountered?
41. Azure DevOps pipeline shows success, but no Azure resource is created. What could be the reason?
42. How would you troubleshoot when the pipeline succeeds but Azure resources are missing?
43. Two engineers run Terraform Apply simultaneously on the same environment. What happens?
44. How does Terraform State Locking work?
45. When would you use `terraform force-unlock`? What precautions should you take?
46. How do you integrate Azure Key Vault into Azure DevOps?
47. If Azure Key Vault is behind a Private Endpoint, how will your pipeline access it?
48. How do you stop or restrict traffic to an Azure App Service?
49. What all does Azure manage automatically for an Azure App Service (PaaS)?
50. A new developer joins your team. What Azure resources, permissions, and access would you provide?
51. How would you configure all the required development tools for a new team member?
52. What is the difference between Managed Identity and Service Principal?
53. What is the difference between `docker build` and `docker commit`?

===============================

Today's Interview Question from NAB and Quess 13 July

1. How would you design a production-grade CI/CD pipeline from scratch?
2. How would you design a CI/CD pipeline for deploying applications to a multi-region AKS/EKS cluster?
3. How would you ensure that deployment to the next region only happens if deployment and validation succeed in the previous region?
4. How would you implement automated deployment promotion between regions?
5. What is synthetic testing, and how would you integrate it into a CI/CD pipeline?
6. What stages would you include in a production-grade CI/CD pipeline from code checkout to deployment notification?
7. How would you automate deployment validation and rollback?
8. How would you authenticate your CI/CD pipeline with Azure or AWS?
9. How does authentication work between the Version Control System and the Cloud?
10. When would you use Managed Identity instead of a Service Principal?
11. What deployment strategies are available in Kubernetes?
12. Explain Rolling Update, Canary, and Blue-Green deployment strategies. What are the differences, and which one is the most cost-effective?
13. What security controls would you include in a banking application's CI/CD pipeline?
14. How would you secure secrets in your CI/CD pipeline?
15. How would you integrate Azure Key Vault into a CI/CD pipeline?
16. How would you prevent hardcoded secrets in your applications?
17. How would you implement RBAC in your CI/CD process?
18. Where would you integrate SonarQube in the pipeline?
19. How would Private Endpoints improve pipeline security?
20. How would you secure communication between Azure Bastion and a Production VM?
21. What security configurations would you implement for Bastion access?
22. Why should Production VMs not have Public IP addresses?
23. How would you secure communication between a Bastion Host and a Production Server?
24. What networking security measures would you implement for Production workloads?
25. How would you migrate existing ClickOps infrastructure to Infrastructure as Code using Terraform?
26. How would you migrate infrastructure across multiple AWS/Azure accounts using Terraform?
27. How would you design reusable Terraform modules for a large enterprise?
28. Explain your Terraform module architecture, including Root Modules and Child Modules.
29. How would you import existing cloud resources into Terraform? What is the purpose of the Terraform Import Block?
30. How would you perform infrastructure migration with minimal downtime?
31. What is Terraform State Locking, and how would you unlock a locked Terraform state?
32. How would you resolve a locked Terraform state when using Terraform Enterprise without Terraform installed locally?
33. How is Terraform state managed in Terraform Enterprise?
34. How would you design an observability solution for a production application?
35. What dashboards would you create for monitoring a production workload?
36. Suppose 30% of requests are timing out, 30% have high latency, and the rest are successful. What dashboards and alerts would you configure?
37. How would you design an alerting strategy for production systems?
38. How would you implement threshold-based monitoring and alerting?
39. What key metrics (KPIs) would you include in your monitoring dashboards?
40. What would you include in a Latency Dashboard?
41. What would you include in an Error Dashboard?
42. What is latency in distributed systems?
43. Explain P50, P95, and P99 latency. What are the differences, and when would you use each?
44. How would you approach migrating workloads from AWS to Azure?
45. How would you manage a multi-cloud environment (AWS, Azure, and GCP)?
46. How would you design a secure cloud architecture for a banking application?
47. How would you design a highly available, production-grade CI/CD pipeline for a banking application?
48. How would you achieve zero-downtime deployments?
49. How would you verify that an application deployment is successful from both a system and an end-user perspective?
50. How would you ensure secure communication between users, Bastion Hosts, and Production Servers?
51. How would you standardize Terraform code across 20+ cloud accounts?
52. How would you monitor application health and automatically notify the operations team when thresholds are breached?


===============================
Cognizant 2nd round 14 July


1. What are your day-to-day responsibilities in your current project?
2. Which CI/CD tool do you use?
3. Have you created custom Terraform modules or built infrastructure from scratch?
4. How do you design reusable Terraform modules for multiple environments (Dev, UAT, Prod), and how can a single module be reused across all environments?
5. What are Terraform Workspaces, why are they used, what are their benefits, and when would you use them instead of separate environment folders?
6. How would you plan and execute a Terraform version upgrade (e.g., from 0.x to 1.x), and what compatibility checks would you perform before upgrading?
7. What is the purpose of `null_resource` in Terraform, and can you give a practical use case?
8. What is a Terraform `data` block, and how do you use it to reference existing Azure resources in your code?
9. If one VM becomes corrupted after deployment, how would you redeploy only that VM using Terraform?
10. If the Terraform state file gets corrupted, how would you recover it, and what are the best practices to protect the state file?
11. How do you securely manage sensitive information such as passwords, keys, and certificates in Terraform, and how do you integrate Azure Key Vault?
12. How would you import existing Azure resources into Terraform so they can be managed as Infrastructure as Code?
13. What is Terraform Drift, and how do you detect and safely handle manual changes made through the Azure Portal before running `terraform plan` and `terraform apply`?
14. Have you worked with Azure Verified Modules (AVM) or Cloud Adoption Framework (CAF) Terraform modules?
15. How do you structure your Terraform projects using root and child modules, and do you build your own modules or reuse existing ones?
16. How do you organize repositories for infrastructure and application code, and should they be kept together or separately?
17. Suppose an application team requests a new VM. What would be your end-to-end approach for provisioning the VM using reusable Terraform modules and handing it over to the application team?
18. How would you structure your Terraform code using root modules, child modules, `locals.tf`, `for_each`, and `tfvars` to follow the **DRY (Don't Repeat Yourself)** principle, so that common resources (Key Vault, Recovery Services Vault, Resource Group, etc.) don't need to be defined for every VM?
19. Which Terraform meta-arguments support **key-value pairs**, and when would you use `for_each`, `count`, `map`, or nested maps?
20. What is your Azure experience? Have you worked only on Azure or on other cloud platforms as well?
21. Have you been involved in cloud migration? If you had to migrate a large on-premises environment (100+ servers, legacy applications) to Azure with minimal downtime, how would you design the migration strategy using the **Cloud Adoption Framework (CAF)**, **Landing Zone**, **Hub-and-Spoke architecture**, **RPO/RTO**, and automation?
22. During migration, if private VMs need temporary internet access to download software while still remaining secure, how would you provide outbound internet connectivity without assigning Public IP addresses?
23. What automation have you worked on recently, and what scripting languages or tools (PowerShell, Bash, Python, AI tools like Copilot) have you used?
24. Suppose you're writing a Python automation script that collects information from Azure resources, but the resource names have inconsistent letter casing (uppercase/lowercase). How would you write the script so it works regardless of case sensitivity?
25. If users suddenly cannot access an Azure VM (RDP/SSH), what would be your end-to-end troubleshooting approach?
26. Have you worked with Azure Policy? Explain the hierarchy (**Definition → Initiative → Assignment → Remediation**) and describe how you would create a custom policy to restrict resource deployment to a specific Azure region (e.g., Central India).
27. Have you worked with Azure Monitor or New Relic? Suppose your monitoring platform suddenly generates hundreds of alerts. As an architect, how would you investigate the issue, distinguish between genuine incidents, false positives, duplicate alerts, and threshold misconfigurations, identify the root cause, and decide the appropriate corrective actions?
28. Have you worked with Azure Private Endpoints? Suppose a VM suddenly loses connectivity to a Storage Account over a Private Endpoint after a Terraform or network change. How would you troubleshoot the issue, including verifying **Private DNS Zone** resolution, **NSGs**, **UDRs**, firewall rules, port **443**, and other network configurations?
29. If you need temporary access to a Storage Account owned by another team, but they cannot grant you RBAC permissions, how would you securely access the Storage Account? Explain the use of **SAS Tokens** and when you would choose them over RBAC.

===========================================

Delloite 1st round 23 july 2026

1. Introduce yourself and explain your DevSecOps experience.
2. How do you organize reusable Terraform modules?
3. How do you structure Terraform code for Dev, QA, Stage, and Production environments?
4. How do you deploy changes using reusable Terraform modules?
5. If you need to add a new VM to an existing infrastructure, what changes do you make?
6. Terraform shows changes even though you didn't modify the code. Why?
7. What is Terraform Drift?
8. How do you resolve Terraform Drift?
9. How do you prevent infrastructure drift?
10. How do you update production infrastructure without downtime?
11. Explain `create_before_destroy`.
12. Explain the `depends_on` meta-argument.
13. How do you manage multiple environments in Terraform?
14. How do you migrate Terraform local state to a remote backend?
15. Which Kubernetes platform are you currently working on?
16. What are the components of an AKS cluster?
17. What is the difference between Load Balancer and Ingress?
18. How do you connect multiple Linux VMs inside a VNet?
19. How many VMs can be connected using a single Public IP?
20. How do you connect two VNets?
21. How do you create an AKS cluster using Terraform?
22. How do you connect to an AKS cluster?
23. Draw and explain your Terraform reusable module structure for AKS.
24. Explain your Terraform project folder structure.
25. What is SAST?
26. Why do you perform SAST in the CI pipeline?
27. How does SonarQube help in code quality?
28. How do you scan a Docker image?
29. What secret management solutions have you used?
30. How does TruffleHog work?
31. A critical vulnerability is found in a production container image. What steps will you take?
32. How do you implement security in Terraform-based AKS deployments?
33. How do you integrate Azure Key Vault with your CI/CD pipeline?
34. How do you securely access secrets in AKS?
35. Do you have any questions for us?

====================================================


KPMG Interview Question 24th July

1. Introduce yourself.
2. What is an Azure Landing Zone?
3. What are the best practices for designing an Azure Landing Zone?
4. Explain the Hub-and-Spoke network architecture.
5. Which resources are typically deployed in the Hub network?
6. What is the best networking strategy for a large enterprise with multiple teams?
7. How does communication happen between Hub and Spoke networks?
8. How do you enable Spoke-to-Spoke communication?
9. Why do we use User Defined Routes (UDRs)?
10. What are the limitations of VNet Peering in large-scale environments?
11. How do you overcome VNet Peering limitations?
12. What is Azure Virtual WAN and when would you use it?
13. How do you connect Azure with On-Premises and other cloud providers?
14. What is AWS Transit Gateway and how is it different from VPC Peering?
15. Explain your Terraform workflow.
16. What are the main components of a GitHub Actions workflow?
17. How do you manage Terraform State Files?
18. What is the best strategy for storing Terraform State remotely?
19. What is SIEM?
20. What is SOAR?
21. Have you worked with any SIEM or SOAR platforms?
22. What is Cloud Security Posture Management (CSPM)?
23. Which CSPM tools have you worked with?
24. Have you used Wiz or similar posture management tools?
25. Have you worked with Zscaler?
26. How do you perform vulnerability management for Virtual Machines?
27. Which tools do you use for vulnerability scanning?
28. Have you worked with AWS Inspector?
29. What is the Azure equivalent of AWS Inspector?
30. What are Pod Security Standards in Kubernetes?
31. How do you secure container images in Kubernetes or AKS?
32. What is Azure Entra ID (Azure AD)?
33. What is Azure Privileged Identity Management (PIM)?
34. What is DevSecOps?
35. How do you integrate security into a CI/CD pipeline?
36. What are the roles and responsibilities of a DevSecOps Engineer?
37. What questions do you have about the role?
=======================================================

Publisis Sapient  1st Round 30th july

1. Introduce yourself and explain what you have been working on in the last one or two years.
2. Which cloud are you currently working on?
3. Explain your Azure architecture at a high level.
4. Which network topology are you using?
5. What different services are provisioned in your Hub network?
6. How many Spokes do you have?
7. How do you decide the segregation of applications across different Spokes?
8. What different application stacks are running in your project?
9. Explain the ingress and egress network flow in your architecture.
10. If any Spoke wants to communicate with the Internet or external systems, what is the complete networking flow?
11. What are the different network hops involved in that flow?
12. Explain the traffic flow from the Internet to a Spoke and back, including the role of Firewall and User Defined Routes (UDRs).
13. Give a practical example of an ingress flow.
14. Have you worked on Kubernetes?
15. What exactly have you done in AKS?
16. Before provisioning an AKS cluster, what networking considerations must be taken care of?
17. Before provisioning an AKS cluster, what security considerations must be taken care of?
18. What networking configuration is required before creating an AKS cluster?
19. Is your AKS cluster private or public?
20. What is the difference between a private and a public AKS cluster?
21. How do you determine whether an AKS cluster is private or public?
22. How would you create and configure a private AKS cluster in Azure?
23. Have you exposed applications over the Internet?
24. Explain the complete request flow from the end user to the application.
25. What Azure components are involved in that end-to-end request flow?
26. How does Azure Application Gateway work in your architecture?
27. What is configured in the Frontend IP Configuration of Application Gateway?
28. What is configured in the Backend Pool of Application Gateway?
29. If the backend application is running on AKS, what will Application Gateway point to?
30. Since AKS node IPs are dynamic, how does Application Gateway continue routing traffic correctly?
31. How do you expose applications running inside Kubernetes?
32. How do you enable HTTPS end-to-end for an application?
33. Besides opening port 443 in the NSG, what additional configuration is required for HTTPS?
34. What Azure components participate in HTTPS communication?
35. Suppose you have production and non-production URLs such as dev.company.com and test.company.com. How would you restrict non-production URLs so that only specific internal users can access them?
36. How would you secure and restrict access to lower environment URLs while still allowing developers, QA, and business users to access them directly?
37. How would you implement access control for non-production environments using Application Gateway?
38. Have you worked with Azure App Service?
39. How did you deploy applications to Azure App Service?
40. If your application is hosted on Azure App Service, how would you restrict Dev and Test environments from public access?
41. How do you manage multiple environments such as Dev, UAT, and Prod in Azure App Service?
42. How do you promote application changes from lower environments to Production?
43. Which Azure services have you worked on apart from VMs and App Service?
44. Have you worked on Azure Static Web Apps?
45. Have you worked on Azure AI Foundry?
46. Have you worked on Azure Monitor?
47. Have you worked with Azure Data Factory?
48. Have you worked with Apache Airflow?
49. Have you worked with any APM (Application Performance Monitoring) tools?
50. Why are you using Azure Monitor?
51. How does Azure Monitor work internally?
52. How are logs collected in Azure Monitor?
53. What is the role of Log Analytics Workspace?
54. How do you build dashboards and monitor application or infrastructure metrics?
55. How strong is your Linux experience?
56. How can you access a Linux server without using a password?
57. Explain how SSH authentication works.
58. What happens internally when SSH authentication occurs?
59. Why do we have both a Public Key and a Private Key?
60. Where is the Public Key stored?
61. Where is the Private Key stored?
62. How do the Public and Private Keys work together?
63. Why are two keys required instead of one?
64. How do you configure SSH key authentication?
65. Why is port 22 used for SSH?
66. How can you change the default SSH port?
67. Which Linux configuration file is modified to change the SSH port?
68. After changing the SSH port, how will end users connect to the server?
69. How would you troubleshoot SSH connectivity issues?
70. How are logging, monitoring, and observability implemented across your platform?
71. Which monitoring tools have you used?
72. How does New Relic work?
73. How does Azure Monitor compare with New Relic?
74. Which CI/CD tools have you worked with?
75. What different pipelines have you created?
76. What infrastructure pipelines have you implemented?
77. What application deployment pipelines have you implemented?
78. What infrastructure components are provisioned through your Terraform pipelines?
79. What is included in your Azure Landing Zone?
80. Which Azure resources are provisioned first in the Landing Zone?
81. What is the order of resource creation in your Terraform deployment?
82. What exactly will your Terraform code contain?
83. Can you deploy the complete Azure Landing Zone in a single click?
84. How would you design your Terraform code for one-click Landing Zone deployment?
85. How would you manage multiple Azure subscriptions?
86. How would you structure Terraform code for multiple subscriptions?
87. How would you authenticate Terraform across multiple Azure subscriptions?
88. How would you manage environments across multiple subscriptions?
89. How would you manage Terraform remote state files for multiple subscriptions?
90. How would you troubleshoot a 502 Bad Gateway error end-to-end?
91. How would you troubleshoot a 503 Service Unavailable error end-to-end?
92. Explain the complete end-to-end troubleshooting approach for 502 and 503 errors, starting from DNS and the client request, through Application Gateway or Load Balancer, networking, AKS or VMs or App Service, and finally the application itself.
93. What Azure services and components would you check first while troubleshooting 502 and 503 errors?
94. How would you identify whether the 502/503 issue is caused by DNS, Application Gateway, Load Balancer, NSG, Firewall, AKS, VM, App Service, backend application, health probes, or application code?

===================================================================================================================================================
Deloitte 2nd round interview 4th Aug

1. Can you walk me through your professional journey and explain your current role?
2. What is your role and responsibility in your current project?
3. How have you transitioned from Application Support to DevSecOps?
4. Explain your DevSecOps workflow from code commit to production deployment.
5. How do you implement security controls in a CI/CD pipeline?
6. Which DevSecOps tools have you used, and for what purpose?
7. How do you integrate security scanning into Azure DevOps pipelines?
8. What is SAST (Static Application Security Testing)?
9. What is DAST (Dynamic Application Security Testing)?
10. What is the difference between SAST and DAST?
11. What is SCA (Software Composition Analysis)?
12. What is the difference between SAST and SCA?
13. At which stage of the SDLC should SAST be integrated?
14. Which SAST tools have you worked with?
15. What kind of vulnerabilities can be detected using SAST?
16. What kind of vulnerabilities can be detected using DAST?
17. How does OWASP ZAP help in application security testing?
18. How does SonarQube work?
19. Where exactly would you integrate SonarQube in the SDLC?
20. What are SonarQube Quality Gates?
21. Why would an organization use both SonarQube and Snyk?
22. What security metrics and reports can SonarQube provide?
23. What actions do you take when SonarQube reports critical vulnerabilities?
24. How do you handle critical and high-severity vulnerabilities?
25. What is your process for vulnerability remediation?
26. How do you coordinate with developers to fix vulnerabilities?
27. How do you track remediation activities?
28. What security metrics do you publish for management?
29. What are application dependencies?
30. Why are software dependencies important?
31. What risks are associated with third-party dependencies?
32. How do you identify vulnerable dependencies?
33. What are vendor dependencies?
34. What are open-source libraries?
35. Can you name some common open-source package managers and repositories?
36. What security risks are associated with NPM packages?
37. How do software supply chain attacks occur?
38. What is Software Supply Chain Security?
39. Have you ever handled a software supply chain attack?
40. How do you secure open-source components used in applications?
41. How would you respond if a dependency becomes vulnerable after deployment?
42. What is an SBOM (Software Bill of Materials)?
43. Why is SBOM important for modern software security?
44. How does SBOM help in vulnerability management?
45. What tools can be used to generate SBOMs?
46. What is open-source license risk?
47. Why should organizations monitor software licenses?
48. What are the risks of using unapproved open-source licenses?
49. If a low-severity vulnerability becomes critical after deployment, what steps would you take?
50. How do you monitor security risks in production?
51. What is continuous security monitoring?
52. What is a Zero-Day Vulnerability?
53. What is a Zero-Day Attack?
54. Explain the Log4j vulnerability and its impact.
55. What is the CVSS score and how is it used?
56. What is the difference between a vulnerability, threat, and risk?
57. What are KPIs in cybersecurity?
58. What are KRIs (Key Risk Indicators)?
59. How do you measure the effectiveness of a DevSecOps program?
60. What security reports would you present to management?
61. What is Nexus Repository?
62. What is the difference between GitHub and Nexus Repository?
63. What type of artifacts are stored in Nexus?
64. How do artifact repositories improve software security?
65. A critical vulnerability is detected in production. What would be your response plan?
66. A dependency used across multiple applications is found vulnerable. How would you handle it?
67. Developers disagree with your security recommendations. How would you convince them?
68. How would you implement a secure Software Supply Chain Security program from scratch?
69. What would be your strategy to enforce secure coding practices across development teams?
70. How would you build a shift-left security culture in an organization?
=====================================================================================================

KPMG 7th Aug

1. Could you walk me through your experience with Terraform and Infrastructure as Code (IaC)?
2. What Terraform best practices have you implemented in your projects?
3. How do you structure your Terraform code using reusable and modular components?
4. What Terraform modules have you created recently? Can you explain one of them in detail?
5. How do you structure the root module and child modules in Terraform?
6. Do you keep your Terraform modules and environment configurations in the same repository or separate repositories? Why?
7. How do you manage multiple environments such as Dev, UAT, and Production using Terraform?
8. How do you consume a reusable Terraform module from the root module?
9. If you were asked to create a Terraform module for an Azure Storage Account, what files would you create?
10. What would you typically define in the `main.tf`, `variables.tf`, and `outputs.tf` files of a Terraform module?
11. How would you define an Azure Storage Account resource inside a Terraform module?
12. How do you pass variables from the root module to a child module?
13. How do you manage dependencies between Terraform resources or modules?
14. Can you explain the Azure Landing Zone architecture you have worked with?
15. How have you implemented the Hub-and-Spoke network topology in your Azure Landing Zone?
16. How are subscriptions and applications organized within your Hub-and-Spoke architecture?
17. How do you decide which Management Group and Resource Group an application should belong to?
18. How many environments and applications were part of your previous Azure Landing Zone implementation?
19. How do you onboard a new application into an existing Azure Landing Zone?
20. What Azure security tools and services have you worked with?
21. What experience do you have with Microsoft Defender for Cloud?
22. Have you worked with Microsoft Sentinel? If yes, how have you used it?
23. How have you implemented Azure Policies in your environment?
24. What is the difference between built-in Azure Policies and custom Azure Policies?
25. What is an Azure Policy Initiative, and why would you use one?
26. At what scope can Azure Policies be assigned, and how would you apply them across an organization?
27. What are the different effects available in Azure Policy?
28. Can you explain the difference between `Deny`, `Modify`, `Audit`, and `DeployIfNotExists` policy effects?
29. How do you automate Azure Policy deployment using Terraform?
30. How do you implement security scanning in your CI/CD pipeline?
31. Could you walk me through your application CI/CD pipeline from source-code checkout to deployment?
32. Which security and code-quality tools have you integrated into your application pipeline?
33. Where would you integrate tools such as SonarQube and Gitleaks in a CI/CD pipeline?
34. What is the purpose of SonarQube quality gates?
35. How do you detect exposed secrets in source code?
36. How do you perform Software Composition Analysis (SCA) in your pipeline?
37. How do you perform Dynamic Application Security Testing (DAST)?
38. Which DAST tool have you used, and at what stage of the pipeline did you integrate it?
39. What happens if a security scan fails in the middle of your pipeline?
40. How do you implement conditional logic in an Azure DevOps pipeline?
41. How do you ensure that the next pipeline stage runs only when the previous stage succeeds?
42. Have you created CI/CD pipelines from scratch? If yes, can you explain your approach?
43. How do you design a Terraform CI/CD pipeline?
44. How do you separate Terraform `init`, `plan`, and `apply` stages?
45. How do you pass the Terraform plan from one pipeline stage to another?
46. Which security and quality tools have you integrated into your Terraform pipeline?
47. How do you integrate tools such as tfsec, TFLint, TruffleHog, Gitleaks, and Infracost into the Terraform pipeline?
48. At what stage would you perform infrastructure cost estimation using Infracost?
49. How would you prevent developers from accidentally committing secrets to GitHub?
50. What repository-level or organization-level security controls can you implement in GitHub?
51. How do GitHub branch protection rules help secure the development workflow?
52. How would you ensure that developers cannot directly push code to the main branch?
53. What is Microsoft Secure Score, and what does it measure?
54. What is Cloud Security Posture Management (CSPM)?
55. What does CSPM do in a cloud environment?
56. Which Azure service enables CSPM capabilities?
57. What is Cloud Workload Protection, and what does it provide?
58. What is the difference between CSPM and Cloud Workload Protection?
59. What is Microsoft Defender for Cloud, and what capabilities does it provide?
60. How would you implement Defender for Cloud using Terraform?
61. How would you integrate Azure security services into an existing Landing Zone?
62. How do you coordinate with dedicated security teams when implementing platform security?
63. What is Policy as Code, and why is it important in cloud environments?
64. How would you implement Policy as Code in Azure?
65. How can Azure Policies be defined and managed using Terraform?
66. How would you version-control Azure Policies as part of an Infrastructure as Code repository?
67. How would you deploy Azure Policies consistently across multiple environments such as Dev, UAT, and Production?
68. How would you manage Azure Policy Initiatives using Terraform?
69. How would you ensure that Policy as Code is validated and enforced through a CI/CD pipeline?
70. What is the difference between managing Azure Policies manually through the Azure Portal and implementing them as Policy as Code?
71. How would you handle changes to an existing Azure Policy through a Pull Request workflow?
72. How would you prevent non-compliant resources from being deployed using Azure Policy and CI/CD?
======================================================================================

KPMG Client round 12th Aug

1. Can you briefly introduce yourself and provide a high-level overview of your experience?
2. What is your understanding of this project and the role you would be performing?
3. Can you walk us through your complete DevSecOps pipeline and explain at which stages you implement different security scans?
4. After scanning the source code or Infrastructure as Code, what do you do with the vulnerabilities identified?
5. How do you communicate security vulnerabilities to the application/development team?
6. How do you ensure that the vulnerabilities identified during scanning are fixed before deployment?
7. Once the vulnerabilities are remediated, how do you take the updated code through the pipeline and eventually deploy it to production?
8. Where and how do you perform dependency scanning in a CI/CD pipeline?
9. How is dependency scanning different from source-code scanning performed by SonarQube?
10. If dependencies are downloaded during the build, how can you perform dependency scanning before the build?
11. What is the difference between source-code scanning, dependency scanning and runtime/application security scanning?
12. How would you perform security testing on a running application?
13. What type of vulnerabilities can OWASP ZAP identify in a running application?
14. At what stage of the CI/CD pipeline would you integrate DAST tools such as OWASP ZAP?
15. Have you integrated security scanning tools with ServiceNow, Azure Boards, Jira, or similar ticketing systems?
16. Can you automatically create tickets or bugs based on vulnerabilities detected by your security scans?
17. If such automation is not implemented, how do you currently communicate vulnerabilities to developers
18. How do you ensure that developers receive, remediate and track security findings until closure?
19. What is an Azure Landing Zone?
20. What components do you have inside your Landing Zone?
21. How do you govern an Azure Landing Zone?
22. How is your Landing Zone organized in terms of Tenant, Management Groups, Subscriptions and Workloads?
23. What is the difference between Platform Landing Zone and Application/Workload Landing Zone?
24. How do you implement governance across multiple subscriptions in a Landing Zone?
25. How do you implement Azure Policies across Management Groups and subscriptions?
26. How do you create and manage Azure Policies using Terraform?
27. What kind of governance policies have you implemented in your Landing Zone?
28. How would you prevent users from creating resources with public IP addresses using Azure Policy?
29. How would you enforce mandatory resource tagging using Azure Policy?
30. How would you prevent resources from being deployed in unauthorized regions?
31. How would you prevent resource deletion using Azure governance mechanisms?
32. What is the difference between Azure RBAC and Azure Policy?
33. If you want to prevent resource deletion, would you use RBAC or Azure Policy, and why?
34. Can you explain a custom or built-in Azure Policy that you have implemented?
35. What are the main fields/components of an Azure Policy definition?
36. How do you define the target resource type in an Azure Policy?
37. How does the condition/logic inside an Azure Policy work?
38. What are the different effects available in Azure Policy, such as Audit, Deny and Modify?
39. How would you design a policy that allows a resource only in specific Azure regions and denies it everywhere else?
40. How do you assign an Azure Policy or Initiative to a Management Group or subscription?
41. What is Microsoft Defender for Cloud?
42. How have you used Defender for Cloud in your projects?
43. What benefits do you get by enabling Defender for Cloud?
44. How do you enable Defender for Cloud for your Azure subscriptions or Management Groups?
45. What is the process you follow to enable Defender for Cloud?
46. What are the different Defender for Cloud protection plans you have worked with?
47. How does Defender for Cloud identify security misconfigurations and vulnerabilities?
48. What is Cloud Security Posture Management (CSPM)?
49. What is Cloud Workload Protection?
50. How do you improve the Microsoft Defender for Cloud Secure Score?
51. What actions have you taken to remediate Defender for Cloud recommendations and improve the Secure Score?
52. How would you design a secure Azure network for a Landing Zone?
53. What security considerations do you take while designing the network topology?
54. How do you decide the CIDR/IP address ranges for a VNet and its subnets?
55. How do you design the network to accommodate future integrations and expansion?
56. Explain the Hub-and-Spoke network architecture that you have implemented.
57. How does traffic flow between the Internet, Hub, Firewall and Spoke networks?
58. What role do User Defined Routes (UDRs) play in securing network traffic?
59. How do you ensure that application traffic goes through Azure Firewall?
60. How would you secure an Internet-facing application in Azure?
61. How would you prevent a VM or backend resource from being directly exposed to the Internet?
62. How do Network Security Groups (NSGs) help secure an Azure network?
63. How would you control inbound and outbound traffic using NSGs?
64. How would you design the subnet architecture for an Internet-facing application?
65. How would you secure an Application Gateway and its subnet?
66. What additional security controls would you implement for an Internet-facing application besides NSGs?
67. Where would you place Azure Application Gateway in your network architecture?
68. What is the difference between Azure Application Gateway and Azure Firewall?
69. What is the difference between a Web Application Firewall (WAF) and a network firewall?
70. Which Azure services provide Layer 7 routing capabilities?
71. What is the difference between Application Gateway, Azure Front Door and Traffic Manager?
72. Which of these services are regional and which are global?
73. At which network/application layer does Traffic Manager operate?
74. How does Traffic Manager route traffic?
75. What routing methods are available in Traffic Manager?
76. What is the difference between host-based/URL-based routing and DNS-based routing?
77. What is the purpose of Front Door for an Internet-facing application?
78. What security capabilities does Azure Front Door provide?
79. When would you choose Application Gateway over Front Door or Traffic Manager?
80. When would you use Traffic Manager instead of Application Gateway?
81. How do you secure an Azure App Registration/service principal used by a CI/CD pipeline?
82. How do you ensure that client secrets or credentials are not exposed in the pipeline?
83. What is passwordless/federated authentication and how can it be used in CI/CD?
84. How would you securely store and retrieve secrets used by a pipeline?
85. How would you integrate Azure Key Vault with an Azure DevOps pipeline?
86. What is the difference between using a client secret and using federated credentials/Workload Identity Federation?
87. How would you prevent secrets from being committed into source code or configuration files?
88. How would you detect hard-coded secrets in source code?
89. How would you integrate GitLeaks or a similar secret-scanning tool into a CI/CD pipeline?
90. At which stage should secret scanning be performed?
91. How would you configure the pipeline to fail automatically if a secret is detected?
92. How would you generate and communicate the secret-scanning report to the development team?
93. How would you prevent developers from accidentally committing passwords, API keys or tokens into the repository?
94. How would you integrate a security tool into an Azure DevOps pipeline?
95. Would you install the security tool directly on the build agent or use a pre-built marketplace task?
96. What are the different approaches for integrating third-party security tools into Azure DevOps?
97. How would you configure the security scanning task and make it part of the pipeline execution?
98. How would you make the security scan mandatory rather than optional?
99. How would you enforce security gates so that developers cannot bypass them?
100. Once the security tools are integrated, how do you enforce that developers actually act on the findings?
101. How would you prevent a developer from commenting out or removing the security scanning step from the pipeline?
102. How would you prevent someone with contributor access from modifying the pipeline configuration and bypassing security controls?
103. How would you protect the pipeline YAML from unauthorized modification?
104. How would you enforce mandatory security checks at the PR level?
105. How would you prevent a developer from bypassing build validation or security checks?
106. How would you use branch policies and permissions to protect the CI/CD pipeline?
107. How would you ensure that security controls remain effective even if a developer has repository contributor permissions?
108. How would you separate developer permissions from pipeline/security configuration permissions?
109. How do you secure a Landing Zone from a platform engineering perspective?
110. What security guardrails would you implement at the platform level?
111. How would you enforce logging for all resources provisioned in the Landing Zone?
112. How would you restrict resource deployment to approved Azure regions?
113. How would you ensure that all VMs have monitoring and logging enabled automatically?
114. How would you implement Data Collection Rules (DCR) for VMs?
115. How would you ensure that VMs are automatically patched?
116. How would you enforce least-privilege access across the platform?
117. How would you implement Just-In-Time / eligible access for privileged users?
118. How would you ensure that all network traffic passes through the required firewall/security controls?
119. How would you detect if a team has deviated from the Landing Zone's security standards?
120. How would you detect if someone temporarily disabled a required security configuration?
121. How would you automatically remediate a configuration if someone disables or changes it?
122. How would you build custom scripts/automation to continuously validate Landing Zone security standards?
123. Do you have any questions for us about the role or project?
124. Do you currently have any offers in hand?
125. What is your expected joining date for the other organization?
126. Why are you looking for another opportunity when you already have an offer?
