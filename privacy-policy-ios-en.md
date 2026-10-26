# NIKA Privacy Policy

**Last updated: October 26, 2026**

This Privacy Policy explains what information the NIKA iOS app ("NIKA", "the app") and its backend service collect, how it is used, where it is stored, who it is shared with, and the choices you have. NIKA is a personal AI assistant. Some features run entirely on your iPhone, and others send data to our servers and to the AI providers named below. This policy describes both.

If you do not agree with this policy, please do not use NIKA.

---

## 1. Who we are and how to contact us

The NIKA service is provided and operated by **Victoria Dochkina**, an individual acting in a personal capacity, not a company ("we", "us", "our"). Victoria Dochkina is responsible for the processing of your personal data described in this Privacy Policy.

- Support and privacy requests: **support@lumorai.online** (the same address the in-app "Contact support" link uses)

You can also reach us from inside the app: **Settings → Data & storage → Contact support**.

---

## 2. Summary

- **Your data is used only for the app to work.** We use your data only to make the app work correctly and provide the features you use. We do not use it for commercial or any other purposes: we do not sell it, rent it, use it for advertising or marketing, or share it for anyone else's purposes.
- **No tracking and no ads.** NIKA does not track you across other companies' apps or websites. It contains no advertising, no advertising identifiers (IDFA), and no third-party analytics or crash-reporting SDKs.
- **We do not sell your personal information**, and we do not share it for advertising or marketing.
- **Some processing happens on your iPhone.** With the on-device model ("Fast" mode or "iPhone only"), on-device speech recognition and on-device Whisper, your request stays on your device.
- **Cloud features send data to our server and to AI providers.** When a request is answered in the cloud ("Deep" mode, or complex requests in "Auto" mode), the content you send goes to our server and to the AI model provider that produces the answer (see Section 6).
- **Health data is read only when you ask about it.** It is used only to answer you. It is never used for advertising or marketing, never sold, and never stored in iCloud (see Section 5).
- **You can delete your account in the app** at any time: **Settings → Delete account**.

---

## 3. Information we collect

We use your data only to make the app work correctly and provide the features you use. We do not use it for commercial or any other purposes: we do not sell it, rent it, use it for advertising or marketing, or share it for anyone else's purposes.

The categories below match the data types Apple uses on the App Store "App Privacy" label. None of this data is used for tracking.

### 3.1 Account and contact information

| Data | When | Purpose |
|---|---|---|
| **Email address** (or other login name) and **password** | If you register or sign in with email and password | Creating your account and signing you in. Passwords are sent over an encrypted connection to our server for authentication. |
| **Name and email from Sign in with Apple** | If you choose Sign in with Apple | Apple gives us an identity token. The first time you sign in, it may also give us your name and your real or private-relay email address. We use them to create your account and to address you. |
| **Telegram account identifier** | If you choose "Continue with Telegram" | Sign-in goes through our Telegram bot. Telegram confirms the sign-in to us and gives us the identifier of your Telegram account. |
| **Invite code** (optional) | At sign-up, if you enter one | Applying the invitation to your account. |
| **User ID** | Always, once you have an account | An internal account identifier, used to keep your data separate from other users' data. |
| **Phone number** | Only if you connect an online store that signs in by phone number (see 3.6) | Signing in to that store for you. A one-time code you enter is passed to the store for the same purpose. |

### 3.2 User content

- **Messages and conversations** that you type, dictate or share with NIKA, and the assistant's replies. These include text you share to NIKA from other apps through the Share extension.
- **Photos, videos, documents and other files** that you attach, take with the camera, or ask NIKA to work with. Images that NIKA creates for you are stored too.
- **Audio data**: voice recordings. These are uploaded only when you pick a speech-recognition mode or voice feature that runs in the cloud (see 3.4).
- **Memory**: facts, notes and observations about you. NIKA saves them when you ask it to, or learns them from your conversations while **Memory → "Remember from conversations"** is on.
- **Goals, plans, reminders, scheduled tasks ("errands") and automations** that you create in NIKA.
- **Answer reports and feedback**: a reason, an optional comment, and an excerpt of the reply you report. You send these when you use **"Report this reply"** or comment on a thumbs-down.
- **Cloud browser and task input**: anything you type into a task that NIKA carries out for you in a browser on our server, plus screenshots of that browser session.

### 3.3 Health and fitness data

These are read from Apple Health (HealthKit) and the iPhone motion sensor (Core Motion). Read-only, and only when you ask. See **Section 5** for details.

### 3.4 Voice

