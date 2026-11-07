# AI Job Application Assistant

An AI Agent Skill that helps job seekers prepare clear, honest, and job-specific application materials using their real background and the employer's job description.

> This repository contains an **Agent Skill**, not a standalone website or chatbot.

## What it can help you do

- Break down a job description into responsibilities, required skills, and useful keywords.
- Compare the role's requirements with the user's actual education, skills, and experience.
- Improve CV wording and structure without inventing qualifications or achievements.
- Draft a tailored cover letter based on verified information.
- Prepare for interviews with role-specific questions and practice answers.
- Review application materials for clarity, consistency, and unsupported claims.

## How it works

1. The user shares a job description and relevant background information.
2. The skill identifies the role's key requirements.
3. It maps the user's evidence to those requirements and flags missing details.
4. It helps create or improve the requested application material.
5. It performs a final review and asks the user to confirm uncertain information.

The skill should ask follow-up questions when important information is missing. It must not fill gaps by guessing.

## Core principles

- **Honesty:** Never fabricate education, employment, skills, certifications, dates, or achievements.
- **Evidence-based tailoring:** Use only information supplied or confirmed by the user.
- **Transparency:** Clearly identify gaps, assumptions, and details that need confirmation.
- **Privacy:** Do not request passwords, identity numbers, or unnecessary sensitive information.
- **No guarantees:** The skill cannot guarantee interviews, employment, or hiring outcomes.

## Repository contents

- `ai-job-application-assistant/SKILL.md` — the main Agent Skill instructions.

## Installation and use

Use this skill with an AI agent that supports the [Agent Skills format](https://agentskills.io/).

With a compatible GitHub CLI version, an example installation command is:

```bash
gh skill install harmainsharifain90-cpu/Ai-job-application-assistant ai-job-application-assistant
```

Installation support and skill locations can vary by agent. Check the documentation for the AI agent you use.

## Example request

> Here is the job description and my real background. Identify the role's requirements, show me where my experience matches, and help tailor my CV. Ask me about anything missing instead of making details up.

## Project status

The skill instructions are maintained in this repository and are being tested with practical CV, cover-letter, interview-practice, and final-review tasks.

## License and reuse

No open-source license has been added yet. The project remains under the repository owner's copyright. Please contact the owner before redistributing, modifying, or using the project commercially.
