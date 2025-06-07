# WarfaRef-Showcase

<p align="center">
  <img src="images/warfaref-icon.png" alt="WarfaRef Logo" width="120"/>
</p>

<h2 align="center">WarfaRef</h2>
<p align="center"><em>A Digital Health Mobile Application for Warfarin Self-Monitoring and Early Risk Detection</em></p>


## Team & Contributions
**Advisors:** Stefan Lukianov and Daniel Wang
- **Hunter Risdon**: Full-stack development, UI/UX design, backend data processing, algorithm integration
- **Numa Yazadi**: Algorithm development, frontend/backend bridging, usability testing
- **Somto Ikeanyi**: Iconography


> Developed at **UC San Diego – Bioengineering Department** in partnership with **Salve Therapeutics**


---

## Overview
WarfaRef is a cross-platform mobile application designed to modernize anticoagulation therapy management for patients on warfarin. Built using React Native and Firebase, WarfaRef enables patients to monitor their INR values, visualize health trends, and receive real-time alerts for abnormal readings and health trends that correspond with increased risk of adverse clinical events. The application currently supports manual data entry and is architected for future integration with Bluetooth INR devices and Electronic Health Record (EHR) systems.

> **Note:** The source code for WarfaRef is **private** due to proprietary healthcare algorithms and HIPAA-related design considerations. Recruiters and collaborators may request restricted access by contacting the team directly.

----
### App Demo

<p align="center">
  <img src="images/warfaref-demo.gif" alt="WarfaRef App Demo" width="300"/>
</p>

<p align="center">
  <a href="videos/demo-link.mp4">Watch Demo Video</a>
</p>

---

## Key Features
- **Early Risk Detection**: Real-time alerts based on personalized thresholds for abnormal INR values, using synthetic-data trained logic models.
- **Machine Learning Personalization**: Custom INR range predictions based on patient profile data and risk factors.
- **Data Visualization**: Interactive graphs, trend displays, and calendar-based health tracking.
- **EHR Integration (in progress)**: Future provider-facing dashboard with HL7 FHIR compatibility.

---

## Technology Stack
- **Frontend**: React Native (Expo)
- **Backend**: Firebase Authentication & AsyncStorage
- **ML Integration**: Python-based model prototyping using synthetic patient data (via Synthea), with planned integration into AutoML pipelines
- **Upcoming**: HL7 FHIR-based EHR communication; security mechanisms aligned with HIPAA-compliant data flow standards (future phases)

---
<h2 align="center">Design Artifacts & Media</h2>

<p align="center"><strong>Original Figma Design</strong><br/>
  <img src="images/figma-design.png" alt="Figma Mockup" width="925"/>
</p>

<p align="center"><strong>WarfaRef Design Poster</strong><br/>
</p>
<p align="center">
  <img src="images/warfaref-poster.png" alt="Poster" width="925"/>
</p>

<p align="center">
  <strong>Workflow Diagram</strong>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <strong>Competitor Matrix</strong>
</p>
<p align="center">
  <img src="images/workflow-diagram.png" alt="Workflow Diagram" width="450"/>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <img src="images/competitor-diagram.png" alt="Competitor Diagram" width="450"/>
</p>


---

## Research & Design Foundations
WarfaRef was designed in alignment with:
- IEC 62304 (Medical Software Lifecycle)
- ISO 14971 (Risk Management)
- FDA 21 CFR Part 11 (Electronic Records)
- HL7 FHIR (Healthcare Interoperability)

> Our decision logic for alerting abnormal INR values is based on peer-reviewed clinical guidelines and further enhanced with ML techniques trained on synthetic patient cohorts. The model developed for risk prediction has been trained solely on synthetic datasets and has not yet been tested or validated using real-world patient data. It is intended only as a supplemental tool to help patients better understand their health data. Patients must always consult with their healthcare provider before making any decisions based on app-generated insights. We plan to pursue clinical testing and validation in the future, once full compliance with HIPAA and relevant IRB (Institutional Review Board) guidelines has been achieved.

---

## Roadmap
- ✅ Core patient app with real-time alerts
- 🔄 Provider dashboard under development
- 🔄 Bluetooth INR device support
- 🔄 EHR integration (FHIR compliant)
- 🔄 AI-driven dosing recommendation engine (under clinical trial design)

---

## Future Vision & Clinical Impact
WarfaRef aims to:
- Improve **Time in Therapeutic Range (TTR)** to over 60%
- Reduce provider response time to critical INR events by 40%
- Enable broader use of INR home-testing across elderly populations
- Serve over **6 million warfarin users** and **900,000 providers** in the U.S.

In the next phase, we aim to complete pilot deployment in San Diego clinics, publish clinical trial results, and finalize HIPAA/FDA compliance for scaled deployment.

---

## Screenshots & Visuals

> _The following screenshots demonstrate the primary user flows and features of the WarfaRef mobile application._

<table style="border-collapse: collapse; margin: 0 auto;">
  <tr>
    <td align="center" style="border: none;">
      <img src="images/login-screen.png" width="250"/><br/>
      <strong>Login</strong>
    </td>
    <td align="center" style="border: none;">
      <img src="images/home-screen.png" width="250"/><br/>
      <strong>Home</strong>
    </td>
    <td align="center" style="border: none;">
      <img src="images/data-entry-screen.png" width="250"/><br/>
      <strong>Data Entry</strong>
    </td>
    <td align="center" style="border: none;">
      <img src="images/statistics-averages.png" width="250"/><br/>
      <strong>Statistics Averages</strong>
    </td>
  </tr>
  <tr>
    <td align="center" style="border: none;">
      <img src="images/statistics-graph-inr.png" width="250"/><br/>
      <strong>INR Graph</strong>
    </td>
    <td align="center" style="border: none;">
      <img src="images/statistics-graph-full.png" width="250"/><br/>
      <strong>Full Stats Graph</strong>
    </td>
    <td align="center" style="border: none;">
      <img src="images/statistics-abnormalities.png" width="250"/><br/>
      <strong>Abnormalities</strong>
    </td>
    <td align="center" style="border: none;">
      <img src="images/calendar-screen.png" width="250"/><br/>
      <strong>Calendar</strong>
    </td>
  </tr>
  <tr>
    <td align="center" style="border: none;">
      <img src="images/chat-screen.png" width="250"/><br/>
      <strong>Chat</strong>
    </td>
    <td align="center" style="border: none;">
      <img src="images/notification-list.png" width="250"/><br/>
      <strong>Notifications</strong>
    </td>
    <td align="center" style="border: none;">
      <img src="images/questionnaire-screen.png" width="250"/><br/>
      <strong>Questionnaire</strong>
    </td>
    <td align="center" style="border: none;">
      <img src="images/settings-screen.png" width="250"/><br/>
      <strong>Settings</strong>
    </td>
  </tr>
</table>

---

## Contact & Access
For demo access (TestFlight or Expo) or inquiries about restricted source code:
- Email: risdonhunter@gmail.com  
- LinkedIn: www.linkedin.com/in/hunter-risdon  

> **License**: This repository is licensed under a View-Only Intellectual Property License. See LICENSE for terms.
