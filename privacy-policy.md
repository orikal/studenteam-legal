# Privacy Policy — Studenton

**Effective Date:** March 31, 2026  
**Last Updated:** March 31, 2026

This Privacy Policy describes how **Studenton** ("we", "our", or "us") collects, uses, stores, and protects personal information about users ("you") of the Studenton mobile application ("App").

By using the App you agree to the practices described in this policy. If you do not agree, please discontinue use of the App.

This Privacy Policy should be read together with our **[Terms of Service](terms-of-service.md)**, which set rules for using the App (including forums and the private tutor marketplace).

---

## 1. Who We Are

Studenton is a student-organizer and academic community application developed and operated by **Ori**.

- **Privacy contact:** [privacy@studenton.app](mailto:privacy@studenton.app)  
- **General contact:** [contact@studenton.app](mailto:contact@studenton.app)

The App is distributed on **iOS** (Apple App Store) and may also be available on **Android**. This policy applies regardless of platform.

---

## 2. Information We Collect

### 2.1 Account & authentication

When you create an account or sign in, we process:

| Data | Purpose |
|------|---------|
| **Email address** | Account identity, sign-in, and essential service messages (e.g. verification). |
| **Authentication credentials** | Password-based sign-in is handled by **Supabase Auth** (passwords are hashed; we do not store plaintext passwords). |
| **Session tokens** | Stored on your device using secure storage (**expo-secure-store**, backed by the device keychain / secure hardware where available) to keep you signed in. |
| **OAuth profile data** | If you use **Sign in with Apple** or **Google**, we receive identifiers and profile elements that those providers share with us (for example name, email as permitted by the provider, and profile image URL where applicable), in line with each provider’s settings and policies. |

We do **not** receive your Apple or Google account password.

### 2.2 Profile & account settings (stored with your account)

The following may be stored in our database (Supabase) and linked to your user account:

- **Display name** — shown in the App and, when you use community features, may be visible to other users (for example next to forum posts).
- **Profile photo** — if you upload an image or use a provider profile picture we sync, the image URL or file may be stored in our systems (including file storage) and can be visible to other users where the App shows your profile in community areas.
- **Institution** — optional link to an academic institution from our reference list.
- **Account role** — for example **student** or **private tutor**, used to label content and enable tutor-related features.
- **Locale and timezone** — used to present the App appropriately (defaults may apply if not set).

### 2.3 Optional details stored only on your device

Certain extended profile fields (for example full name, age, city, degree details, study year, semester preferences, and tutor subject/course selections used in onboarding flows) are stored **locally on your device** (for example via **AsyncStorage**) and are **not** uploaded to our servers as part of that local profile store. If you separately choose to publish information in the forum or tutor listings, that published content is stored on our servers as described below.

### 2.4 Academic & organizer data (your account, cloud-synced)

Data you enter into organizer features is stored in your account on our backend so it can sync across devices. This includes, depending on what you use:

- **Courses** — name, code, credits, year, semester, grades, labels, etc.
- **Exams** — titles, dates, times, locations, notes, links to courses.
- **Assignments** — titles, due dates, status, notes, course links.
- **Schedule** — slots, times, locations, notes.
- **Grades** — entries, weights, scores, dates.
- **Study sessions** — timing, duration, mode, linked courses.
- **Gamification / stats** — for example streaks, points, levels associated with your account.
- **Practice / questions** — content you create for self-study (prompts, answers, difficulty, course links), where you use those features.

### 2.5 Community forum & user-generated content

If you use the **forum** or related features, we store content you submit on our servers, including:

- **Posts and replies** — text, images, and file attachments you upload.
- **Metadata** — subject/course association, post type, timestamps, moderation status, and similar fields required to operate the forum.
- **Tutor marketplace listings** — posts intended to connect students and private tutors (for example offers or requests); may include descriptive text, pricing indications you type, teaching mode, and attachments you choose to upload.

Forum content you publish may be **visible to other users** of the App according to how the feature is designed (for example by subject or listing type). Your **display name** and **profile image** (if any) may appear alongside your content.

We process forum submissions through **Supabase Edge Functions** and related server-side logic for validation, safety, and abuse prevention.

### 2.6 Private tutor profile documents

If you register as a **private tutor** and upload optional documents (for example a CV or certification), those files may be stored in **Supabase Storage** and associated with your tutor profile. Access is governed by our security rules; such materials are intended to support your public tutor presence inside the App where you enable it.

### 2.7 In-app notifications about forum activity

We store **in-app notification records** (for example when someone replies to a thread you participate in) so the App can show you an activity list. These records are tied to your account. This is separate from **local** assignment reminders scheduled on your device (see Section 10).

### 2.8 Local device data (not sent to us)

Examples of data that typically remain **on-device** unless you explicitly upload or publish something:

- Preferences for **local assignment reminders** (scheduled notification identifiers mapped to your assignments).
- Cached copies of files you open for your own use.
- Local keys for app preferences.

### 2.9 Technical & automatic data

- We **do not** embed third-party **advertising** or **analytics** SDKs for behavioral tracking in the App.
- When you use online features, **standard technical information** is processed automatically as part of operating any internet service — for example **IP address**, timestamps, and request metadata — by us and by our infrastructure providers (such as **Supabase** and hosting networks) for **security**, **fraud prevention**, **reliability**, and **legal compliance**. We do not sell this information.