| Mode | Where it is processed |
|---|---|
| **"Fast" speech recognition** (Apple Speech) | On your iPhone. NIKA asks iOS for on-device recognition. If your device or language does not support on-device recognition, Apple's speech service may process the audio under Apple's own privacy policy. |
| **"Whisper" speech recognition** | On your iPhone, using a Whisper model downloaded to the device. Audio does not leave the device. |
| **"Server" speech recognition** | The recording is uploaded to our server, transcribed, and the text is returned to you. |
| **Spoken replies with a system voice** | On your iPhone. |
| **Spoken replies with ElevenLabs** (optional; you need to add your own ElevenLabs API key) | The text of the reply goes directly from your iPhone to ElevenLabs to be turned into speech. |
| **Live voice conversation via OpenRouter** (optional; you need to add your own OpenRouter API key) | Your voice recording and up to the last six text turns of the conversation go directly from your iPhone to OpenRouter (see Section 6). |

### 3.5 Calendar and Reminders

If you grant access, NIKA reads your calendar events (title, time, location, calendar name). It uses them to show your events in the planner and the home-screen widget, to suggest ideas, and to build daily briefs. NIKA also creates a separate "NIKA" calendar and adds your goal steps to it. With Reminders access, NIKA creates reminders, lists upcoming ones, and marks them complete when you ask. This processing happens on your iPhone. NIKA does not upload your calendar or reminders list in the background. An event title or detail reaches our server only if you send it yourself, for example by typing it or by sending a suggestion card that mentions it.

### 3.6 Connected services and shopping

You can connect accounts at third-party services, such as online stores or other services listed in **Connections**. Sign-in happens on the service's own page, which opens inside NIKA. After you sign in, the app sends the service's **session cookies** for that sign-in to our server, so that NIKA can act in that service for you, for example to search for products or manage your cart. For stores that sign in by phone, your phone number and the one-time code go to our server, and our server passes them to the store. You can disconnect a service in **Connections** at any time. Its stored session is then deleted from our server.

NIKA can put together a shopping cart or an order. **NIKA never enters payment details and never pays for you.** You finish and pay for any purchase yourself, on the store's own website or app.

### 3.7 Device and usage information

- **Technical data sent with requests**: your IP address (visible to any server you connect to), app platform ("ios"), interface language and time zone. These are needed to deliver the service, to show dates correctly, and to keep the service secure.
- **Usage counters (quotas)**: how many requests and tokens your account has used, so that usage limits can be applied.
- **On-device only (never sent)**: "Local analytics" (off by default; turn it on in **Settings → Data & storage**) keeps simple event counts on your iPhone only, with no message text, URLs or identifiers. Thumbs-up/down ratings, quality counters (for example "regenerate" or "stop") and performance timings are also kept only on the device. The declared date of birth from the age check is stored only on your iPhone.

### 3.8 Information we do not collect

NIKA does not request your precise or approximate **location**. It does not access your **contacts**. It does not read your **photo library** (photos you choose in the system picker are shared only one at a time; the "Add to Photos" permission only lets NIKA save images you ask it to save). It has no advertising identifier and contains no third-party advertising, analytics or crash-reporting SDKs.

---

## 4. iOS permissions and how they are used

NIKA asks for each permission only when you first use the feature that needs it. You can change any permission later in iOS **Settings → Privacy & Security** or in NIKA's **Access** screen.

| Permission | What NIKA does with it |
|---|---|
| **Health** (read only) | Reads steps, walking and running distance, active energy, resting heart rate, sleep and workouts when you ask about your activity. NIKA never writes data to Health. iOS shows the "write" line together with the read request, but NIKA does not use it. |
| **Motion & Fitness** | Reads steps and distance from the motion sensor when Health is not available, when you ask about your activity. |
| **Calendars** (full access) | Shows your events in the planner and widget, and adds your goal steps to a "NIKA" calendar. |
| **Reminders** (full access) | Creates, lists and completes reminders when you ask. |
| **Camera** | Takes photos or videos that you attach to a message. |
| **Microphone** | Voice input and voice conversations. |
| **Speech Recognition** | Turns your speech into message text. |
| **Photos – Add only** | Saves images that NIKA creates to your photo library when you ask. |
| **Notifications** | Local notifications for reminders, automations and daily briefs. |
| **Background App Refresh** | Prepares scheduled automations, such as daily briefs, on the device. |

---

## 5. Health data (HealthKit and Motion)

