📘 Academic Writing Journey (AWJ)
> **B2 → C1 · 6 Hours · 2,500 XP · 6 Levels**  
> A gamified, self-paced eLearning unit on academic abstract writing for English for Specific Purposes (ESP/EAP).
Live app: https://profeanaeslavaedtech.github.io/Gamification/  
Author: Ana Eslava-Graterol · @profeanaeslava  
Co-developed with: Claude Code — AI-Powered Web Development Engineer  
Course context: "Simulation, Games and Technology in EFL Teaching" · Prof. Casañ Pitarch, Ricardo · UPV
---
Table of Contents
Overview
Instructional Design
Level Journey
XP & Badges
Key URLs
SCORM Compatibility
UDL Accessibility Features
Student Instructions
Teacher Instructions
Tech Stack
Citation & Copyright
---
Overview
The Academic Writing Journey is a fully asynchronous, self-paced gamified unit designed to move English language learners from B2 to C1 in academic writing, with a focus on the scholarly abstract as the target genre.
Learners take on the role of researchers progressing through six levels — from Curious Student to Academic Challenger — mastering Swales' 5-Move Abstract Structure and Hyland's Metadiscourse Framework along the way.
Key figures:
6 progressive levels + 1 Bonus Escape Room
18 sequenced core activities (3 per level)
2,500 total XP available
Estimated completion time: 6 hours
Language focus: B2 → C1 (CEFR)
---
Instructional Design
Framework	Application
SAM (Successive Approximation Model)	Iterative design with rapid prototyping
Casañ-Pitarch IPO	Input → Processing → Output per level
ESA (Engage–Study–Activate)	Lesson structure within each level
CLIL 4Cs	Content, Communication, Cognition, Culture
UDL (Universal Design for Learning)	Accessibility layer: voice, contrast, text size
Gamification	XP, badges, leaderboard, boss level, escape room
---
Level Journey
Level 1 · Word Hunter 🧭
Title: Curious Student | XP: 100 | Badge: Bronze Compass  
IPO Focus: Input — AWL & Academic Register  
Activities:
1.1 Vocabulary in context (AWL Tier 1)
1.2 Register identification (formal vs. informal)
1.3 Word Families table (interactive input fields)
Resources: Canva Lesson · Quizlet Flashcards · AWL Sublist 1 PDF  
URL: https://profeanaeslavaedtech.github.io/Gamification/#level1
---
Level 2 · Abstract Detective 🔍
Title: Apprentice Researcher | XP: 200 | Badge: Silver Notebook  
IPO Focus: Input + Processing — Reading Abstracts  
Activities:
2.1 Read and annotate a real Q1 abstract
2.2 Identify Swales' 5 Moves (M1–M5)
2.3 Gap analysis — what's missing?
Resources: Canva Lesson · Sample Abstract PDF · Swales Move Guide  
URL: https://profeanaeslavaedtech.github.io/Gamification/#level2
---
Level 3 · Junior Scholar 🔬
Title: Junior Scholar | XP: 300 | Badge: Golden Microscope  
IPO Focus: Processing — Grammar for Academic Writing  
Activities:
3.1 Passive voice in abstracts
3.2 Hedging language (modal verbs, adverbs)
3.3 Sentence transformation practice
Resources: Canva Lesson · Grammar Reference Sheet · Practice Quiz  
URL: https://profeanaeslavaedtech.github.io/Gamification/#level3
---
BONUS · The Abstract Heist 🏛️🔐
Unlocked after: Level 3 completion  
XP: Bonus (variable) | Status: Secret Vault  
Description: An interactive escape room where learners crack the vault by correctly identifying and assembling the 5 moves of a scrambled abstract under time pressure.  
URL: https://profeanaeslavaedtech.github.io/escaperoom/
---
Level 4 · Research Navigator 🗺️
Title: Developing Author | XP: 400 | Badge: Platinum Journal  
IPO Focus: Processing + Output — Listening & Note-taking  
Activities:
4.1 Watch a lecture on Hyland's Metadiscourse
4.2 Interactive metadiscourse labelling game
4.3 Note-taking & summary writing
Resources: Canva Lesson · Hyland Framework PDF · Listening task  
Game URL: https://profeanaeslavaedtech.github.io/Gamification/level4game  
URL: https://profeanaeslavaedtech.github.io/Gamification/#level4
---
Level 5 · Master Abstract Builder ✍️
Title: Emerging Researcher | XP: 500 | Badge: Sapphire Globe  
IPO Focus: Output — Writing  
Activities:
5.1 Guided abstract writing (template scaffold)
5.2 Peer review on Padlet
5.3 Revision and self-assessment
Resources: Canva Lesson · Abstract Template · Padlet Board · Rubric  
URL: https://profeanaeslavaedtech.github.io/Gamification/#level5
---
Level 6 · Academic Communicator 🎤 (Boss Level)
Title: Academic Challenger | XP: 1,000 | Badge: Diamond Crown  
IPO Focus: Output — Speaking & Presenting  
Activities:
6.1 Record a 2-minute abstract pitch (Flip / Vocaroo)
6.2 Self-assess using C1 criteria
6.3 Submit for teacher feedback
Resources: Canva Lesson · Pitch Script Template · Flip Recording Guide  
URL: https://profeanaeslavaedtech.github.io/Gamification/#level6
---
XP & Badges
Level	Title	XP	Badge	Cumulative XP
1	Curious Student	100	🧭 Bronze Compass	100
2	Apprentice Researcher	200	📓 Silver Notebook	300
3	Junior Scholar	300	🔬 Golden Microscope	600
BONUS	The Abstract Heist	Variable	🏛️ Vault Master	600+
4	Developing Author	400	📔 Platinum Journal	1,000
5	Emerging Researcher	500	🌐 Sapphire Globe	1,500
6	Academic Challenger	1,000	👑 Diamond Crown	2,500
---
Key URLs
Resource	URL
Live App	https://profeanaeslavaedtech.github.io/Gamification/
Escape Room (Bonus)	https://profeanaeslavaedtech.github.io/escaperoom/
Level 4 Game	https://profeanaeslavaedtech.github.io/Gamification/level4game
Portfolio Page	https://profeanaeslavaedtech.github.io/portofolio/
GitHub Repository	https://github.com/profeanaeslavaedtech/Gamification
---
SCORM Compatibility
The AWJ `index.html` includes a built-in SCORM 2004 4th Edition API bridge. When loaded inside an LMS, it automatically:
Calls `Initialize("")` on page load
Reports `cmi.score.raw` and `cmi.score.scaled` on each level completion  
(Score = earned XP ÷ 2,500 × 100)
Sets `cmi.completion_status = completed` and `cmi.success_status = passed` when Level 6 is completed
Calls `Terminate("")` on window unload
To package as SCORM:
Use devlin.ai/dashboard/scorm-wrap
Upload `index.html` — select SCORM 2004, threshold 60, trigger: score
Upload the resulting `.zip` to your LMS or SCORM Cloud for testing
When run on GitHub Pages (outside an LMS), the SCORM bridge silently does nothing — no errors.
---
UDL Accessibility Features
A floating accessibility toolbar (bottom-right) provides:
Feature	Description
🎤 Voice Dictation	Web Speech API — speak into any text field
🔊 Read Aloud	Text-to-speech for selected content
🔡 Large Text	Increases body font size to 120%
🌙 High Contrast	Dark background, high-contrast text
💬 Talk to PhD Chema	Opens AI voice tutor (Chema)
Accessibility preferences persist across the session via `sessionStorage`.
---
Student Instructions
Start here: Watch the intro video (button at the top of the page)
Read the overview — click "Show Full Academic Overview" to understand the full journey
Complete levels in order — each level unlocks the next
Click "Mark Level X Complete" at the bottom of each level to record your progress and earn XP
Unlock the Bonus Escape Room after Level 3 — crack the vault to warp ahead!
Final boss (Level 6): Record your abstract pitch and submit to your teacher
Claim your Diamond Crown 👑 — you've mastered academic abstract writing at C1 level
Tips:
Use the voice dictation button if you prefer speaking over typing
The leaderboard tracks your XP progress on the right side of the screen
You can revisit any completed level at any time
---
Teacher Instructions
Deployment Options
GitHub Pages (free): Already live at the URL above — share directly with students
LMS embed: Wrap as SCORM 2004 (see above) and upload to Moodle, Canvas, Blackboard, etc.
Direct link: Share `https://profeanaeslavaedtech.github.io/Gamification/` — no login required
Assessment Integration
Level 5: Monitor the class Padlet board for peer review submissions
Level 6: Collect Flip / Vocaroo recordings for speaking assessment
SCORM reports: If deployed via LMS, track completion status and scores in the gradebook
Customisation
All content is in a single `index.html` file. To customise:
Edit level descriptions, activity links, and XP values in the `levels` array (JavaScript)
Replace Canva course links with your own
Update the leaderboard names in the `leaderboard` array
Change the SCORM score threshold in the bridge (`TOTAL_XP` constant = 2500)
---
Tech Stack
Technology	Purpose
HTML5 / Vanilla JS	Single-file app — no build step required
Tailwind CSS (CDN)	Utility-first styling
Font Awesome 6	Icons
Bebas Neue (Google Fonts)	Display typography
Web Speech API	Voice dictation & read-aloud (UDL)
SCORM 2004 API bridge	LMS integration (built-in)
Canva	Course videos, lessons, intro & farewell videos
GitHub Pages	Free hosting & deployment
---
Citation & Copyright
© June 2026 Ana Eslava-Graterol · @profeanaeslava  
Developed in co-authorship with Claude Code — AI-Powered Web Development Engineer.  
Project aimed at promoting ethical and responsible Human–AI Collaboration in Education in AI Literacy and Academic Literacy in English for Specific Purposes (ESP/EAP).
APA 7th Edition:
> Eslava-Graterol, A. (2026). *Academic Writing Journey: A gamified eLearning unit for academic abstract writing (B2–C1)* [Interactive web application]. GitHub Pages. https://profeanaeslavaedtech.github.io/Gamification/
Course: "Simulation, Games and Technology in Second Language Teaching"  
Prof. Casañ Pitarch, Ricardo · Universitat Politècnica de València (UPV)
---
For issues or contributions, open a GitHub Issue or contact @profeanaeslava.

