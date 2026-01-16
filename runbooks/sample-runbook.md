# System Setup & Ops Runbook

## 1. Overview
This system hosts an internal application used by the team for daily operations.
It runs on a virtual machine and is accessed over the network by authorized users.
The system is expected to be available during business hours.

## 2. Components
- Virtual Machine (VM): Hosts the application and related services
- Network: Allows users to access the system over the internet or internal network
- User Access: Controls who can log in and use the system

## 3. Common Issues
- Users are unable to access the system
- Users receive permission or access denied errors

## 4. Runbook: System Not Accessible

### Symptoms
- User reports that the application is not loading
- Connection times out or shows an error
- System was working earlier but is now unreachable

### Possible Causes
- Virtual machine is stopped or not responding
- Network connectivity issue
- Service on the system is not running
- Access or firewall rules blocking traffic

### Checks to Perform
1. Check if the virtual machine is running
2. Verify network connectivity to the system
3. Confirm required services are running on the VM
4. Check if recent changes were made to access or network settings

### Resolution Steps
1. Start the virtual machine if it is stopped
2. Restart the affected service if it is not running
3. Restore network or firewall rules if they were changed
4. Verify access permissions and update if required
5. Confirm system access with the user after fixing

## 5. Warnings
- Do not make network or access changes without documentation
- Avoid restarting services during peak usage without informing users
- Always confirm the impact before applying changes

