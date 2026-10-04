Bilkul bhai. Maine **poori file ko dekh kar repeated questions ko merge karke topic-wise buckets** bana diye hain. Same concept baar-baar alag companies ne poocha hai, isliye duplicates hata diye hain. File me questions ka major focus **Terraform, Azure Landing Zone, CI/CD, DevSecOps, Networking, AKS, Monitoring** par hai. 

## 1. Azure Landing Zone

1. What is Azure Landing Zone?
2. Why is Landing Zone important?
3. How do you design an Azure Landing Zone from scratch?
4. What are the different types of Landing Zones?
5. What components are included in a Landing Zone apart from Hub-and-Spoke?
6. Explain your current Landing Zone architecture.
7. What services/resources do you provision through Landing Zone?
8. What are Platform Landing Zone and Application/Workload Landing Zone?
9. How do you organise Tenant, Management Groups, Subscriptions and Workloads?
10. How do you onboard a new application into an existing Landing Zone?
11. How do you manage multiple subscriptions?
12. How do you structure Terraform for multiple subscriptions?
13. How do you authenticate Terraform across multiple subscriptions?
14. How do you manage environments across multiple subscriptions?
15. How do you design a Multi-Region Landing Zone?
16. How do you handle Identity, Networking and DR in Multi-Region Landing Zone?
17. How do you design a scalable Landing Zone for thousands of VNets?
18. What governance controls do you implement in Landing Zone?
19. How do you secure a Landing Zone from a platform-engineering perspective?

---

## 2. Hub-and-Spoke / Azure Networking

1. Explain Hub-and-Spoke architecture.
2. Why do we use Hub-and-Spoke?
3. What resources are deployed in the Hub?
4. How does communication happen between Hub and Spoke?
5. How do you enable Spoke-to-Spoke communication?
6. How do you decide application segregation across Spokes?
7. What are VNet Peering limitations?
8. How do you overcome VNet Peering limitations?
9. What is Azure Virtual WAN and when would you use it?
10. How do you connect Azure with On-Premises?
11. How do you connect Azure with other cloud providers?
12. What is AWS Transit Gateway vs VPC Peering?
13. How do you design networking for hundreds/thousands of VNets?
14. Explain complete ingress traffic flow.
15. Explain complete egress traffic flow.
16. Explain Internet → Hub → Firewall → Spoke traffic flow.
17. What are the network hops involved in traffic flow?
18. How do you design CIDR/IP ranges?
19. How do you design subnet architecture for future expansion?



---

# 3. Azure Firewall + UDR

1. How do you implement Azure Firewall?
2. What best practices do you follow while creating a firewall?
3. How do you ensure all outbound traffic passes through Azure Firewall?
4. How do you design centralized egress?
5. What is UDR?
6. Why do we use UDR?
7. Where do you associate UDR?
8. How do you force traffic through Azure Firewall?
9. Explain complete packet flow through Azure Firewall.
10. How do you make Azure use custom routes instead of system routes?
11. How do you secure Internet-facing applications using Firewall?
12. How do you prevent backend resources from direct Internet exposure?



---

# 4. Terraform – Core

1. What is Terraform?
2. What is IaC?
3. Explain Terraform workflow.
4. What is Terraform State?
5. How is Terraform State managed?
6. What is remote backend?
7. Why should Terraform State be stored remotely?
8. What is State Locking?
9. What happens when two engineers run `terraform apply` simultaneously?
10. When would you use `terraform force-unlock`?
11. What precautions should you take with `force-unlock`?
12. What happens if Terraform State gets corrupted?
13. How do you recover corrupted State?
14. How do you migrate local State to remote backend?
15. How do you secure sensitive information in State?
16. Terraform Cloud vs Terraform Vanilla?
17. Terraform Enterprise State management?
18. What is the difference between `required_providers` and Provider block?
19. AzureRM Provider vs AzAPI Provider?
20. When would you use AzAPI Provider?

