---
layout: default
title: Di41og Privacy Policy
permalink: /apps/di41og/privacy/
---

# Privacy Policy for Di41og

Effective date: November 23, 2026

This policy covers Di41og for iPhone and iPad, the iPad app on Apple silicon Macs, and the separate Di41og Mac audio companion.

## Your Choices

Di41og is a local-first conversation copilot. No developer account is required, and the developer does not operate a conversation-storage or AI-processing server. The app contains no advertising SDK, third-party analytics SDK or third-party crash-reporting SDK.

Speech recognition, speaker analysis, live guidance and knowledge answers run on device. Final summaries also use the on-device model by default. The app does not automatically switch to remote processing when a local model is unavailable or declines content.

You can separately enable a selected Ollama server for final summaries, connect encrypted conversation sync to a folder you choose, save a reviewed calendar event, look up a selected term online, or share information. These choices have the data flows described below. Raw microphone and computer audio are processed in memory; neither Di41og nor its companion creates an audio recording file.

## Optional App Store Subscription

Di41og offers free conversations with a limited active listening duration and an optional monthly Di41og Plus subscription for longer conversations. Apple processes purchases, renewals, refunds and payment details under your Apple Account and Apple's applicable policies. Di41og reads verified subscription transactions and entitlement status on the device to determine access. It does not operate a purchase-validation server or attach conversation content to purchase requests.

Active listening time is stored with the local conversation record; pauses do not consume the allowance. Saved transcripts, notes and exports remain available without an active subscription. Subscription operations do not enable optional conversation sync or remote AI processing. Apple may require an internet connection for purchase or restoration; locally available verified entitlements can remain usable offline.

## Local Conversation Records

Depending on the features you use, Di41og stores conversation titles and dates; transcripts and language/timing information; objectives, preparation and agenda; topic and summary interpretations; decisions, requests and tasks; source quotations and coverage receipts; private guidance and Helpful / Not helpful ratings; speaker labels, estimated activity and names you assign; manual voice corrections; and context and preferences you supply.

Reusable product/team profiles and imported knowledge material are separate local stores. Generated interpretations and voice labels can be wrong. They are not identity verification or an accuracy guarantee.

Guidance ratings stay with their conversation. If you enable learning from feedback, local preference rules can affect later optional guidance; they do not alter transcript evidence or train a remote model. Turning learning off retains the ratings until you remove them or delete their conversation.

## Microphone, Speech and Default AI

Starting a microphone conversation requires participant-consent confirmation and microphone permission. You can pause or end listening. Backgrounding the main app pauses capture; a Lock Screen activity does not enable background recording.

Microphone buffers support Apple's on-device speech recognition and optional local speaker analysis, then are released. The transcript and derived records are saved instead of audio. Speech has device, language and installed-asset requirements and has no remote recognition fallback.