**What we read.** When you ask about your activity, NIKA reads only the metrics your question needs, for a period of up to 31 days. The metrics available are steps, walking and running distance, active energy burned, resting heart rate, sleep analysis and workouts. NIKA reads summaries per period, such as totals per day, not your complete Health history.

**On-device vs cloud.** If the on-device model answers your question, health data stays on your iPhone. If the answer is produced in the cloud, the summaries you asked for go to our server and become part of that conversation. The AI model provider that produces the answer receives them too (Section 6). The app shows a "Health data" card in the chat, so you can see what was read and shared.

**Our commitments for health data:**

- Health data is used **only to answer your question and provide the features you use**.
- It is **never used for advertising, marketing or use-based data mining**, by us or by third parties.
- It is **never sold** and **never shared with data brokers, advertising networks or information resellers**.
- It is shared only with the service providers that process it to give you an answer (Section 6). We do not use it for advertising or marketing, and we do not sell it.
- **It is not stored in iCloud.** NIKA does not use iCloud, iCloud Drive or iCloud Keychain to store any data.
- Health data is **never written** to Apple Health.

You can revoke NIKA's access at any time in iOS **Settings → Health → Data Access & Devices → NIKA**. To remove health data that is already part of a conversation, delete that conversation or your account.

---

## 6. On-device processing, cloud processing and third parties

### 6.1 Where a request is processed

- **On your iPhone**: "Fast" mode and the **"iPhone only"** setting use an AI model downloaded to your device. Your request and the answer are not sent over the internet. On-device memory is also stored locally (see Section 8).
- **In the cloud**: "Deep" mode, and complex requests in "Auto" mode, are sent to our server. Our server uses AI models from third-party providers to produce the answer.
- **Temporary chat**: these conversations are marked so that they are not saved to your history and never write to memory.

### 6.2 Who receives data

We do not sell personal information. We share it only with the recipients below, and only for the purposes described.

| Recipient | What it receives | Why |
|---|---|---|
| **Our backend servers** (operated by us with a hosting provider) | Account data, conversations, attachments, memory, goals, reminders and errands, uploaded audio (in "Server" mode), health summaries you asked for, connected-service sessions, feedback | Operating the service |
| **OpenRouter, Inc.** (AI model router), plus the AI model provider selected for the request (for example OpenAI, Anthropic, Google, Mistral, DeepSeek, Qwen or others, depending on the model chosen) | The content of cloud requests: your message, relevant conversation history, memory, attachments and any health summaries you asked for | Producing the AI answer |
| **OpenRouter, Inc.**, directly from your device (optional) | Voice recordings and recent conversation turns, if you turn on live voice with your own OpenRouter key | Live voice conversation |
| **ElevenLabs, Inc.**, directly from your device (optional) | The text of replies to be spoken, if you add your own ElevenLabs key | Text-to-speech |
| **Your own OpenRouter API key** (optional) | If you add one under the model settings, it is sent to our server and stored there, so that your cloud requests can use your OpenRouter account. You can remove it at any time. | Using your own OpenRouter account |
| **Apple** | Sign in with Apple data, and, if on-device recognition is not available, speech audio | Sign-in and speech recognition, under Apple's privacy policy |
| **Telegram** | Your Telegram sign-in confirmation, and, if you connect Telegram in **Connections**, the messages you exchange with our bot | Sign-in, and NIKA's Telegram channel if you use it |
| **Third-party services you connect** (online stores and other services in **Connections**) | Your session for that service, your phone number and one-time code (for phone sign-in), and the actions you ask NIKA to take there | Acting in that service for you |
| **Hugging Face** and our model server | Download requests only (IP address); none of your content | Downloading on-device AI and speech models |
| **Apple Maps / Google Maps** | The place or route you ask to open | Opening directions in the maps app or website you choose |

Third parties that you use directly (ElevenLabs, OpenRouter, Telegram, connected stores, Apple, Google) handle your data under their own privacy policies.

We may also disclose information when the law requires it, to protect the rights, safety and security of our users or others, or as part of a merger, acquisition or sale of assets. In that last case, this policy will continue to apply to your information.

### 6.3 How AI providers use your data

We do not sell your conversations and do not use them for advertising. We have no control over the data practices of third-party AI providers beyond our agreements with them and their published API terms.

---

## 7. No tracking, no advertising

NIKA does not "track" you as Apple defines the term. We do not link data collected in NIKA with data from other companies' apps, websites or offline properties for advertising or advertising measurement, and we do not share your data with data brokers. NIKA does not use the advertising identifier (IDFA), shows no ads and contains no third-party analytics or advertising SDKs.

---

## 8. Where data is stored and for how long

### 8.1 On your device

