<!-- ==================== HEADER ==================== -->

<div align="center">

<img src="./header.svg" width="100%" alt="Vimukthi Rajapaksha" />

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=21&pause=1500&color=D4AF37&center=true&vCenter=true&width=850&lines=Computer+Engineering+Undergraduate;High+Performance+Computing+Minor;Exploring+Software%2C+Cloud+and+IoT;Learning+Through+Hands-On+Projects" alt="Computer Engineering undergraduate with a minor in High Performance Computing" width="100%" />

<br />

<p align="center">
  <img src="https://img.shields.io/badge/University_of_Sri_Jayewardenepura-4C1D95?style=for-the-badge&labelColor=140B2E" alt="University of Sri Jayewardenepura" />
  <img src="https://img.shields.io/badge/Faculty_of_Engineering-B08D29?style=for-the-badge&labelColor=140B2E" alt="Faculty of Engineering" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Major-Computer_Engineering-4C1D95?style=flat-square&labelColor=140B2E" alt="Major in Computer Engineering" />
  <img src="https://img.shields.io/badge/Minor-High_Performance_Computing-B08D29?style=flat-square&labelColor=140B2E" alt="Minor in High Performance Computing" />
  <img src="https://img.shields.io/badge/Location-Sri_Lanka-3B2A6B?style=flat-square&labelColor=140B2E" alt="Sri Lanka" />
</p>

<br />

<a href="https://www.linkedin.com/in/vimukthirajapaksha/">
  <img src="https://img.shields.io/badge/LinkedIn-4C1D95?style=for-the-badge&logo=linkedin&logoColor=D4AF37&labelColor=140B2E" alt="LinkedIn" />
</a>
<a href="mailto:vimukthiudeshan2018@gmail.com">
  <img src="https://img.shields.io/badge/Email-4C1D95?style=for-the-badge&logo=gmail&logoColor=D4AF37&labelColor=140B2E" alt="Email" />
</a>
<a href="https://github.com/VimukthiUdeshan?tab=repositories">
  <img src="https://img.shields.io/badge/GitHub-4C1D95?style=for-the-badge&logo=github&logoColor=D4AF37&labelColor=140B2E" alt="GitHub" />
</a>

</div>

<!-- ==================== MAIN CONTENT ==================== -->

<div align="left">

## About Me

I am a **Computer Engineering undergraduate** at the **University of Sri Jayewardenepura**, pursuing a minor in **High Performance Computing (HPC)**.

My interests include **Software Engineering, Full Stack Development, Artificial Intelligence, IoT Systems, Mobile Development, Cloud Computing, and Parallel Computing**. I enjoy exploring how hardware and software work together to solve practical problems.

Through academic and personal projects, I am building experience in:

- Web and mobile application development
- Embedded systems and IoT monitoring
- Cloud-integrated applications using AWS
- C++ programming and algorithm implementation
- Database-driven applications

### Open To

- Software Engineering Internships
- Full Stack and Mobile Development Opportunities
- AI / ML and IoT Projects
- Cloud & DevOps Learning Opportunities
- Open Source Contributions
- HPC and Research Collaborations

---

## Featured Projects

<!--
ADD A PROJECT:
Copy a complete <details open>...</details> block.
Update its title, description, table, and repository link.
Use <details> to make the project collapsed initially.
-->

<details>
<summary><b>TropicStore — Smart Fruit Ripening Chamber</b></summary>

<br />

An **IoT-based smart fruit ripening chamber** designed to provide an automated and controlled environment for fruit ripening.

The system uses an ESP32 to monitor environmental conditions and control actuators, with MQTT, AWS IoT, and a dedicated mobile application supporting remote monitoring and control.

| Area | Details |
| :--- | :--- |
| Domain | Embedded Systems · IoT · Cloud Integration |
| Core technologies | ESP32 · MQTT · AWS IoT |
| Chamber controls | Exhaust fan, servo-operated ventilation door, mist maker, and lighting |
| Objective | Reduce continuous manual monitoring through automated chamber control |

<!--
Add when ready:
**My contribution:** Describe your firmware, hardware, app, or cloud work.
-->

<a href="https://github.com/TropicStore/TropicStore">
  <img src="https://img.shields.io/badge/View_Repository-TropicStore-6D28D9?style=for-the-badge&logo=github&logoColor=D4AF37&labelColor=140B2E" alt="View TropicStore repository" />
