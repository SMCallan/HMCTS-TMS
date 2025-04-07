# HMCTS-TMS
Task Management System for HMCTS

# HMCTS Developer Technical Test Submission - Task Management System

**Submitted by: Callan Smith MacDonald**

## Project Overview

This submission addresses the HMCTS Developer Technical Test requirement to build a simple API and frontend system for caseworkers to track their tasks. The goal was to create a functional full-stack application demonstrating best coding practices, including API development, frontend UI implementation, database integration, testing, and deployment.

## Live Demo

The fully deployed application can be accessed here:

*   **Live Frontend Application:** **[https://fluffy-paprenjak-e29c80.netlify.app](https://fluffy-paprenjak-e29c80.netlify.app)**

*(The backend API is running and connected automatically)*

<img width="640" alt="Screenshot 2025-04-07 at 18 26 32" src="https://github.com/user-attachments/assets/149c09f8-daca-428e-ae9a-786d49da0bd9" />

## Code Repositories

The project is split into two separate repositories: one for the backend API and one for the frontend application.

*   **Backend API Repository:** **[https://github.com/SMCallan/hmcts-task-api](https://github.com/SMCallan/hmcts-task-api)**
    *   *(Contains Node.js/Express API, Prisma, PostgreSQL integration, Jest/Supertest tests)*
*   **Frontend UI Repository:** **[https://github.com/SMCallan/hmcts-task-ui](https://github.com/SMCallan/hmcts-task-ui)**
    *   *(Contains React/Vite/TypeScript UI, Axios for API calls, Jest/RTL tests)*

*Note: These repositories may currently be private but can be made public or access granted upon request for review.*

## Fulfillment of Requirements

The following requirements outlined in the technical test brief have been addressed:

**Backend API:**

*   [x] **Create Task:** Endpoint `POST /api/tasks` implemented.
*   [x] **Retrieve Task by ID:** Endpoint `GET /api/tasks/:id` implemented.
*   [x] **Retrieve All Tasks:** Endpoint `GET /api/tasks` implemented.
*   [x] **Update Task Status:** Endpoint `PATCH /api/tasks/:id/status` implemented.
*   [x] **Delete Task:** Endpoint `DELETE /api/tasks/:id` implemented.

**Frontend Application:**

*   [x] **Create, View, Update, Delete Tasks:** UI allows performing all CRUD operations via interaction with the backend API.
*   [x] **User-Friendly Interface:** A clean interface displays tasks and provides forms/buttons for interaction.

**Technical Requirements:**

*   [x] **Any Language/Framework:** Backend uses Node.js/Express, Frontend uses React/Vite/TypeScript.
*   [x] **Implement Unit Tests:**
    *   Backend API tests using Jest/Supertest are included in the backend repository.
    *   Frontend component tests using Jest/React Testing Library are included in the frontend repository (Note: One form validation test is currently skipped due to test environment inconsistencies; manual testing confirms functionality).
*   [x] **Store Data in a Database:** PostgreSQL database hosted on Railway is used for persistence.
*   [x] **Include Validation and Error Handling:** Implemented on both backend (API request validation, error responses) and frontend (user feedback on errors, basic input handling).
*   [x] **Document API Endpoints:** Detailed API documentation is available in the backend repository's `README.md`.
*   [x] **Repositories on GitHub:** Code hosted in the linked repositories.
*   [x] **Helpful README.md:** Each repository contains a `README.md` with setup, run, test instructions, and technical details.

**Deployment:**

*   [x] Backend API deployed on Railway.
*   [x] Frontend application deployed on Netlify.
*   [x] Deployed frontend successfully communicates with the deployed backend.

## Technology Stack Summary

*   **Backend:** Node.js, Express, Prisma, PostgreSQL, Jest, Supertest, CORS, Dotenv
*   **Frontend:** React, TypeScript, Vite, Axios, Jest, React Testing Library, CSS
*   **Database:** PostgreSQL (Hosted on Railway)
*   **Deployment:** Railway (Backend + DB), Netlify (Frontend)
*   **Version Control:** Git, GitHub

## How to Run Locally

Detailed instructions for setting up and running both the backend API and the frontend application locally are provided in the `README.md` files within their respective repositories:
(private)
1.  **Backend:** [hmcts-task-api/README.md](https://github.com/SMCallan/hmcts-task-api/blob/main/README.md)
2.  **Frontend:** [hmcts-task-ui/README.md](https://github.com/SMCallan/hmcts-task-ui/blob/main/README.md)

---

Thank you for the opportunity to complete this technical test.