---

# 5. Terraform Modules

1. What is a Terraform Module?
2. Root Module vs Child Module?
3. How do you create reusable Terraform modules?
4. How do modules communicate with each other?
5. How do you pass variables from root to child module?
6. How do you pass outputs from one module to another?
7. How do you handle dependencies between modules?
8. How do you consume a reusable module?
9. How do you version reusable modules?
10. How do you share modules across environments?
11. Have you created private Terraform modules?
12. What files are generally present in a module?
13. What do you keep in `main.tf`?
14. What do you keep in `variables.tf`?
15. What do you keep in `outputs.tf`?
16. How would you design a Storage Account module?
17. How would you design enterprise-level reusable modules?
18. How do you follow DRY principle in Terraform?
19. How do you use `locals.tf`, `tfvars`, `for_each` and maps together?
20. How would you structure Terraform for Dev/UAT/Prod?



---

# 6. Terraform Advanced / Scenario Based

1. What is Terraform Drift?
2. How do you detect Drift?
3. How do you resolve Drift?
4. How do you prevent manual changes from causing Drift?
5. Resource created manually in Azure — how do you bring it under Terraform?
6. Explain Terraform Import.
7. What is Terraform Import Block?
8. Which files are required during import?
9. What is `data` block?
10. What is `null_resource`?
11. What is `lifecycle` block?
12. What is `create_before_destroy`?
13. What is `depends_on`?
14. What are Terraform Meta-Arguments?
15. `count` vs `for_each`?
16. When would you use maps/nested maps?
17. How would you redeploy only one corrupted VM?
18. How do you upgrade Terraform safely?
19. How do you handle Terraform version compatibility?
20. What challenges have you faced during Terraform upgrades?
21. How do you manage Terraform across Dev/QA/Prod?
22. Terraform pipeline succeeds but resource is missing — troubleshoot.
23. How do you monitor Terraform deployment failures?
24. Explain a real Terraform failure you resolved.
25. How do you migrate ClickOps infrastructure to Terraform?
26. How do you migrate infrastructure across multiple cloud accounts?
27. How do you migrate infrastructure with minimal downtime?



---

# 7. Terraform CI/CD Pipeline

1. How do you design a Terraform CI/CD pipeline?
2. Explain Terraform `init → validate → plan → apply`.
3. How do you separate Init, Plan and Apply stages?
4. How do you pass Terraform Plan between pipeline stages?
5. How do you implement approval before Apply?
6. How do you integrate security checks into Terraform pipeline?
7. Where do you integrate tfsec?
8. Where do you integrate TFLint?
9. Where do you integrate TruffleHog/Gitleaks?
10. Where do you integrate Infracost?
11. At which stage do you perform cost estimation?
12. How do you prevent developers from bypassing Terraform security checks?
13. How do you standardize Terraform across 20+ cloud accounts?



---

# 8. Azure DevOps / GitHub Actions / CI-CD

1. Explain your complete CI/CD architecture.
2. Explain your Azure DevOps YAML pipeline.
3. What CI/CD tools have you worked with?
4. GitHub Actions workflow components?
5. What is a workflow file?
6. Where do you define a CI/CD pipeline?
7. Explain Multi-Stage Pipeline.
8. What stages do you have in application deployment?
9. Explain CI/CD from code checkout to production.
10. How do you implement PR validation?
11. How do you implement branch protection?
12. How do you prevent direct push to main?
13. How do you prevent deployment from feature branch to Production?
14. How do you implement conditional execution?
15. How do you ensure next stage runs only after previous stage succeeds?
16. Microsoft Hosted vs Self-Hosted Agent?
17. Why Ubuntu instead of Windows agent?
18. How do you make a CI/CD pipeline lightweight?
19. How do you implement rollback?
20. How do you achieve zero-downtime deployment?
21. How do you implement production approval?
22. How do you authenticate pipeline with Azure/AWS?
23. How does authentication work between Git and Cloud?
24. Managed Identity vs Service Principal?
25. When would you use Workload Identity Federation?