</a>

</details>

<details>
<summary><b>StuDZ — University Student Companion App</b></summary>

<br />

A cross-platform **mobile app for engineering undergraduates** that brings timetables, attendance, exams, GPA, notes and a campus community into one place. It is built around the **Faculty of Engineering Student Guide 2026**, so the module, lecturer and elective data is built into the app.

| Area | Details |
| :--- | :--- |
| Domain | Mobile Development · Backend & Security · Gemini API Integration |
| Core technologies | React Native · Expo · TypeScript · Supabase · Gemini API |
| Status | **In active development** · Android builds via EAS |

### Key Features

- **Timetable Extraction with Gemini API:** Students upload a PDF or photo of their timetable. A Supabase Edge Function sends it to the Gemini API, which returns structured JSON. Lecturers are matched against the staff directory, and a review screen lets students correct every entry before it is saved.
- **Semester Setup:** Compulsory, elective and optional modules, with elective credit groups taken from the handbook.
- **Hybrid Attendance:** Online participation limits per module, labs attended in person, and adaptive notification polls after each class.
- **Live Class Countdown:** A circular progress ring during lectures, with a one-tap join link for online sessions.
- **Exams & Revision Tracking:** Exam countdowns with per-module syllabus coverage.
- **GPA Tools:** The handbook grading scale, re-sit and repeat caps, class honours, and past-semester grade entry.
- **Notes:** Typed, handwritten (SVG canvas) and photo notes organised by module and topic, with sharing to the community.
- **Community & Groups:** Posts with photos, comments and reporting, plus private invite-code groups with realtime chat.
- **Account Security:** University-email registration enforced by database triggers, email confirmation, Row Level Security, rate limits, and automatic hiding of repeatedly reported content.
- **Admin Website:** A web panel for the module catalog, lecturers, academic calendar, announcements, moderation and users.

### Technology Stack

| Component | Technologies |
| :--- | :--- |
| Mobile Application | React Native · Expo (SDK 54) · TypeScript · Expo Router |
| Backend & Database | Supabase Auth · PostgreSQL · Row Level Security · Realtime · Storage |
| Serverless | Supabase Edge Functions (Deno) |
| Document Understanding | Gemini API (image and PDF input, structured JSON output) |
| Graphics & Device | react-native-svg · expo-notifications · expo-image-picker |
| Build & Release | EAS Build (Android APK) |
| Admin Panel | HTML · CSS · JavaScript |

<!--
<a href="https://github.com/VimukthiUdeshan/StuDZ">
  <img src="https://img.shields.io/badge/View_Repository-StuDZ-6D28D9?style=for-the-badge&logo=github&logoColor=D4AF37&labelColor=140B2E" alt="View StuDZ repository" />
</a>
-->

</details>

<details>
<summary><b>RescueMesh — AI-Assisted Flood Emergency Response</b></summary>

<br />

A flood emergency response project combining a **mobile application, registration website, administrative dashboard, and backend services** to support rescue-request management.

The software processes SOS messages, associates requests with registered household information, predicts message severity using **machine learning**, and uses **Google Gemini** for concise summaries and suggested responses.

**Recognition:** SLIOT 2026 — **Semifinalist**

### Key Features

- **SOS Processing:** Receives alerts, checks active device registration, and checks for repeated messages within a 60-second window.
- **Incident Context:** Associates requests with registered household details, family size, and home coordinates.
- **ML-Based Severity Classification:** Uses **TF-IDF text features** and a **Random Forest classifier with 100 decision trees**, served through a Flask API.
- **Emergency Button Handling:** Assigns predefined severity levels to critical and general button alerts.
- **AI Summaries:** Uses **Gemini 2.5 Flash** to summarise longer messages, with instructions to retain Sinhala for Sinhala requests.
- **Suggested Responses:** Generates short, context-aware reply suggestions for operators.
- **Gateway Reply Queue:** Stores submitted responses for gateway retrieval and tracks gateway-reported send status.
- **Incident History:** Maintains alert records, response history, timestamps, and handling status in Cloud Firestore.

### Technology Stack

| Component | Technologies |
| :--- | :--- |
| Mobile Application | Flutter · Dart |
| Backend | Node.js · Express.js |
| Database | Firebase Cloud Firestore |
| Severity Classification | Python · scikit-learn · TF-IDF · Random Forest |
| ML Prediction API | Flask |
| Summaries & Reply Suggestions | Google Gemini 2.5 Flash |

