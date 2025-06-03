a) Purpose 
The primary purpose of the On-Road Vehicle Breakdown Assistance System is to:

Enable real-time roadside assistance: Use GPS and mapping APIs to locate and dispatch the closest qualified mechanic to a driver’s broken-down vehicle, reducing response times, especially in remote or underserved areas.

Streamline service ordering: Provide an intuitive interface for drivers to request services such as towing, tire changes, and fuel delivery—eliminating the delays of traditional call centers.

Enhance transparency and efficiency: Offer status updates, estimated time of arrival (ETA), and pricing information to both drivers and mechanics, building trust and optimizing operations.

Note: Every component and process within the system is also illustrated through detailed diagrams, ensuring clarity of system architecture, data flow, and user interaction.

The Software Requirements Specification (SRS) document is 
designed to: 
1. Define clear requirements: Articulate exactly what the system must do 
(functional requirements) and how well it must perform (non-functional 
requirements), reducing ambiguity. 
2. Align stakeholder expectations: Serve as a formal agreement 
between clients, mechanics, admins, and the development team on system 
scope, features, and constraints. 
3. Guide development and testing: Provide a roadmap for architects, 
developers, and QA analysts to design, implement, and validate the system 
against documented standards. 
4. Mitigate project risks: By detailing requirements upfront, identify 
potential issues early, enable accurate cost and schedule estimates, and 
minimize costly changes during later development phases.

b) Project Scope 
The scope of the system covers three user-facing modules—Client, 
Mechanic, and Admin—plus shared Authentication Services, enabling 
clients to locate mechanics, place and manage service orders, submit 
feedback, and share real-time location; mechanics to view and fulfill orders, 
offer prices, and update availability; and admins to manage user accounts, 
approve or block mechanics, and generate system reports. The SRS 
explicitly excludes payment processing, supply chain management, and 
advanced analytics beyond basic performance reporting. 

c) Glossary and Abbreviations 
Definitions for technical and non-technical terms. 
Client: A user who requests on-road vehicle repair services. 

Mechanic: A certified service provider who fulfills client orders. 
Admin: System operator with privileges to manage users and system data. 

ETA (Estimated Time of Arrival): Predicted time when a mechanic 
reaches the client's location. 

2FA (Two-Factor Authentication): Security mechanism requiring two 
forms of identity verification. 

MoSCoW: Prioritization scheme dividing requirements into Must, Should, 
Could, and Won't categories. 

SRS: Software Requirements Specification document that details system 
requirements. 

d) List of the System Stakeholders.  
Clients: End users who request and track services. 
Mechanics: Service providers who respond to orders and update service 
status. 
Admins: Internal staff who manage user accounts, mechanics, and system 
configurations. 
Developers: Engineers implementing the system components. 
Testers/QA Analysts: Personnel validating system functionality against 
requirements. 
Business Analysts/Product Owners: Individuals who define business 
needs and approve require 
