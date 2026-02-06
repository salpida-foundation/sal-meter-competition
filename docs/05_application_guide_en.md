# Application Guide: How to Apply for the Sal-Meter Open Competition

This document provides step-by-step guidance for teams and individuals wishing to participate in the Sal-Meter Open Competition.

> **For PIs and lab leaders**
>
> Before reading the full application guide, you may wish to review the  
> **[PI Quick Decision Pack (2 pages)](./PI_Quick_Decision_Pack.md)**.
>
> This document is designed to support a PI-level go/no-go decision within
> 30 minutes, and can be shared directly in a lab or group meeting without
> modification.

---

## Overview

Participation consists of **3 stages**:

1. **Pre-Application (2-3 weeks):** Read 4 mandatory documents, assemble team
2. **Application Package (1 week):** Prepare application materials
3. **Submission (1 day):** Submit via official email

**Total Time Required:** Approximately 2-4 weeks

---

## Stage 1: Pre-Application (2-3 weeks)

### 1-1) Read Mandatory Documents (2-3 hours)

All applicants must read the following **4 canonical documents**. These are the "constitution" of the competition.

| Order | Document | DOI | Content |
|-------|----------|-----|---------|
| 1 | Sal-Meter Definition v1.0 | https://doi.org/10.5281/zenodo.18452075 | What is Sal-Meter, technical specifications |
| 2 | CAIS Compliance Boundary v1.0 | https://doi.org/10.5281/zenodo.18452269 | Mandatory requirements, disqualification criteria |
| 3 | Competition Charter v1.0 | https://doi.org/10.5281/zenodo.18452453 | Competition rules, judging criteria, IP policy |
| 4 | Negative Definition v1.0 | https://doi.org/10.5281/zenodo.18452694 | What Sal-Meter is **NOT** |

**Important:**
- Failure to read these 4 documents significantly increases risk of rejection
- **Mandatory for Track A/B applicants**
- **Reference level for Track C**

### 1-2) Assemble Your Team (1-2 weeks)

Recruit needed talent. See [Team Composition Guide](./03_team_composition.md).

**Recruitment Channels:**

- LinkedIn: Search researchers/engineers
- GitHub: Find open-source contributors
- Universities: Faculty referrals, alumni networks
- Conferences: International scientific meetings
- Social Media: Twitter, Reddit, community forums

**Team Validation Checklist:**

For Track A/B:
- [ ] Team Leader (3+ years experience in field)
- [ ] Technical Staff (2-3 people, 2+ years experience)
- [ ] Project Manager (1)
- [ ] Leader/PM English proficiency (for international communication)

For Track C:
- [ ] Minimum 1 person (experience level not required)

---

## Stage 2: Application Package Preparation (1 week)

### 2-1) Prepare Application Materials

Assemble a **package** including the following:

#### A) Team Introduction (1-2 pages)

Include the following information:

- **Team Name** (English)
- **Team Size** (current members, target final size)
- **Team Background**
  - Previous project experience
  - Home institution (university, company, independent lab)
  - Prior achievements (papers, patents)
- **Motivation for Sal-Meter Project**
  - Why participate?
  - Your perspective on consciousness measurement
- **Contact Information** (Team Leader name, email, phone)

**Example:**

Team Name: Pacific Consciousness Research Collective

Team Size: Currently 5 members, target 7 members

Background:

UC Berkeley Bioengineering Lab (1 Professor, 2 Postdocs)

Google Brain AI Research (2 Machine Learning Scientists)

Prior Achievements: 6 peer-reviewed papers in biosensors and AI, 2 patents filed, 
3 open-source projects with 5K+ GitHub stars

Motivation:

Consciousness represents the frontier of human understanding. We believe that 
measurable, objective consciousness state indicators are achievable and necessary 
for both scientific advancement and AI safety. Our diverse background in 
neurotechnology, signal processing, and machine learning positions us uniquely 
to bridge the gap between theory and implementation.

