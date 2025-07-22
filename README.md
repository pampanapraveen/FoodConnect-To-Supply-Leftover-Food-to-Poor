# FoodConnect-To-Supply-Leftover-Food-to-Poor
## 🎬 Demo Video

Watch the demo video [here](https://drive.google.com/file/d/1kpXndSnu7L2jpXmfva0OBzScDG0iz3c-/view?usp=sharing)


FoodConnect – Salesforce CRM Project
Connecting leftover food donors to needy communities efficiently.

🚀 Project Overview
FoodConnect is a Salesforce CRM application designed to manage leftover food donation processes. It registers donor venues, automates pickup and delivery tasks, allocates volunteers based on availability, and generates insightful reports to minimise food wastage and ensure operational transparency.

🎯 Objectives
Register venues donating leftover food with drop-off points.

Automate task creation for food pickup and delivery.

Allocate volunteers efficiently based on availability.

Track pickups, deliveries, and execution details.

Provide reports and dashboards for operational monitoring and planning.

🔍 Phase I: Requirement Analysis & Planning
➡️ Understanding Business Requirements
Venues: Register food availability and drop-off locations.

Volunteers: Receive precise task allocations with location details.

Admin: Monitor tasks in real-time.

Organisation: Access operational data for reporting and planning drives.

➡️ Project Scope
Develop custom objects (Venue, Drop-Off Point, Task, Volunteer, Execution Details).

Automate task record creation flows.

Add triggers for status updates.

Create reports and dashboards.

Configure profiles, roles, and sharing rules.

➡️ Data & Security Model
Objects: Venue, Drop-Off Point, Task, Volunteer, Execution Details.

Security: NGO profile for volunteers/coordinators. Sharing rules based on drop-off point distances (Iksha group <15km, NSS group 15-30km, Street Cause group 30-50km).

💻 Phase II: Salesforce Development – Backend & Configurations
⚙️ Environment Setup
Created Salesforce Developer Org for implementation.

⚙️ Customization
Objects & Fields: Developed objects with required fields for Venue, Drop-Off Point, Task, Volunteer, and Execution Details.

⚙️ Automation
Flows: Auto-create Task records upon Venue creation.

Triggers: On Drop-Off Point insert, update related Task status to “Ready for Delivery”.

🎨 Phase III: UI/UX Development & Customisation
Lightning App: Created “FoodConnect” app with tabs for all objects.

Page Layouts & Dynamic Forms: Designed for efficient view and editing.

User Management: Profiles for System Admin, NGO coordinators, volunteers.

Reports & Dashboards:

Venue and Drop-Off Point reports

Volunteer Task reports

Operations dashboard: Tasks status and volunteer utilisation

🔐 Phase IV: Data Migration & Security
Data Loading: Used Salesforce Data Import Wizard for bulk Venue data upload.

Security: Configured profiles and distance-based sharing rules to enhance data safety and localised task allocation.

🚀 Phase V: Deployment, Documentation & Maintenance
Deployment: Developed and tested within Salesforce Developer Org.

Documentation: Documented features, flows, triggers, and sharing rules with screenshots for clarity.

Maintenance: Reviewed flows and triggers periodically, debugged errors, gathered user feedback for enhancements.

✅ Conclusion
FoodConnect streamlines leftover food distribution by:

Automating pickups and delivery assignments.

Monitoring drop-off locations and execution details.

Minimising manual efforts with flows and triggers.

Applying effective security and sharing rules.

🌟 Future Enhancements
WhatsApp notifications

AI-based volunteer scheduling

Chatbot integration for improved accessibility

🙏 Thank You
Developed by P. Praveen

📧 College Email: 22341A1281@gmrit.edu.in

📧 Registered Email: ppraveenbye@gmail.com
