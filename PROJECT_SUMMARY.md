# Portfolio Project Summary

**Owner:** Mark Hubert Boctulan (MHB)  
**Type:** Single-page HTML portfolio website  
**Purpose:** Job application portfolio showcasing skills, projects, and contact info

---

## File Structure

| File | Description |
|------|-------------|
| `index.html` | Main production file (deployed entry point) |
| `forfolio.html` | Source/working copy (same content, uses `./assets/` paths) |
| `Resume.pdf` | Downloadable resume linked in the contact section |
| `assets/Profile.png` | Profile photo used in the hero section |
| `assets/TimberScan.jpg` | TimberScan project screenshot (live camera scan) |
| `assets/TimberScan2.jpg` | TimberScan project screenshot (classification results) |
| `assets/BaoMeter.jpg` | BaoMeter system prototype photo |

---

## Design & Tech

- **Stack:** Pure HTML + CSS + vanilla JavaScript (no build tools, no frameworks)
- **Theme:** Dark background (`#0e0d0b`) with gold/amber accent (`#c9a84c`)
- **Fonts:** Cormorant Garamond (headings), Inter (body), DM Mono (code/tags)
- **Visual effects:** Three animated gold glow orbs (fixed, blurred, CSS keyframes)
- **Animations:** IntersectionObserver-driven `.reveal` fade-ins on scroll
- **Modals:** Custom `<dialog>`-based project detail overlays with a lightbox for screenshots
- **Responsive:** Multiple CSS breakpoints covering mobile, tablet, and desktop

---

## Page Sections

### 1. Hero
- Name: **Mark Hubert Boctulan**
- Tagline: *"Computer Engineering student building embedded systems, AI tools, and apps."*
- CTAs: **View My Work** (→ Projects) · **Let's Connect** (→ Contact)

### 2. About — "Building with purpose"
> *"I'm a Computer Engineering student who likes turning ideas into tools people can actually use. My work sits at the intersection of software, hardware, and interface design, with a strong focus on clarity, reliability, and usefulness in real situations."*

Goal: grow into an engineer who solves practical problems for communities and organizations, not just ships polished demos.

### 3. Skills — Technical Capabilities

| Skill Area | Tags |
|---|---|
| Web & PWA Development | JavaScript, Firebase |
| Mobile Development | Flutter, Dart |
| AI / Machine Learning | Python, TensorFlow Lite |
| Embedded Systems | C++, Arduino, Arduino IDE |

**Tools & Platforms:** VS Code · Android Studio · Google Colab · Firebase · Supabase · Flutter SDK · Arduino IDE · Git & GitHub

### 4. Projects — Featured Work

#### Resilink — Disaster Response PWA
- **Type:** Progressive Web App
- **Purpose:** LGU disaster response coordination for Antequera and San Isidro, Bohol
- **Features:** Real-time Firestore database sync, FCM push notifications via Vercel serverless backend, full offline support for low-connectivity emergency situations, Leaflet-based disaster mapping with evacuation routes, collapsible topic sections
- **Stack:** JavaScript, Firebase
- **Live:** [markhubertb.github.io/Resilink/](https://markhubertb.github.io/Resilink/)

#### TimberScan — Lumber Identification App
- **Type:** Flutter mobile application
- **Purpose:** Identifies lumber types from live camera images using a trained CNN
- **Role:** Lead Developer
- **ML pipeline:** Trained in Google Colab (Python), converted to TensorFlow Lite, deployed on-device for real-time classification
- **Features:** Live camera scanning, classification results display, frontend UI for dataset interaction and result visualization
- **Stack:** Flutter, Dart, Python, TensorFlow Lite, Google Colab

#### BaoMeter — Fare System
- **Type:** Embedded hardware system
- **Purpose:** Electronic fare system for BaoBao (small passenger) vehicles
- **Role:** Systems Integrator
- **Features:** Hall sensor for passenger detection, ISR debouncing for reliable input, `READY → COUNTING → STOPPED` state machine, automated fare computation, display output
- **Stack:** C++, Arduino, Arduino IDE

### 5. Education
- **Degree:** Bachelor of Science in Computer Engineering
- **School:** Bohol Island State University (BISU), Tagbilaran City, Bohol
- **Status:** Currently 3rd Year · Expected Graduation: **2027**

### 6. Contact

| Channel | Detail |
|---|---|
| Resume | `Resume.pdf` (downloadable) |
| Phone / WhatsApp | 0970 819 9724 |
| Email | boctulanm@gmail.com |
| GitHub | github.com/MarkHubertB |
| LinkedIn | Linked in site |
| Location | Cogon, Tagbilaran City, Bohol |

---

## Git History (recent)

| Commit | Message |
|---|---|
| `0e667c1` | Update the job title |
| `08f7b37` | Web visit link fix |
| `0c8bc1e` | Fix Image bug |
| `9fbf42f` | Fix some Bugs |
| `5fc30cc` | Improve the Hero section |
