# Privacy Policy for ISS Cockpit

**Last Updated:** August 22, 2026

This Privacy Policy explains how **ISS Cockpit**, published under package name `com.sealt.astre`, collects, uses, and protects your information when you use our mobile application.

We respect your privacy and are committed to protecting it through compliance with applicable data protection laws, including the European Union General Data Protection Regulation (**GDPR**), the US Children's Online Privacy Protection Act (**COPPA**), and the California Consumer Privacy Act as amended by the California Privacy Rights Act (**CCPA/CPRA**).

---

## 1. Summary of Core Privacy Principles

- **No User Accounts:** You do not need to create an account, register, or provide personal details (name, email, phone number) to use **ISS Cockpit**.
- **No Developer Backend Server:** We do not operate remote servers or user databases. All application logic, orbital calculations, and gamification data run directly on your device.
- **On-Device Location Processing:** Location access is used strictly on your device to calculate International Space Station (ISS) flyovers. Your location is **never** transmitted to us or any third party.
- **Local Storage:** All app preferences, settings, offline cached data, and gamification progress (streaks, badges, ranks) are stored locally on your physical device.
- **Usage Analytics:** The Application integrates Google Firebase to collect aggregate technical usage statistics and crash reports so we can measure stability and improve the experience.

---

## 2. Information We Process and How It Is Used

### A. Geolocation Data (On-Device Only)
- **Permissions:** The Application requests access to your device's location.
- **Purpose:** Location coordinates are used solely to compute visible flyovers (ISS passes) of the International Space Station relative to your current location using mathematical orbital calculations.
- **Storage & Transmission:** Geolocation data is processed in real time in volatile device memory (RAM) and is **never** transmitted to remote servers, stored in databases, or shared with third parties.
- **User Control:** Location permission is optional. If denied or unavailable, the Application defaults to standard reference coordinates (Paris) without affecting basic dashboard functionality.

### B. Local Device Storage
- **Data Stored:** App configuration, localized user preferences, API response cache (e.g. cached TLE telemetry), launch event reminders, login streaks, completed space missions, badges, and user rank status.
- **Retention:** Stored locally on your device until you clear the Application's storage data via operating system settings or uninstall the Application.

### C. Local Notifications
- **Purpose:** The Application uses local device notifications to issue alerts for upcoming rocket launches and ISS flyover passes.
- **Privacy:** Notifications are scheduled and handled entirely on-device. No push tokens, user identifiers, or device profiles are created or sent to external notification servers.

### D. Usage Analytics Data
- **Data Processed:** The Application sends limited technical information to Google Firebase, such as an anonymous application instance identifier, device and operating system characteristics, IP address, and aggregated usage and stability data.
- **Purpose:** Used solely to measure application performance and stability, understand general usage patterns, detect crashes, and guide future improvements.
- **No Personal Profiles:** This data is technical and aggregate in nature. It is never combined with your identity or precise location, and we do not create user profiles from it.

---

## 3. Third-Party Services and SDKs

To provide live space data, video streams, monetize the Application, and understand how it performs, we integrate third-party services. These services may collect technical information directly from your device as outlined in their respective privacy policies:

### A. Google AdMob (Advertising)
- **Purpose:** Displays banner advertisements and app-open ads.
- **Data Collected by Google:** Mobile advertising identifiers (such as Android Advertising ID / AAID or Apple IDFA), IP address, device hardware specs, crash logs, and ad interaction data.
- **Opt-Out & Ad Controls:** You can limit ad tracking or reset your advertising identifier in your device settings:
  - **Android:** *Settings → Google → Ads → Reset Advertising ID or Delete Advertising ID*.
  - **iOS:** *Settings → Privacy & Security → Tracking → Disable "Allow Apps to Request to Track"*.
