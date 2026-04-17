## Hi there 👋
Hi there! 👋 I’m Mohamed A Mohamed

I’m an Informatics student at the University of Washington focused on Data Science and Software Development, with hands-on experience building risk-aware analytics systems, dashboards, and AI-powered tools in high-stakes environments.

Get to know me

😁 Pronouns: he/him
🖥️ Data Science & Product Intern at Boeing
🎓 Informatics major at UW (HCI + Data Science focus)
☁️ Built cloud-hosted web apps with authentication and APIs
📊 Experienced in dashboards, anomaly detection, and analytics
🤝 Active in STEM outreach and community mentorship
📫 Contact me: linkedin.com/in/your-link-here

🎓 Education

University of Washington, Seattle
Bachelor of Science in Informatics (Data Science / Software Development)
Anticipated Graduation: June 2026
GPA: 3.5

🚀 Some Projects I’ve Worked On
AI-Powered Study Planner Web App

A multi-user React + Firebase platform that helps students generate personalized study plans using AI while enforcing structured input, validation, and access controls.

Tech: React, Firebase, APIs
Focus: User behavior tracking, AI integration, usability, trust

Fleet Chief Office Service Dashboard

Built Tableau and SQL dashboards to track operational delays, workload distribution, and service performance for leadership decision-making.

Tech: SQL, Tableau
Focus: Risk metrics, process bottlenecks, customer experience

💼 Professional Experience
The Boeing Company — Data Scientist Intern

Seal Beach, CA

Worked with large-scale operational data to surface anomaly patterns and risk signals impacting system reliability. Built dashboards for leadership and partnered with engineering teams to turn insights into system improvements for cloud-hosted platforms.

The Boeing Company — Product Lifecycle Data Management Engineer Intern

St. Louis, MO

Designed AI-enabled workflows to extract and validate sensitive contract data, saving over 1,200 hours annually. Built governance processes to ensure compliance, audit readiness, and lifecycle traceability.

AVELA — STEM Tutor

Seattle, WA

Provided STEM outreach to students from underrepresented backgrounds and helped raise math scores through targeted tutoring and mentorship.

🧠 I’m Familiar With

Java
Python
JavaScript
SQL
React
HTML/CSS
Tableau
R
Figma
Firebase
Git / Jira
Cloud APIs & Monitoring

Capstone Project: HumanHealth
HumanHealth is a web app built as a University of Washington capstone project. It helps people who notice a visible skin concern — like a rash, breakout, or irritation — figure out what type of care to seek without falling into the trap of self-diagnosis online. Upload a photo, answer a few questions, and get guidance on whether to handle it at home, see a primary care doctor, visit a dermatologist, or go to urgent care.
Goals
Build a working, mobile-first tool that routes users toward the right type of care using AI image analysis. Cover common conditions like eczema, acne, psoriasis, warts, and fungal infections. Be transparent about limitations and never pretend to diagnose.
Process
Winter quarter we focused on the frontend. We built the full user flow in React with TypeScript and Tailwind — landing page, consent screen, image upload, follow-up questions, loading state, recommendation page, and a care education section. By the end of winter we had a polished UI but the backend was just placeholder logic. It ignored the uploaded image entirely and gave generic recommendations based on multiple-choice answers.
This quarter we built the real backend. We trained a model to categorize skin conditions from images across our target conditions, integrated it into a FastAPI backend, and connected it to the frontend. A big focus was making sure the model performed across diverse skin tones — we sourced training data that included Fitzpatrick skin types I through VI and tested accuracy across all of them. Right now the backend is nearly complete and we're moving into testing and validation.
Individual Contributions
I owned the backend AI integration. That included researching and curating training data, identifying and addressing skin tone bias in the dataset, building the image analysis pipeline in Python, creating the FastAPI endpoint that accepts uploads and returns structured care guidance, and designing the system's approach to ethical AI — focusing on care routing over diagnosis and defaulting to "consult a professional" when confidence is low.
Takeaways
Dataset quality matters more than model architecture. We spent serious time evaluating and balancing our training data before building anything, and that groundwork is what made the model usable across skin tones.
The other big insight: care routing accuracy matters more than classification accuracy. We found cases where the model got the specific condition wrong but still pointed the user to the right type of doctor. That shaped our whole design — the care recommendation is front and center while the category label stays small.
Next Steps
Testing and polish. Skin tone accuracy validation across Fitzpatrick I-VI, user testing to confirm people understand the tool is non-diagnostic, mobile optimization, and final presentation prep.
<!--
**Mohamed2time/mohamed2time** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
