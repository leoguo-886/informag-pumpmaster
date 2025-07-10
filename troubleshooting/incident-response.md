# Troubleshooting & Security Incident Response

## 1. Check the Device
- Is the pump online and connected?
- Are device logs and IoT Hub metrics healthy?

## 2. Trace the Data
- Is telemetry routed correctly in IoT Hub?
- Any errors in Stream Analytics?
- Is data in the database?
- Are API and frontend working and showing the data?

## 3. Check Security
- Does the user have the right permissions?
- Any suspicious activity in audit logs?
- Are secrets safe and data encrypted?

## 4. Automate Response
- Set up alerts for missing data or failures
- Use Logic Apps/Functions for important notifications and fixes
- Keep runbooks for common issues
