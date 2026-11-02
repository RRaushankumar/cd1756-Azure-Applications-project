# Write-up Template
<br>

### Analyze, choose, and justify the appropriate resource option for deploying the app.
<br>

*For **both** a VM or App Service solution for the CMS app:*

**Virtual Machine (VM)**
- **Cost:** Higher management and maintenance overhead.
- **Scalability:** Can scale vertically or horizontally but requires additional configuration.
- **Availability:** Multiple VMs may be required for higher availability.
- **Workflow:** Provides full infrastructure control but requires OS patching, maintenance, and server management.

**Azure App Service (Web App)**
- **Cost:** Managed hosting reduces infrastructure management overhead.
- **Scalability:** Supports scaling based on application requirements.
- **Availability:** Multiple instances can be configured to improve availability.
- **Workflow:** Simplifies application deployment and supports CI/CD integration.

**Choice and Justification**

I chose **Azure App Service Web App** because the CMS application does not require direct control over the underlying infrastructure. App Service simplifies deployment, scaling, and maintenance, allowing the team to focus on the application rather than managing servers.

<br>

### Assess app changes that would change your decision.
<br>

*Detail how the app and any other needs would have to change for you to change your decision in the last section.*

I would consider using a **Virtual Machine** if the application required OS-level control, specialized software, or infrastructure configurations that cannot be supported by App Service. Requirements such as authentication, networking, database connectivity, monitoring, backups, and application dependencies should also be considered.
