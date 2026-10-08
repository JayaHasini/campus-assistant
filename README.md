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

**Live Application:** [http://127.0.0.1:5000/]


## Demo Video

**Demo Video:** [https://youtu.be/HYnxCyZ4N_E]

[Student: “Where is the CSE department?”
CampusBuddy: “The CSE department is located in Block A, 2nd Floor.”

Flow:
Ask → Gemma processes → Campus data retrieved → Answer displayed.]

## Open Source and AI Usage
Python, Flask, HTML, CSS, JavaScript.
### AI / Models
Google Gemma is used to understand student queries and generate responses.
- **[Model]:** [Campus information is stored locally and used to provide relevant answers.]

### Open Source Components

- **[Library / Framework]:** Flask — Backend and request handling
- **[Dataset]:** Campus Knowledge Base — Stores campus information
- **[API / Service]:**Gemma API — AI-based query processing and response generation

Python & Flask: Open-source software used under their respective licenses.
Gemma: Google’s open model, used according to its Gemma Terms of Use.
HTML, CSS & JavaScript: Standard web technologies.
Acknowledgement: Thanks to the open-source community and Google for providing the tools and AI model used in CampusBuddy.

## Install Python and required Flask packages.
Add the Gemma API key and campus knowledge base.
Run the Flask backend locally.
Open the CampusBuddy web interface in a browser.
Enter a campus-related question and receive an AI-generated answer.

### Prerequisites
Python 3.x
Flask
Gemma API access & API key
Web browser
Campus knowledge-base data
Internet connection
- 
### Installation
Install Python 3.x.
Install Flask: pip install flask
Add the Gemma API key.
Add the campus knowledge base.
Run the Flask application.
Open CampusBuddy in a web browser.

### Environment Variables
GEMMA_API_KEY — API key for accessing the Gemma AI model.
FLASK_ENV — Flask application environment (development / production).
PORT — Port number used to run the application.



### Running the Project

```bash
[git bash]
```

### Usage

Open CampusBuddy in a web browser.
Enter a campus-related question.
Gemma processes the query using the campus knowledge base.
View the generated answer instantly.

## Devpost Submission

**Devpost Project:** [-]

[Add the link to the team's Devpost submission. Ensure the Devpost project page is complete and contains the required project information, links, media, and team details.]

## Credits and License

### Credits

AI Model: Google Gemma
Backend: Python & Flask
Frontend: HTML, CSS & JavaScript
License: Open-source components used under their respective licenses.
Acknowledgement: Google and the open-source community.

### License

[https://github.com/google-deepmind/gemma/blob/main/LICENSE?utm_source=chatgpt.com]

## Submission Checklist

- [yes ] Project title and description added
- [ yes] All team members listed
- [ yes] Problem clearly explained
- [ yes] Reason for choosing the problem explained
- [ yes] Solution and key features documented
- [yes ] Innovation and differentiation explained
- [ yes] Architecture included
- [ yes] Technical implementation documented
- [ yes] Work completed during the hackathon documented
- [ yes] Team contributions documented
- [ yes] Working application is functional
- [yes ] Live application link added where applicable
- [yes ] Demo video added
- [ yes] AI and open-source components documented
- [yes] ] Setup and usage instructions tested
- [yes] ] Setup and usage instructions tested
- [yes] ] Setup and usage instructions tested
- [ yes]] Challenges and learnings documented
- [ yes]] Devpost submission completed
- [ ] Devpost link added
- [ yes]] Credits added
- [yes] ] License added
- [yes] ] Repository is organized and complete
- [ ] 
