# LingoSTEM.AI

An AI-powered localized STEM and vocational training platform built for the Claude Builders Club Hackathon. This platform utilizes the Claude API to break down educational barriers by generating personalized learning architectures, adaptive curriculum paths, and culturally relevant localized analogies for complex technical concepts.

## Project Details
* **Project Name:** LingoSTEM.AI
* **Track:** Economic Empowerment and Education
* **Core Technology:** Claude API (Claude 3.5 Sonnet), Lovable, React, Vite, Tailwind CSS, Supabase

## The Problem
Access to quality STEM and vocational education is one of the most reliable vehicles for economic mobility. However, deep linguistic barriers and dry, Western-centric technical terminology often isolate learners who do not speak English as their primary language or lack baseline context[cite: 1]. Traditional solutions typically fallback on standard machine translation tools that translate text literally without translating the actual conceptual framework, leading to poor information retention[cite: 1]. Furthermore, typical educational applications function as static learning management systems or basic chatbot wrappers that fail to provide structural, guided, and interactive learning frameworks[cite: 1].

## Our Solution
LingoSTEM.AI shifts the educational paradigm from generic chat interfaces to an engineered, structured learning management ecosystem powered by structural AI agents[cite: 1]. The platform empowers users to enter their specific career goals and regional context, which are then parsed to output custom-tailored technical paths[cite: 1]. Instead of standard keyword translations, LingoSTEM.AI leverages advanced contextual models to frame complex software engineering, mechanics, or mathematics concepts within highly relatable, regional, real-world analogies[cite: 1]. This approach eliminates pedagogical friction and accelerates skill acquisition for underserved global communities[cite: 1].

## Core Features
* **AI Smart Learning Path Generator:** Converts free-form professional or vocational goals into strict, step-by-step modular curricula mapped with estimated completion timelines and core skill milestones[cite: 1].
* **Contextual Concept Explainer:** An interactive workspace view allowing users to select technical blocks and dynamically generate analogies matching their native cultural and regional background[cite: 1].
* **Interactive Labs and Adaptive Assessments:** Injected modular multi-choice micro-quizzes generated on-the-fly by the AI engine to continuously validate comprehension and map learner metrics[cite: 1].
* **Persistent Student Analytics Dashboard:** A full-stack metrics workspace tracking skills unlocked, overall course completion percentages, and structural learning progression logs[cite: 1].

## Deep Integration of Claude API
LingoSTEM.AI strictly rejects the chatbot wrapper pattern[cite: 1]. The core functionality leverages Claude 3.5 Sonnet as a deterministic pedagogical architect, integrated into full-stack workflows[cite: 1]:

1. **Structured JSON Engine:** The application enforces structured outputs using precise schema engineering[cite: 1]. The client requests roadmaps, and the backend prompts Claude to deliver strict JSON structures containing modules, text content, precise indices for correct answers, and duration estimations[cite: 1].
2. **Context-Aware Analogies:** Rather than translating syntax, Claude is configured with systemic regional constraints to generate contextual metaphors[cite: 1]. For example, explaining object-oriented programming states or database indexing through regional transport or local marketplace architectures[cite: 1].
3. **Dynamic Assessment Generation:** Claude evaluates real-time user progress logs and synthesizes targeted situational multi-choice questions that measure conceptual depth rather than simple memorization[cite: 1].

## Architecture and Technical Stack
* **Frontend:** Single Page Application (SPA) architecture engineered via React, Vite, and styled with Tailwind CSS via Lovable, ensuring highly responsive and accessible UI elements[cite: 1].
* **Backend and Database:** Supabase PostgreSQL database architecture hosting schemas for user profile entities, dynamic learning path structures, module completion tracking, and analytical telemetry[cite: 1].
* **AI Orchestration:** Backend API layer routing structural prompts to the Claude API with strict schema assertions, state handling, and direct serialization into the database layout[cite: 1].

## Database Schema Model
The system operates on four core relational tables within Supabase[cite: 1]:
* `users`: Stores user identity profiles, account creation telemetry, and preferred language/regional metadata[cite: 1].
* `learning_paths`: Retains the primary root object of the AI-generated curriculum, storing structural JSON strings containing the path layout[cite: 1].
* `modules`: Maps child rows to the parent learning path tracking localized learning states such as locked, in_progress, and completed[cite: 1].
* `analytics`: Tracks absolute interactive logs, specific time markers, and score percentages for user assessment evaluation[cite: 1].

## Installation and Local Setup

Follow these steps to configure and run the application locally[cite: 1]:

### Prerequisites
* Node.js (v18 or higher recommended)[cite: 1]
* npm or pnpm[cite: 1]
* Supabase account and project setup[cite: 1]

### Step-by-step Configuration

1. Clone the repository[cite: 1]:
```bash
   git clone [https://github.com/username/lingostem-ai.git](https://github.com/username/lingostem-ai.git)
   cd lingostem-ai
