---
layout: default
title: Di41og Support
permalink: /apps/di41og/support/
---

# Di41og Support

For help or feedback, email [starktdh@arcor.de](mailto:starktdh@arcor.de).

Read the [Di41og Privacy Policy](privacy.md) for local storage and the separate choices for summary processing, encrypted sync, calendar saving, computer audio and sharing.

## Getting Started

Create a conversation or choose **Start an ad hoc conversation**. Preparation, templates, participant count, and a time limit are optional. Confirm participant consent before beginning and allow microphone access when requested.

Keep Di41og in the foreground while listening. You can pause or end a session; backgrounding the app pauses capture. Same-iPhone telephone-call audio is not supported.

## On-Device AI Availability

Di41og requires iOS or iPadOS 26 or later. Live AI features additionally need Apple Intelligence-capable hardware, supported system settings, and a model that is enabled and ready. In Di41og Settings, use **Check availability** to see the current status.

Speech recognition has its own device and installed-language-asset requirements. Missing Apple speech or AI assets may need a network connection to download. The app does not automatically switch to a cloud provider. Supported transcription, manual preparation, local document search, timers and transcript-based notes can still be used without on-device AI.

An AI notice is separate from microphone status. A declined analysis does not by itself mean listening has stopped. Check the live listening indicator; if capture is paused, read its reason and use **Resume** when ready.

## Languages and Speaker Labels

Automatic language selection follows English and German. Short phrases, background noise, and overlapping speech can be ambiguous. Pause a live session to choose a fixed language there, or change the default language in Settings after ending the session.

**Distinguish speakers** estimates up to four voices and is enabled by default for new settings. First use may download a model; later sessions can use its cached copy. If labels are unavailable, check the speaker status and network connection for an initial download. The labels are estimates, and you assign any names yourself.

For an incorrectly attributed passage, select the relevant word range and correct its voice label. This preserves the source words and timing; it does not identify the speaker or teach the app a cross-conversation voice identity. Review overlapping speech manually.

The interface is currently English. English and German speech support and German store text do not imply a German interface.

## Summary Processing and Coverage

Final summaries default to Apple's on-device model. Review workstream accounts and their original quotations; partial-coverage notices mean the draft may omit sections or connections. A source citation establishes traceability, not agreement or complete minutes. Edit the notes and check original speech before relying on them.

In Settings you can explicitly choose and allow an Ollama server/model for final summaries. This choice sends bounded transcript/source text, the meeting title, chapter metadata and evidence-linked goal anchors to that processor when you later end a conversation or request a fresh summary. They do not change on-device speech, live guidance or local knowledge answers. Return to the on-device option or disable permission to stop later alternative-summary requests.

For Ollama, check the exact server address, installed model and its processing/retention practices. Checking models contacts that server without sending conversation text. Private Cloud Compute integration is prepared but disabled in the current build, with its consent control locked. It requires Apple's managed entitlement, a configured rebuild and iOS/macOS 27 or later. An option shown in Settings is not a usable service or evidence of entitlement approval. There is no automatic retry through another provider.

Helpful / Not helpful guidance ratings remain local to the conversation. Optional learning changes guidance preferences; switching it off retains history. Ratings and private guidance are included if you later sync complete conversations.

## Knowledge Library and CV Assistance

Import a PDF with selectable text or a text/Markdown file. Search and source-cited answers use local extracted text. A scanned PDF without extractable text needs OCR elsewhere first. Encrypted/password-locked or oversized documents may be rejected; the importer supports up to 10 MB, 300 PDF pages and 500,000 extracted characters per document.

Choose which documents to use and enable **Include other saved conversations** only when intended. CV/project answer assistance supplies source quotations, not invented experience. If Apple Intelligence is unavailable or declines the request, you can still read local search matches. Removing an imported item deletes its extracted library text, not the original file. Knowledge documents are separate from conversation sync.

## Calendar, Reminders and Lock Screen

Connect Calendar only if wanted, choose included calendars and exclude individual event occurrences. To book a preparation, open its system event draft, review the title, time, purpose and agenda, then choose Save. No invitation is sent automatically. Your calendar service may synchronize saved events.

Preparation reminders require opt-in notification permission and use generic text. Shortcuts/App Intents can create or open an editable preparation; they do not start listening. Optional Live Activities show recording status, clocks and agenda position without titles, transcript, tasks or guidance. They do not keep recording active while Di41og is in the background.

## Home Screen preparation widget

The optional widget offers static links for a new preparation or the upcoming draft. It opens Di41og without starting capture and displays no private conversation or calendar content. It does not keep private data in a shared widget container.

## Encrypted Conversation Sync

Choose a Files folder in the sync settings, save its recovery key and connect the other device to the same folder with that key. Synchronize manually after ending the active conversation. Folder sync includes full conversation records, including private guidance and ratings; imported knowledge documents and reusable profiles remain separate.

If the folder already contains encrypted records, use its existing recovery key. A lost key cannot be recovered by the developer. File-provider conflicts or concurrent edits require review; do not discard another device's copy just to clear an error. Disabling sync leaves the encrypted snapshots in your selected folder. Remove provider files, other-device copies and backups separately when intended.

## Computer Audio on a Mac

The iPad app on a compatible Apple silicon Mac can pair with the separately installed Di41og Mac audio companion on macOS 26 or later. Choose a display/app in the companion's system picker, create a pairing and choose **Open Di41og to pair**. In Di41og, confirm participant consent and explicitly start the conversation. The companion uses selected system audio, not the microphone, and creates no audio file.

Capture stops on Pause, disconnect, source change, unpair or quit. The same prepared pairing supports an explicit Resume; reconnecting alone does not start audio. **Stop and unpair** invalidates it. If the source fails, check macOS Screen & System Audio Recording permission and create a new pairing when needed. The helper does not bypass protected sources or record telephone-call audio on the iPhone.

## Topics, Templates, and Online Terms

AI topics and template suggestions are interpretations. Open their supporting transcript quotations and decide whether the suggestion helps. Accepting a live template preserves your existing objectives, agenda, and current timer. Duration guidance uses the optional participant count you supply.

Term detection is local. An online Wikipedia lookup starts only when you tap a term. If you are offline, lookup may be unavailable while other on-device features continue to work with installed assets.

## Managing Your Data

Review the retention setting under **Your data, your control**. You can delete conversations individually or end the active session and choose **Delete all conversations**. Saved product/team profiles and imported knowledge documents have separate controls. Deleting locally does not recall exports or immediately erase every synced provider/device copy. Disable sync before uninstalling if you intend to remove its device key and configuration; remove shared files and outside copies at their destinations.

## Before Contacting Support

Please include:

- The Di41og version and build, if available.
- Your device model and operating-system version.
- A short description of the issue and steps that reproduce it.
- Whether the issue concerns capture, transcription, voice corrections, on-device AI, an explicitly enabled summary processor, knowledge, sync, calendar or sharing. For sync/model issues, omit recovery keys, pairing keys, credentials and private server details.
- The relevant status or error wording, with private details removed.

You do not need to send an entire transcript or recording to report a problem. Remove personal names, confidential meeting content, company details, and other private information from screenshots or examples. Do not post that material in public GitHub issues or comments.

[Back to Di41og](index.md)