Contact:

Leader: Dr. Sarah Mitchell (s.mitchell@berkeley.edu, +1-510-642-0123)

#### B) Team Member CVs (1-2 pages each)

Prepare a resume for each team member:

- **Name, Title** (PhD, Senior Engineer, Postdoctoral Researcher, etc.)
- **Education** (degree, institution, field, graduation year)
- **Work Experience** (company/institution, position, duration, key achievements)
- **Core Competencies** (sensors, AI, signal processing, etc.)
- **Key Achievements**
  - Top 3 publications
  - Top 3 projects with brief descriptions
  - Patents/awards/recognitions
- **Contact** (email)

**Example CV Section:**

Dr. James Chen | Senior Biosensor Engineer

Education: PhD in Biomedical Engineering, MIT (2019)

Experience:
- Principal Engineer, Stanford Medical Devices Lab (2019-Present) - Led development of 
  3 FDA-approved biomarker sensors; published 8 peer-reviewed papers
- Postdoctoral Fellow, Harvard Medical School (2019-2020) - Aptamer sensor design

Core Competencies: Aptamer engineering, surface plasmon resonance, electrochemistry, 
biomarker validation

Key Achievements:
- Lead author on "Multiplexed Aptamer Sensors for Real-Time Biomarker Detection" 
  (Nature Biotech, 2023)
- Co-inventor on 2 patents in biosensor miniaturization
- Best Poster Award, IEEE Sensors Conference (2022)

#### C) Technical Proposal (2-3 pages)

Write a technical plan for your project:

**Track A (Full System):**
- Sal-Meter overall architecture (block diagram)
- Key technical innovations (sensor, signal processing, AI, etc.)
- Development schedule (milestones, quarterly)
- Risk factors and mitigation strategies
- CAIS compliance plan
- Expected performance (sensitivity, specificity)

**Track B (Component):**
- Component description
- Technical approach
- Reusable code/modules
- Expected deliverables

**Track C (Open Community):**
- Contribution area (prototype, paper, documentation, etc.)
- Expected outputs
- Timeline

**Example Structure:**

**Executive Summary**

We propose to develop an integrated Sal-Meter prototype combining advanced aptamer 
biosensing with real-time AI-powered consciousness field estimation (CFI). Our 
innovation centers on a novel iodine oxidation-state transduction mechanism coupled 
with Kalman-filtered signal processing.

**Technical Innovation**

Core Innovation: Multiplexed aptamer array with simultaneous optical and electrochemical 
readout for improved VCE/CRI discrimination

Competitive Advantage: 40% faster response time, 25% improved reproducibility vs. 
existing approaches

**Architecture Overview**

[Block diagram showing: Sensor Cartridge → Analog Front-End → DSP Module → 
ML Inference Engine → API/Output]

- Sensor Module: 8-channel aptamer array + iodine redox cycling
- Signal Processing: Multi-stage filtering (Butterworth → Kalman → Feature Extraction)
- AI Pipeline: Ensemble model (LSTM + XGBoost) for VCE/CRI/CFI inference
- Output: JSON REST API + Mobile iOS/Android app

**Development Timeline**

Month 1-2 (Jul-Aug 2026): Sensor prototype, component validation

Month 3-4 (Sep-Oct 2026): Signal processing algorithm optimization, preliminary testing

Month 5-6 (Nov-Dec 2026): AI model development, integration testing

Month 7-9 (Jan-Mar 2027): Performance validation, documentation, open-source release

**CAIS Compliance Strategy**

- VCE Implementation: Post-experience state recovery dynamics via OE/EE/RE encoding
- CRI Measurement: Relational coherence via multi-channel correlation analysis
- CFI Derivation: Conscious field integration via spectral coherence metrics
- Validation: CRO protocol adherence, sensitivity ≥80%, specificity ≥85%

**Risk Management**