---

# 9. DevSecOps / Security in CI-CD

1. What is DevSecOps?
2. How do you implement security controls in CI/CD?
3. How do you prevent developers from bypassing security scans?
4. How do you make security scans mandatory?
5. How do you enforce security gates?
6. How do you prevent someone from commenting out security steps?
7. How do you protect pipeline YAML?
8. How do you prevent unauthorized pipeline modification?
9. How do you enforce mandatory PR security checks?
10. How do you separate developer permissions from pipeline/security permissions?
11. How do you handle a failed security gate?
12. How do you verify vulnerabilities are true/false positives?
13. How do you ensure developers remediate vulnerabilities?
14. How do you track vulnerability remediation?
15. How do you integrate security tools into 100+ applications?
16. Build-time vs runtime security?
17. How do you implement shift-left security?



---

# 10. SAST / DAST / SCA / SonarQube

1. What is SAST?
2. What is DAST?
3. SAST vs DAST?
4. What is SCA?
5. SAST vs SCA?
6. At which SDLC stage should SAST run?
7. What vulnerabilities can SAST detect?
8. What vulnerabilities can DAST detect?
9. What is OWASP ZAP?
10. How does OWASP ZAP work?
11. Where do you integrate DAST?
12. How do you perform DAST?
13. What is SonarQube?
14. How does SonarQube work?
15. Where do you integrate SonarQube?
16. What are SonarQube Quality Gates?
17. What does SonarQube achieve?
18. How do you fail pipeline if code coverage is below 80%?
19. SonarQube vs Snyk?
20. What security reports/metrics does SonarQube provide?
21. What do you do if SonarQube reports critical vulnerability?
22. How do you integrate Checkmarx?
23. What security tools have you used?



---

# 11. Secrets / Key Vault / Secret Scanning

1. How do you secure secrets in CI/CD?
2. How do you integrate Azure Key Vault with Azure DevOps?
3. How does Azure DevOps authenticate with Key Vault?
4. How does Service Connection work?
5. How do you fetch secrets from Key Vault?
6. Key Vault behind Private Endpoint — how does pipeline access it?
7. Can Microsoft Hosted Agent access Private Endpoint?
8. How do you securely communicate with private Azure resources?
9. Client Secret vs Federated Credential?
10. What is passwordless authentication?
11. How do you prevent hardcoded secrets?
12. How do you detect hardcoded secrets?
13. How does Gitleaks work?
14. How does TruffleHog work?
15. At which stage should secret scanning happen?
16. How do you fail pipeline if secret is detected?
17. How do you rotate secrets without impacting applications?
18. How do you secure Service Principal credentials?

---

# 12. Software Supply Chain / SBOM

1. What is Software Supply Chain Security?
2. How do supply-chain attacks happen?
3. What are application dependencies?
4. What risks exist with third-party dependencies?
5. What are vendor dependencies?
6. What are open-source libraries?
7. What risks are associated with NPM packages?
8. How do you identify vulnerable dependencies?
9. What is SBOM?
10. Why is SBOM important?
11. How does SBOM help vulnerability management?
12. Which tools generate SBOM?
13. What is open-source license risk?
14. How do you secure open-source components?
15. What happens when a dependency becomes vulnerable after deployment?
16. Explain Log4j vulnerability and impact.
17. What is Zero-Day vulnerability?
18. What is CVSS?
19. Vulnerability vs Threat vs Risk?



---

# 13. AKS / Kubernetes

