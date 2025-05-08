# BizDevOps Reference Architecture - Architectural Building Block

[PDF Version](/files/BizDevOps%20Reference%20Architecture%20-%20Architectural%20Building%20Blocks.pdf)

This appendix presents textual descriptions of the Architectural Building Blocks (ABB) specified for BizDevOps-RA. Each ABB is detailed according to the layer and/or aspect it belongs to within the ArchiMate 3.2 full framework. Specifically, the last ABB, Location, is classified under the “_Others_” section because it does not belong to any of the defined layers or aspects. For each ABB, the corresponding ArchiMate notation element, the ABB code (_dct:type_), and its definition (_dct:definition_) are provided, with the latter being part of the ABB metadata.

The visualization of each of these ABBs in the form of ArchiMate views (diagrams) can be accessed at the following [link](https://guillermofuentesuclm.github.io/BizDevOps-RA/).

## Strategy Layer

This section presents the ABBs represented with elements of the ArchiMate Strategic layer.

 ### BizDevOps Capability

- **ArchiMate Notation Element:** Capability
- **Building Block Code (dct:type):** BDO:BizDevOpsCapability
- **Definition (skos:definition):** This capability represents the organization's ability or capacity to develop software with BizDevOps. It ensures an agile alignment of IT with the business while preserving the benefits and characteristics of DevOps.

 ### IT/Business Alignment while Ensuring Agility

- **ArchiMate Notation Element:** Course of Action
- **Building Block Code (dct:type):** BDO:AgileITBusinessAlignment
- **Definition (skos:definition):** IT/Business Alignment while Ensuring Agility involves implementing strategies and practices that align IT services with business objectives while maintaining flexibility and responsiveness. This includes adopting agile ways of working, fostering continuous collaboration, and ensuring rapid adaptation to changing business needs and market conditions.

## Business Layer

This section presents the ABBs represented with elements of the ArchiMate Business layer.

 ### Agility Manager

- **ArchiMate Notation Element:** Business Role
- **Building Block Code (dct:type):** BDO:AgilityManager
- **Definition (skos:definition):** In BizDevOps, this role ensures the team remains agile across all phases of the approach. They create an environment for efficient and productive work. In Scrum and similar frameworks, this role is often filled by the Scrum Master.

 ### Alignment

- **ArchiMate Notation Element:** Business Process
- **Building Block Code (dct:type):** BDO:AlignmentProcess
- **Definition (skos:definition):** The Alignment Process in BizDevOps ensures that software development activities are continuously synchronized with business objectives. It integrates business and IT domains, aligning strategies, goals, and practices to maximize value delivery and maintain business agility.

 ### BizDevOps Software Development Function

- **ArchiMate Notation Element:** Business Function
- **Building Block Code (dct:type):** BDO:SwDevelopmentProcess
- **Definition (skos:definition):** The BizDevOps Software Development Process integrates business, development, and operations activities throughout the software lifecycle to ensure that delivered products effectively meet business and end-user needs. It includes phases such as exploration, prototyping, backlog creation, agile development, and continuous delivery.

 ### BizDevOps Team

- **ArchiMate Notation Element:** Business Role
- **Building Block Code (dct:type):** BDO:BizDevOpsTeam
- **Definition (skos:definition):** The BizDevOps Team is a cross-functional unit integrating business, development, and operations roles to ensure continuous IT alignment with business objectives and agility. It includes roles such as Product Owner and Agility Manager, supported by DevOps professionals.

 ### Building and Testing

- **ArchiMate Notation Element:** Business Process
- **Building Block Code (dct:type):** BDO:BuildingAndTestingProcess
- **Definition (skos:definition):** The Building and Testing Process in BizDevOps focuses on iterative product development and rigorous testing to ensure quality. The team employs continuous integration (CI) practices to develop, test, and integrate code automatically, enabling safe and efficient deployment into production. Initial product increments often focus on transforming a prototype into a Minimum Viable Product (MVP), which allows early user feedback for further refinement.

 ### Delivery and Operation

- **ArchiMate Notation Element:** Business Process
- **Building Block Code (dct:type):** BDO:DeliveryAndOperationProcess
- **Definition (skos:definition):** The Delivery and Operation Process in BizDevOps ensures efficient product deployment, monitoring, and maintenance. Key activities include continuous deployment, real-time monitoring, and ensuring product operation aligns with business requirements and user expectations.

 ### DevOps Roles

- **ArchiMate Notation Element:** Business Role
- **Building Block Code (dct:type):** BDO:DevOpsRoles
- **Definition (skos:definition):** DevOps roles encompass a variety of responsibilities that ensure continuous integration, delivery, and deployment of software. These roles include IT Development and Operations, DevOps Architects, Site Reliability Engineers (SREs), and other specialized positions that facilitate automation, collaboration, and efficiency in software delivery.

 ### Discovery

- **ArchiMate Notation Element:** Business Process
- **Building Block Code (dct:type):** BDO:DiscoveryProcess
- **Definition (skos:definition):** The Discovery Process in BizDevOps is a fundamental phase that focuses on identifying and understanding customer needs and problems, as well as exploring new market opportunities. This phase ensures alignment between business objectives and technical capabilities by gathering insights from business experts, analysts, and key users. The process includes defining high-level business goals, establishing a clear product vision, and formulating hypotheses that guide further experimentation and validation through user feedback.

 ### Internal Agreement

- **ArchiMate Notation Element:** Contract
- **Building Block Code (dct:type):** BDO:InternalAgreement
- **Definition (skos:definition):** Internal agreements establish shared objectives, roles, responsibilities, and collaboration protocols among team members. These agreements support efficiency and quality in BizDevOps processes by aligning expectations across business, development, and operations teams.

 ### Minimum Viable Product (MVP)

- **ArchiMate Notation Element:** Product
- **Building Block Code (dct:type):** BDO:MVP
- **Definition (skos:definition):** The MVP represents the initial version of a product with the essential features required to address core business needs and validate market assumptions. It serves as the foundation for iterative development and continuous improvement based on user feedback.

 ### MVP Business Information


- **ArchiMate Notation Element:** Business Object
- **Building Block Code (dct:type):** BDO:MVPBizInformation
- **Definition (skos:definition):** Business information associated with an MVP includes key data and insights gathered from the MVP’s performance, user interactions, and feedback. This information helps validate assumptions, guide further development, and inform strategic decisions to improve the product.

 ### MVP Business Process

- **ArchiMate Notation Element:** Business Process
- **Building Block Code (dct:type):** BDO:MVPBizProcess
- **Definition (skos:definition):** An MVP (Minimum Viable Product) business process is the simplest, most streamlined version of a business process that achieves its primary objectives. It includes only the essential steps and elements needed to validate the process's effectiveness, gather feedback, and make iterative improvements with minimal resources and risk.

 ### MVP Service

- **ArchiMate Notation Element:** Business Service
- **Building Block Code (dct:type):** BDO:MVPService
- **Definition (skos:definition):** An MVP (Minimum Viable Product) business service is the simplest version of a service that delivers core functionality to meet initial business goals and customer needs. It includes only essential features to validate the service concept, gather user feedback, and iterate on improvements with minimal investment and risk.

 ### Planification

- **ArchiMate Notation Element:** Business Process
- **Building Block Code (dct:type):** BDO:PlanificationProcess
- **Definition (skos:definition):** The Planification Process in BizDevOps is a crucial stage where realistic timelines, resources, and project milestones are set. This phase involves creating a detailed roadmap that outlines the necessary steps to deliver the product, ensuring that all team members are aligned and prepared for execution. Continuous planning allows teams to iteratively refine priorities, address dependencies, and adjust strategies to optimize product delivery.

 ### Product Owner

- **ArchiMate Notation Element:** Business Role
- **Building Block Code (dct:type):** BDO:ProductOwner
- **Definition (skos:definition):** The Product Owner in BizDevOps is responsible for maximizing the value of the product by ensuring that development efforts align with business needs. This role involves defining the product vision, managing the backlog, and prioritizing tasks to ensure alignment between business objectives and technical execution. The Product Owner acts as a bridge between stakeholders and development teams, fostering collaboration and ensuring that delivered features provide tangible business value.

## Application Layer

This section presents the ABBs that are represented with elements of the ArchiMate
Application layer.

 ### MVP Application

- **ArchiMate Notation Element:** Application Component
- **Building Block Code (dct:type):** BDO:MVPApplication
- **Definition (skos:definition):** The MVP Application represents a modular, self-contained unit of software that provides specific functionality required by the service. It supports the execution of the MVP business process by delivering essential features and enabling efficient development and deployment.

 ### MVP Application Data

- **ArchiMate Notation Element:** Data Object
- **Building Block Code (dct:type):** BDO:MVPApplicationData
- **Definition (skos:definition):** Application Data associated with an application component refers to the specific data that the component creates, processes, stores, and manages. This data supports the functionality provided by the application component and is crucial for the operation of the application service.

 ### MVP Application Function

- **ArchiMate Notation Element:** Application Function
- **Building Block Code (dct:type):** BDO:MVPApplicationFunction
- **Definition (skos:definition):** The Application Function is a unit of behavior performed by an application component that provides specific functionality necessary for the realization of an Application Service. It represents the internal processing, actions, or tasks that the application executes to deliver its defined services, aligning with business requirements and technical capabilities.

 ### MVP Application Service

- **ArchiMate Notation Element:** Application Service
- **Building Block Code (dct:type):** BDO:MVPApplicationService
- **Definition (skos:definition):** An application service associated with an MVP business process exposes the services offered by an application, which are necessary to support the initial and optimized version of a business process.

## Technology & Physical Layer

This section presents the ABBs that are represented with elements of the ArchiMate
Technology & Physical layer.


 ### BizDevOps Bus Service

- **ArchiMate Notation Element:** Technology Service
- **Building Block Code (dct:type):** BDO:BizDevOpsBusTechService
- **Definition (skos:definition):** The BizDevOps Bus Service provides an integrated set of tools and practices to support collaboration between business, development, and operations, ensuring alignment and continuous delivery of value.

 ### Communication Network

- **ArchiMate Notation Element:** Communication Network
- **Building Block Code (dct:type):** BDO:CommunicationNetwork
- **Definition (skos:definition):** A Communication Network representing the infrastructure that enables the exchange of information between devices and systems within the BizDevOps approach, ensuring connectivity and data flow required for collaboration, integration, and continuous delivery processes.

 ### Device

- **ArchiMate Notation Element:** Device
- **Building Block Code (dct:type):** BDO:Device
- **Definition (skos:definition):** A Device representing a physical hardware resource within the BizDevOps approach, such as servers, workstations, or network equipment, that provides the foundational infrastructure necessary to support the execution of software components and delivery of services.

 ### Expose Way

- **ArchiMate Notation Element:** Technology Interface
- **Building Block Code (dct:type):** BDO:ExposeWay
- **Definition (skos:definition):** A Technology Interface representing the means by which technology services or functions are exposed and made accessible within the BizDevOps approach, enabling integration, communication, and interaction between different components or systems.

 ### Node

- **ArchiMate Notation Element:** Node
- **Building Block Code (dct:type):** BDO:Node
- **Definition (skos:definition):** A Node representing a physical or virtual computational resource within the BizDevOps approach, responsible for hosting, executing, and supporting application components and infrastructure services critical to enabling continuous integration, delivery, and deployment processes.

 ### Path

- **ArchiMate Notation Element:** Path


- **Building Block Code (dct:type):** BDO:Path
- **Definition (skos:definition):** A Path element representing the logical or physical connection between different system components, ensuring seamless data flow and integration to support BizDevOps processes.

 ### System Software

- **ArchiMate Notation Element:** System Software
- **Building Block Code (dct:type):** BDO:SystemSoftware
- **Definition (skos:definition):** A System Software element representing foundational software components such as operating systems or middleware that support the execution of processes and services within the BizDevOps approach.

 ### Technology Function

- **ArchiMate Notation Element:** Technology Function
- **Building Block Code (dct:type):** BDO:TechFunction
- **Definition (skos:definition):** A Technology Function representing the internal technical capabilities required to support and enable specific services or processes within the BizDevOps approach, focusing on automation, integration, and continuous delivery practices.

## Motivation

This section presents the ABBs that are represented with elements of the ArchiMate
Motivation aspect.

 ### Agile Software Development

- **ArchiMate Notation Element:** Driver
- **Building Block Code (dct:type):** BDOAgileSwDevelopmentDriver
- **Definition (skos:definition):** An Agile Software Development Driver is a motivating factor that promotes the adoption of agile methodologies to enhance flexibility, speed, and collaboration in software development. It aims to deliver high-quality software incrementally, respond quickly to changes, and meet customer needs effectively through iterative development and continuous feedback.

 ### Agility

- **ArchiMate Notation Element:** Principle
- **Building Block Code (dct:type):** BDO:AgilityPrinciple
- **Definition (skos:definition):** Incorporates agility throughout all operational cycles.

 ### Agility is Maintained in the SW project

- **ArchiMate Notation Element:** Assessment
- **Building Block Code (dct:type):** BDO:AgilityMaintainedAssessment


- **Definition (skos:definition):** Agility is Maintained in the SW project is an assessment indicating that the organization continues to operate with flexibility and responsiveness. It ensures that processes, teams, and technologies can quickly adapt to changes, meet evolving customer needs, and support continuous improvement and innovation.

 ### Alignment

- **ArchiMate Notation Element:** Principle
- **Building Block Code (dct:type):** BDO:AlignmentPrinciple
- **Definition (skos:definition):** Ensures continuous alignment of IT initiatives with business objectives.

 ### Architecture Principle

- **ArchiMate Notation Element:** Principle
- **Building Block Code (dct:type):** BDO:ArchitecturePrinciple
- **Definition (skos:definition):** Architecture principles are fundamental guidelines and rules that inform and shape the design, development, and evolution of an organization's systems and structures, ensuring alignment with business goals and effective decision-making.

 ### BizDevOps Principle

- **ArchiMate Notation Element:** Principle
- **Building Block Code (dct:type):** BDO:BizDevOpsPrinciple
- **Definition (skos:definition):** BizDevOps principles are fundamental guidelines that integrate business, development, and operations practices to enhance collaboration, accelerate delivery, and align IT efforts with business objectives.

 ### Business First

- **ArchiMate Notation Element:** Principle
- **Building Block Code (dct:type):** BDO:BusinessFirstPrinciple
- **Definition (skos:definition):** Prioritizes organizational objectives over technical details.

 ### Business Need

- **ArchiMate Notation Element:** Requirement
- **Building Block Code (dct:type):** BDO:BusinessNeed
- **Definition (skos:definition):** Business needs are the essential requirements and demands an organization must fulfill to achieve its strategic and operational goals, such as improving efficiency, increasing profitability, expanding market share, and enhancing customer satisfaction.

 ### Continuity in Everything


- **ArchiMate Notation Element:** Principle
- **Building Block Code (dct:type):** BDO:ContinuityInEverythingPrinciple
- **Definition (skos:definition):** Utilizes automated practices across business, development, and operations to maintain continuous process flow.

 ### Customer Focus

- **ArchiMate Notation Element:** Principle
- **Building Block Code (dct:type):** BDO:CustomerFocusPrinciple
- **Definition (skos:definition):** Adopts a customer-centered approach, prioritizing tasks to deliver maximum value and effectively managing risks.

 ### Enterprise Objective

- **ArchiMate Notation Element:** Goal
- **Building Block Code (dct:type):** BDO:EnterpriseObjetive
- **Definition (skos:definition):** Enterprise objectives are the strategic goals and targets that an organization aims to achieve to ensure its long-term success and growth.

 ### Functional Requirement

- **ArchiMate Notation Element:** Requirement
- **Building Block Code (dct:type):** BDO:FunctionalRequirement
- **Definition (skos:definition):** Specifications of the functions a system or component must perform, including inputs, outputs, and behaviors under various conditions.

 ### Integrated Team

- **ArchiMate Notation Element:** Principle
- **Building Block Code (dct:type):** BDO:IntegratedTeamPrinciple
- **Definition (skos:definition):** Rather than having separate teams, BizDevOps involves a unified team with roles spanning business, development, and operations to collaboratively meet software needs.

 ### IT/Business Alignment

- **ArchiMate Notation Element:** Driver
- **Building Block Code (dct:type):** BDO:ITBizAlignmentDriver
- **Definition (skos:definition):** An IT/Business Alignment Driver is a motivating factor that ensures IT strategies and services are integrated with and support business goals. This alignment enhances efficiency, drives competitive advantage, and creates value for the organization by ensuring that IT capabilities directly contribute to business success.


 ### Non-Functional Requirement

- **ArchiMate Notation Element:** Requirement
- **Building Block Code (dct:type):** BDO:NonFunctionalRequirement
- **Definition (skos:definition):** Criteria that define the quality attributes of a system, such as performance, usability, reliability, security, compatibility, maintainability, and portability.

 ### Shift-Left

- **ArchiMate Notation Element:** Principle
- **Building Block Code (dct:type):** BDO:ShiftLeftPrinciple
- **Definition (skos:definition):** Anticipates tasks typically performed at the later stages of development, such as quality and security testing, to address them earlier in the lifecycle.

### Systems Thinking

- **ArchiMate Notation Element:** Principle
- **Building Block Code (dct:type):** BDO:SystemsThinkingPrinciple
- **Definition (skos:definition):** Promotes a comprehensive understanding of the system from start to finish, aiding in the resolution of complex issues that may arise.

### SW project is aligned with business

- **ArchiMate Notation Element:** Assessment
- **Building Block Code (dct:type):** BDO:ITBusinessAlignmentAssessment
- **Definition (skos:definition):** SW project is aligned with business is an assessment indicating that IT initiatives, resources, and strategies effectively support and enhance business goals. This alignment ensures cohesive operations, maximizes efficiency, and drives organizational success by ensuring that IT contributions are directly aligned with business needs and objectives.

## Other

This section presents the ABB that is represented by an element that does not belong to a
particular layer or aspect of ArchiMate.

### Location

- **ArchiMate Notation Element:** Location
- **Building Block Code (dct:type):** BDO:Location
- **Definition (skos:definition):** A Location representing a specific physical or logical place within the BizDevOps approach where organizational, technological, or operational resources are situated or interact, facilitating the alignment of business and IT activities.



