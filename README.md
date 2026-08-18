# Awesome-Medical-Scribe-AI

## Top Medical Scribe AI Platforms Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Ambient Clinical Documentation, Real-Time Transcription, SOAP/Progress Note Generation, EHR Integration & Physician Workflow Automation*
**Last updated: August 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Medical Scribe AI** (also called ambient clinical intelligence or AI scribes). These systems listen to clinician–patient conversations, transcribe the encounter, and automatically generate structured clinical notes (SOAP, progress notes, etc.) that can be reviewed and pushed into the EHR.

**Examples** include Abridge, Nabla, Suki, DeepScribe, Freed AI, Microsoft Dragon Copilot (Nuance DAX), Augmedix, Notable, Nuance DAX, and Heidi Health (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for local-first or self-hosted ambient scribes, note generation pipelines, and OpenEMR-integrated tools — ideal for privacy-conscious clinics, researchers, health systems, and developers seeking full data control and lower cost.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial | Company Size |
|---|---|---|---|---|
| [Microsoft Dragon Copilot / Nuance DAX](https://www.microsoft.com/) | Enterprise ambient documentation solution (formerly Nuance DAX) with deep Epic and multi-EHR integration, backed by Microsoft. | $369–$830/provider/month (enterprise, custom quotes) | No free tier; proof-of-concept available on request | ~$19.7B (acquired by Microsoft in 2021) |
| [Abridge](https://www.abridge.com/) | Enterprise ambient AI documentation platform with strong evidence linking, deep EHR (especially Epic) integration, and large-scale health-system deployments. | ~$208/provider/month (enterprise contracts ~$2,500/yr) | No free tier; enterprise pilot available on request | $5.3B valuation (Series E, Jun 2025); ~$800M+ total funding |
| [Suki](https://www.suki.ai/) | Voice-first clinical assistant that combines ambient documentation with natural-language commands for EHR navigation and workflow automation. | $299/user/month (Suki Compose); $399/user/month (Suki Assistant) | Free tier: limited to 10 Pro Actions/month | $500M valuation (Series D, Oct 2024); $168M total funding |
| [Notable](https://www.notablehealth.com/) | Healthcare AI platform that includes ambient documentation and broader automation of clinical and administrative workflows. | Enterprise-only custom pricing (contact sales) | No public free tier; demo available on request | $600M valuation; $116M+ total funding |
| [Heidi Health](https://www.heidihealth.com/) | Flexible AI scribe with extensive template support, multi-language capabilities, and options suitable for individual clinicians and groups. | $40/user/month (Evidence Plus); $110/user/month (Clinician) | Free tier: unlimited basic consults + 10 Pro Actions/month | $465M valuation (Series B, Oct 2025); $96.6M total funding |
| [Nabla](https://www.nabla.com/) | Modern ambient scribe focused on speed, usability, and high-quality clinical notes with strong mobile and clinician-friendly workflows. | $119/provider/month (Pro plan) | Free tier: up to 30 encounters/month (unlimited for residents/interns) | ~$180M valuation (Series C, Jun 2025); $120M total funding |
| [DeepScribe](https://www.deepscribe.ai/) | Specialty-oriented ambient scribe strong in complex documentation (oncology, cardiology, etc.) with coding suggestions and longitudinal context. | ~$350–$750/provider/month (enterprise, custom quotes) | 20 free sessions for new users (trial) | ~$135M valuation (Series B); $60M total funding |
| [Augmedix](https://www.augmedix.com/) | Ambient medical documentation platform combining AI with human review options for high-accuracy clinical notes. | ~$1,200+/provider/month (enterprise, custom quotes) | No free tier; demo available on request | Acquired by Commure for $139M (2024); ~$52M TTM revenue |
| [Freed AI](https://www.getfreed.ai/) | Simple, clinician-friendly AI scribe popular with solo and small practices; emphasizes ease of use and transparent pricing. | $39/month (Starter, 40 notes); $79/month (Core, unlimited) | 7-day free trial (unlimited notes, no credit card) | $34M total funding (Series A, Mar 2025); ~$19M ARR |
| [Other notable platforms](https://) | Additional commercial offerings continue to emerge, often differentiating on specialty depth, pricing model, or specific EHR partnerships. | Varies | Varies | Varies |

## Open-Source GitHub Projects
- **[Phlox](https://github.com/bloodworks-io/phlox)**  
  Open-source, local-first AI medical agent and ambient scribe with patient management, adaptive note generation, and fully private on-device operation.

- **[scribeHC](https://github.com/trevorpfiz/scribeHC)**  
  Open-source AI ambient scribe app for healthcare that records encounters and generates SOAP notes from transcripts.

- **[Open Medical Scribe](https://github.com/BirgerMoell/open-medical-scribe)**  
  Modular, privacy-first open-source medical scribe supporting pluggable transcription (Whisper, etc.) and LLM providers, including fully local operation.

- **[Berta AI Scribe](https://github.com/phairlab/berta-ai-scribe)**  
  Open-source modular platform for AI-enabled clinical documentation, successfully deployed at provincial scale with significant cost reduction versus commercial tools.

- **[OpenScribe](https://github.com/sammargolis/OpenScribe)**  
  Open-source AI scribe that records patient encounters and generates structured clinical notes with local-first storage and no vendor lock-in.

- **[OpenEMR-AI](https://github.com/iupui-soic/openemr-ai)**  
  Artificial intelligence tooling for OpenEMR focused on ambient listening, note summarization, and automated coding with FHIR write-back.

- **[Caduceus / open-healthcare-ai-scribe](https://github.com/lukehollis/open-healthcare-ai-scribe)**  
  Open-source healthcare AI scribe for real-time medical documentation and clinical templates across text and voice.

- **[AI Ambient Scribe projects (FHIR/EHR-integrated)](https://github.com/)**  
  Community efforts that transcribe encounters, structure notes with LLMs, and write results back to EHRs via FHIR while emphasizing GDPR/HIPAA considerations.

- **[Specialty and bilingual note generators](https://github.com/)**  
  Open projects focused on structured outputs for specific specialties or bilingual (e.g., English/Spanish) clinical documentation.

- **[Whisper + local LLM pipelines](https://github.com/)**  
  Reusable open-source stacks combining on-device or self-hosted speech-to-text with local or private LLMs for note generation.

### Additional Strong Open-Source Options
- Faster-Whisper, whisper.cpp, and other high-performance open ASR engines fine-tuned or prompted for clinical audio.
- Open medical LLMs and RAG pipelines over clinical guidelines or local knowledge bases.
- FHIR clients and SMART-on-FHIR apps that enable secure note write-back into open or commercial EHRs.
- Template engines and prompt libraries specifically designed for SOAP, H&P, and progress notes.
- Desktop and mobile recording front-ends that keep audio processing under user control.

**Frameworks for building custom systems**: Capture audio locally or via a controlled stream, transcribe with **Whisper**-family models (on-device or private cloud), structure the transcript into clinical notes using a local or private LLM (optionally with RAG over specialty templates), present a review UI, and write approved notes back via FHIR or direct EHR integration. Projects such as **Phlox**, **Open Medical Scribe**, and **Berta** provide ready starting points. Prioritize audit logging, consent capture, and data minimization for compliance.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Medical documentation is a regulated, high-stakes activity. Ambient AI scribes process protected health information (PHI). Open-source tools can offer excellent privacy and cost advantages but require rigorous validation, clinical oversight, security hardening, and compliance with HIPAA, GDPR, or equivalent regulations before any clinical use.
- Generated notes must always be reviewed and approved by a licensed clinician. These systems assist documentation; they do not replace clinical judgment.

---
**Made for clinicians, health-system IT teams, and open-source health-tech developers.**
Let's make high-quality clinical documentation more accessible, private, and clinician-controlled.
