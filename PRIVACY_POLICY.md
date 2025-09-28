# Privacy Policy · YRA (Your Workout Assistant)

> Last updated: September 28, 2025

This Privacy Policy explains how the **YRA – Your Workout Assistant** application ("YRA", "we") collects, uses, stores, and protects the personal data of its users ("you"). YRA is a personalized workout application built with Flutter, featuring artificial intelligence, voice control, and Firebase integration.

By using YRA, you agree to the practices described in this Policy. If you do not agree, please discontinue use of the application and request the deletion of your data.

## Quick overview

- We use your Google account for secure authentication.
- Your workouts, progress, and preferences are stored in Firebase Firestore with access restricted to your user ID.
- Voice commands are processed locally; only temporary transcriptions are sent to speech services.
- We rely on the Google Gemini API to generate personalized workouts based on your profile and preferences.
- You can request access to, correction of, or deletion of your data at any time.

## 1. Data controller

The data controller for the personal data processed by YRA is the development team responsible for the YRA – Your Workout Assistant project. For privacy-related inquiries, please use the project’s official support channels or open an issue in the public GitHub repository at `https://github.com/yurisantos-y/yra-web/`.

## 2. Personal data collected

We collect only the information needed to deliver the best workout experience. The data falls into the categories below:

### 2.1 Information you provide

- **Profile and identity**: name, email address, and profile picture supplied by Google Sign-In.
- **Workout preferences**: available time, goals, fitness level, and equipment availability.
- **Configuration data**: preferred language, granted permissions (microphone, notifications), and app personalization options.

### 2.2 Data generated during usage

- **Workout history**: workouts created, workouts completed, duration, sets, reps, weights, and user feedback.
- **Progress and analytics**: consolidated metrics (training volume, frequency, exercise performance), completed goals, and unlocked achievements.
- **Session events**: workout status (active, paused, completed), rest adjustments, and triggered commands.

### 2.3 Voice and communication data

- **Voice commands**: audio snippets are processed locally and converted to text via speech recognition libraries. Only temporary transcriptions are kept to interpret commands.
- **Text-to-Speech (TTS)**: the app generates spoken guidance based on workout data. Playback audio is not stored.

### 2.4 Technical and device data

- Device and operating system identifiers.
- Error logs, performance events, and stability metrics.
- Notification tokens (when you opt in to receive reminders).

### 2.5 Third-party integrations

- **Firebase**: authentication (Firebase Auth), database (Cloud Firestore), and local notifications.
- **Google Sign-In**: OAuth 2.0 authentication and account synchronization.
- **Google Gemini**: personalized workout generation based on your profile details and preferences.

## 3. Purposes and legal bases

We process personal data in accordance with the Brazilian General Data Protection Law (LGPD) and equivalent international regulations (such as GDPR). The main purposes and legal bases are:

| Purpose | Data used | Legal basis |
| --- | --- | --- |
| Authenticate and maintain your account | Name, email, authentication token | Performance of a contract |
| Configure and personalize workouts | Preferences, workout history, profile data | Performance of a contract |
| Generate AI-powered workouts | Preferences, time constraints, fitness level, history | Consent and performance of a contract |
| Sync data across devices | Workout history, progress | Performance of a contract |
| Improve the app and fix issues | Logs, usage metrics, feedback | Legitimate interest |
| Send notifications and reminders | Push token, notification preferences | Consent |
| Comply with legal obligations | Account data, access records | Legal obligation |

## 4. Data sharing

We only share your data when necessary:

- **Technology providers**: Firebase, Google Sign-In, speech services, and Google Gemini, all bound by confidentiality and security commitments.
- **Payment processors**: the app currently does not process payments; if that changes, this Policy will be updated.
- **Legal compliance**: when required by law, court order, or requests from competent authorities.
- **International transfers**: data may be processed on servers located outside your country (for example, in the United States) under standard contractual clauses or equivalent safeguards.

We do not sell or rent your personal data.

## 5. Storage, security, and retention

- All data is stored in **Google Cloud (Firebase)** with encryption at rest and in transit.
- Firestore security rules restrict document access to the authenticated user who owns the data.
- Sensitive tokens (such as the Gemini API key) are kept in environment variables or secure services and are never embedded in public builds.
- We retain your data while your account remains active or as long as needed to provide the service. Data may be anonymized for statistical purposes.
- We perform periodic security reviews, access control checks, and log audits to detect misuse.

## 6. Your rights

You have the rights granted by LGPD, GDPR, and other applicable regulations:

- Confirm whether we process your data and obtain access to it.
- Correct incomplete, inaccurate, or outdated data.
- Request anonymization, blocking, or deletion of unnecessary data.
- Port your data to another service provider, when technically feasible.
- Withdraw consent and be informed of the consequences.
- Object to processing based on legitimate interest.
- Request deletion of personal data processed with your consent.

To exercise your rights, use the channels listed in Section 1. We will respond within 30 calendar days unless another legal deadline applies.

## 7. Device permissions

YRA depends on certain permissions to operate correctly:

- **Microphone**: required to recognize voice commands. Audio is processed solely to interpret commands.
- **Notifications**: used for workout reminders and important updates.
- **Local storage**: used for temporary caches, preferences, and limited offline functionality.

You may revoke permissions in your device settings at any time. Doing so may limit certain features.

## 8. Cookies and tracking technologies

YRA does not use cookies within the mobile application. Associated web services (such as information pages or admin panels) may use strictly necessary cookies for authentication or analytics. You will be notified separately in those scenarios.

## 9. Children and adolescents

YRA is not designed for children under 13 years of age. Users aged 13 to 18 should only use the application with consent and supervision from a legal guardian. If we discover unauthorized data from a minor, we will take steps to delete it.

## 10. International data transfers

Because we use Google services (Firebase, Gemini, authentication), your data may be processed in data centers located outside your country of residence. We adopt standard contractual clauses and routinely assess the safeguards provided by these vendors.

## 11. Changes to this Policy

We may update this Policy periodically to reflect changes in the application or applicable laws. We will publish the latest version in the project repository or official communication channels, indicating the date of the most recent revision. Significant changes may be communicated through in-app notifications or email, when available.

## 12. Contact

If you have questions, comments, or requests about privacy, please reach out through the in-app support channels or open an issue in the public repository at `https://github.com/yurisantos-y/yra-web/`.

---

**YRA – Your Workout Assistant**
Transform your workouts with artificial intelligence while staying in control of your personal data.
