# osTicket - Ticket Lifecycle: Intake Through Resolution

This tutorial demonstrates the ticket lifecycle within **osTicket**, an open-source help desk ticketing system. From intake to resolution, this guide outlines how to manage and work with tickets, along with practical tasks and tips to help you get familiar with the system's capabilities.

## Video Demonstration

- **[How to create, work, and resolve tickets within osTicket](https://www.youtube.com)**

## Environments and Technologies Used

- **Microsoft Azure** (Virtual Machines/Compute)
- **Remote Desktop**
- **Internet Information Services (IIS)**

## Operating Systems Used

- **Windows 10** (21H2)

## Ticket Lifecycle Stages

1. **Intake**
2. **Assignment and Communication**
3. **Working the Issue**
4. **Resolution**

### Ticket Lifecycle Workflow

![Ticket Lifecycle Image](https://i.imgur.com/DJmEXEB.png)

## Practical Tasks & Activities

### Admin/Analyst Login:
- **Admin Panel**: [http://localhost/osTicket/scp/login.php](http://localhost/osTicket/scp/login.php)

### End Users osTicket URL:
- **User Panel**: [http://localhost/osTicket](http://localhost/osTicket)

---

### Creating Tickets as an End User

1. **Ticket 1**: *Entire mobile/online banking system is down*
   - **Assigned To**: SysAdmins
   - **Priority**: Sev-A (1 hour, 24/7)
   - **Department**: Online Banking Department
   - **Resolution**: Work the ticket to completion as **Jane**.

2. **Ticket 2**: *Accounting department needs Adobe upgrade (broken)*
   - **Assigned To**: Support
   - **Priority**: Sev-B (4 hours, 24/7)
   - **Department**: Support
   - **Resolution**: Work the ticket to completion as **John**.

3. **Ticket 3**: *CFO’s laptop will no longer turn on*
   - **Assigned To**: Support
   - **Priority**: Sev-B (4 hours, 24/7)
   - **Department**: Support
   - **Resolution**: Work the ticket to completion as **John**.

---

### Key Tasks

- **Set Properties**: Change ticket properties such as severity and department.
- **Observe Escalated Tickets**: After changing properties, observe how escalated tickets become inaccessible for further changes.
- **Admin Permissions**: Assign yourself view access to SysAdmins and observe how escalated tickets behave.
- **Work the Tickets**: Complete each ticket and ensure it is resolved according to the SLAs.

### Additional Tasks

- **Switching to the Admin Panel**: Change SysAdmins to a Top-Level Department and delete the Maintenance Department.
- **Email Notifications**: Learn how most ticketing systems (including osTicket) notify users via email each time a ticket is updated.

---

### Real-Life Ticket Intake

In real-life IT environments, tickets may come through various channels:
- **Phone Calls**
- **Chat Apps**
- **Emails**
- **Web Forms**
- **In-Person Requests**

Although it's tempting to fix issues on the spot, **creating tickets for all tasks** is essential for tracking work, improving metrics, and reporting performance.

---

### Additional Practice

- Explore osTicket’s features further by redoing this lab multiple times.
- Use the **email feature** for better communication and ticket updates.
- Revisit the **Technical Skills Pillar** to develop your abilities and intuition in ticket management.

---

### Conclusion

This lab provides a basic but comprehensive introduction to osTicket's ticket lifecycle, helping you build a solid foundation for managing IT support tickets. It’s a useful tool in any IT help desk, enabling agents to track, prioritize, and resolve issues efficiently.

---
