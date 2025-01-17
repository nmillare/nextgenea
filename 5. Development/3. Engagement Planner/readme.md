# Spec for Engagement Planner
![Engagement Planner](https://github.com/I304296/nextgenea/blob/main/images/EngagementPlanner.png)
Functional Specifications Document (Engagement Planner)
1. Introduction
1.1 Purpose
	•	The purpose of this document is to outline the functional specifications for the "Engagement Planner" development, which aims to provide a platform for teams to manage their tasks and projects using Enterprise 		Architecture methodology.
1.2 Scope
	•	This project will cover the development of an Engagement Planner BTP app, including user registration, task creation, and progress tracking. It will not cover integration with external project management tools.
2. Overall Description
2.1 Product Perspective
	•	The Engagement Planner is a standalone web application that helps teams organize their work using Enterprise Architecture practices. It integrates with email services for notifications.
2.2 Product Functions
	•	The main functions include user registration, task creation, backlog management, and progress tracking.
2.3 User Characteristics
	•	The target users are Enterprise Architects who are familiar with Enterprise Architecture methodology. They may have varying levels of technical proficiency.
3. Specific Requirements
3.1 Functional Requirements
	•	Use Case: User Registration
	o	Description: Users must be able to create an account by providing their email, password, and personal details.
	o	User Story: As a new user, I want to register an account so that I can access the Engagement Planner.
	•	User Story: As a team member, I want to create tasks so that I can track my work.
	•	Functional Requirement: The system shall allow users to create and assign tasks to sprints.
	o	User Story: As a team member, I want to assign tasks to sprints so that I can organize my work within specific time frames.
	•	User Story: As a project manager, I want to view the product backlog so that I can prioritize tasks for upcoming sprints.
	•	User Story: As a team member, I want to update the status of my tasks so that I can keep the team informed of my progress.
3.3 Interface Requirements
	•	User Interface: The dashboard should display the current sprint, backlog, and task status.
	o	User Story: As a team member, I want to see the current sprint and task status on the dashboard so that I can quickly understand the project's progress.
	•	API: The system should provide a RESTful API for retrieving task details.
	o	User Story: As a developer, I want to access task details via an API so that I can integrate the system with other tools.
3.4 System Features
	•	The system should allow users to view their task history and track the status of their tasks.
	o	User Story: As a team member, I want to view my task history so that I can review my past work and track my progress.
4. Data Requirements
4.1 Data Models
	•	The data model includes tables for users, tasks, sprints, and notifications. Each table has fields such as userid, taskid, otherid, and notificationid.
	o	User Story: As a database administrator, I want to understand the data models so that I can manage the database effectively.
4.2 Data Storage
	•	Data will be stored in a relational database (e.g., PostgreSQL). Backups will be performed daily.
	o	User Story: As a system administrator, I want to ensure data is backed up daily so that we can recover from data loss.
5. External Interface Requirements
5.1 User Interfaces
	•	The user interface should include a dashboard, task creation page, sprint planning page, and backlog management page.
	o	User Story: As a user, I want an intuitive interface so that I can easily navigate and use the system.
