<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
TThis tutorial provides a step-by-step explanation of a ticket's journey within osTicket, the open-source help desk system. We'll break down the key stages, from initial ticket creation and agent assignment to resolution and closure, in an easy-to-understand way.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines: Windows 10 recommend for this guide)
- RD Client
- osTicket System Software

<h2>Operating Systems Used </h2>

- Windows 10 Pro

-----

<h2>Creating Tickets</h2>
<p>To create a ticket in osTicket, follow these steps:</p>

- Log in as an **agent** using the login info you've from the previous tutorial. *(Hint: the agents you've created 'Jane' and 'John', you've set up their username and password as a way to login and have access to checking out the tickets.)*
    - Navigate to the "Tickets" section.
    - Click on "Open New Ticket."
    - Fill out the ticket details, including the requester, subject, and description.
    - Assign it to the relevant department or team.

- Tickets in osTicket go through various stages, from creation to resolution:
    - New: The ticket is newly created and awaiting assignment.
    - Open: The ticket has been assigned and is in the process of being addressed.
    - Overdue: The ticket has exceeded its expected resolution time.
    - Resolved: The issue has been resolved, and the ticket is waiting for confirmation from the requester.
    - Closed: The ticket is closed after successful resolution and confirmation.

<h3>Ticket Examples:</h3>
<p>Let's explore some ticket examples to better understand how to handle them within osTicket:</p>

- Sev-A (1 hour, 24/7) - [Entire Mobile/Online Banking System is Down]
    - Severity: Critical
    - Description: The entire mobile and online banking system is down, affecting customers.
    - Assignment: Assign this ticket to the "SysAdmins" department for immediate action.

- Sev-B (4 hours, 24/7) - [Accounting Department Needs Adobe Upgrade, Broken]
    - Severity: High
    - Description: The accounting department requires an Adobe upgrade due to a broken installation.
    - Assignment: Assign this ticket to the relevant department responsible for software upgrades.

- Sev-B/C (2 hours, business hours) - [CFO’s Laptop Seems a Bit Slow]
    - Severity: Medium
    - Description: The CFO's laptop is experiencing performance issues, and it needs attention.
    - Assignment: Assign this ticket to the IT department during business hours for investigation.

<p>Remember, the severity levels (Sev-A, Sev-B, etc.) help prioritize and categorize tickets based on their impact and urgency. It's crucial to handle tickets promptly and efficiently to ensure a smooth ticketing process.</p>

-----

<h1>Conclusion</h1>
Feel free to practice creating, triaging, and solving these ticket examples to become proficient in using osTicket. This hands-on experience will be invaluable for your portfolio and future ticket-handling tasks. Happy ticketing!
