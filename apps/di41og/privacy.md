---
layout: default
title: Di41og Privacy Policy
permalink: /apps/di41og/privacy/
---

# Privacy Policy for Di41og

Effective date: November 14, 2026

This policy explains how Di41og handles data in its iPhone and iPad app, including when the iPad app runs on an Apple silicon Mac.

## Short Version

Di41og is a local-first conversation copilot. You can prepare a conversation, transcribe speech, follow topics, and review notes on your device.

- Di41og does not require an account with the developer.
- The app does not contain advertising SDKs or third-party analytics or crash-reporting SDKs.
- The developer does not operate a server that receives your conversations, and the app does not send your conversations for advertising or model training.
- Raw microphone audio is processed in memory and is not saved as an audio file by Di41og.
- Speech recognition, speaker analysis, and supported AI analysis run on device. Di41og does not switch them to a remote provider when they are unavailable.
- Optional online term lookup and model downloads make the network requests described below.
- You choose whether to copy, export, share, or send information outside the app.

## Information Stored on Your Device

Depending on how you use Di41og, its local records may include:

- Conversation titles, dates, transcripts, recognized languages, and timing information.
- Your intentions, objectives, preparation, agenda items, and time slots.
- Topics, explanations, recommendations, decisions, questions, tasks, summaries, and other notes derived from the conversation.
- Estimated speaker activity, speaking times, voice labels, and names you assign to speakers.
- Meeting templates, your chosen role, participant counts, and company, product, team, audience, or other background you supply.
- Reusable product and team profiles and your app preferences.

This information supports the app's preparation, transcription, guidance, reflection, and export features. Generated interpretations and speaker labels can be wrong; review them before using or sharing them.

## Microphone, Speech Recognition, and AI

Di41og requests microphone access for a conversation you start. The app asks you to confirm participant consent before listening begins. You can pause or end listening, and Di41og pauses capture when it enters the background.

Microphone buffers are used for on-device speech recognition and optional speaker analysis, then released. The app saves the resulting transcript and derived records, rather than a raw audio recording.

Apple's on-device speech models provide transcription. Supported on-device Foundation Models provide AI analysis when Apple Intelligence is available and ready. Apple's model assets may need to be downloaded through system services. The app does not send microphone audio, transcripts, or meeting background to a developer-operated AI service, and it has no remote transcription or AI fallback.

Apple's services, asset downloads, device diagnostics, and permission controls operate under Apple's policies and your system settings. See [Apple's Privacy Policy](https://www.apple.com/legal/privacy/).

## Speaker Labels and Model Downloads

**Distinguish speakers** is on by default for new preferences. You can turn it off in Settings before starting a conversation. When you start listening with the feature enabled, first use may download the speaker model from Hugging Face and its file-delivery services. Later sessions can use the cached model.

The download request identifies the model files and can expose ordinary network information, such as an IP address and request details, to those services. It does not include your microphone audio, transcript, or meeting background. See [Hugging Face's Privacy Policy](https://huggingface.co/privacy).

Speaker analysis runs locally and estimates up to four voices. Its labels do not establish a person's identity. Derived labels, estimated activity, and names you supply can be saved with that conversation. Di41og does not persist acoustic embeddings or a reusable voiceprint, and it does not use a voice profile to identify a person across conversations.

## Calendar Access

Connecting a calendar is optional. With permission, Di41og reads upcoming events so you can prepare for a conversation. Event titles, dates, duration, and available notes, location text, or event URLs can inform that preparation. Details you use for a conversation can become part of its local record.

Di41og does not send calendar information to a developer server. Your calendar provider and Apple's calendar services continue to handle the calendar itself under their own settings and policies. You can revoke Di41og's calendar permission in system Settings.

## Optional Wikipedia Term Lookup

Di41og can identify potentially useful terms locally while following a conversation. Finding a term does not itself start an online lookup.

When you tap a term to look it up, Di41og sends the selected term in an HTTPS search request to English or German Wikipedia. The term itself may contain information from your conversation. Di41og does not attach the rest of the transcript, source passages, objectives, or meeting/participant records. Wikipedia receives the selected term and ordinary network request information, including an IP address and the app's request identifier.

If you choose to open a reference article, your browser or the receiving app makes that separate request. These services operate under the [Wikimedia Foundation Privacy Policy](https://foundation.wikimedia.org/wiki/Policy:Privacy_policy). The developer does not receive your Wikipedia queries.

## Local Storage, Backups, and Retention

Conversation archives and reusable product/team profiles are stored in the app's local container. On iOS and iPadOS, these stores use complete file protection. The conversation archive, reusable-profile store, and app-managed PDF export cache are marked as excluded from device backups. Other system behavior, including handling of preferences and copies outside the app, follows your device and service settings.

Completed conversations are kept until you delete them by default. You can instead select a retention period of 7, 30, or 90 days. Expired completed conversations are removed when Di41og opens or the retention setting changes; drafts are retained until you delete them.

You can delete individual conversations or use **Delete all conversations** after ending an active session. Saved products and teams are managed separately under **Saved products & teams**. Deleting a reusable profile does not remove context already copied into an existing conversation; delete the relevant conversation as well if you want to remove that copy.

Before uninstalling, you can use the app's deletion controls to remove conversation records and saved profiles. Uninstallation and removal of remaining app data follow your operating system and device-management settings. Copies you exported or sent elsewhere may remain in their destinations.

## Copying, Exporting, and Sharing

When you copy original transcript wording, share notes, or export a PDF, you choose the content and destination. Exports and copied text can contain personal or confidential conversation information. Di41og may create a protected temporary PDF copy to support sharing.

The receiving app, clipboard, file location, or service handles the copy under its own policies and settings. Deleting a conversation in Di41og does not recall a copy you already shared or remove files outside Di41og's managed storage.

## Support, Websites, and Diagnostics

If you email the developer, the developer and email service process the message and information you choose to send in order to respond. Contact: [starktdh@arcor.de](mailto:starktdh@arcor.de).

The public policy and support pages are hosted on GitHub. Visiting them or interacting with a public repository is subject to [GitHub's Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement). Do not put private transcripts, names, meeting details, company information, or unredacted screenshots in public issues or comments.

Di41og does not include a developer-operated analytics or third-party crash-reporting service. Apple may provide the developer with App Store, TestFlight, crash, or other diagnostic information according to Apple's tools and your system or testing settings. Feedback you choose to submit may include the information and attachments you send.

## Changes and Contact

This policy may change as Di41og's features or data handling change. The effective date above will be updated when meaningful changes are made.

For privacy questions or questions about information you have sent to support, email [starktdh@arcor.de](mailto:starktdh@arcor.de). See the [Di41og support page](support.md) for help using the app.
