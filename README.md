# Consent and Royalties for AI Training Data

**C-SW312 – Introduction to Software Engineering**  
**Project 16 | Team 11**

## About the Project

This project is about creating a platform for the Arab Creators Rights Collective that helps content creators control how their work is used by AI companies.

The main problem is that some AI companies use creative content for training without getting permission from the original creators. Our proposed system aims to solve this by letting creators register their work, choose how it can be used, and receive royalties when their content is licensed.

The platform is also meant to help AI companies find and license Arabic content legally.

## Main Features

The system is planned to support the following features:

- **Creator Registration:** Creators can register, verify their identity, and upload their works or provide links to them.
- **Ownership Verification:** Uploaded works are checked using an external fingerprinting service to help detect ownership conflicts.
- **Consent Management:** Creators can choose which AI uses they allow for each work, including research, commercial training, and voice cloning.
- **Dataset Requests:** AI companies can browse available works and create dataset requests based on content type, language, dialect, and allowed use.
- **Licensing and Payments:** The platform calculates dataset prices, manages licensing agreements, and provides secure downloads after payment.
- **Royalties:** Creators receive quarterly royalties, while the Collective keeps 15%.
- **Consent Withdrawal:** Creators can withdraw permission for future licensing. Existing buyers must confirm removal from future training sets within 30 days.
- **Misuse Reports:** Creators can report suspected misuse, which can then be reviewed by the Rights Officer.

## Our Work

For this project, we are following the Software Development Life Cycle (SDLC), starting with system analysis and requirements gathering.

Our first deliverable focuses on understanding the problem, identifying the stakeholders, and documenting how the proposed system should work.

The work includes:

1. System Vision Document
2. Stakeholder Identification
3. Functional Requirements
4. Requirements Elicitation Techniques
5. Interview Agendas
6. User Questionnaire
7. UML Activity Diagrams

We used **StarUML** to create two activity diagrams covering the creator work submission and ownership verification process, and the buyer dataset request and licensing process.

## Project Scope

The first release is planned to focus on writers and voice actors, with support for images and music planned for later stages.

Some parts of the system also have special rules. For example, voice cloning requires additional signed consent and video verification, and works belonging to members under 18 cannot be licensed for AI training.

There are still some questions that need to be discussed with stakeholders, including how shared ownership should be handled and whether buyers should be allowed to access samples before purchasing datasets.

## Tools Used

- **StarUML:** Creating UML Activity Diagrams.
- **Microsoft Word:** Writing and organizing project documentation.
- **GitHub:** Keeping project files organized and allowing team members to collaborate.
- **Jira:** Planning and tracking project tasks.

## Project Status

The project is currently in the analysis and requirements documentation stage. The focus is on understanding the client's needs and defining the system before moving on to design and implementation.

This repository contains our work and documentation for the Software Engineering course at Egypt University of Informatics.
