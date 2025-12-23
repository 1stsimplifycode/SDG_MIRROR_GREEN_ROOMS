# SDG Mirror Assessment  
**Project Samudaya – Verifiable SDG Intelligence**

---

## Overview

**SDG Mirror Assessment** is a web-based, AI-powered sustainability auditing platform that evaluates real-world indoor spaces (homes, kitchens, workplaces, living areas) against the **United Nations Sustainable Development Goals (SDGs)** using **visible evidence only**.

The system analyzes a single uploaded image and produces:
- A **transparent SDG scorecard**
- **Explainable AI reasoning** for each SDG
- A **normalized sustainability score (0–100)**
- A **radar visualization** for comparative assessment

No assumptions are made.  
No behavioral inference is used.  
Only what is visible in the image is evaluated.

---

## Why This Project Matters

Sustainability audits are often:
- Expensive
- Opaque
- Based on surveys or self-reporting

**SDG Mirror** introduces a **verifiable, evidence-first approach** that can scale across:
- Education infrastructure
- Urban housing
- Government inspections
- ESG reporting
- Smart cities and policy dashboards

This project is designed to be **policy-compatible**, **auditable**, and **institutionally deployable**.

---

## Key Principles

- **No Assumptions**  
  The AI evaluates only what is visibly present in the image.

- **Explainability-First**  
  Every score includes explicit positive and negative reasoning.

- **Policy Alignment**  
  Designed to align with Karnataka Vision 2030 and UN SDG frameworks.

- **Human-Centric Framing**  
  Deficiencies are stated factually without shaming, while acknowledging real-world constraints.

---

## Supported SDGs (Current Version)

The system currently evaluates **7 SDGs**, each scored on a 0–15 scale:

- **SDG 3** – Good Health & Well-Being  
- **SDG 6** – Clean Water & Sanitation  
- **SDG 7** – Affordable & Clean Energy  
- **SDG 10** – Reduced Inequalities  
- **SDG 11** – Sustainable Cities & Communities  
- **SDG 12** – Responsible Consumption & Production  
- **SDG 13** – Climate Action  

Scores are normalized to a **100-point sustainability index**.

---

## How It Works (Technical Flow)

1. User uploads a room image (JPEG/PNG)
2. Image is converted to Base64
3. A structured, constraint-heavy prompt is sent to **Mistral Pixtral**
4. The AI returns:
   - Detected objects
   - SDG-wise scores
   - Positive & negative evidence
   - Explicit reasoning
5. The frontend:
   - Parses the response deterministically
   - Renders SDG cards
   - Draws a radar chart
   - Displays full AI transparency on demand

All logic runs in a **single HTML file** for portability and demo-readiness.

---

## Tech Stack

- **Frontend**: HTML, CSS (Neumorphic UI), Vanilla JavaScript  
- **AI Model**: Mistral `pixtral-12b-2409`  
- **Visualization**: HTML Canvas (Radar Chart)  
- **Architecture**: Client-side, single-file prototype (demo-focused)

> Note: API keys are hardcoded **only for demonstration and transparency**.  
> In production, all inference would be server-side.

---

## Intended Use Cases

- Government sustainability audits
- Education infrastructure assessment
- ESG & CSR monitoring
- Smart city pilots
- Policy showcases and demos
- Research on explainable multimodal AI

---

## Showcase & Recognition Context

The following communication documents the **official selection and showcase opportunity** associated with this project:

---

**Dear Adishree,**

**Congratulations!**

You have been selected as one of the distinguished changemakers from Bengaluru to participate in a prestigious **1M1B showcase meeting** with **Ms. Khushboo G. Chowdhary, IAS**, Secretary – Higher Education Department, Government of Karnataka.

**Meeting Details**  
📍 *Karnataka State Higher Education Council, Gandhinagara, Bengaluru*  
🗓 *Tuesday, 23rd December 2025*  
⏰ *3:00 PM – 4:00 PM*

Ms. Khushboo G. Chowdhary is a highly respected IAS officer, known for her visionary leadership in higher education, governance reforms, women empowerment, and youth development.

The showcase meeting will also include leadership representatives from **IBM**, along with members of the **1M1B team**.

### The showcase will include:
- A closed-door interaction with Ms. Khushboo G. Chowdhary, IAS  
- A **3-minute rocket pitch** presenting impact-driven work  

### Next Steps:
- Begin preparing your 3-minute rocket pitch. It should be concise, impactful, and clearly highlight the change you are creating.
- You will be contacted for an interview, after which final selection will be confirmed.
- A **virtual selection-cum-rehearsal session** will be conducted on Wednesday. Attendance is mandatory.
- Please ensure parental consent to attend the meeting.

This is a proud milestone for you and your family.

**Thanks & Regards,**  
**Rahul Moorjani**  
One Million for One Billion (1M1B)  
📞 +91 910 606 9138  
LinkedIn

---

## Project Status

- Prototype: ✅ Complete  
- Live demo: ✅ Ready  
- Policy showcase: ✅ Prepared  
- Research extension: 🔄 In progress  
- Multi-SDG expansion: 🔄 Planned  

---

## Author

**Adishree Gupta**  
B.Tech Computer Science  
Project Samudaya  
Focus: Explainable AI · Sustainability · Policy-Tech

---

## License

This project is shared for **educational, research, and policy demonstration purposes**.  
Commercial deployment requires explicit authorization.
