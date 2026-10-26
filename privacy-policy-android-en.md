# NIKA Privacy Policy (Android)

**Last updated: October 26, 2026**

This Privacy Policy explains what information the NIKA Android app ("NIKA", "the app") and its backend service collect, how it is used, where it is stored, who it is shared with, and the choices you have. NIKA is a personal AI assistant. Some features run entirely on your phone, and others send data to our servers and to the AI providers named below. This policy describes both.

If you do not agree with this policy, please do not use NIKA.

---

## 1. Who we are and how to contact us

The NIKA service is provided and operated by **Victoria Dochkina**, an individual acting in a personal capacity, not a company ("we", "us", "our"). Victoria Dochkina is responsible for the processing of your personal data described in this Privacy Policy.

- Support and privacy requests: **support@lumorai.online**

The Android app currently has a Russian-language interface. Where this policy names a screen, button or setting, the Russian label is given in brackets.

---

## 2. Summary

- **Your data is used only for the app to work.** We use your data only to make the app work correctly and provide the features you use. We do not use it for commercial or any other purposes: we do not sell it, rent it, use it for advertising or marketing, or share it for anyone else's purposes.
- **No tracking and no ads.** NIKA does not track you across other companies' apps or websites. It contains no advertising, does not use the Android advertising ID, and contains no third-party analytics or crash-reporting SDKs.
- **We do not sell your personal information**, and we do not share it for advertising or marketing.
- **Some processing happens on your phone.** With an on-device model that you download and choose in the model picker, on-device speech recognition and on-device Whisper, your request stays on your device.
- **Cloud features send data to our server and to AI providers, and only after you allow it.** When a request is answered in the cloud ("Auto" or a cloud model in the model picker), the content you send goes to our server and to the AI model provider that produces the answer (see Section 6). NIKA asks for your permission ("Cloud AI") before it first sends anything to the cloud, and you can withdraw it at any time.
- **Health data is read only when you ask for it.** It is read from Health Connect, stays on your phone, and reaches our server only if you send a health summary to a chat yourself. It is never used for advertising or marketing and never sold (see Section 5).
- **You can delete your account in the app** at any time: **Settings → Account → Delete account** («Настройки → Аккаунт → Удалить аккаунт»).

---

## 3. Information we collect

We use your data only to make the app work correctly and provide the features you use. We do not use it for commercial or any other purposes: we do not sell it, rent it, use it for advertising or marketing, or share it for anyone else's purposes.

The categories below describe what NIKA collects and why. None of this data is used for tracking.

### 3.1 Account and contact information

| Data | When | Purpose |
|---|---|---|
| **Login name** (for example, an email address) and **password** | If you register or sign in with a login and password | Creating your account and signing you in. Passwords are sent over an encrypted connection to our server for authentication. |
| **Telegram account identifier** | If you choose to sign in with Telegram | Sign-in goes through our Telegram bot. Telegram confirms the sign-in to us and gives us the identifier of your Telegram account. |
| **Invite code** (optional) | At sign-up, if you enter one | Applying the invitation to your account. |
| **User ID** | Always, once you have an account | An internal account identifier, used to keep your data separate from other users' data. |
| **Phone number** | Only if you sign in to an online store in NIKA's **Store** screen («Магазин») that signs in by phone number (see 3.6) | Signing in to that store for you. A one-time code you enter is passed to the store for the same purpose. |

### 3.2 User content

- **Messages and conversations** that you type, dictate or share with NIKA, and the assistant's replies. These include text you share to NIKA from other apps through Android's **Share** menu. Shared text is placed in the message field and is not sent until you send it.
- **Photos, documents and other files** that you choose in Android's file picker and attach, or ask NIKA to work with, including a photo you choose for a media effect. Images and files that NIKA creates for you are stored too.
- **Memory**: facts, notes and observations about you. NIKA saves them when you ask it to, or learns them from your conversations. Memory linked to your account is stored on our server. Memory that the on-device model learns is stored only on your phone (see Section 8).
- **Goals, steps, plans, events in your NIKA account calendar, reminders, scheduled tasks ("errands") and automations** that you create in NIKA.
- **Cloud browser and task input**: anything you type into a task that NIKA carries out for you in a browser on our server, plus screenshots of that browser session.
- **News**: if you use the personal news feed, which items you have seen and which ones you choose to discuss in a chat.

### 3.3 Health and fitness data

These are read from **Health Connect** on your phone. Read-only, and only when you ask. See **Section 5** for details.

### 3.4 Voice

