# Secure & Scalable Azure Architecture

**1. Identity & Tenancy**
- Azure AD B2C for secure login and multi-tenant access

**2. Device Connectivity**
- Azure IoT Hub for real-time, secure MQTT communication with pumps

**3. Backend API**
- .NET/C# API on Azure App Service for business logic and pump management

**4. Data Storage**
- Azure SQL Database for structured data (users, assets, inspections)
- Azure Cosmos DB for high-volume telemetry

**5. Secrets Management**
- Azure Key Vault for storing secrets and certificates

**6. Access Control**
- Azure RBAC for least-privilege access and managed identities

**7. Network Security**
- Private Endpoints, NSGs, and Firewall/WAF for protection

**8. Monitoring**
- Azure Monitor, Application Insights, and Log Analytics for visibility and alerts

**9. Infrastructure as Code**
- Terraform and Azure DevOps Pipelines for automated, repeatable deployments