- **Privacy Policy:** For details on how Google processes ad data, visit [Google Privacy & Terms](https://policies.google.com/technologies/ads).

### B. YouTube Live Stream (Embedded Video)
- **Purpose:** Streams live cameras from the International Space Station via an embedded YouTube player.
- **Data Collected by Google/YouTube:** Interacting with the embedded player may allow YouTube/Google to record your IP address, device details, and place web cookies/storage markers in accordance with [Google Privacy Policy](https://policies.google.com/privacy).

### C. Open Space Data APIs
- **Purpose:** Fetches real-time space launch schedules, space weather (solar flares, Kp index), asteroid telemetry, and astronaut counts.
- **Privacy:** HTTP requests originate directly from your device to these public API providers, exposing standard network telemetry (such as your IP address) to their web server infrastructure.

### D. Firebase Analytics & Crashlytics (Google)
- **Purpose:** Measures aggregate application usage and automatically collects crash reports to maintain stability and reliability.
- **Data Collected by Google:** An anonymous app instance identifier, device model and manufacturer, operating system version, IP address, technical usage events, and crash diagnostics (such as stack traces) when the Application unexpectedly stops.
- **Privacy Policy:** For details on how Google processes Firebase data, visit [Google Privacy Policy](https://policies.google.com/privacy) and [Firebase Privacy Information](https://firebase.google.com/support/privacy).

---

## 4. EU/EEA & UK Privacy Rights (GDPR)

If you reside in the European Economic Area (EEA), European Union (EU), or United Kingdom (UK), you have specific rights under the General Data Protection Regulation (GDPR):

### A. Legal Bases for Processing
- **Legitimate Interest:** Operating basic dashboard features, orbital math, caching public API responses, and processing aggregate technical usage statistics and crash reports through Firebase to ensure the Application remains stable and functional. This analytics data is not used by us for advertising profiling.
- **Consent:** Requesting location access and serving personalized advertisements via Google AdMob (where required by law).

### B. Your GDPR Rights
- **Right to Access & Data Portability:** Because all user preferences and gamification data reside on your local device, you can access your data directly inside the Application.
- **Right to Erasure ("Right to be Forgotten"):** You can erase all locally stored data at any time by clearing the Application data in your device settings or uninstalling the Application.
- **Right to Object / Restrict Processing:** You can revoke location permissions or opt out of personalized advertising at any time through your device settings.
- **Right to Lodge a Complaint:** You have the right to submit a complaint to your local Supervisory Authority (e.g. CNIL in France, ICO in the UK).

---

## 5. California Consumer Privacy Notice (CCPA / CPRA)

This section applies solely to California residents pursuant to the California Consumer Privacy Act (**CCPA**) as amended by the California Privacy Rights Act (**CPRA**).

### A. Categories of Personal Information Collected
In the preceding 12 months, the following categories of personal information may have been collected or processed via third-party SDKs:
- **Identifiers:** Device IP address, advertising identifiers (AAID / IDFA), and anonymous application instance identifiers generated by Firebase.
- **Geolocation Data:** Coarse/fine location coordinates (processed 100% locally on-device).
- **Internet / Network Activity:** Interactions with AdMob advertisements and embedded YouTube player, plus aggregate technical usage information processed by Firebase.

### B. Disclosure & "Sale" or "Sharing" of Personal Information
- We do **not** sell your personal information for monetary payment.
- However, the use of Google AdMob to deliver interest-based advertisements may be classified as a **"Sale"** or **"Sharing"** of personal information (advertising IDs) under California law.
- **Right to Opt-Out of Sale/Sharing:** You can exercise your right to opt out of interest-based ad tracking by adjusting your device privacy and advertising settings as described in Section 3.A.

### C. California Consumer Rights
California residents have the right to:
1. **Know** what personal information is collected, used, or disclosed.
2. **Delete** personal information collected from them.
3. **Opt-Out** of the sale or sharing of personal information for cross-context behavioral advertising.
4. **Non-Discrimination** for exercising any CCPA/CPRA privacy rights.

---

## 6. Children's Privacy (COPPA Notice)

- **General Audience Service:** ISS Cockpit is an educational space information tool designed for a general audience aged **13 and older**.
- **No Intentional Collection from Children:** We do not knowingly solicit, collect, or maintain personal information from children under the age of 13 in compliance with the U.S. Children's Online Privacy Protection Act (**COPPA**).
- **AdMob Child-Directed Settings:** We configure advertising requests in compliance with applicable child protection guidelines.
- **Parental Inquiries:** If a parent or guardian becomes aware that a child under 13 has provided personal data or device identifiers, please contact us at `sealt.support@gmail.com`, and we will assist in resolving the matter.

---

## 7. Data Retention and Security

- **Storage Location:** All user-generated settings, streaks, and progress remain strictly stored on your local device hardware.
- **Data Security:** We do not operate our own servers or databases. Locally stored personal data never leaves your device; only the limited technical data described in Sections 2.D and 3 is transmitted to third-party providers, mitigating remote data breach risks.
- **Deletion:** Uninstalling the Application permanently deletes all locally stored data.

---

## 8. International Data Transfers

ISS Cockpit operates globally. While the Application itself does not transfer personal data to remote servers, third-party providers (such as Google AdMob, Google Firebase, and open API services) may process network activity and device identifiers on servers located in the United States or other countries. These transfers are governed by the privacy policies of the respective providers.

---

## 9. Changes to This Privacy Policy

We may update this Privacy Policy from time to time to reflect changes in legal requirements, app features, or data practices. Any updates will be posted in this file and published within the Application repository or store listing, accompanied by a revised **"Last Updated"** date.

---

## 10. Contact Us

If you have any questions, concerns, or requests regarding this Privacy Policy or your privacy rights, please contact us:

- **App Name:** ISS Cockpit
- **Package Name:** `com.sealt.astre`
- **Contact Email:** `sealt.support@gmail.com`