1. What Kubernetes platform are you working on?
2. What are AKS components?
3. What have you done in AKS?
4. How do you create AKS using Terraform?
5. How do you connect to AKS?
6. How do you expose applications in Kubernetes?
7. Load Balancer vs Ingress?
8. What is Ingress?
9. What is Application Gateway integration with AKS?
10. What does Application Gateway point to when backend is AKS?
11. How does routing work when AKS node IPs are dynamic?
12. Private AKS vs Public AKS?
13. How do you create Private AKS?
14. What networking considerations are required before AKS?
15. What security considerations are required before AKS?
16. What are Kubernetes deployment strategies?
17. Rolling vs Canary vs Blue-Green?
18. Which deployment strategy is most cost-effective?
19. How do you implement Blue-Green deployment on AKS?
20. How do you secure container images in AKS?
21. What are Pod Security Standards?
22. How do you securely access secrets in AKS?
23. How do you implement security in Terraform-based AKS?



---

# 14. Application Gateway / Load Balancer / Front Door

1. Application Gateway vs Load Balancer?
2. Application Gateway vs Azure Front Door?
3. Application Gateway vs Traffic Manager?
4. Front Door vs Traffic Manager?
5. Which service is regional/global?
6. What is Layer 7 routing?
7. What is DNS-based routing?
8. What is URL/host-based routing?
9. How does Application Gateway work?
10. What is Frontend IP Configuration?
11. What is Backend Pool?
12. How does Application Gateway route to AKS?
13. How do you configure HTTPS end-to-end?
14. Apart from opening 443 in NSG, what else is required?
15. How do you secure Application Gateway subnet?
16. How do you restrict lower-environment URLs?
17. How do you allow only internal users to access Dev/Test?

---

# 15. 502 / 503 Troubleshooting

1. Application Gateway returns 502 — how troubleshoot?
2. Application Gateway returns 503 — how troubleshoot?
3. Backend is healthy but Application Gateway returns 503 — what next?
4. What do you check in backend for 503?
5. Explain end-to-end troubleshooting from DNS → Gateway → Network → AKS/VM/App Service → Application.
6. How do you identify whether issue is DNS?
7. How do you identify whether issue is Application Gateway?
8. How do you identify whether issue is Load Balancer?
9. How do you identify NSG/Firewall issue?
10. How do you check AKS?
11. How do you check VM/App Service?
12. How do you check health probes?
13. How do you determine whether application code is responsible?



---

# 16. Azure Policy / Governance

1. What is Azure Policy?
2. Azure Policy vs RBAC?
3. Explain Policy hierarchy:
   **Definition → Initiative → Assignment → Remediation**
4. Built-in vs Custom Policy?
5. What is Policy Initiative?
6. What are Policy effects?
7. Audit vs Deny vs Modify vs DeployIfNotExists?
8. At what scope can Policy be assigned?
9. How do you create custom Policy?
10. How do you restrict deployment to specific regions?
11. How do you prevent Public IP creation?
12. How do you enforce mandatory tags?
13. How do you prevent resource deletion?
14. How do you automate Policy using Terraform?
15. What are the main fields of Policy definition?
16. How does Policy condition/logic work?
17. How do you assign Policy/Initiative to Management Group?
18. What is Policy as Code?
19. How do you version-control Policy?
20. How do you validate Policy through CI/CD?
21. How do you handle Policy changes through PR?
22. How do you automatically remediate non-compliance?



---

# 17. Azure RBAC / IAM / Identity

1. What is Azure RBAC?
2. How do you implement IAM in Landing Zone?
3. How do you implement RBAC in CI/CD?
4. Explain an RBAC scenario from your project.
5. How can RBAC prevent deployment failures?
6. Managed Identity vs Service Principal?
7. How do you secure Service Principal?
8. What is Microsoft Entra ID?
9. Static vs Dynamic Groups?
10. What is PIM?
11. How do you implement least privilege?
12. How do you provide access to a new developer?
13. How do you implement eligible/Just-In-Time access?
14. Domain Admin vs Enterprise Admin?
15. How do you exclude specific users from MFA?

---

# 18. Private Endpoint / Private Networking

