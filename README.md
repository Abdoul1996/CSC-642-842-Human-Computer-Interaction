# CSC-642-842 Human-Computer Interaction Project

## Project Overview

This repository contains the coursework and project materials for CSC-642-842 Human-Computer Interaction at SFSU. The project focuses on **PathFinder** - a web application designed to help Computer Science students choose the right courses each term through personalized recommendations and an intelligent chatbot interface.

## Project Website

📖 **Live Project Website**: [Google Sites](https://sites.google.com/d/1KsWDpNrs1bFc_jfNuGdc91oXGCLRUeeW/p/1-1JUk3zc-i-yLDQx7xXdJWp6XI8fTbIp/edit)

## Project Description

**PathFinder** is an innovative web application that addresses the critical challenge CS students face when planning their academic journey. The app combines official degree requirements with personalized student preferences to provide intelligent course recommendations through an explainable chatbot interface.

### Problem Statement
Many CS students, especially first-generation college students, struggle with course planning. They often don't know academic advisors are available, face limited appointment times, or get confused about prerequisites. This leads to:
- Delayed graduation and financial strain
- Mismatched courses and self-doubt
- Students switching majors or dropping out
- Over-reliance on peer guidance that may be inaccurate

### Target Users
- **First- and second-year CS students** at SFSU
- **Transfer students** needing guidance with course alignment
- **First-year graduate students** navigating new program requirements
- Students who need course planning assistance in **personal academic settings** (home, library, commuting) on **laptops** and **mobile devices**

### Solution Approach
PathFinder uses a **graph/constraint model** to encode prerequisites and degree requirements, then provides:
- Instant eligibility checking for next courses
- Personalized ranking based on student interests and workload preferences
- Conversational chatbot explanations for recommendations
- Integration with professor ratings and workload patterns

## Project Goals

- [ ] Reduce confusion and increase confidence in course planning
- [ ] Support timely degree completion for CS students
- [ ] Provide transparent, explainable course recommendations
- [ ] Bridge the gap between limited advisor access and student needs
- [ ] Create a user-centered solution that adapts to individual student preferences

## Key Features

- **Graph-Based Course Eligibility**: Encodes prerequisites, co-requisites, and degree requirements as a constraint model
- **Personalized Ranking System**: Questionnaire-based preferences covering interests, workload tolerance, and math comfort
- **Intelligent Chatbot Interface**: GPT-powered conversational explanations for recommendations
- **Real-Time Course Suggestions**: Instant surfacing of eligible next courses based on completed coursework
- **Professor & Workload Integration**: Optional indicators of ratings and workload patterns from public data

## Methodology

### Research Methods
- **10 student interviews** with freshmen, sophomores, transfers, and graduate students at SFSU
- **Short survey** to quantify pain points (confidence, time spent planning, prerequisite errors)
- **Usability testing** using SUS (System Usability Scale), task completion, A/B testing, and think-aloud protocols
- **Heuristic evaluation** to identify interface issues

### Design Process
- **User-Centered Design (UCD)** approach focusing on real CS student needs
- **User personas** creation (freshman navigating prerequisites, transfer student aligning credits, upper-division student exploring electives)
- **Storyboards and design sketches** based on research findings
- **Low-fidelity prototypes** for course planner and chatbot workflows
- **High-fidelity prototypes** using Figma and React for interactive mockups
- **Iterative refinement** based on usability testing and feedback

### Evaluation Plan
- **Usability testing methods**: SUS, task completion, A/B testing, think-aloud protocols
- **Success metrics**: Improved course-planning confidence, reduced planning time, fewer prerequisite errors
- **Iterative design process**: Findings from tests inform interface refinements and chatbot improvements

## Technology Stack

- **Frontend**: React for user interface
- **Backend**: FastAPI or Flask for logic and API communication
- **Database**: PostgreSQL or SQLite for course data and user progress
- **AI Integration**: GPT-based API (OpenAI) for chatbot interface
- **Design Tools**: Figma for prototyping
- **Development**: Web-based platform for cross-device accessibility

## Project Timeline

| Phase | Duration | Deliverables |
|-------|----------|--------------|
| User Research | Ongoing | 10 student interviews, survey results, pain point analysis |
| Ideation & Personas | Ongoing | User personas, storyboards, design sketches |
| Low-Fidelity Prototyping | Ongoing | Wireframes of course planner and chatbot workflows |
| High-Fidelity Prototyping | Ongoing | Interactive Figma mockups, React prototype |
| Evaluation & Iteration | Ongoing | Usability testing, heuristic evaluation, A/B testing results |
| Final Implementation | TBD | Complete web application with all core features |

## Getting Started

### Prerequisites
- [List any prerequisites for running/viewing the project]

### Installation
```bash
# Add installation instructions if applicable
```

### Usage
[Add usage instructions]

## Project Structure

```
CSC-642-842-Human-Computer-Interaction/
├── README.md                           # This file
├── LICENSE                            # Project license
├── Project Proposal and Website (1).pdf # Original project proposal
├── docs/                              # Documentation (if applicable)
├── prototypes/                        # Design prototypes (if applicable)
├── research/                          # Research materials (if applicable)
└── deliverables/                      # Final project deliverables (if applicable)
```

## Research & Design Artifacts

- [Link to user research findings]
- [Link to wireframes/mockups]
- [Link to prototypes]
- [Link to usability test results]

## Evaluation Results

[Add your evaluation results and findings here]

## Lessons Learned

[Reflect on what you learned during the project]

## Future Work

[Describe potential future improvements or extensions]

## Team

- **Abdoulfatah Abdillahi** (aabdillahi@mail.sfsu.edu) - Team Lead / Full-Stack
- **Omshree Bharodiya** (obharodiya@sfsu.edu) - Back-End Developer / DB Lead
- **Bryan Escobar** (bescobar5@sfsu.edu) - Front-End Developer / UX Lead  
- **Course**: CSC-642-842 Human-Computer Interaction
- **Semester**: Fall 2025

## References

- **Coursewise** - Reference example for data-driven course guidance
- **SFSU CS Degree Requirements** - [CS-Degree-Underg](https://example.com)
- **SFSU Data Science & AI Graduate Program** - [DS&AI-Degree-Grad](https://example.com)  
- **SFSU CS Graduate Program** - [CS-Degree-Grad](https://example.com)
- **Market Research**: Analysis of existing university degree planners, schedule builders, and course review sites

## License

This project is licensed under the MIT.

---

*Last updated: September 7th 2025 *