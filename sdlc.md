Hola hola,

This document is meant to provide a complete overview of the THT Software Development Lifecycle (SDLC) moving forward.

Here is a list of operational issues that this document, and this new SDLC aims to address:

1. Client Requirements are received and Tickets are created and added to the Backlog column of the relevant GitHub Project.
2. Tickets receive tags: **_Mobile, Web, Android, iOS, Bug, Feature Request, Build Task, Good First Task_**, **_Severity 1, Severity 2, Severity 3_, _Needs More Info_**.
3. Tickets are added to the **Ready For Designs** column.
4. When the Designer is finished with the Ticket, or the Designer needs some guidance/feedback, the Ticket should be moved to the **Needs Design QA/Feedback** column.
5. When Design QA/Feedback is finished, the Ticket should be moved to the **Ready For Development** column.
6. When the Developer is finished with the Ticket, or the Developer needs some guindance/feedback, the Ticket should be moved to the **Needs Dev QA/Feedback** column.
7. When Development QA/Feedback is finished, a PR should be opened to merge the solution into the `dev` branch and the Ticket should be moved to the **PR Open** column.
8. When the PR has been tested, the PR should be merged into the `dev` branch.
9. On **Monday** and **Wednesday**, a PR from the `dev` branch should be opened to merge recent updates to the `staging` branch.
10. On **Tuesday** and **Thursday**, the open PR should be merged to the `prod` branch.
11. All Tickets for the PR should be moved to the **Done** column.
