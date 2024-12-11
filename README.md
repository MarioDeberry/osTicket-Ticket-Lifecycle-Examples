<p align="center">
  <img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

# osTicket - Ticket Lifecycle: Intake Through Resolution

This tutorial covers the lifecycle of a ticket from intake to resolution in the open-source help desk ticketing system, osTicket.

## Environments and Technologies Used
- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

## Operating Systems Used
- Windows 10 (21H2)

## Ticket Lifecycle Stages
1. Intake
2. Assignment and Communication
3. Working the Issue
4. Resolution

## Working Through Tickets

In this simulation, we will walk through the lifecycle of helpdesk tickets. First, log in as an admin, navigate to **Agents**, then go to **Departments**. Select the **Maintenance** department, click **More**, and choose **Delete**.

Next, go to localhost / osTicket and create a new ticket. We'll start by addressing a case where a user named Karen reports that her company's mobile/online banking system is down.

<p>
  <img src="https://i.imgur.com/QjJatQ0.png/user-attachments/assets/61ae6ef0-e982-4ba3-8588-da6b03129add" height="80%" width="80%" alt="user portal"/>
 __________________________________________________________________________________________________________________________
</p>
<p>
  <img src="https://github.com/user-attachments/assets/eed67ceb-8e24-4e0a-bd92-a33c2b2c65f5" height="80%" width="80%" alt="ticket 1 created"/>
</p>

We access the ticket using the **John Doe** user from the Post-Installation project. Since this is an urgent online banking issue, the SLA is set to **Sev-A**. Instead of assigning it to John from the support team, we assign it to the **Online Banking team**, where **Jane** will resolve and close the ticket.

<p>
  <img src="https://i.imgur.com/8h1sKY3.png/user-attachments/assets/a7402634-c5b3-4934-8735-26a3fcf6da48" height="80%" width="80%" alt="john accessing ticket"/>
 __________________________________________________________________________________________________________________________
  <img src="https://i.imgur.com/tQw9vYv.png" height="80%" width="80%" alt="jane closing ticket"/>
</p>

Next, let’s assume a new ticket comes in reporting that the **Adobe software update** is broken in the **accounting department**. John reviews the details and decides to contact the customer for clarification, as the issue may be due to a faulty patch or an Adobe-specific issue.

In this case, we categorize the issue as **Sev-C** (minor impact), suggest that users restart their computers, and close the ticket if the issue resolves.

<p>
  <img src="https://i.imgur.com/MDmp3dh.png/user-attachments/assets/30d6e70b-fb5c-4dab-acbb-c69bcb2c0950" height="80%" width="80%" alt="closed 2nd ticket"/>
</p>

For our final case, a **CFO** is unable to turn on their laptop, which is critical due to the need for important documents. Depending on how quickly we can fix the problem (e.g., battery vs. inverter issue), we initially set the priority to **emergency** and adjust it later based on additional information.

<p>
  <img src="https://github.com/user-attachments/assets/200479b3-9c71-4b46-a0b9-e102b7be4522" height="80%" width="80%" alt="closed 3rd ticket"/>
</p>

After discovering that the issue was a broken charger, the SLA is set to **Sev-B**, as this is a relatively simple fix. Once the charger is replaced, the laptop powers on, and the ticket is closed.

## Conclusion
Resolving tickets effectively involves careful investigation, asking the right questions, and knowing when to escalate. These practices ensure smooth operations and help resolve issues efficiently.