Conversations cached for offline use, on-device memory, files NIKA creates, downloaded AI and speech models, and your settings are stored in the app's private storage on your iPhone. Data shared between the app and its widget and Share extension is stored in a shared App Group container on your iPhone. Sign-in tokens and API keys are stored in the iOS Keychain, are available only on this device, and do not sync to iCloud. Memory and the app's file storage are excluded from device backups. Local data remains until you delete it in the app (**Settings → Memory → Clear all memory**, **Settings → Storage on iPhone**) or delete the app.

### 8.2 On our servers

Server data is kept while your account exists, unless you delete it sooner:

- Conversations, attachments, memory, goals, reminders and errands: until you delete them or your account.
- Answer reports and feedback: as long as needed to review them and fix problems with answers, then deleted.
- Connected-service sessions: until you disconnect the service or delete your account.
- Server logs (technical data, IP addresses): for a limited period needed for security and troubleshooting, then deleted.
- Backups: deleted data may remain in encrypted backups for a limited period before it is permanently overwritten.

### 8.3 Deleting your data and your account

- **Delete a conversation**: delete it from your chat history. You can also answer "Do not save" when NIKA asks whether to keep a conversation.
- **Delete memory**: **Settings → Memory**. Delete individual items there, or use **Clear all memory**. You can also turn off **"Remember from conversations"**, or turn on **"Don't remember this conversation"** for a single chat.
- **Disconnect a service**: **Connections** → choose the service → disconnect.
- **Delete your account**: in the app, go to **Settings → Delete account** and confirm. This permanently deletes your account and its conversations, files, images, goals, memory and settings from our servers. After that, you can no longer sign in to it with email, Telegram or Apple. Deletion cannot be undone. If you signed in with Apple, you can also stop using Apple ID with NIKA in iOS **Settings → [your name] → Sign in with Apple**.
- You can also ask us to delete your data by writing to **support@lumorai.online**.

---

## 9. Security

- All network traffic uses HTTPS (TLS). App Transport Security blocks unencrypted connections to internet hosts.
- Sign-in tokens and API keys are stored in the iOS Keychain with "this device only" access and are excluded from iCloud Keychain.
- On-device data uses iOS Data Protection (file encryption tied to your device passcode).
- Access to account data on our servers is limited to authenticated requests for that account. We use access controls and other reasonable technical and organizational measures to protect data on our servers.

No method of transmission or storage is completely secure. If a data breach affects your personal information, we will notify you and the relevant authorities as the law requires.

---

## 10. Your rights

Depending on where you live, you may have the right to:

- **access** the personal information we hold about you and receive a copy of it;
- **correct** inaccurate information;
- **delete** your information (most of it you can delete directly in the app, see Section 8.3);
- **restrict or object to** certain processing;
- **data portability**;
- **withdraw consent** at any time, for example by revoking an iOS permission, turning off memory, disconnecting a service or deleting your account. Withdrawing consent does not affect processing that took place before;
- **complain** to your local data-protection authority.

**EEA/UK users (GDPR).** We process your data to perform our contract with you (providing NIKA); on your consent (health data, iOS permissions, optional features and connected services); for our legitimate interests (security, preventing abuse, improving reliability); and to comply with legal obligations. Health data is special-category data, which we process only with your explicit consent, given when you ask NIKA about it and grant Health access.

**California users (CCPA/CPRA).** We do not sell or "share" personal information for cross-context behavioral advertising. We use sensitive personal information (health data, account credentials) only to provide the service you request. You have the right to know, delete and correct your information, and we will not discriminate against you for using these rights.

To use any of these rights, contact **support@lumorai.online**. We will respond within the time the applicable law requires, and we may need to verify your identity first.

---

## 11. Age requirement and children

NIKA is intended for users who are **18 years of age or older**. The app asks for your date of birth before first use and does not allow access if you are under 18. The date of birth stays on your device. We do not knowingly collect personal information from children. If you believe a child has given us personal information, contact **support@lumorai.online** and we will delete it.

---

## 12. International data transfers

Our servers and the AI providers in Section 6 may process data in countries other than your own, including the United States. When we transfer personal data across borders, we use the safeguards the applicable law requires, such as the European Commission's Standard Contractual Clauses.

---

## 13. Changes to this policy

We may update this Privacy Policy from time to time. The "Last updated" date at the top shows when it last changed. We will tell you about material changes in the app or by email before they take effect. If the law requires it, we will ask for your consent again.

---

## 14. Contact

**Victoria Dochkina**
Email: **support@lumorai.online**
