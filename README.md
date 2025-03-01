<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

# **osTicket - Ticket Lifecycle: Intake Through Resolution**
This guide outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system, **osTicket**.

---

## **Environments and Technologies Used**
- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop Protocol (RDP)
- Internet Information Services (IIS)

---

## **Operating System Used**
- Windows 10 (21H2)

---

## **Ticket Lifecycle Stages**
1. **Intake** – A user submits a support ticket via email or the customer portal.
2. **Assignment and Communication** – The ticket is assigned to an agent, and communication begins.
3. **Working the Issue** – The agent investigates and works on resolving the issue, providing updates within the ticketing system.
4. **Resolution** – The issue is resolved, the ticket is closed, and the user is notified of the resolution.

---

## **Lifecycle Stages Overview**

### **Stage 1: Ticket Intake**
<p>
<img src="https://i.imgur.com/0yjALrc.png" alt="Ticket Intake"/>
</p>

- A user submits a new ticket under the appropriate help topic (e.g., Business Critical Outage).
- The reported issue is documented with relevant details (e.g., CRM software is down).

### **Stage 2: Assignment and Communication**
<p>
<img src="https://i.imgur.com/BNXolkz.png" alt="Ticket Assignment"/>
</p>

- Agents review active tickets in the **Agent Panel**.
- Queue managers prioritize tickets and assign them based on severity and urgency.
- Service Level Agreements (SLAs) are applied to ensure timely resolution.

### **Stage 3: Working the Issue**
<p>
<img src="https://i.imgur.com/4FvPpMN.png" alt="Working the Issue"/>
</p>

- The assigned agent begins troubleshooting the issue.
- The priority of the ticket is adjusted as necessary (e.g., marked as an **Emergency** if critical).
- The appropriate **SLA Plan** is applied to dictate resolution timelines.
- The ticket is assigned to a senior technician if escalation is needed.

### **Stage 4: Resolution and Closure**
<p>
<img src="https://i.imgur.com/rNycELQ.png" alt="Resolution and Closure"/>
</p>

- Once the root cause is identified and addressed, the issue is marked as resolved.
- The ticket status is changed to **Closed**, and a final response is provided to the customer.
- An internal note may be added for reference, including customer feedback and follow-up actions if needed.

---

## **Conclusion**
Understanding the ticket lifecycle in osTicket ensures a structured approach to issue resolution. By following these lifecycle stages, organizations can efficiently manage support requests and maintain high customer satisfaction.