| Risk | Probability | Impact | Mitigation |
|------|-------------|--------|-----------|
| Aptamer batch variability | Medium | High | Establish 3+ supplier relationships, implement QC protocols |
| AI model overfitting | Medium | Medium | Cross-validation, transfer learning from synthetic data |
| Hardware integration delays | Low | High | Parallel development tracks, modular architecture |

#### D) Budget Plan (1-2 pages, Track A only)

Track A teams must provide estimated development costs:

**Budget Items:**

- **Personnel Costs** (salary × 9 months)
  - Lead Biosensor Researcher: $15K/month = $135K
  - Hardware/Firmware Engineer: $12K/month = $108K
  - AI/ML Engineer: $12K/month = $108K
  - Supporting Research Engineer: $8K/month = $72K
  - Project Management: $6K/month = $54K
  - **Subtotal: $477K**

- **Equipment & Capital**
  - Sensor fabrication equipment (cleanroom access): $80K
  - Measurement instruments (spectrophotometer, etc.): $50K
  - Computing infrastructure (GPU servers): $40K
  - Testing equipment: $30K
  - **Subtotal: $200K**

- **Materials & Consumables**
  - Aptamers, reagents, chemicals: $60K
  - Biological samples, calibration standards: $40K
  - PCB prototyping, components: $30K
  - **Subtotal: $130K**

- **Operations & Facilities**
  - Lab space rental/access: $120K
  - Software licenses, cloud services: $40K
  - Travel for CRO validation, meetings: $30K
  - Miscellaneous: $20K
  - **Subtotal: $210K**

- **Total Budget: ~$1,017K**

**Funding Sources:**

- Sal-Meter Competition Prize: $300K (if successful)
- UC Berkeley Chancellor's Fund: $300K (committed)
- NSF SBIR Phase I: $150K (pending)
- Team members' institutions R&D support: $150K (committed)
- **Total Secured + Expected: $900K+**

**Note:**
- The $300K prize covers design/validation completion, not full development
- Teams demonstrate financial viability through committed co-funding

#### E) Portfolio (Optional)

You may optionally attach:

- **Key Publications** (3 most recent, PDF format)
- **GitHub Repository Links** (open-source code samples)
- **News Coverage** (any relevant media mentions)
- **Letters of Support** (from established researchers or institutions)

**Example:**

- "Multiplex Real-Time Biosensing with Aptamer Arrays" - Nature Biotech (2023)
- "Consciousness Field Metrics: Novel Computational Approaches" - arXiv preprint
- GitHub: https://github.com/pacific-consciousness-lab/aptamer-sensing

---

### 2-2) Application Checklist

Before submission, verify the following:

**Required:**
- [ ] Team Introduction (1-2 pages)
- [ ] All Team Member CVs (1-2 pages each)
- [ ] Technical Proposal (2-3 pages, with diagrams)
- [ ] Budget Plan (Track A only, 1-2 pages)

**Format:**
- [ ] File Format: PDF preferred (Word acceptable)
- [ ] File Names: English, concise (e.g., Team_PacificConsciousness_Intro.pdf)
- [ ] Total Size: Under 50MB
- [ ] Language: English throughout

**Content Validation:**
- [ ] All 4 mandatory documents read and understood
- [ ] CAIS compliance explicitly stated
- [ ] Team members meet experience criteria (Track A/B)
- [ ] Technical approach is clear and feasible
- [ ] Budget is realistic and justified

---

## Stage 3: Submission (1 day)

### 3-1) Submit via Email

**To:** contact@salpida.foundation

**Subject Line:**

[Track A/B/C] Sal-Meter Open Competition Application - [Team Name]

Examples:
- [Track A] Sal-Meter Open Competition Application - Pacific Consciousness Research Collective
- [Track B] Signal Processing Module - Boston Biotech Engineers
- [Track C] Consciousness Field Theory Documentation - Prof. Emma Rodriguez

**Email Body:**

Dear SICS Judging Committee,

