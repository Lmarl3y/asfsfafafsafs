<div align="center">

# NEA Idea Generator

![Status](https://img.shields.io/badge/status-in%20development-blue)
![AQA NEA](https://img.shields.io/badge/AQA-NEA%20Project-darkgreen)
![License](https://img.shields.io/badge/license-MIT-lightgrey)

A personalised system that helps A-Level Computer Science students generate NEA project ideas based on their interests, ability, and preferences.

</div>

---

## Overview

The NEA Idea Generator is a web-based system designed to help students produce suitable NEA project ideas through structured profiling, AI-assisted generation, and custom ranking algorithms.

It combines:
- User profiling via questionnaires
- AI-generated idea candidates
- Deterministic scoring and ranking logic

---

## Features

- Secure authentication system (login & signup)
- Password encryption and session handling
- CAPTCHA protection and optional 2FA
- Personalised questionnaire system
- AI-assisted idea generation
- Custom scoring and ranking algorithm
- Dynamic recommendation system based on user profile
- Editable user data dashboard

---

## Pages

<details>
<summary><strong>Index</strong></summary>

- Landing page for the system  
- Explains purpose and functionality  
- Designed for A-Level Computer Science NEA support  

</details>

<details>
<summary><strong>Login / Signup</strong></summary>

- User registration and authentication system  
- CAPTCHA protection against bots and brute force attempts  
- Optional Google login integration  
- Email-based account requirement  
- Optional two-factor authentication (email / authenticator app)  

</details>

<details>
<summary><strong>Questionnaire</strong></summary>

- Initial onboarding flow  
- Collects structured user data:
  - Interests  
  - Programming ability  
  - Hobbies  
  - Predicted grades  
  - Optional personal statement  
- Stores responses for later processing  
- Redirects to dashboard after completion  

</details>

<details>
<summary><strong>Dashboard</strong></summary>

- Displays user profile information  
- Shows questionnaire responses  
- Allows editing and updating of stored data  
- Acts as central navigation hub  

</details>

<details>
<summary><strong>Generator</strong></summary>

- Generates multiple NEA project ideas using AI  
- Parses AI output into structured data format  
- Applies custom scoring and weighting algorithm  
- Ranks and filters results to select best match  
- Supports prompt-based refinement of results  
- Outputs explainable recommendations  

</details>

---

## File Structure
<details>
<summary><strong>
nea-idea-generator/
│
├── app.py
├── config.py
├── models.py
│
├── routes/
│   ├── auth_routes.py
│   ├── user_routes.py
│   ├── generator_routes.py
│
├── services/
│   ├── auth_service.py
│   ├── scoring_service.py
│   ├── generator_service.py
│
├── utils/
│   ├── validators.py
│   ├── security.py
│
├── data/
│   └── users.json
│
└── templates/
    ├── index.html
    ├── login.html
    ├── dashboard.html
    ├── questionnaire.html
    └── generator.html
</summary></strong>
</details>

---
## Architecture

The system follows a structured pipeline:

1. User profile creation (questionnaire)
2. Data storage and retrieval
3. AI-assisted idea generation
4. Parsing and structuring of generated ideas
5. Scoring and ranking algorithm
6. Recommendation output

---

## AQA NEA Compliance Checklist

<details>
<summary><strong>Core Programming Requirements</strong></summary>

- Modular design using functions/procedures  
- Use of classes where appropriate (OOP)  
- Selection (if / elif / else logic)  
- Iteration (for / while loops)  
- Input validation and sanitisation  
- Error handling (try / except or equivalent)  
- Appropriate data structures (lists, dictionaries, etc.)  
- Nested data structures where appropriate  

</details>

<details>
<summary><strong>Data & Storage</strong></summary>

- File handling for persistent storage (save/load/update)  
- Structured storage of user profiles  
- Retrieval and updating of stored data  

</details>

<details>
<summary><strong>Algorithmic Complexity</strong></summary>

- Evidence of non-trivial problem solving  
- At least one meaningful algorithm (scoring / ranking / filtering)  
- Processing of real dynamic user data  
- Clear transformation of input → output logic  
- Demonstration of algorithm design beyond CRUD operations  

</details>

<details>
<summary><strong>System Design</strong></summary>

- Clear separation of input, processing, and output  
- Decomposition into manageable sub-problems  
- Maintainable and logically structured codebase  
- User session/state management  
- System-wide navigation and flow control  

</details>

---

## Design Philosophy

This system prioritises:
- Structured decision-making over random generation
- Transparent and explainable outputs
- Scalable user-driven data processing
- Maintainable modular architecture

---

## License

MIT License
