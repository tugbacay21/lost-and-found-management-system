# System Vision and Boundary

## 1. Project Purpose
The Lost and Found Management System is a web-based application designed to help university students and staff report, search for, and recover lost belongings. The system aims to replace fragmented communication methods with a centralized, accessible, and organized platform.

## 2. Target Users
- Students: Report lost items, search for found items, and submit ownership claims.
- University staff: Report found belongings and assist with item recovery.
- Administrators: Review reports, manage inappropriate content, and oversee claim resolution.

## 3. System Responsibilities and Core Functionalities
The system will provide the following core functionalities:
- User registration and login.
- Creation of lost-item and found-item reports.
- Item descriptions, categories, locations, dates, and optional images.
- Searching and filtering item reports.
- Submission and tracking of ownership claims.
- Administrative review of reports and claims.
- Updating item status, such as Open, Claimed, and Resolved.

## 4. System Context and External Interactions
Users will access the system through a web browser. The frontend will communicate with a backend REST API. The backend will validate requests, apply business rules, and store information in a database.

External interactions may include:
- An image storage service for uploaded item photographs, if needed.
- An email notification service, if implemented in a later sprint.

These optional integrations are not required for the initial minimum viable product (MVP).

## 5. In-Scope Features
The initial project scope includes:
- Basic user authentication and role-based access.
- Creating and viewing lost and found reports.
- Searching and filtering reports.
- Submitting ownership claims.
- Basic administrator moderation.
- Managing report and claim statuses.

## 6. Out-of-Scope Features
The following features are excluded from the initial MVP:
- Native Android or iOS applications.
- GPS-based real-time item tracking.
- AI-powered image recognition or automatic item matching.
- Payment processing and delivery services.
- Integration with external university information systems.
- Real-time chat between users.

## 7. Constraints
- The project will be developed within the university course schedule and four sprint structure.
- Development resources and team availability are limited.
- The application must follow basic security and privacy principles.
- Sensitive user information and credentials must not be exposed in the public repository.
- The system must be usable through modern desktop and mobile web browsers.

## 8. Assumptions
- Users have internet access and a modern web browser.
- Users provide reasonably accurate item descriptions.
- University staff or designated administrators are available to review disputed claims.
- The university community is willing to use a centralized lost and found platform.
- The project team can use open-source development tools.

## 9. System Boundary Summary
The system is responsible for managing reports, searches, claims, moderation, and status updates. It does not physically store, transport, or guarantee the return of lost items. Final ownership verification and physical handover may require coordination outside the application.

## 10. Expected Benefits
- Faster discovery of reported lost and found belongings.
- Reduced dependence on scattered social media and messaging groups.
- Better organization and tracking of ownership claims.
- A clearer process for students, staff, and administrators.

## 11. Document Status
Initial Sprint 1 draft. Functional details and optional integrations may be refined during subsequent sprints.
