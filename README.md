# osTicket Lab Exercise

This lab exercise involves creating, observing, and completing tickets within the osTicket system, both as an end-user and as a help desk agent. This project will help develop ticket management skills, which are essential in a help desk or IT support role.

## Access URLs

- **Admin/Analyst Login Page:** [http://localhost/osTicket/scp/login.php](http://localhost/osTicket/scp/login.php)
- **End Users osTicket URL:** [http://localhost/osTicket](http://localhost/osTicket)

---

## Lab Overview

In this lab, you will:

- Create tickets as an end-user.
- Observe and manage ticket properties as a help desk agent.
- Work through ticketing scenarios to completion.
- Explore the capabilities of the osTicket system, including role management, SLAs, and department configuration.

---

## Configuration Tasks

### 1. Update Department Settings

- Change the **SysAdmins Department** to a **Top Level Department**.
- **DELETE** the Maintenance Department (instead of archiving it).

---

## Ticket Scenarios

### Scenario 1: Mobile/Online Banking System Down

1. **As an End User**, create a ticket with the following description:  
   - **Issue**: "Entire mobile/online banking system is down."

2. **As a Help Desk Agent (John)**, observe the ticket's properties:
   - **Priority**: Default
   - **Department**: SysAdmins
   - **SLA**: Default
   - **Assigned To**: Unassigned

3. **Set Properties for the Ticket**:
   - **SLA**: Sev-A (1 hour, 24/7)
   - **Department**: Online Banking Department

4. **As John**, attempt to view or change the ticket after setting properties. Note whether you have access.

5. **As Jane**, work the ticket to completion.

---

### Scenario 2: Accounting Department Needs Adobe Upgrade

1. **As an End User**, create a ticket with the following description:  
   - **Issue**: "Accounting department needs Adobe upgrade, broken."

2. **As a Help Desk Agent (John)**, observe the ticket's properties:
   - **Priority**: Default
   - **Department**: Accounting
   - **SLA**: Default
   - **Assigned To**: Unassigned

3. **Set Properties for the Ticket**:
   - **SLA**: Sev-B (4 hours, 24/7)
   - **Department**: Support

4. **As John**, work the ticket to completion.

---

### Scenario 3: CFO’s Laptop Will No Longer Turn On

1. **As an End User**, create a ticket with the following description:  
   - **Issue**: "CFO’s laptop will no longer turn on."

2. **As a Help Desk Agent (John)**, observe the ticket's properties:
   - **Priority**: Default
   - **Department**: Support
   - **SLA**: Default
   - **Assigned To**: Unassigned

3. **Set Properties for the Ticket**:
   - **SLA**: Sev-B (4 hours, 24/7)
   - **Department**: Support

4. **As John**, work the ticket to completion.

---

## Managing Escalated Tickets

- **Set Properties** to all the tickets. Assign **SEV-A** for the SysAdmins ticket last. 
- Observe that the ticket becomes **inaccessible** after setting SEV-A.
- Switch to the **Admin Panel** and assign yourself view access to SysAdmins.
- Switch back to the **Agent Panel** and observe the **escalated ticket**.
- Note that you can no longer make changes to this ticket.

---

## Final Steps and Observations

1. **Solve all of the tickets**. 
2. Discuss the **email feature**:
   - In most ticketing systems, including osTicket, there’s an email notification feature. Each time a ticket is updated, the user is notified, and they can respond via email.
3. **Real-Life Ticket Intake**:
   - Tickets are often created through various channels like phone, chat, email, web forms, or in-person requests. It’s important to document everything you work on for accurate metrics and reporting.
   - Even if you resolve an issue on the spot, make sure to create a ticket for it.

---

## Additional Practice

This lab covers only a portion of osTicket's capabilities. You are encouraged to explore the system further, especially the email feature. Try repeating the lab steps multiple times to build intuition. 

---

## Key Skills Developed

This lab will help build your proficiency in:
- **Technical Ability**: Understanding osTicket’s ticketing workflow and configuration.
- **Problem Solving**: Using ticket properties like SLAs, departments, and priority to manage and complete tickets efficiently.
