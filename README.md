# MedLog Pro 🩺
**Professional Clinical Logbook & Portfolio Management System**

MedLog Pro is a comprehensive Android application designed for healthcare professionals, surgical trainees, and medical students to document their clinical journey, manage surgical logs, and generate professional portfolios for accreditation and training requirements.

---

## 🚀 Key Features

### 📋 Clinical Logbook
- **Comprehensive Case Entry:** Document diagnoses, procedures, anesthesia details, and outcomes with a streamlined UI.
- **Media Management:** Securely attach clinical photographs, investigation reports, and videos to specific cases (with built-in patient consent reminders).
- **Document Scanning:** Integrated ML-powered document scanner to digitize paper records instantly.

### 🎓 Professional Portfolio
- **Automated Generation:** Generate professional PDF portfolios and CSV exports of your clinical activity.
- **Supervisor Workflow:** Nominate supervisors to review and digitally approve your logged cases.
- **Analytics:** Visualize your clinical exposure with integrated charts (powered by Vico).

### 🛡️ Security & Privacy
- **Biometric Security:** Secure your sensitive clinical data with Fingerprint or Face ID.
- **Cloud Sync:** Encrypted data synchronization across devices using Firebase.
- **Privacy-First:** Built-in EULA and Privacy Policy ensuring compliance with institutional standards.

### 💎 Premium Tiers
- **Free:** Essential logging for students.
- **Standard & Pro:** Extended limits for media uploads, unlimited case entries, and advanced export features.

---

## 🛠️ Technical Stack
- **Language:** 100% Kotlin
- **UI:** Jetpack Compose (Modern Declarative UI)
- **Database:** Room (Local Persistence) & Firestore (Cloud Sync)
- **Authentication:** Firebase Auth (Email/Google Sign-In)
- **Storage:** Firebase Storage (Media hosting)
- **Architecture:** MVVM (Model-View-ViewModel)
- **Dependency Management:** Version Catalog (libs.versions.toml)

---

## 📦 Installation & Setup
1. Clone the repository.
2. Add your `google-services.json` to the `app/` directory.
3. Build using Android Studio (Ladybug or newer).
4. Ensure you have a valid Firebase project with Firestore and Storage enabled.

---

## ⚖️ Legal & Privacy
This application handles Sensitive Personal Health Information (PHI). Users are responsible for obtaining informed patient consent and adhering to their institution's privacy policies.

**Developer:** Jamaal Butt
**Contact:** jamaalbutt@hotmail.com