We are submitting an application to the Sal-Meter Open Competition [Track X].

Team Name: Pacific Consciousness Research Collective
Track: A
Contact: Dr. Sarah Mitchell (s.mitchell@berkeley.edu, +1-510-642-0123)
Institution: University of California, Berkeley

Our team has thoroughly reviewed the four canonical documents:

- Sal-Meter Canonical Definition v1.0
- CAIS Compliance Boundary v1.0
- Sal-Meter Open Competition Charter v1.0
- Sal-Meter Negative Definition v1.0

We understand the evaluation criteria and are committed to full CAIS compliance 
in our design and development approach.

Our interdisciplinary team brings complementary expertise in biosensing, signal 
processing, machine learning, and consciousness studies. We believe this 
competition represents a critical opportunity to advance objective consciousness 
measurement at global scale.

Best regards,

Dr. Sarah Mitchell
Team Lead, Pacific Consciousness Research Collective

**Attachments:**

01_Team_Introduction.pdf

02_CV_Sarah_Mitchell.pdf

03_CV_James_Chen.pdf

04_CV_Michael_Torres.pdf

05_CV_Lisa_Wong.pdf

06_Technical_Proposal.pdf

07_Budget_Plan.pdf

08_Portfolio_Publications.pdf (optional)

### 3-2) Confirmation Process

- Confirmation email received within **2-3 business days** of submission
- Review completion notification within **1-2 weeks**
- If additional information is needed, SICS will contact your team lead directly

---

## Application Timeline and Deadlines

| Phase | Period | Activity |
|-------|--------|----------|
| Preparation (Phase 0) | Jan-Mar 2026 | Document finalization, system setup |
| **Application Period Opens** | **April 1, 2026** | **Application submissions begin** |
| Selection (Phase 1) | Apr-Jun 2026 | Team evaluation and selection |
| Development (Phase 2) | Jul 2026 - Mar 2027 | Prototype development sprint |
| Validation (Phase 3) | Apr-Sep 2027 | Independent CRO validation |

**For Latest Updates:**
- Visit: https://github.com/salpida-foundation/sal-meter-competition
- Email: contact@salpida.foundation

---

## FAQ: Application Questions

### Q1. When will I receive results from my application?

A. Typical timeline:
- Initial review: 1-2 weeks
- Technical evaluation: 1 additional week
- Interview (if needed): 3-5 days
- Final decision: Total 2-3 weeks from submission

Results are communicated via email directly to the team leader.

---

### Q2. Can we apply for multiple tracks at the same time?

A. Yes. For example:
- Primary application: Track A (full system)
- Supporting contribution: Track B (signal processing component)

This is permitted provided there is no conflict of interest or resource duplication.

---

### Q3. Can we update and resubmit our application before the deadline?

A. Yes, before the submission deadline:
- Send revised materials with subject: "[TRACK X] Sal-Meter Application [UPDATE] - [Team Name]"
- Include note: "This submission supersedes previous version dated [DATE]"
- Only your final submission will be evaluated

---

### Q4. What if we need more than 4 weeks to prepare?

A. Applications can be submitted anytime during the open window (Apr-Jun 2026). 
Early submissions (April) receive thorough review; late submissions (June) are 
reviewed more quickly. There is no advantage to early submission; completeness 
matters most.

---

### Q5. Can international teams apply?

A. Yes, absolutely. International teams are encouraged. Requirements:
- At least one team member with strong English communication skills
- Coordination across time zones for any interviews
- No citizenship or residency restrictions

---

## Reference Materials

- [Technical Details: How the Sal-Meter Works](./01_technical_details.md)
- [Development Roadmap: 4-Phase Detailed Plan](./02_phase_roadmap.md)
- [Team Composition Guide](./03_team_composition.md)
- [Frequently Asked Questions](./04_faq_extended_en.md)

---

**License:** CC BY-SA 4.0

**Last Updated:** February 3, 2026
