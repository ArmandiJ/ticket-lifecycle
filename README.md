<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Computers)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Intake</h2>

- In osTicket Select Open a New Ticket
- Email Address: Ken@osTicket.com
- Name: Ken Ken
- Help Topic Dropdown Menu: Personal Computer Issues
- Issue Summary: Entire accounting department adobe reader not working
- Details: Ever since the upgrade last night, nobody in accounting has been able to use Adobe Reader
- Create Ticket


![image](https://github.com/ArmandiJ/ticket-lifecycle/assets/153237878/6464f387-816c-4795-b6ad-bbacf5a4e90f)


![image](https://github.com/ArmandiJ/ticket-lifecycle/assets/153237878/328ebe1c-02fe-48f8-bfdb-f751a68876b6)


<h2>Assignment and Communication</h2>

- Sign into osTicket as an Agent
- We created jane.doe in previous tutorial, log in with those credentials.
- Select the ticket we created
- Priority: High
- Assigned to: John Doe
- SLA Plan: SEV-B
- Department: Support
- Response text box: Re-assigned to SEV-B, reached out to John for a warm handoff.
- Select Post Reply

![image](https://github.com/ArmandiJ/ticket-lifecycle/assets/153237878/c20a4f05-9461-4c90-80cb-f5c9b8bb0213)


<h2>Working the Issue</h2>

- Sign into osTicket as John
- Select the ticket we assigned to John
- Response text box: Rolled back version of Adobe reader to previous version allowing them to work
- Post Reply
- Response text box: In the meantime, I will research why the new version doesn't work on the accounting department's hardware
- Post Reply


![image](https://github.com/ArmandiJ/ticket-lifecycle/assets/153237878/0d6e237e-8540-44ac-b8b2-4e57aff8e0cf)


<h2>Resolution</h2>

- Once issue is resolved head back to the ticket and update the end user
- Response text box: Figured out the problem, re-upgraded everyone's computer, so all computers are working now
- Under Ticket Status select resolved
- Post Reply
- The ticket will now under the closed tab since it has been resolved

  ![image](https://github.com/ArmandiJ/ticket-lifecycle/assets/153237878/6ca63c18-50af-428e-8c90-25a223fea09d)

