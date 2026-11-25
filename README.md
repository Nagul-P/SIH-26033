Smart India Hackathon Workshope,
accDate: 25/11/2026
Reference Number: 26001811
Name: P.Nagul
Problem Title
SIH [ID – replace with official number]: Limited access to timely primary healthcare and specialist consultation in rural and remote areas.
Problem Creator's Organization
Ministry of Health & Family Welfare (replace if your chosen statement differs)
Theme
Medical Devices / HealthTech & Rural Development
Problem Description
aExpected Solution: Create a digital health platform that:
• Connects rural patients with doctors and specialists through low-bandwidth telemedicine.
• Provides AI-assisted symptom triage and early risk detection.
• Links Primary Health Centres (PHCs), ASHA workers, pharmacies and diagnostic labs in one workflow.
Benefits:
• Faster diagnosis and treatment for rural patients.
• Reduced travel cost and loss of daily wages.
• Lower load on district hospitals through proper referral.
Proposed Solution
SwasthSetu: An AI-Powered Rural Healthcare Bridge
SwasthSetu is a mobile-first digital health ecosystem that brings doctor consultation, triage and follow-up to villages. ASHA workers and PHC staff register patients, capture symptoms and vitals, and the platform routes each case to the right level of care: self-care advice, a PHC doctor, a remote specialist, or an emergency referral.
How it addresses the problem:
• AI Symptom Triage: A guided questionnaire plus a risk-scoring model classifies cases as low, medium or high priority, so doctors see urgent cases first.
• Low-Bandwidth Teleconsultation: Audio-first video calls that fall back to voice and SMS when the network is weak, with consultation notes synced later.
• Integrated Referral & Medicine Tracking: Digital prescriptions are sent to the nearest partner pharmacy, and the system tracks medicine stock at PHCs to avoid shortages.
• Follow-up Engine: Automated reminders for medicines, vaccinations and repeat visits, especially for chronic conditions like diabetes and hypertension.
Innovation and Uniqueness:
• Multilingual Voice Assistant: Patients and ASHA workers describe symptoms by voice in their regional language; the assistant converts them to structured medical input.
• Offline-First Design: The app stores records locally and syncs automatically when connectivity returns, which suits remote villages.
• Outbreak Heatmaps: Aggregated, anonymised symptom data helps district officers spot disease clusters early.
Technical Approach
Technologies to be used:
• Frontend (Mobile & Web): React Native for the patient and ASHA worker app (Android first, with offline storage), React.js for the doctor and PHC admin dashboard.
• Backend & APIs: Node.js with Express, REST and WebSocket for real-time consultation status.
• Database: PostgreSQL for patient records and appointments, Redis for queues and session caching, SQLite on device for offline data.
• AI/ML & Analytics:
    ◦ Triage Model: Python (scikit-learn / XGBoost) trained on public symptom-disease datasets, with rule-based safety overrides for red-flag symptoms.
    ◦ Speech & Language: Speech-to-text and translation APIs for regional languages.
    ◦ Outbreak Analytics: Time-series anomaly detection on aggregated case data.
• Teleconsultation: WebRTC with adaptive bitrate and audio-only fallback.
• Cloud & Infrastructure: AWS (EC2, S3 for reports), Firebase (push notifications), Twilio (SMS/IVR).
• Security & Interoperability: Encrypted data storage, role-based access, consent management, and ABDM (Ayushman Bharat Digital Mission) compatible health IDs and records.
Feasibility and Viability
Feasibility of the Idea:
• Existing Infrastructure: PHCs, Health & Wellness Centres and a large ASHA network already exist and can act as ground-level access points.
• Digital Public Infrastructure: ABDM health IDs, UPI and widespread smartphones make digital records and payments practical.
• Proven Model: Government telemedicine services like eSanjeevani show strong demand, and this solution adds triage, offline support and follow-up.
Potential Challenges and Risks:
• Connectivity and Digital Literacy: Weak networks and limited comfort with apps in rural areas.
• Data Privacy and Trust: Health data is sensitive and patients may worry about misuse.
• AI Safety: Incorrect triage could delay care, so the AI must not replace a doctor.
• Doctor Availability: Specialists may be overloaded.
Strategies for Overcoming Challenges:
• ASHA-Assisted Model: Trained community workers operate the app on behalf of patients and build trust.
• Offline-First and SMS/IVR Fallback: Core features keep working without stable internet.
• Human-in-the-Loop AI: The AI only suggests priority; a qualified doctor makes every final decision, and emergency keywords trigger immediate referral.
• Privacy by Design: Explicit consent, encryption, anonymised analytics and compliance with Indian data protection rules.
• Doctor Pooling: Partner with medical colleges, retired doctors and private clinics to share teleconsultation load.
Impact and Benefits
Potential Impact on the Target Audience:
• Patients: Expected to cut travel time and cost significantly and enable earlier diagnosis, especially for chronic and maternal health conditions.
• Health Workers: Less paperwork, clearer referral guidance and better decision support.
• Government and PHCs: Better visibility into disease trends and medicine stock for planning.
Benefits of the Solution:
• Economic: Saves wages and travel costs for rural families and reduces avoidable hospital admissions.
• Social: Improves equity in healthcare access, supports women and elderly patients, and strengthens the role of ASHA workers.
• Environmental: Fewer long-distance trips and a paperless record system reduce travel emissions and paper use.
Research and References
• Ayushman Bharat Digital Mission (ABDM): Framework for health IDs and interoperable digital health records.
• eSanjeevani (Ministry of Health & Family Welfare): Existing national telemedicine service, studied to identify gaps such as triage, offline support and follow-up.
• National Health Mission (NHM) and ASHA programme: Community health worker structure used as the ground-level delivery channel.
• Reference Datasets for AI: Public symptom-disease datasets (for example from Kaggle) and open health data from data.gov.in for prototype training and testing.
Note: Replace the problem ID, organization and theme with the exact details from the official SIH problem statement you choosordingly.