Supported Apple Foundation Models provide preparation, live analysis, guidance and knowledge answers on device. Final summaries use that model unless you explicitly enable a different summary option. Apple model assets may be downloaded through system services. Apple's permission controls, model downloads and system diagnostics follow Apple's policies and your settings: [Apple Privacy Policy](https://www.apple.com/legal/privacy/).

## Optional Final-Summary Processing

Settings lets you choose a summary processor and separately allow its processing. That permission applies when you later end a conversation or request a new final summary, until you disable the permission or return to the on-device option. Selecting an option alone does not send a conversation.

For an enabled alternative, Di41og sends bounded sections of original transcript text, nearby source context, source positions, the meeting title, activity/chapter metadata, evidence-linked goal anchors, source-derived labels/issue interpretations and the requested output language to the chosen processor. Later organization uses admitted quotations and their interpretations. This can include personal or confidential information spoken in the conversation. Raw audio, the private guidance history and imported document files are not attached to these summary requests. A quoted transcript can itself contain information about any of those subjects.

**Ollama:** requests go to the server address and model you configure. A server on this same device can process locally; a server elsewhere receives the request over the network. A selected server/model may itself use cloud processing. Its operator controls access, logs, retention and subsequent handling; review those practices before enabling it. Di41og's developer does not receive those requests through a developer-operated service. Checking installed models contacts that server without sending conversation text. The server also receives ordinary network request information such as an IP address.

**Apple Private Cloud Compute:** integration is prepared but disabled in the current build; its consent control is locked. An explicitly configured rebuild and Apple's entitlement grant are required before this option can be enabled. In such a configured build, if selected, available and permitted, final-summary source text is processed by Apple's cloud model. This needs iOS/macOS 27 or later, supported Apple Intelligence availability and Apple's managed developer entitlement. An option shown in Settings does not establish that the entitlement is granted or the service is usable. Apple's processing follows its [Private Cloud Compute information](https://security.apple.com/private-cloud-compute/) and applicable policies.

Changing summary processing does not change the on-device speech, live-guidance or knowledge-answer services. Returned text still passes Di41og's source checks and may be incomplete or incorrect.

## Optional Computer Audio on Mac

The separate Mac companion uses Apple's system picker to let you choose a display or application. Selection and pairing prepare the source; capture starts only after the paired main app receives your consent confirmation and an explicit Start or Resume.

The companion sends selected system-audio buffers through an authenticated connection on the same Mac's loopback interface for on-device transcription and speaker analysis. It does not use the microphone, create an audio file, or send this stream to a network model. Di41og saves the resulting transcript and derived conversation record. If you enabled alternative final-summary processing or folder sync, that resulting text can later follow those separate choices.

Pause, Stop, disconnect or changing the source stops the capture stream. The pairing remains available for a new authenticated Start or Resume until you unpair, change source or quit the companion. The pairing key stays in memory unless you choose to copy its link. The operating system controls screen/system-audio recording permission and its capture indicator.

## Local Knowledge and Answer Assistance

You can import PDFs with extractable text and text/Markdown files, including CV or project material. Di41og saves the extracted text, filename, title and page references locally, rather than a copy of the original document file or continuing access to that file. The original file and any Files-provider download remain under the source provider's settings.

Search runs locally. Knowledge answers use your question and selected local source excerpts with an on-device model. Including other saved conversations is an explicit retrieval option. Answer assistance organizes quotations from your sources rather than verifying professional experience or inventing missing achievements. Source material is data, not an instruction to contact anyone or upload it.

Imported knowledge documents are not included in encrypted conversation sync. Delete an imported document from the knowledge library to remove its extracted text; deleting a conversation does not delete the separate library or the original file.

## Encrypted Conversation Sync

Sync is off until you choose a Files folder and configure a key. Synchronization is a manual action when no conversation is active. The folder can be local or supplied by iCloud Drive or another Files provider. Di41og does not run a sync server.

Before writing to that folder, Di41og encrypts conversation snapshots using AES-GCM with a random 256-bit key. Snapshots contain complete conversation records, including transcripts, private guidance, ratings, preparation, speaker annotations, outcomes and notes. Separate imported knowledge files, reusable product/team profiles and general app settings are not included. The folder provider can see file names, sizes, dates and its own account/network information; the conversation payload is encrypted.

The key is stored in the device's Keychain without Keychain synchronization. You can explicitly display or copy a recovery key to connect another device to the same folder. Anyone who has both the key and encrypted snapshots can read the conversations. The developer cannot recover a lost key. Clipboard, key copies and your folder provider have their own handling and backup settings.

Sync can propagate deletions on later synchronization; concurrent versions may be retained for review. Deleting a local conversation does not instantly erase every other device, provider version or backup. Disabling sync removes this device's connection and stored sync key, but leaves encrypted snapshots in the chosen folder. Remove those files and other copies separately when intended.

## Calendar, Reminders and System Integrations

Calendar connection is optional. With your permission, Di41og reads events from your selected calendars and lets you exclude individual occurrences. Titles, dates, duration and available notes, locations or URLs can become part of a preparation you create. A local preparation can also open an editable system event draft containing its title, time, purpose and agenda. Di41og does not automatically save it or send invitations; you review the draft and choose Save. Your calendar provider handles saved events and their synchronization under its settings.

Optional preparation reminders use local notifications with generic wording and a conversation identifier, without meeting titles, transcripts or guidance. Notifications require permission and do not start recording. App Intents/Shortcuts create or open local editable preparations; they do not capture audio, send invitations or contact participants. Siri and Shortcuts handle your invocation and supplied parameters under Apple's policies and settings.

An optional Home Screen widget contains static preparation links only. It displays no conversation titles, calendar events, transcript or guidance, and no private state enters its timeline or a shared application container. Tapping a link opens Di41og; it does not start capture.

An optional Live Activity exposes recording/paused status, elapsed/remaining time, agenda position and an app conversation identifier on supported system surfaces. It omits conversation titles, participants, transcript, tasks and guidance. It does not use a push-notification server or enable capture while the app is backgrounded.

## Speaker Model Downloads

**Distinguish speakers** defaults on for new preferences. You can turn it off before capture. Preparing models with the microphone off, or starting with the feature enabled, may download the model from Hugging Face and its file-delivery services on first use. Those services receive model-file requests and ordinary network information, such as an IP address, without microphone audio, transcript or meeting background. See [Hugging Face Privacy Policy](https://huggingface.co/privacy).

Analysis estimates up to four voices locally. Labels do not establish identity; user-assigned names and word-range corrections belong to the conversation. Di41og does not persist acoustic embeddings or a reusable voiceprint to identify a person across conversations.

## Optional Wikipedia Lookup

Local term detection does not make an online request. Tapping a term sends that selected term in an HTTPS search request to English or German Wikipedia. The term may itself contain conversation information. The request does not attach the transcript, other source passages or meeting records. Wikipedia receives the term and ordinary request information, including an IP address and app request identifier. Opening an article is a separate browser/app request. See [Wikimedia Foundation Privacy Policy](https://foundation.wikimedia.org/wiki/Policy:Privacy_policy). The developer does not receive your queries.

## Storage, Backups and Deletion

Local conversation archives, knowledge text and reusable profiles use complete file protection on iOS/iPadOS and are marked excluded from device backups; app-managed PDF export caches are also excluded. Preferences and copies outside app-managed storage follow system/provider settings. Sync snapshots deliberately reside in the folder you choose and may be backed up or synchronized by that provider.

Completed conversations remain until deleted by default. Optional 7-, 30- or 90-day retention removes expired completed records on app opening or a retention-setting change; drafts remain until deleted. Delete conversations individually or use **Delete all conversations** after ending an active session. Knowledge documents and saved product/team profiles have separate deletion controls. Deleting a profile does not remove context already copied into a conversation.

Uninstalling follows operating-system and device-management behavior. Keychain items and externally copied material can have a different lifecycle; disable sync and use the relevant deletion controls before uninstalling when you intend to remove those items. Provider copies, backups and shared exports need separate removal.

## Copying, Exports and Support

You choose what to copy, export or share and its destination. Notes can contain personal or confidential information. A temporary protected PDF may be created for sharing. Ordinary notes exclude private live guidance. The separate **Private analysis export** requires an explicit choice to include original transcript, private guidance, preparation, evidence, human review entries and coverage in a JSON file. It contains no raw audio and is not sent automatically to the developer. The receiving app, clipboard, Files provider or service handles the copy under its policies. Deleting in Di41og does not recall a shared copy.

If you email support, the developer and email service process the message and attachments you choose to send to respond. Contact: [starktdh@arcor.de](mailto:starktdh@arcor.de). You do not need to send a full transcript. Remove private details from examples and do not post them in public issues.

Policy/support pages are hosted on GitHub, under [GitHub Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement). Apple may provide App Store, TestFlight and diagnostic information under its tools and your settings. Di41og has no developer-operated analytics or third-party crash-reporting service.

## Changes and Contact

This policy is updated when meaningful data handling changes. For privacy questions or support information you have sent, email [starktdh@arcor.de](mailto:starktdh@arcor.de). See [Di41og support](support.md) for feature and data controls.
