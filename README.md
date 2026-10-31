# TieEdu AI Assistant 🎓

### Internship Project Showcase | AI-Powered Educational Chatbot

## 1. Project Overview

TieEdu AI Assistant is a conversational chatbot developed for the TieEdu education and career platform. It aims to help students and early-career developers find relevant information about competitive programming, recruitment drives, courses, and interview preparation.

The project focuses on building a modular chatbot architecture that can evolve from mock data and AI providers to real API and LLM integrations.

## 2. Problem Statement

Students often need to search across different resources to find information about recruitment opportunities, programming courses, eligibility criteria, and preparation roadmaps.

The goal of this project was to provide a conversational interface where users could access relevant information more easily.

## 3. My Contribution

I worked on this project as part of my internship at TieEdu.

My work involved contributing to:

- Development of a floating chatbot interface.
- Frontend and backend integration.
- Designing modular service and provider abstractions.
- Implementing chatbot request handling and context retrieval.
- Testing application workflows and handling error scenarios.

*Only retain the contributions that accurately represent your individual work.*

## 4. Key Features

- Floating chatbot interface.
- Conversational message handling.
- Quick-action prompts.
- Context-based information retrieval.
- Centralized backend error handling.
- Modular frontend and backend architecture.

## 5. Technology Stack

- Frontend: React, TypeScript, Vite, Tailwind CSS.
- Backend: Node.js, Express.js, TypeScript.
- Validation: Zod.
- Development tools: Git and GitHub.

## 6. Architecture Overview

The application follows a decoupled architecture:

1. Frontend chatbot widget receives user queries.
2. Backend API handles incoming chat requests.
3. Chatbot service coordinates the request.
4. Repository abstraction provides relevant educational data.
5. AI provider abstraction handles intent classification and response generation.

The architecture separates business logic from data sources and AI providers.

## 7. Development Challenges

Some important areas explored during development included:

- Keeping frontend and backend responsibilities separate.
- Designing reusable service interfaces.
- Handling API errors and unsuccessful responses.
- Making the architecture adaptable to future integrations.
- Maintaining consistent request and response structures.

## 8. Current Scope and Limitations

The documented Phase 1 implementation uses isolated mock datasets and a deterministic mock AI provider.

Production AI integration, live TieEdu API integration, authentication, and persistent chat history were identified as future development areas.

## 9. Key Learnings

Working on this project helped me understand:

- How conversational applications are structured.
- How frontend and backend services communicate.
- Why modular architecture matters.
- How context retrieval supports chatbot responses.
- Why error handling and response reliability are important in AI applications.

---

*This repository is a project showcase and does not contain the original internship source code.*