1. What is Private Endpoint?
2. How does Private Endpoint work?
3. Private DNS Zone role?
4. VM cannot access Storage over Private Endpoint — troubleshoot.
5. DNS resolves Storage to public IP — what could be wrong?
6. How do NSGs affect Private Endpoint connectivity?
7. How do UDRs affect Private Endpoint connectivity?
8. How do Firewall rules affect Private Endpoint?
9. How do you troubleshoot port 443?
10. How does a Microsoft Hosted Agent access Private Endpoint?
11. How do you securely access private Azure resources from CI/CD?

---

# 19. Azure VM / Bastion / SSH / Linux

1. How do you securely access an Azure VM?
2. Why should Production VMs not have Public IP?
3. What is Azure Bastion?
4. How do you secure Bastion access?
5. How do you secure communication between Bastion and Production VM?
6. How do you access Linux without password?
7. Explain SSH authentication.
8. What happens internally during SSH authentication?
9. Public Key vs Private Key?
10. Where is Public Key stored?
11. Where is Private Key stored?
12. Why are two keys required?
13. How do you configure SSH key authentication?
14. Why port 22?
15. How do you change SSH port?
16. Which Linux config file is changed?
17. How will users connect after changing SSH port?
18. How do you troubleshoot SSH connectivity?
19. VM high CPU — which Azure tools would you use?
20. Linux root filesystem full — how do you add disk and extend filesystem?
21. How do you update 10/100 VMs simultaneously?
22. Azure Automation Account vs Update Manager?

---

# 20. Azure App Service / PaaS

1. What PaaS services have you worked with?
2. What is Azure App Service?
3. How do you deploy applications to App Service?
4. How do you secure App Service communication?
5. How do you restrict App Service traffic?
6. How do you restrict Dev/Test App Service from public access?
7. How do you manage Dev/UAT/Prod App Services?
8. How do you promote application changes to Production?
9. What does Azure manage automatically for App Service?

---

# 21. Monitoring / Observability / New Relic / Azure Monitor

1. Which monitoring tools have you used?
2. How do you implement end-to-end monitoring?
3. How does Azure Monitor work?
4. How are logs collected in Azure Monitor?
5. What is Log Analytics Workspace?
6. How do you create monitoring dashboards?
7. What KPIs do you monitor?
8. What thresholds do you configure?
9. What is observability?
10. How do you design production observability?
11. What dashboards would you create?
12. What would you include in Latency Dashboard?
13. What would you include in Error Dashboard?
14. What is latency?
15. Explain P50/P95/P99.
16. How do you design alerting strategy?
17. How do you handle noisy/false-positive alerts?
18. How do you distinguish genuine vs duplicate alerts?
19. How does New Relic work?
20. Azure Monitor vs New Relic?
21. How does New Relic access application logs?
22. Where are logs stored for historical retrieval?
23. What is log retention?



---

# 22. Cost Optimization

1. How do you perform Azure cost optimization?
2. How do you use OpenCost?
3. What use case did you implement using OpenCost?
4. Which resources did you optimize?
5. Apart from VMs, which Azure resources did you optimize?
6. How can shutting down a VM still incur cost?
7. Where would you integrate Infracost?
8. How do you estimate infrastructure cost before deployment?
9. How do you integrate cost estimation into Terraform pipeline?

---

# 23. Backup / DR / HA

1. How does Backup work in your environment?
2. How does Disaster Recovery work?
3. How do you design DR for multi-tier application?
4. Explain RPO and RTO.
5. How do you design Multi-Region DR?
6. How do you achieve High Availability in Azure?
7. How do you achieve zero downtime?
8. What is your rollback strategy?
9. How do you perform real-time rollback?
10. How do you validate deployment from system and end-user perspective?

---

# 24. Cloud Migration

