## Hi, I'm Carain

Final-year Biomedical Engineering student at KPRIET, Coimbatore (2027), building software for healthcare: IoT monitoring systems, full-stack web apps, and data tools.
Open to software engineering roles in backend and health-tech · carainsridhar@gmail.com

### Technical skills

**Programming languages**
<br>
<img src="https://img.shields.io/badge/Java-161b22?style=flat-square&logo=openjdk&logoColor=white" alt="Java">
<img src="https://img.shields.io/badge/Python-161b22?style=flat-square&logo=python&logoColor=white" alt="Python">
<img src="https://img.shields.io/badge/SQL-161b22?style=flat-square&logo=mysql&logoColor=white" alt="SQL">

**Web technologies**
<br>
<img src="https://img.shields.io/badge/HTML-161b22?style=flat-square&logo=html5&logoColor=white" alt="HTML">
<img src="https://img.shields.io/badge/CSS-161b22?style=flat-square&logo=css&logoColor=white" alt="CSS">
<img src="https://img.shields.io/badge/JavaScript-161b22?style=flat-square&logo=javascript&logoColor=white" alt="JavaScript">
<img src="https://img.shields.io/badge/Node.js-161b22?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js">
<img src="https://img.shields.io/badge/Express-161b22?style=flat-square&logo=express&logoColor=white" alt="Express">
<img src="https://img.shields.io/badge/MongoDB-161b22?style=flat-square&logo=mongodb&logoColor=white" alt="MongoDB">
<img src="https://img.shields.io/badge/Streamlit-161b22?style=flat-square&logo=streamlit&logoColor=white" alt="Streamlit">

**AI & generative AI**
<br>
Generative AI fundamentals · LLM fundamentals · Prompt engineering · AI-assisted development · Gemini API (used in [SafeSignal](https://github.com/Carain-dev/safesignal))

**Tools**
<br>
<img src="https://img.shields.io/badge/Git-161b22?style=flat-square&logo=git&logoColor=white" alt="Git">
<img src="https://img.shields.io/badge/GitHub-161b22?style=flat-square&logo=github&logoColor=white" alt="GitHub">
<img src="https://img.shields.io/badge/VS_Code-161b22?style=flat-square&logo=vscodium&logoColor=white" alt="VS Code">
<img src="https://img.shields.io/badge/Vercel-161b22?style=flat-square&logo=vercel&logoColor=white" alt="Vercel">
<img src="https://img.shields.io/badge/Render-161b22?style=flat-square&logo=render&logoColor=white" alt="Render">

### Projects

**IVORA: Smart IV Monitoring Prototype** · *capstone, in progress*
<br>
Healthcare IoT prototype that tracks IV bag weight (load cell → HX711 → ESP32 → Blynk). A FastAPI service polls the readings, estimates the weight-change rate in g/min, raises rule-based flags (possible flow interruption, low weight, bag replacement) and an Isolation Forest anomaly flag, and shows everything on a React dashboard. Currently a single-bed demo; heuristic flags, not clinically validated.
<br>
`ESP32` `HX711` `Blynk` `FastAPI` `SQLAlchemy` `React` `Vite` `Docker`

**[IEEE EMBS Student Chapter Website](https://github.com/Carain-dev/EMBS-Website)** · [live site](https://embs-website-chi.vercel.app)
<br>
Full-stack site for my college's IEEE EMBS chapter, with a password-protected admin CMS for events, members, projects, blogs, podcasts, gallery and announcements. I led development.
<br>
`Node.js` `Express` `MongoDB` `JWT auth` `Cloudinary` `REST API`

**[SafeSignal: Drug Side-Effect Explorer](https://github.com/Carain-dev/safesignal)** · [live app](https://safesignal-carain.streamlit.app)
<br>
Queries FDA adverse-event reports (openFDA) for any drug and charts top reactions, seriousness and yearly trends, with an LLM-written summary and a template fallback. Modular code with 33 pytest tests.
<br>
`Python` `Streamlit` `pandas` `REST API` `Gemini API` `pytest`

**QR-Based Indoor Navigation** · *code not yet on GitHub*
<br>
Web platform where admins upload floor maps and define rooms, paths and restricted areas. Users scan a QR code at an entry point to get in-building directions, with Normal, Panic and Wheelchair routing modes.
<br>
`HTML` `CSS` `JavaScript`

**Prosthetic Hand Prototype** · *bench-test prototype*
<br>
ESP32 drives a servo-actuated finger/hand mechanism. A potentiometer is the temporary control input: its ADC reading is mapped to a smoothed servo angle. A Python simulator tests the control logic without hardware. EMG integration is planned, not yet implemented.
<br>
`ESP32` `Arduino C++` `Servo control` `Python`

**[Supermarket Billing System](https://github.com/Carain-dev/Mini-Projects)**
<br>
Core Java console app with admin/customer roles, inventory, cart and checkout, loyalty rewards and reports, organised into model, repository and service layers.
<br>
`Java 17` `OOP` `Collections`

### Highlights

Internship, Aspire Technologies (nurse alert system) · Finalist, national hackathon at VIT (2026) · 1st place, project presentation at SREC (2025) · Design Lead, IEEE EMBS Student Chapter