| Mode | Where it is processed |
|---|---|
| **Dictation with Android on-device recognition** | On your phone. NIKA uses only Android's on-device speech recognizer (available on Android 13 and later, depending on the device) and does not fall back to a network service. If on-device recognition is not available, you can use Whisper instead. |
| **Whisper speech recognition** | On your phone, using a Whisper model downloaded to the device from our server. Audio does not leave the device. |
| **Android voice input in Settings → Voice** («Настройки → Голос») | Your speech is recognized by the speech-recognition service installed on your phone (for example, Google's). Depending on that service and its settings, the audio may be processed on its provider's servers under that provider's privacy policy. NIKA receives only the recognized text. |
| **Spoken replies** | By the text-to-speech engine selected in your Android settings, under its provider's terms. |
| **Live voice conversation via OpenRouter** (optional; you need to add your own OpenRouter API key and allow Cloud AI) | Your voice recording and up to the last six turns of the live conversation (their text, or the recording where there is no text) go directly from your phone to OpenRouter and to the audio model provider it uses for the request (currently an OpenAI audio model) (see Section 6). Your OpenRouter key is stored encrypted on your phone and is not sent to our server. |

### 3.5 Calendar, tasks and reminders

If you grant calendar access, NIKA reads events from the calendars on your phone (title, time, location, calendar name). It uses them to show your events on the **Agenda** screen («Повестка») and in the home-screen widget, to suggest ideas, and to answer you when you ask the on-device model about your schedule. This reading happens on your phone. NIKA does not upload your device calendar in the background. An event title or detail reaches our server only if you send it yourself, for example by typing it or by sending a suggestion that mentions it to a chat.

With write access, NIKA adds the events you choose to save to your device calendar. If you turn on goal-step sync on the Agenda screen, NIKA also adds your goal steps to a separate "NIKA" calendar on your phone. Events that you save to the **NIKA account calendar** («Календарь аккаунта NIKA») instead are stored on our server.

Personal tasks and reminders that you create on the phone are stored on your device, and NIKA shows them to you with local notifications.

### 3.6 Connected services and shopping

You can connect accounts at third-party services, such as online stores or other services listed in the **Actions** tab («Действия»). Sign-in happens on the service's own page, which opens in a separate built-in browser window inside NIKA. This window does not read cookies from Chrome or other browsers on your phone. After you sign in and confirm the connection, the app sends the service's **session cookies** for that sign-in to our server, so that NIKA can act in that service for you, for example to search for products or manage your cart. For stores that sign in by phone, your phone number and the one-time code go to our server, and our server passes them to the store. You can disconnect a service in the **Actions** tab at any time. Its stored session is then deleted from our server.

NIKA can put together a shopping cart or an order. **NIKA never enters payment details and never pays for you.** You finish and pay for any purchase yourself, on the store's own website or app.

### 3.7 Device and usage information

- **Technical data sent with requests**: your IP address (visible to any server you connect to) and, with some requests, the app platform ("android"). Scheduled tasks are stored with the time zone used to run them. These data are needed to deliver the service, to run tasks at the right time, and to keep the service secure.
- **Usage counters (quotas)**: how many requests and tokens your account has used, so that usage limits can be applied.
- **On-device only (never sent)**: the declared date of birth from the age check, your Cloud AI choice, your drafts and the conversations you have with the on-device model are stored only on your phone.

### 3.8 Information we do not collect

NIKA does not request your precise or approximate **location**. It does not access your **contacts**. It does not use your **camera**. It does not read your **photo or media library**: it gets access only to the files you choose in Android's file picker, and it saves files only where you choose in Android's save dialog. It does not use the advertising ID and contains no third-party advertising, analytics or crash-reporting SDKs.

---

## 4. Android permissions and how they are used

NIKA asks for each runtime permission only when you first use the feature that needs it. You can change permissions later in Android **Settings → Apps → NIKA → Permissions**, in the Health Connect settings on your phone, or in NIKA's **Access** screen («Настройки → Доступы»). The exact names of Android menus depend on your device.

| Permission | What NIKA does with it |
|---|---|
| **Health Connect** (read only) | Reads steps, distance, active calories burned, resting heart rate, sleep and exercise sessions when you ask about your activity or open NIKA's **Health** screen («Здоровье»). NIKA has no permission to write data to Health Connect. |
| **Calendar** (read) | Shows your events on the Agenda screen and in the widget, suggests ideas, and lets the on-device model answer questions about your schedule. |
| **Calendar** (write) | Adds the events you choose to save to your device calendar and, if you turn on sync, your goal steps to a "NIKA" calendar on your phone. |
| **Microphone** | Dictation, voice input and live voice conversations. |
| **Notifications** | Local notifications for reminders and automations, and to tell you that a reply is ready. NIKA does not use remote push notifications. |
| **Run at startup** | Restores your scheduled local reminders and automations after the phone restarts or the time or time zone changes. |
| **Network access and audio settings** | Connecting to the service, checking whether you are online, and routing audio during voice conversations. |

---

## 5. Health data (Health Connect)

**What we read.** NIKA reads only the metrics you have allowed in Health Connect: steps, distance, active calories burned, resting heart rate, sleep sessions and exercise sessions (workouts). It reads them on the **Health** screen (for today or the past week) and when you ask the on-device model about your activity (for the period your question needs, for example today, a week or a month). NIKA reads summaries per period, such as totals per day, and the list of workouts, not your complete Health Connect history. NIKA does not request Health Connect's permission to read older history.

**On-device vs cloud.** Health data is read on your phone. If the on-device model answers your question, health data stays on your phone. Health data reaches our server only if you send it to a chat yourself: on the **Health** screen, the **Send summary to chat** button («Передать сводку в чат») shows you the exact text and asks you to confirm. If that chat is answered in the cloud, the summary goes to our server and becomes part of that conversation. The AI model provider that produces the answer receives it too (Section 6).

**Our commitments for health data:**

- Health data is used **only to answer your question and provide the features you use**.
- It is **never used for advertising, marketing or use-based data mining**, by us or by third parties.
- It is **never sold** and **never shared with data brokers, advertising networks or information resellers**.
- It is shared only with the service providers that process it to give you an answer, and only after you send it to a cloud chat yourself (Section 6). We do not use it for advertising or marketing, and we do not sell it.
- NIKA **never writes** data to Health Connect. The app's data is excluded from Android cloud backup.

You can revoke NIKA's access at any time on NIKA's **Health** screen («Отключить доступ NIKA») or in the Health Connect settings on your phone (**App permissions → NIKA**). To remove health data that is already part of a conversation, delete that conversation or your account.

---

## 6. On-device processing, cloud processing and third parties

### 6.1 Where a request is processed

- **On your phone**: when you choose an on-device model in the model picker, NIKA uses an AI model that you downloaded to your device (or imported as a file). Your request and the answer are not sent over the internet. On-device memory, file tools, reading text from PDF files and recognizing text in images (OCR) also work on your phone (see Section 8).
- **In the cloud**: requests in "Auto" mode and requests to a cloud model chosen in the model picker are sent to our server. Our server uses AI models from third-party providers to produce the answer. Errands, the cloud browser, image generation and media effects, account memory and the news feed also work on our server.
- **Cloud AI permission**: NIKA asks for your permission before it first sends a message or a file to the cloud. You can withdraw it at any time in **Settings → Data & storage → Cloud AI** («Настройки → Данные и место → Облачный ИИ»). While it is off, NIKA does not send your messages or files to the cloud, does not create errands and does not start live voice conversations.
- **Temporary chat**: these conversations are marked so that they are not saved to your history and never write to memory.

### 6.2 Who receives data

We do not sell personal information. We share it only with the recipients below, and only for the purposes described.

| Recipient | What it receives | Why |
|---|---|---|
| **Our backend servers** (operated by us with a hosting provider) | Account data, conversations, attachments, account memory, goals, calendar events you save to the NIKA account calendar, reminders and errands, health summaries you sent to a cloud chat, connected-service sessions | Operating the service |
| **OpenRouter, Inc.** (AI model router), plus the AI model provider selected for the request (for example OpenAI, Anthropic, Google, Mistral, DeepSeek, Qwen or others, depending on the model chosen) | The content of cloud requests: your message, relevant conversation history, memory, attachments and any health summaries you sent to the chat | Producing the AI answer |
| **OpenRouter, Inc.**, directly from your device (optional), and the audio model provider it uses (currently OpenAI) | Voice recordings and recent turns of the live conversation, if you turn on live voice with your own OpenRouter key | Live voice conversation |
| **Telegram** | Your Telegram sign-in confirmation | Sign-in |
| **Third-party services you connect** (online stores and other services in the **Actions** tab) | Your session for that service, your phone number and one-time code (for phone sign-in), and the actions you ask NIKA to take there | Acting in that service for you |
| **Speech-recognition and text-to-speech services on your phone** (for example Google), only if you use them | Audio for Android voice input; text of replies to be spoken | Speech recognition and spoken replies, under the provider's own privacy policy |
| **Hugging Face**, **GitHub**, **OpenRouter** (public model list) and our model server | Download requests only (IP address); none of your content | Downloading on-device AI models, speech models and text-recognition (OCR) language data, and showing the list of cloud models |
| **OpenStreetMap** (OpenStreetMap Foundation) | When a reply contains a map: requests for map images of the area shown (with your IP address). When you open a map or route link: the place or route in that link | Showing maps in replies and opening maps or directions on openstreetmap.org. NIKA does not send your location |

Third parties that you use directly (OpenRouter, Telegram, connected stores, speech services on your phone, OpenStreetMap) handle your data under their own privacy policies.

We may also disclose information when the law requires it, to protect the rights, safety and security of our users or others, or as part of a merger, acquisition or sale of assets. In that last case, this policy will continue to apply to your information.

### 6.3 How AI providers use your data

We do not sell your conversations and do not use them for advertising. We have no control over the data practices of third-party AI providers beyond our agreements with them and their published API terms.

---

## 7. No tracking, no advertising

NIKA does not track you. We do not link data collected in NIKA with data from other companies' apps, websites or offline properties for advertising or advertising measurement, and we do not share your data with data brokers. NIKA does not use the Android advertising ID, shows no ads and contains no third-party analytics or advertising SDKs.

---

## 8. Where data is stored and for how long

### 8.1 On your device

Conversations cached for offline use, conversations with the on-device model, drafts, on-device memory, personal tasks and reminders, files in NIKA's working folder and files NIKA creates, downloaded AI and speech models, OCR language data, and your settings are stored in the app's private storage on your phone, which other apps cannot access. Sign-in tokens, the cached copy of your account data, your conversation journal and drafts, and your live-voice API key are additionally encrypted with keys that are kept in the Android Keystore and never leave it. The home-screen widget shows your agenda on your home screen. The app's data is excluded from Android cloud backup. Local data remains until you delete it in the app, clear the app's data in Android settings, or uninstall the app.

### 8.2 On our servers

Server data is kept while your account exists, unless you delete it sooner:

- Conversations, attachments, account memory, goals, account-calendar events, reminders and errands: until you delete them or your account.
- Connected-service sessions: until you disconnect the service or delete your account.
- Server logs (technical data, IP addresses): for a limited period needed for security and troubleshooting, then deleted.
- Backups: deleted data may remain in encrypted backups for a limited period before it is permanently overwritten.

### 8.3 Deleting your data and your account

- **Delete a conversation**: delete it from your chat history. To avoid saving a conversation at all, use **Temporary chat** («Временный чат»).
- **Delete memory**: **Settings → Data & storage → Memory** («Настройки → Данные и место → Память»). Delete individual items there. You can also turn off **Remember from conversations** («Запоминать из разговоров») so that the on-device model stops learning memory from your conversations.
- **Disconnect a service**: **Actions** tab → choose the service → disconnect.
- **Delete your account**: in the app, go to **Settings → Account → Delete account** («Настройки → Аккаунт → Удалить аккаунт») and confirm. This permanently deletes your account and its conversations, files, images, goals, memory and settings from our servers, and deletes this account's local automations and on-device memory from your phone. After that, you can no longer sign in to it with your login or Telegram. Deletion cannot be undone. Other data stored on the phone, such as personal tasks and downloaded models, is removed when you clear the app's data or uninstall the app.
- You can also ask us to delete your data by writing to **support@lumorai.online**.

---

## 9. Security

- All network traffic uses HTTPS (TLS). The app does not allow unencrypted (cleartext) connections.
- Sign-in tokens, the cached account data, the conversation journal and API keys are encrypted with AES-GCM keys held in the Android Keystore. The keys never leave the Keystore.
- On-device data is kept in the app's private storage and is excluded from Android cloud backup.
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
- **withdraw consent** at any time, for example by revoking an Android permission or Health Connect access, turning off Cloud AI, turning off memory, disconnecting a service or deleting your account. Withdrawing consent does not affect processing that took place before;
- **complain** to your local data-protection authority.

**Users in Russia.** You have the rights provided by Federal Law No. 152-FZ "On Personal Data", including the right to receive information about the processing of your personal data, to demand that it be clarified, blocked or destroyed, to withdraw your consent, and to appeal to Roskomnadzor (the authority for the protection of the rights of personal data subjects) or to a court.

**EEA/UK users (GDPR).** We process your data to perform our contract with you (providing NIKA); on your consent (health data, Android permissions, Cloud AI, optional features and connected services); for our legitimate interests in keeping the service secure and working correctly (security, preventing abuse, reliability); and to comply with legal obligations. Health data is special-category data, which we process only with your explicit consent, given when you grant Health Connect access and ask NIKA about your activity or send a health summary to a chat.

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