1. Have you performed On-Prem to Cloud migration?
2. What is the process to migrate a VM?
3. How do you migrate 100+ servers to Azure?
4. How do you use CAF during migration?
5. How do you use Landing Zone during migration?
6. How do you maintain minimal downtime?
7. How do you handle RPO/RTO?
8. How do private VMs get temporary outbound Internet?
9. How do you migrate AWS workloads to Azure?
10. How do you manage multi-cloud AWS/Azure/GCP?

---

# 25. Scripting / Automation / Python

1. What automation have you implemented?
2. What scripting languages do you know?
3. PowerShell experience?
4. Bash experience?
5. Python experience?
6. Explain an Azure DevOps automation using PowerShell/Bash.
7. How do you automate Azure resource information collection?
8. Python case-insensitive resource-name handling?
9. Can security tools run directly on Linux without CI/CD?
10. Have you implemented AI-driven DevOps automation?
11. How can Copilot/AI help DevOps automation?

---

# 26. Git / Branching / Repository

1. Explain your Git branching strategy.
2. How do you implement feature → integration → main?
3. How do you protect main?
4. How do you prevent direct push?
5. How do you enforce PR validation?
6. How do you prevent production deployment from feature branch?
7. How do you organize Infrastructure and Application repositories?
8. Monorepo vs separate repositories?
9. How do GitHub branch protection rules secure development?

---

# 27. Containers / Docker

1. How do you create a Dockerfile?
2. Write a Dockerfile for an application.
3. What stages are involved in a multi-stage Docker build?
4. `docker build` vs `docker commit`?
5. How do you scan Docker images?
6. What happens if a production container has critical vulnerability?
7. How do you manage a common Java base image across 100 microservices?
8. If Java 11 → Java 17, how would you upgrade the base image?
9. How would you roll out base-image changes to 100 microservices?
10. How do you secure container images?

---

# 28. Azure Networking Miscellaneous

1. Subnet vs Gateway Subnet?
2. How do you connect two VNets?
3. Can VNets in different subscriptions be peered?
4. How do you restrict inbound/outbound traffic across tenant?
5. NSG inbound vs outbound rules?
6. Load Balancer vs Application Gateway?
7. NAT Gateway — when and why?
8. How does outbound Internet work without Public IP?
9. How many VMs can use one Public IP?
10. How do you design HA networking?

---

## 🔥 Bhai, **interview ke liye sabse HIGH PRIORITY topics**

Agar tujhe is 900+ questions wali file ko **actually prepare** karna hai, to main isko priority me aise rakhunga:

**Priority 1 — Must Prepare**

1. **Azure Landing Zone**
2. **Terraform Modules**
3. **Terraform State / Drift / Import / Lock**
4. **Hub-Spoke + Firewall + UDR**
5. **CI/CD Architecture**
6. **DevSecOps Pipeline**
7. **SAST / DAST / SCA**
8. **SonarQube**
9. **Key Vault + Secrets + WIF**
10. **AKS**
11. **502/503 Troubleshooting**
12. **Azure Policy**

**Priority 2 — Strong Architect Level**
13. Private Endpoint / Private DNS
14. RBAC / Managed Identity / PIM
15. Monitoring / Observability
16. DR / RPO / RTO
17. Cost Optimization / OpenCost / Infracost
18. Multi-Region Architecture
19. Cloud Migration
20. Supply Chain / SBOM

**Priority 3 — Supporting**
21. Docker
22. Linux / SSH
23. Python / PowerShell / Bash
24. App Service
25. Front Door / Traffic Manager
26. SIEM / SOAR / CSPM
27. Entra ID / AVD
28. Git / Branching

Ye grouping directly tumhari uploaded interview-question file se nikali hai; same concepts ko multiple interviews se consolidate kiya gaya hai. 

Agar tu **ekdum interview preparation mode** me jaana chahta hai, next best step hoga: **in topics ko Basic → Intermediate → Advanced → Scenario based sequence me arrange karna**, taaki tu ek-ek topic systematically padh sake.
