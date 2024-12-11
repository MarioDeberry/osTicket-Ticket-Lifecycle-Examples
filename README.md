<p align="center">
  <img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

# osTicket - Ticket Lifecycle: Intake Through Resolution

This tutorial covers the lifecycle of a ticket from intake to resolution in the open-source help desk ticketing system, osTicket.

## Environments and Technologies Used
- **Microsoft Azure** (Virtual Machines/Compute)
- **Remote Desktop**
- **Internet Information Services** (IIS)

## Operating Systems Used
- **Windows 10** (21H2)

## Ticket Lifecycle Stages
1. **Intake**
2. **Assignment and Communication**
3. **Working the Issue**
4. **Resolution**

## Working Through Tickets

In this simulation, we will walk through the lifecycle of helpdesk tickets. Below are the steps followed in managing tickets:

### 1. Ticket Intake and Creation
- Log in as an **admin**.
- Navigate to **Agents**, then go to **Departments**.
- Select the **Maintenance** department, click **More**, and choose **Delete**.
- Go to localhost/osTicket and create a new ticket.
- **Ticket Issue**: A user named **Karen** reports that her company’s mobile/online banking system is down.

<p>
  <img src="https://i.imgur.com/QjJatQ0.png" height="80%" width="80%" alt="user portal"/>
</p>
<p>
  <img src="https://github.com/user-attachments/assets/eed67ceb-8e24-4e0a-bd92-a33c2b2c65f5" height="80%" width="80%" alt="ticket 1 created"/>
</p>

- **Ticket Assignment**: As the issue is urgent (**Sev-A**), we assign it to the **Online Banking team**, where **Jane** will resolve and close the ticket.

<p>
  <img src="https://i.imgur.com/8h1sKY3.png" height="80%" width="80%" alt="john accessing ticket"/>
  <img src="https://i.imgur.com/tQw9vYv.png" height="80%" width="80%" alt="jane closing ticket"/>
</p>

### 2. Ticket Issue Clarification and Resolution
- A new ticket comes in about a broken **Adobe software update** in the **Accounting department**.
- **John** reviews the ticket, contacts the customer for clarification, and suggests restarting their computers.
- After determining the issue is minor (**Sev-C**), the ticket is closed after the suggestion resolves the issue.

<p>
  <img src="https://i.imgur.com/MDmp3dh.png" height="80%" width="80%" alt="closed 2nd ticket"/>
</p>

### 3. Emergency Ticket: CFO Laptop Issue
- A **CFO** reports an urgent issue: they cannot turn on their laptop, which is critical for accessing important documents.
- The priority is initially set to **emergency** and adjusted based on further investigation (e.g., battery vs. inverter issue).

<p>
  <img src="https://github.com/user-attachments/assets/200479b3-9c71-4b46-a0b9-e102b7be4522" height="80%" width="80%" alt="closed 3rd ticket"/>
</p>

- **Resolution**: After discovering a broken charger, the priority is set to **Sev-B** for a simple fix. Once the charger is replaced, the laptop powers on, and the ticket is closed.

## Conclusion
Resolving tickets effectively involves careful investigation, asking the right questions, and knowing when to escalate. These practices ensure smooth operations and help resolve issues efficiently.
