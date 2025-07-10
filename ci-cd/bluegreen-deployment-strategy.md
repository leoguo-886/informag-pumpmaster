# Blue/Green Deployment Strategy

## How It Works in Azure
- Use **App Service deployment slots** for Blue and Green.
- Deploy new version to Green slot.
- Run automated tests and health checks.
- If all is well, swap Green to production.
- Blue becomes standby for rollback.

## Azure DevOps Pipeline Example
- Read [text](azure-pipeline-bluegreen.yaml)

## Rollback Mechanism
- If Green fails health checks, do not swap—Blue stays live.
- If issues appear after swap, swap back to Blue or redeploy last good version.
- Rollback can be automated with Azure CLI or DevOps tasks.
