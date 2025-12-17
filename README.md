# CSS-255-System-Analysis-and-Design
The DriverPass project focused on designing a comprehensive driver-training system for a new company called DriverPass. The client was Liam (the owner), and he wanted a cloud-based, web-accessible system that works from both computers and mobile devices so the business and customers can access information anywhere. 

Project one document

 The system was intended to help customers pass DMV driving tests through structured training, while also keeping course content current by integrating DMV updates and notifications about rule or policy changes. 

Project one document

One thing I did particularly well was translating the interview needs into clear functional and nonfunctional requirements that covered both customer and employee workflows. For example, I captured core capabilities like account creation, test progress tracking, appointment scheduling, role-based access for different staff roles, reservation history/audit tracking, and DMV update notifications. 

Project one document

 I also included practical quality attributes like cross-platform browser access, quick page performance targets, and security controls like encryption and account lockouts. 

Project one document

 

Project one document

 On the system design side, I did a solid job mapping these needs into technical requirements such as using a relational database, implementing authentication with password reset workflows, logging key actions, and supporting scheduling logic that prevents double-booking. 

CS 255 System Design Document T…

If I could revise one part of my work, I would strengthen the “how” behind a few major integrations and edge cases—especially the DMV update integration and the operational maintenance side of the system. I would improve it by being more explicit about how DMV updates enter the system (API vs. batch updates), what happens when updates fail, and how admins verify and publish updated content. I’d also refine the limitations/assumptions into more actionable risk items, since the design depends on internet availability and external vendors like the DMV and payment providers, and offline access would be read-only. 

Project one document

To interpret the user’s needs, I broke the system into user groups (customers, secretary/admin staff, IT officer, and owner) and then mapped each group’s goals into features and access rules. For customers, that included accounts, progress monitoring, and receiving updates; for staff, it included scheduling, preventing reservation duplication, password resets, and accountability tracking for changes. 

Project one document

 Designing around user needs is critical because it’s how you ensure the system is actually usable and adopted—if the workflows don’t match what users are trying to do (or don’t protect them with the right security and permissions), the system will either be avoided, misused, or require expensive rework later. 

Project one document

When I approach software design, I start by clarifying the problem, identifying the users and their top tasks, and then turning those tasks into requirements I can trace through models and implementation decisions. Going forward, I’d keep using techniques like use cases and UML diagrams for behavior, a data model for structure, and a simple traceability checklist that ties every major requirement to a design element (screen, service, database table, or rule). I’d also lean more into iterative review—prototyping key screens early, validating role-based access assumptions, and writing acceptance criteria so testing and maintenance stay aligned with what the system was built to accomplish.

Sources
remove the links on to the documents. Instead just use the naem

The DriverPass project focused on designing a comprehensive driver-training system for a new company called DriverPass. The client was Liam (the owner), and he wanted a cloud-based, web-accessible system that works from both computers and mobile devices so the business and customers can access information anywhere. This is described in the “CS 255 System Design Document Template Project Two” document. The system was also intended to help customers pass DMV driving tests through structured training, while keeping course content current by incorporating DMV updates and notifying users when rules or policies change, which is also explained in the Project Two system design document.

One thing I did particularly well was translating the interview and project needs into clear functional and nonfunctional requirements that covered both customer and employee workflows. In the “Project One Document,” I captured core capabilities like account creation, appointment scheduling, tracking test progress, role-based access, reservation history/audit tracking, and update notifications. I also included practical quality expectations like cross-platform access, performance considerations, and security requirements like password protections and account lockouts, which are reinforced in the “CS 255 System Design Document Template Project Two” document.

If I could revise one part of my work, I would strengthen the detail around integrations and edge cases—especially the DMV update process and ongoing maintenance workflows. I would improve it by being more specific about how updates enter the system, how failures are handled, and how admins verify and publish new or changed content. I’d also expand on system limitations and assumptions to connect them more directly to risks and mitigation steps (for example, internet outages, vendor dependencies, and what limited offline access would look like), which would make the design even more realistic and implementation-ready.

To interpret the user’s needs, I first identified the main user groups (customers, secretary/admin staff, IT officer, and the owner) and then mapped each group’s goals into system features and access controls. Customers needed accounts, scheduling, training support, and progress visibility; staff needed tools to manage schedules, avoid duplicate reservations, reset passwords, and maintain accountability through logging and reporting. Considering user needs is crucial because it determines whether the system is usable, secure, and actually solves the real problems—if the workflows don’t match how users operate, the system becomes frustrating, leads to mistakes, and creates expensive rework later.

When I approach software design, I start by clarifying goals, defining users and their tasks, turning those tasks into requirements, and then tracing those requirements into models and technical decisions. In the future, I would keep using techniques like use cases and UML diagrams for behavior, a database/data model for structure, and traceability so every requirement clearly connects to a design element. I would also use more early validation, like quick prototypes and acceptance criteria, so testing and maintenance stay aligned with what the system is supposed to deliver.
