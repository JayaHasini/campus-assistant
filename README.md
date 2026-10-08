# Campus Buddy

> A mobile-friendly web application featuring a natural language chat interface that answers student queries strictly using a curated campus knowledge base.

## Team

**Team Name:** Team Kernel


| Member | Contribution   |
| ------ | -------------- |
| Jayithri | Connected GitHub environment, engineered project prompts, and integrated knowledge base logic. |
| Sahasra | Assisted with user interface layout design, testing fallback edge cases, and mobile optimization. |
| Hasini | Managed repository synchronization, environment staging, and sandbox deployment validation. |
| Mihir | Curated the 25 core campus question-and-answer datasets for the internal system knowledge base. |


## Problem Statement

### The Problem

Navigating university life can be incredibly overwhelming for both freshers and returning students. Crucial daily information—such as library operational hours, financial aid office locations, IT support steps, and cafeteria schedules—is frequently scattered across massive, unorganized college websites, confusing PDFs, or physical bulletin boards. Students lose valuable time trying to find quick, simple answers to routine administrative questions.

### Why We Chose This Problem

We chose this problem to eliminate institutional navigation friction. Traditional campus portals are complex, lack mobile responsiveness, and require manual searching. By building an accessible tool, we ensure students get immediate, accurate answers, lowering the stress of administrative campus tasks and letting them focus heavily on their academics.

## Solution

CampusBuddy addresses this by providing a clean, responsive web dashboard centered around an intelligent natural language chat interface. Instead of hunting through links, students ask questions in plain english. The application intercepts queries and matches them against a strictly closed, verified campus information database, completely eliminating "AI hallucinations" by defaulting to a helpful administrative fallback message when an answer cannot be verified.

### Key Features

- Natural Language Processing (NLP) Chat Interface: Students can type free-form, conversational questions to instantly pull matching administrative rules.
- Suggested Quick-Question Buttons: Features 4 high-frequency shortcut buttons for instant, single-tap access to critical daily data (Wi-Fi, Exams, Health Centre, Library).
- Strict Context Verification (Hallucination Control): Protects students from wrong data by safely returning a fallback message ("I don't have that info...") if a query falls outside the official campus data scope.
- Mobile-First Responsive Layout: Designed completely from scratch to be clean, accessible, and fast on all iOS, Android, and desktop screens.

## Innovation and Differentiation

Standard AI chatbots pull information broadly from the open web, often resulting in inaccurate, generic, or completely hallucinated answers that do not apply to a specific college campus. CampusBuddy innovates by implementing a strict Closed-World Assumption model. It acts as a highly disciplined system that prioritizes accurate institutional guardrails over generic text generation, guaranteeing that a student never receives confidently incorrect information regarding critical events like exams or medical emergencies.

## Technical Implementation
we have used gemma ai to be integrated with our webpage and html for the creation 
### Architecture
Student → Web UI → Python Backend → Campus Knowledge Base + Gemma AI → Answer
  Student
           ↓
   CampusBuddy Website
           ↓
      Python Backend
           ↓
   Campus Knowledge Base
           ↓
      Gemma AI Model
           ↓
   Simple Relevant Answer
           ↓
        Student
### Technology Stack


| Category        | Technologies                |
| --------------- | --------------------------- |
| Frontend        | [HTML, CSS, JavaScript]     |
| Backend         | [Python, Flask]             |
| Database        | [JSON / Local Knowledge Base]|
| AI / ML         | [Google Gemma] |
| Infrastructure  | [Localhost / Python Environment]|
| APIs / Services | [Gemma API]            |


If a category or technology is not implemented in the project, specify `N/A` instead of leaving the field blank.

### How It Works

[Student asks a question → Backend receives it → Gemma processes it with campus data → Generates an answer → Answer shown on website..]

### Technical Decisions
Frontend: HTML, CSS, JavaScript for a simple chat interface.
Backend: Python Flask for handling requests.
AI: Gemma for natural-language understanding and responses.
Knowledge Base: JSON-based campus information for easy updates.
Integration: Gemma API connects the AI with the backend.
[]

## Implementation During the Hackathon
Built the CampusBuddy web interface.
Connected the Flask backend with the frontend.
Added a campus knowledge base with relevant information.
Integrated Gemma AI for answering student queries.
Tested common campus questions and improved responses.


### Team Contributions

- **[jayithri]:** [Frontend & UI design]
- **[sahasra]:** [Backend & Flask integration]
- **[jaya hasini]:** [Gemma AI & knowledge base]
- **[mihir]:** [Testing, documentation & presentation]

## Working Application

**Live Application:** [Live URL]

[Briefly explain how the deployed application can be accessed and what functionality can be tested.]

The submitted application should be functional and accessible through the provided link where applicable.

## Demo Video

**Demo Video:** [Video URL]

[https://youtu.be/HYnxCyZ4N_E]

## Open Source and AI Usage

### AI / Models

- **[Model]:** [How it is used]

### Open Source Components

- **[Library / Framework]:** [Purpose]
- **[Dataset]:** [Purpose]
- **[API / Service]:** [Purpose]

[Include relevant licenses, attribution, and acknowledgements for external components.]

## Setup and Usage

### Prerequisites

- [Requirement]
- [Requirement]

### Installation

```bash
git clone [repository-url]
cd [project-directory]
[installation-command]
```

### Environment Variables

```env
[VARIABLE_NAME]=[value]
```



### Running the Project

```bash
[run-command]
```

### Usage

[Explain the basic steps required to use the project.]

## Devpost Submission

**Devpost Project:** [Devpost Project URL]

[Add the link to the team's Devpost submission. Ensure the Devpost project page is complete and contains the required project information, links, media, and team details.]

## Credits and License

### Credits

[Credit libraries, frameworks, datasets, models, APIs, contributors, and other external resources used.]

### License

[License name and/or link.]

## Submission Checklist

- [ ] Project title and description added
- [ ] All team members listed
- [ ] Problem clearly explained
- [ ] Reason for choosing the problem explained
- [ ] Solution and key features documented
- [ ] Innovation and differentiation explained
- [ ] Architecture included
- [ ] Technical implementation documented
- [ ] Work completed during the hackathon documented
- [ ] Team contributions documented
- [ ] Working application is functional
- [ ] Live application link added where applicable
- [ ] Demo video added
- [ ] AI and open-source components documented
- [ ] Setup and usage instructions tested
- [ ] Challenges and learnings documented
- [ ] Devpost submission completed
- [ ] Devpost link added
- [ ] Credits added
- [ ] License added
- [ ] Repository is organized and complete
- [ ] 
