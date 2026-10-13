\# SupportFlow - System Requirements



\## Overview



SupportFlow is an IT support ticketing and incident management system designed to simulate a real-world service desk workflow.



The application allows users to report technical issues, support agents to manage and resolve incidents, and administrators to manage the support environment.



\## User Roles



\### Customer



A customer can:



\- Create support tickets

\- View their own tickets

\- Add comments to their tickets

\- Follow the status of reported incidents



\### Support Agent



A support agent can:



\- View support tickets

\- Assign tickets to themselves

\- Change ticket status

\- Add comments

\- Resolve incidents



\### Administrator



An administrator can:



\- Perform support agent actions

\- Manage users

\- Manage ticket categories

\- Access system management functionality



\## Ticket Workflow



Tickets can have the following statuses:



\- Open

\- In Progress

\- Waiting for User

\- Resolved

\- Closed



\## Ticket Priorities



Tickets can have the following priorities:



\- Low

\- Medium

\- High

\- Critical



\## Core Functional Requirements



\### FR-01 - User Authentication



Users must be able to authenticate before accessing protected functionality.



\### FR-02 - Ticket Creation



Authenticated customers must be able to create a support ticket containing:



\- Title

\- Description

\- Category

\- Priority



\### FR-03 - Ticket Assignment



Support agents must be able to assign an unassigned ticket to themselves.



\### FR-04 - Ticket Status Management



Support agents must be able to change the status of a ticket.



\### FR-05 - Ticket Comments



Users and support agents must be able to add comments to tickets they are authorised to access.



\### FR-06 - Status History



The system must record ticket status changes, including:



\- Previous status

\- New status

\- User responsible for the change

\- Date and time of the change



\### FR-07 - Category Management



Administrators must be able to create and manage ticket categories.



\## Initial Non-Functional Requirements



\- The application must use authenticated access.

\- User permissions must depend on their assigned role.

\- Input must be validated before being stored.

\- Database relationships must preserve data integrity.

\- API responses must use appropriate HTTP status codes.

\- Core application behaviour should be covered by automated tests.