### Repositories

| Component | Repository |
| :--- | :--- |
| **Mobile Application** | [View App](https://github.com/VimukthiUdeshan/Rescue-Mesh) |
| **Registration Website** | [View Registration Site](https://github.com/VimukthiUdeshan/Rescue-Mesh-Registration-Site) |
| **Administrative Dashboard** | [View Dashboard](https://github.com/VimukthiUdeshan/Rescue-Mesh-Official-Dashboard) |
| **Backend** | [View Backend](https://github.com/VimukthiUdeshan/Rescue-Mesh-Backend) |
| **ML Model & Prediction API** | Repository link coming soon |

<!--
ADD YOUR ML REPOSITORY:
Replace "Repository link coming soon" in the table above with:

[View ML Repository](YOUR_ML_REPOSITORY_URL)
-->


<!--
FUTURE UPDATES:
- Add screenshots or a demo video.
- Add your specific contributions within the team.
- Update the IoT integration status after testing.
- Add model evaluation results once measured on held-out data.
-->

</details>

<details>
<summary><b>AI Business Automation Platform — Beauty of Cloud 2.0</b></summary>

<br />

A cloud solution concept and dashboard demo developed by **Team VR Force** for **Beauty of Cloud 2.0**, achieving **1st Runner-Up**.

The proposed platform enables businesses to create task-specific AI assistants that use authorised company information and approved tools to handle requests such as order cancellations, appointment bookings, customer complaints, and document preparation.

The design focuses on keeping each business’s data separate, requiring human approval for sensitive actions, maintaining audit records, and controlling usage costs.

| Area | Details |
| :--- | :--- |
| Team | VR Force |
| Competition | Beauty of Cloud 2.0 |
| Achievement | 1st Runner-Up |
| Deliverables | Cloud architecture proposal and dashboard demo |
| Demo frontend | React · TypeScript |
| Proposed cloud platform | Amazon Web Services (AWS) |
| Architecture components | Amazon Bedrock · Lambda · API Gateway · Cognito · S3 · CloudFront · SQS · Step Functions · DynamoDB · Aurora PostgreSQL |
| Design priorities | Tenant isolation · Human approval · Auditability · Cost control |

### Dashboard Demo

The dashboard includes interfaces for an operational overview, knowledge management, conversations, orders, analytics, and security settings.

### Proposed Architecture

- **AI assistance:** Use Amazon Bedrock with retrieval of relevant, authorised business documents.
- **Controlled actions:** Validate permissions and require approval before sensitive operations.
- **Workflow management:** Use SQS and Step Functions for queued tasks and approval workflows.
- **Business data isolation:** Apply tenant-aware access controls across application and storage layers.
- **Operational visibility:** Track task progress, usage, spending, and action records.

**Project scope:** A competition prototype demonstrating the dashboard and proposed architecture; the full production platform was not implemented.

<!--
ADD YOUR REPOSITORY:
Replace "Repository: Coming soon." above with the following line,
then replace YOUR_REPOSITORY_URL with your GitHub repository link.

[View Repository →](YOUR_REPOSITORY_URL)
-->
<a href="https://github.com/VR-Force/cloud-based-multi-tenant-ai-platform">
  <img src="https://img.shields.io/badge/View_Repository-Cloud_AI_Platform-6D28D9?style=for-the-badge&logo=github&logoColor=D4AF37&labelColor=140B2E" alt="View Cloud AI Platform repository" />
</a>

</details>

<details>
<summary><b>Shelfy AI — NLP Supermarket Shopping Assistant</b></summary>

<br />

A desktop chatbot designed for a supermarket entrance. Shoppers type their grocery list in plain English, and the assistant finds each item, shows its shelf location, and exports a printable PDF shopping list.

Developed for **CO3251 – Natural Language Processing** at the University of Sri Jayewardenepura.

### Key Features

- **NLP Item Extraction:** Uses NLTK tokenization, POS tagging, and lemmatization, with a noise-word filter, to pull grocery items out of free-form sentences.
- **Product Lookup:** Searches a database of 101 products across 18 shelf zones, using exact matching first and then fuzzy matching.
- **Typo Recovery:** Suggests close matches with one-tap *Yes / No* buttons (for example, "chokolate" → "milk chocolate").
- **PDF Shopping List:** Exports the cart with shelf locations, date, and time using ReportLab.
- **Accounts and History:** Supports email, Google, and guest sign-in, with trips saved to Firebase Realtime Database.

### Technology Stack

| Component | Technologies |
| :--- | :--- |
| Language | Python |
| NLP | NLTK · WordNet · difflib |
| Desktop GUI | CustomTkinter |
| Authentication & Storage | Firebase Auth · Realtime Database · Google OAuth2 |
| PDF Export | ReportLab |

<a href="https://github.com/VimukthiUdeshan/shelfy-ai">
  <img src="https://img.shields.io/badge/View_Repository-Shelfy_AI-6D28D9?style=for-the-badge&logo=github&logoColor=D4AF37&labelColor=140B2E" alt="View Shelfy AI repository" />
</a>

</details>

<details>
<summary><b>Load-Balanced Parallel GNN Inference — HPC Project</b>&nbsp;</summary>

<br />

A High Performance Computing project on **parallel Graph Neural Network (GNN) inference for large collections of small graphs**.

The goal is to build a **C/C++ inference engine**, parallelise it with **OpenMP**, and compare **scheduling strategies** to distribute workload evenly across CPU cores.

| Area | Details |
| :--- | :--- |
| Domain | Parallel Programming · Multicore Computing · Performance Evaluation |
| Core technologies | C/C++ · OpenMP |
| Focus | Load balancing and scheduling strategy comparison |
| Status | **In progress** |

</details>

<details>
<summary><b>Smart Farming — AI-Assisted Crop Advisory & Soil Monitoring</b></summary>

<br />

A **Flutter mobile application** that helps farmers make data-driven decisions without needing prior agricultural knowledge. It combines **live soil sensor readings, local weather data, and AI** to recommend suitable crops, identify plant problems, and answer farming questions.

Soil data is collected by an **ESP32** connected to a **pH probe sensor (0–14 pH)** and an **RS485 3-in-1 soil sensor (EC, humidity, and temperature)**, and streamed to the app through **Firebase Realtime Database** for real-time field monitoring.

### Key Features

- **Crop Recommendation:** Combines soil pH, EC, moisture, temperature, soil type, and live weather to suggest suitable crops, with manual input when no sensor is connected.
- **Live Soil Monitoring:** Animated gauges for pH, EC, soil humidity, and soil temperature, updated from the ESP32 through Firebase.
- **Plant Doctor:** Take or upload a plant photo for identification using the **PlantNet API**, with past results saved in scan history.
- **AI Assistant:** A **Google Gemini** chatbot that answers farming questions in plain language.
- **Weather Insights:** Current conditions and forecasts through the **OpenWeather API**.
- **Multilingual Support:** English, Sinhala, and Tamil.
- **Authentication:** Email and Google sign-in with Firebase Auth.

### Technology Stack

| Component | Technologies |
| :--- | :--- |
| Mobile Application | Flutter · Dart |
| Microcontroller | ESP32 |
| Sensors | pH probe sensor (0–14 pH) · RS485 3-in-1 EC, humidity, and temperature soil sensor |
| Backend & Database | Firebase Auth · Cloud Firestore · Realtime Database |
| AI & APIs | Google Gemini · PlantNet · OpenWeather |
| Crop Scoring Module | Python · Flask |

<a href="https://github.com/Rifthy2003/Smart-Farming">
  <img src="https://img.shields.io/badge/View_Repository-Smart_Farming-6D28D9?style=for-the-badge&logo=github&logoColor=D4AF37&labelColor=140B2E" alt="View Smart Farming repository" />
</a>

</details>

---

## Technical Skills

### Programming Languages

<p align="left">
  <img src="https://skillicons.dev/icons?i=cpp,python,java,js,ts,dart&theme=dark" alt="C++, Python, Java, JavaScript, TypeScript, Dart" />
</p>

### Web, Backend & Databases

<p align="left">
  <img src="https://skillicons.dev/icons?i=html,css,nodejs,express,flask,mysql,postgres&theme=dark" alt="HTML, CSS, Node.js, Express, Flask, MySQL, PostgreSQL" />
</p>

### Mobile App Development

<p align="left">
  <img src="https://skillicons.dev/icons?i=flutter,react&theme=dark" alt="Flutter, React Native" />
</p>

### Cloud, Backend Services & Containers

<p align="left">
  <img src="https://skillicons.dev/icons?i=aws,firebase,supabase,docker&theme=dark" alt="AWS, Firebase, Supabase, Docker" />
</p>

### Development & Design Tools

<p align="left">
  <img src="https://skillicons.dev/icons?i=git,github,vscode,figma,postman&theme=dark" alt="Git, GitHub, Visual Studio Code, Figma, Postman" />
</p>

### Also Worked With

<p align="left">
  <img src="https://img.shields.io/badge/Expo-EAS_Build-000020?style=flat-square&logo=expo&logoColor=white&labelColor=140B2E" alt="Expo and EAS Build" />
  <img src="https://img.shields.io/badge/Google_Gemini-API-6D28D9?style=flat-square&labelColor=140B2E" alt="Google Gemini API" />
  <img src="https://img.shields.io/badge/Deno-Edge_Functions-3B2A6B?style=flat-square&labelColor=140B2E" alt="Supabase Edge Functions on Deno" />
  <img src="https://img.shields.io/badge/scikit--learn-ML-3B2A6B?style=flat-square&labelColor=140B2E" alt="scikit-learn" />
</p>

---

## Volunteering & Extracurricular Experience

<!--
ADD EXPERIENCE:
Copy a complete <details>...</details> block.
Update the club, event, role, and contributions.
Use <details open> to expand a role by default.
-->

<details>
<summary><b>CGS — Career Xplore 2025 | Marketing Team Member</b></summary>

<br />

- Contributed to event promotion as a member of the marketing team.
- Designed promotional flyers and banners for the event.

**Skills:** Graphic Design · Visual Communication · Teamwork

</details>

<br />

<details>
<summary><b>Nexus — Dark Laugh | Marketing Team Member</b></summary>

<br />

- Supported event publicity as a member of the marketing team.
- Created flyers for promotional use.

**Skills:** Graphic Design · Visual Communication · Teamwork

</details>

<br />

<details>
<summary><b>IESL JIY 2025 | Editorial Pillar Member</b></summary>

<br />

- Served as a member of the Editorial Pillar.

<!-- Add your specific editorial contributions here when ready. -->

</details>

---

## Creative Skills

Alongside my technical work, I enjoy visual communication and creative media production.

- **Graphic Design:** Promotional flyers, banners, and event visuals
- **Video Editing:** Editing and assembling video content
- **Content Creation:** Developing visual and written content

---

## Competitions & Achievements

<!--
ADD AN ACHIEVEMENT:
Copy a table row and update the competition, result, and details.
-->

| Competition | Achievement | Project / Organiser |
| :--- | :--- | :--- |
| **SLIOT 2026** | **Semifinalist** | RescueMesh |
| **Beauty of Cloud 2.0** | **1st Runner-Up** | IEEE, University of Sri Jayewardenepura |

---

## Certifications & Badges

<!--
ADD A CERTIFICATE:
Copy a complete table row (the line starting with "| <a href=...").
Update the image path, title, issuer, date, badges and verification link.
Keep image widths: 180 for square badges, 280 for landscape certificates.
-->

| Certificate | Details |
| :--- | :--- |
| <a href="./assets/aws-cloud-foundations.png"><img src="./assets/aws-cloud-foundations.png" alt="AWS Academy Graduate - Cloud Foundations - Training Badge" width="180" /></a> | **AWS Academy Graduate – Cloud Foundations**<br />Issued by Amazon Web Services Training and Certification<br /><br /><img src="https://img.shields.io/badge/AWS_Academy-Cloud_Foundations-232F3E?style=flat-square&logo=amazonaws&logoColor=white&labelColor=140B2E" alt="AWS Academy Cloud Foundations" /> <img src="https://img.shields.io/badge/Type-Training_Badge-3B2A6B?style=flat-square&labelColor=140B2E" alt="Training Badge" /><br /><br />[Verify Badge on Credly →](https://www.credly.com/go/rAV5W1Ypo425QERsXvnjUA) |
| <a href="./assets/kaggle-intro-to-machine-learning.png"><img src="./assets/kaggle-intro-to-machine-learning.jpg" alt="Kaggle - Intro to Machine Learning Certificate of Completion" width="280" /></a> | **Intro to Machine Learning**<br />Issued by Kaggle · 26 November 2026<br /><br /><img src="https://img.shields.io/badge/Kaggle-Certificate_of_Completion-20BEFF?style=flat-square&logo=kaggle&logoColor=white&labelColor=140B2E" alt="Kaggle Certificate of Completion" /> <img src="https://img.shields.io/badge/Issued-November_2026-B08D29?style=flat-square&labelColor=140B2E" alt="Issued November 2026" /> <img src="https://img.shields.io/badge/Focus-Machine_Learning-3B2A6B?style=flat-square&labelColor=140B2E" alt="Machine Learning" /><br /><br />*Certificate of Completion awarded by Kaggle for successfully completing the Intro to Machine Learning course.*<br /><br />[View Certificate →](./assets/kaggle-intro-to-machine-learning.jpg) |
| <a href="./assets/python-for-beginners-uom.pdf"><img src="./assets/python-for-beginners-uom.png" alt="Python for Beginners E-Certificate, University of Moratuwa" width="280" /></a> | **Python for Beginners (Participant)**<br />Centre for Open & Distance Learning (CODL), University of Moratuwa · 26 November 2026<br /><br /><img src="https://img.shields.io/badge/Python-E--Certificate-6D28D9?style=flat-square&logo=python&logoColor=white&labelColor=140B2E" alt="Python E-Certificate" /> <img src="https://img.shields.io/badge/Issued-November_2026-B08D29?style=flat-square&labelColor=140B2E" alt="Issued November 2026" /> <img src="https://img.shields.io/badge/University_of_Moratuwa-CODL-3B2A6B?style=flat-square&labelColor=140B2E" alt="University of Moratuwa CODL" /><br /><br />*E-Certificate for participating in the Python for Beginners online learning programme, conducted by the Department of Computer Science & Engineering, Faculty of Engineering, University of Moratuwa.*<br /><br />**Credential ID:** `7uuGW3soj8`<br />[Verify Certificate →](https://open.uom.lk/verify) · [Download PDF →](./assets/python-for-beginners-uom.pdf) |

<!--
KAGGLE CREDENTIAL LINK:
If you have a public Kaggle certificate URL, add it next to "View Certificate" like:
· [Verify on Kaggle →](YOUR_KAGGLE_CERTIFICATE_URL)
-->

---

## Current Focus

<ul align="left">
  <li>Strengthening my <strong>React and application development</strong> skills.</li>
  <li>Expanding my knowledge of <strong>AWS and cloud computing</strong>.</li>
  <li>Building and documenting <strong>IoT and embedded systems projects</strong>.</li>
  <li>Exploring <strong>OpenMP, parallel GNN inference, and load balancing</strong> through my HPC project.</li>
</ul>

---

## GitHub Activity
 
<p align="center">
  <img src="https://github-stats-extended.vercel.app/api?username=VimukthiUdeshan&show_icons=true&hide_border=true&bg_color=140B2E&title_color=D4AF37&icon_color=F5D77A&text_color=EDE9FE&border_radius=12" alt="Vimukthi Rajapaksha's GitHub statistics" width="460" />
</p>

<!--
<p align="center">
  <img src="./assets/stats.svg" alt="Vimukthi Rajapaksha's GitHub statistics" width="460" />
</p>
-->

---

## Connect With Me

Interested in discussing software, cloud computing, IoT, or parallel computing? Get in touch.

<p align="left">
  <a href="https://www.linkedin.com/in/vimukthirajapaksha/">
    <img src="https://img.shields.io/badge/LinkedIn-Vimukthi_Rajapaksha-6D28D9?style=for-the-badge&logo=linkedin&logoColor=D4AF37&labelColor=140B2E" alt="Vimukthi Rajapaksha on LinkedIn" />
  </a>
  <a href="mailto:vimukthiudeshan2018@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-Contact_Me-6D28D9?style=for-the-badge&logo=gmail&logoColor=D4AF37&labelColor=140B2E" alt="Contact me by email" />
  </a>
  <a href="https://github.com/VimukthiUdeshan">
    <img src="https://img.shields.io/badge/GitHub-VimukthiUdeshan-140B2E?style=for-the-badge&logo=github&logoColor=D4AF37&labelColor=140B2E" alt="VimukthiUdeshan on GitHub" />
  </a>
</p>

</div>

<!-- ==================== FOOTER ==================== -->

<img src="./footer.svg" width="100%" alt="" />