### 2.10 Bug reports and support

If you send a **bug report** from the App, we process:

- The **message text** you enter (please avoid including passwords, payment details, or unnecessary personal data).
- **Account-related identifiers** needed to route the report (for example your **email address** or user ID associated with your session), so we can investigate and reply if needed.

Reports are submitted through **Supabase Edge Functions** and may be delivered to our **support email inbox** via an email provider (for example SMTP). That provider processes the message in transit according to its own terms. We use this information only to **diagnose issues, improve the App, and respond to you** where appropriate.

---

## 3. How We Use Your Information

We use personal information to:

| Purpose | Typical legal basis (where GDPR applies) |
|--------|-------------------------------------------|
| Provide sign-in, sync, and core organizer features | Performance of a contract / steps at your request |
| Operate the forum, marketplace listings, and in-app notifications | Performance of a contract; legitimate interests in operating a safe community |
| Moderate content, enforce rules, respond to reports | Legitimate interests; legal obligations |
| Store and display profile and content you choose to publish | Performance of a contract; consent where required (e.g. certain optional uploads) |
| Secure the service and troubleshoot errors | Legitimate interests |
| Comply with law and respond to lawful requests | Legal obligation |
| Review bug reports and provide support | Legitimate interests / performance of a contract |

We **do not** sell your personal information. We **do not** use your data for third-party advertising profiling.

---

## 4. How Information Is Shared

- **Service providers (processors):** We use **Supabase** for database, authentication, file storage, and server-side functions. They process data on our instructions. Their privacy policy: [https://supabase.com/privacy](https://supabase.com/privacy)
- **Sign-in providers:** **Apple** and **Google** process authentication according to their policies: [Apple Privacy](https://www.apple.com/legal/privacy/), [Google Privacy](https://policies.google.com/privacy)
- **Other users:** Content you **publish** in the forum or tutor listings may be visible to other App users as designed.
- **Legal & safety:** We may disclose information if required by law, or if we reasonably believe disclosure is necessary to protect rights, safety, or the integrity of the service.
- **Email delivery:** Bug reports may be transmitted to our team through an email / SMTP provider; that provider sees the content of the report as part of delivery.

---

## 5. Data location & international transfers

Your data is processed using cloud infrastructure operated by **Supabase** and may be stored or processed in the regions configured for our project (potentially including the **European Union** or other regions Supabase supports). If you are outside those regions, your information may be **transferred internationally**. We rely on appropriate safeguards where required (such as standard contractual clauses or equivalent mechanisms offered by our providers).

---

## 6. Data retention

- We retain account and content data **while your account is active** and as needed to provide the service.
- If you **delete your account**, we will delete or anonymize associated personal data within a reasonable period, generally **within 30 days**, subject to backup cycles and legal retention needs.
- **Forum content** you posted may have been seen or copied by others before deletion; we cannot control copies outside our systems.
- Local on-device data remains until you uninstall the App or clear app storage.

---

## 7. Security

We implement appropriate technical and organizational measures, including:

- **Encryption in transit (TLS/HTTPS)** for network communication.
- **Secure credential storage** on device for session material.
- **Database access controls** (including row-level security patterns) so users cannot read other users’ **private** organizer data.
- **Community content** is intentionally readable by other users **only** where the product exposes it (forum / listings), not your private grades or personal planner data.

No method of transmission or storage is 100% secure; we encourage strong passwords and device security.

---

## 8. Children’s privacy

The App is **not directed at children under 13** (or the minimum age required in your jurisdiction). We do not knowingly collect personal information from children below that age. If you believe we have done so, contact **privacy@studenton.app** and we will take appropriate steps to delete the information.

---

## 9. Your rights

Depending on your location, you may have rights to **access**, **rectify**, **delete**, **restrict**, or **object** to certain processing, and **data portability**. You may also withdraw consent where processing is consent-based.

To exercise these rights, contact **privacy@studenton.app**. We will respond within **30 days** where applicable law requires it.

If you are in the **EEA/UK**, you may lodge a complaint with your local data protection authority.

**California residents (summary):** You may have rights under the **CCPA/CPRA** (for example to know, delete, and opt out of sale/sharing). We do not sell personal information as defined by California law. To submit a request, email **privacy@studenton.app**.

---

## 10. Notifications

- **Assignment reminders** are implemented as **local notifications** scheduled on your device from assignment data synced to your account. Scheduling metadata (notification IDs) is kept on the device.
- **Forum activity** uses **in-app** notification records stored in our database, as described in Section 2.7. The App does not require remote marketing push notifications for core functionality.

---

## 11. Third-party websites or services

The App may allow you to open links or documents in a browser or in-app web view. Those third parties have their own privacy practices; this policy does not apply there.

---

## 12. Changes to this policy

We may update this Privacy Policy from time to time. We will update the **Last Updated** date at the top. If changes are material, we may provide additional notice (for example in the App). Continued use after the effective date constitutes acceptance of the updated policy where permitted by law.

---

## 13. Contact

**Privacy:** [privacy@studenton.app](mailto:privacy@studenton.app)  
**General:** [contact@studenton.app](mailto:contact@studenton.app)  
**App name:** Studenton  

---

*This policy is intended to be clear and accurate. If anything here does not match what you see in the App, the App’s actual data practices and App Store disclosures should be aligned — please contact us so we can correct documentation.*
