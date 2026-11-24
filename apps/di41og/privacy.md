---
layout: default
title: Di41og Privacy Policy
permalink: /apps/di41og/privacy/
---

# Privacy Policy for Di41og

[English](#english) · [Deutsch](#deutsch)

## English

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

## Deutsch

**Datenschutzerklärung für Di41og**

Gültig ab: 23. November 2026

Diese Erklärung gilt für Di41og auf iPhone und iPad, die iPad-App auf Macs mit Apple Chip und die separate Di41og-Audiobegleitapp für den Mac.

### Deine Wahlmöglichkeiten

Di41og ist ein Gesprächscopilot mit standardmäßig lokaler Verarbeitung. Ein Konto beim Entwickler ist nicht erforderlich. Der Entwickler betreibt keinen Server zur Speicherung von Gesprächen oder zur KI-Verarbeitung. Die App enthält kein Werbe-SDK und keine Analyse- oder Absturzberichts-SDKs von Drittanbietern.

Spracherkennung, Sprecheranalyse, Live-Hinweise und Wissensantworten laufen auf dem Gerät. Auch abschließende Zusammenfassungen nutzen standardmäßig das Modell auf dem Gerät. Die App wechselt nicht automatisch zur Verarbeitung auf entfernten Systemen, wenn ein lokales Modell nicht verfügbar ist oder Inhalte ablehnt.

Du kannst separat einen ausgewählten Ollama-Server für abschließende Zusammenfassungen freigeben, die verschlüsselte Gesprächssynchronisierung mit einem selbst gewählten Ordner verbinden, einen geprüften Kalendereintrag speichern, einen ausgewählten Begriff online nachschlagen oder Informationen teilen. Für diese Entscheidungen gelten die unten beschriebenen Datenflüsse. Rohes Mikrofon- und Computeraudio wird im Arbeitsspeicher verarbeitet; weder Di41og noch seine Begleitapp erstellt eine Audioaufnahmedatei.

### Optionales App Store-Abonnement

Di41og bietet kostenlose Gespräche mit begrenzter aktiver Zuhörzeit und ein optionales monatliches Di41og Plus-Abonnement für längere Gespräche. Apple verarbeitet Käufe, Verlängerungen, Erstattungen und Zahlungsdaten über deinen Apple Account und nach den jeweils geltenden Richtlinien von Apple. Di41og liest bestätigte Abonnementtransaktionen und den Berechtigungsstatus auf dem Gerät, um den Zugang zu bestimmen. Die App betreibt keinen Server zur Kaufprüfung und fügt Kaufanfragen keine Gesprächsinhalte bei.

Die aktive Zuhörzeit wird im lokalen Gesprächsdatensatz gespeichert; Pausen verbrauchen das Kontingent nicht. Gespeicherte Transkripte, Notizen und Exporte bleiben ohne aktives Abonnement verfügbar. Abonnementvorgänge aktivieren weder die optionale Gesprächssynchronisierung noch die KI-Verarbeitung auf entfernten Systemen. Für Kauf oder Wiederherstellung kann Apple eine Internetverbindung verlangen; lokal verfügbare bestätigte Berechtigungen können offline weiter nutzbar sein.

### Lokale Gesprächsdatensätze

Je nach genutzten Funktionen speichert Di41og Gesprächstitel und Datumsangaben; Transkripte sowie Sprach- und Zeitangaben; Ziele, Vorbereitung und Agenda; Themen- und Zusammenfassungsinterpretationen; Entscheidungen, Anfragen und Aufgaben; Quellenzitate und Nachweise über den Prüfungsumfang; private Hinweise und Bewertungen als „Hilfreich“ oder „Nicht hilfreich“; Sprecherzuordnungen, geschätzte Aktivität und von dir vergebene Namen; manuelle Stimmenkorrekturen sowie von dir angegebenen Kontext und Einstellungen.

Wiederverwendbare Produkt- und Teamprofile sowie importiertes Wissensmaterial werden in separaten lokalen Speichern abgelegt. Erzeugte Interpretationen und Stimmenzuordnungen können falsch sein. Sie sind weder eine Identitätsprüfung noch eine Genauigkeitsgarantie.

Bewertungen von Hinweisen bleiben beim jeweiligen Gespräch. Wenn du das Lernen aus Feedback aktivierst, können lokale Einstellungsregeln spätere optionale Hinweise beeinflussen. Sie verändern keine Transkriptbelege und trainieren kein entferntes Modell. Wenn du das Lernen ausschaltest, bleiben die Bewertungen erhalten, bis du sie oder das zugehörige Gespräch löschst.

### Mikrofon, Sprache und standardmäßige KI

Zum Start eines Mikrofon-Gesprächs sind die Bestätigung der Zustimmung der Teilnehmenden und die Mikrofonberechtigung erforderlich. Du kannst das Zuhören pausieren oder beenden. Wenn die Hauptapp in den Hintergrund wechselt, pausiert die Erfassung; eine Aktivität auf dem Sperrbildschirm ermöglicht keine Hintergrundaufnahme.

Mikrofonpuffer dienen Apples Spracherkennung auf dem Gerät und der optionalen lokalen Sprecheranalyse und werden anschließend freigegeben. Anstelle von Audio werden das Transkript und die daraus abgeleiteten Datensätze gespeichert. Für die Spracherkennung gelten Anforderungen an Gerät, Sprache und installierte Modelle; es gibt keinen Rückgriff auf eine entfernte Spracherkennung.

Unterstützte Apple Foundation Models liefern Vorbereitung, Live-Analyse, Hinweise und Wissensantworten auf dem Gerät. Abschließende Zusammenfassungen nutzen dieses Modell, sofern du nicht ausdrücklich eine andere Zusammenfassungsoption aktivierst. Apple-Modellressourcen können über Systemdienste geladen werden. Apples Berechtigungssteuerung, Modelldownloads und Systemdiagnose unterliegen Apples Richtlinien und deinen Einstellungen: [Apple-Datenschutzrichtlinie](https://www.apple.com/legal/privacy/).

### Optionale Verarbeitung abschließender Zusammenfassungen

In den Einstellungen kannst du einen Prozessor für Zusammenfassungen auswählen und seine Verarbeitung separat erlauben. Diese Erlaubnis gilt, wenn du später ein Gespräch beendest oder eine neue abschließende Zusammenfassung anforderst, bis du sie deaktivierst oder zur Option auf dem Gerät zurückkehrst. Die bloße Auswahl einer Option sendet kein Gespräch.

Für eine aktivierte Alternative sendet Di41og begrenzte Abschnitte des ursprünglichen Transkripttexts, benachbarten Quellenkontext, Quellenpositionen, den Gesprächstitel, Metadaten zu Aktivitäten und Kapiteln, mit Belegen verknüpfte Zielanker, aus Quellen abgeleitete Bezeichnungen und Interpretationen von Problemstellungen sowie die gewünschte Ausgabesprache an den gewählten Prozessor. Bei der späteren Gliederung werden zugelassene Zitate und ihre Interpretationen verwendet. Dies kann personenbezogene oder vertrauliche Informationen enthalten, die im Gespräch genannt wurden. Diesen Zusammenfassungsanfragen werden weder Rohaudio noch der Verlauf privater Hinweise oder importierte Dokumentdateien beigefügt. Ein zitiertes Transkript kann selbst Informationen zu jedem dieser Themen enthalten.

**Ollama:** Anfragen gehen an die von dir konfigurierte Serveradresse und das gewählte Modell. Ein Server auf demselben Gerät kann lokal verarbeiten; ein Server an einem anderen Ort erhält die Anfrage über das Netzwerk. Ein ausgewählter Server oder ein Modell kann seinerseits Cloud-Verarbeitung nutzen. Sein Betreiber bestimmt Zugriff, Protokollierung, Aufbewahrung und weitere Verarbeitung; prüfe diese Verfahren vor der Aktivierung. Der Entwickler von Di41og erhält diese Anfragen nicht über einen von ihm betriebenen Dienst. Die Prüfung installierter Modelle kontaktiert diesen Server, ohne Gesprächstext zu senden. Der Server erhält außerdem gewöhnliche Informationen zu Netzwerkanfragen, etwa eine IP-Adresse.

**Apple Private Cloud Compute:** Die Integration ist vorbereitet, aber im aktuellen Build deaktiviert; ihre Freigabe ist gesperrt. Bevor diese Option aktiviert werden kann, sind ein ausdrücklich konfigurierter neuer Build und die Erteilung der Berechtigung durch Apple erforderlich. In einem solchen konfigurierten Build wird Ausgangstext für abschließende Zusammenfassungen durch Apples Cloud-Modell verarbeitet, sofern die Option ausgewählt, verfügbar und erlaubt ist. Dafür sind iOS/macOS 27 oder neuer, die unterstützte Verfügbarkeit von Apple Intelligence und Apples verwaltete Entwicklerberechtigung erforderlich. Eine in den Einstellungen angezeigte Option belegt weder die Erteilung dieser Berechtigung noch die Nutzbarkeit des Dienstes. Apples Verarbeitung richtet sich nach den [Informationen zu Private Cloud Compute](https://security.apple.com/private-cloud-compute/) und den geltenden Richtlinien.

Eine Änderung der Zusammenfassungsverarbeitung ändert nicht die Dienste für Spracherkennung, Live-Hinweise oder Wissensantworten auf dem Gerät. Zurückgegebener Text durchläuft weiterhin die Quellenprüfungen von Di41og und kann unvollständig oder falsch sein.

### Optionales Computeraudio auf dem Mac

Mit Apples Systemauswahl lässt dich die separate Mac-Begleitapp einen Bildschirm oder eine Anwendung wählen. Auswahl und Kopplung bereiten die Quelle vor; die Erfassung beginnt erst, nachdem die gekoppelte Hauptapp deine Zustimmungsbestätigung und einen ausdrücklichen Start oder ein ausdrückliches Fortsetzen erhalten hat.

Die Begleitapp sendet ausgewählte Systemaudio-Puffer über eine authentifizierte Verbindung an der Loopback-Schnittstelle desselben Macs zur Transkription und Sprecheranalyse auf dem Gerät. Sie verwendet kein Mikrofon, erstellt keine Audiodatei und sendet diesen Stream nicht an ein Netzwerkmodell. Di41og speichert das daraus entstehende Transkript und den abgeleiteten Gesprächsdatensatz. Wenn du eine alternative Verarbeitung abschließender Zusammenfassungen oder die Ordnersynchronisierung aktiviert hast, kann dieser entstandene Text später den jeweiligen separaten Einstellungen folgen.

Pause, Stopp, Trennung oder ein Wechsel der Quelle beendet den Erfassungsstream. Die Kopplung bleibt für einen neuen authentifizierten Start oder ein Fortsetzen verfügbar, bis du entkoppelst, die Quelle wechselst oder die Begleitapp beendest. Der Kopplungsschlüssel bleibt im Arbeitsspeicher, sofern du seinen Link nicht kopierst. Das Betriebssystem steuert die Berechtigung zur Bildschirm- und Systemaudioaufnahme sowie deren Aufnahmeanzeige.

### Lokales Wissen und Antwortunterstützung

Du kannst PDFs mit extrahierbarem Text sowie Text- und Markdown-Dateien importieren, einschließlich Lebenslauf- oder Projektmaterial. Di41og speichert den extrahierten Text, den Dateinamen, den Titel und Seitenverweise lokal, anstatt eine Kopie der ursprünglichen Dokumentdatei zu speichern oder fortlaufenden Zugriff auf diese Datei zu behalten. Die ursprüngliche Datei und etwaige Downloads durch einen Dateianbieter unterliegen weiterhin den Einstellungen des Quellanbieters.

Die Suche läuft lokal. Wissensantworten verwenden deine Frage und ausgewählte lokale Quellenauszüge mit einem Modell auf dem Gerät. Das Einbeziehen anderer gespeicherter Gespräche ist eine ausdrücklich wählbare Suchoption. Die Antwortunterstützung gliedert Zitate aus deinen Quellen, statt Berufserfahrung zu bestätigen oder fehlende Leistungen zu erfinden. Quellenmaterial ist Datenmaterial und keine Anweisung, jemanden zu kontaktieren oder es hochzuladen.

Importierte Wissensdokumente sind nicht Teil der verschlüsselten Gesprächssynchronisierung. Lösche ein importiertes Dokument aus der Wissensbibliothek, um seinen extrahierten Text zu entfernen. Das Löschen eines Gesprächs löscht weder die separate Bibliothek noch die ursprüngliche Datei.

### Verschlüsselte Gesprächssynchronisierung

Die Synchronisierung bleibt aus, bis du einen Ordner in „Dateien“ auswählst und einen Schlüssel konfigurierst. Synchronisiert wird manuell, wenn kein Gespräch aktiv ist. Der Ordner kann lokal sein oder von iCloud Drive oder einem anderen Dateianbieter bereitgestellt werden. Di41og betreibt keinen Synchronisierungsserver.

Vor dem Schreiben in diesen Ordner verschlüsselt Di41og Gesprächssicherungen mit AES-GCM und einem zufälligen 256-Bit-Schlüssel. Die Sicherungen enthalten vollständige Gesprächsdatensätze, einschließlich Transkripten, privaten Hinweisen, Bewertungen, Vorbereitung, Sprecheranmerkungen, Ergebnissen und Notizen. Separat importierte Wissensdateien, wiederverwendbare Produkt- und Teamprofile sowie allgemeine App-Einstellungen sind nicht enthalten. Der Ordneranbieter kann Dateinamen, Dateigrößen, Datumsangaben und seine eigenen Konto- und Netzwerkinformationen sehen; die Gesprächsinhalte sind verschlüsselt.

Der Schlüssel wird im Schlüsselbund des Geräts ohne Schlüsselbundsynchronisierung gespeichert. Du kannst einen Wiederherstellungsschlüssel ausdrücklich anzeigen oder kopieren, um ein weiteres Gerät mit demselben Ordner zu verbinden. Wer sowohl den Schlüssel als auch die verschlüsselten Sicherungen besitzt, kann die Gespräche lesen. Der Entwickler kann einen verlorenen Schlüssel nicht wiederherstellen. Für Zwischenablage, Schlüsselkopien und deinen Ordneranbieter gelten eigene Verarbeitungs- und Sicherungseinstellungen.

Die Synchronisierung kann Löschungen bei späteren Synchronisierungsvorgängen weitergeben; gleichzeitige Versionen können zur Prüfung erhalten bleiben. Das Löschen eines lokalen Gesprächs entfernt nicht sofort alle anderen Geräteversionen, Anbieterversionen oder Sicherungen. Das Deaktivieren der Synchronisierung entfernt die Verbindung dieses Geräts und den gespeicherten Synchronisierungsschlüssel, lässt die verschlüsselten Sicherungen im gewählten Ordner aber bestehen. Entferne diese Dateien und andere Kopien bei Bedarf separat.

### Kalender, Erinnerungen und Systemintegrationen

Die Kalenderverbindung ist optional. Mit deiner Erlaubnis liest Di41og Ereignisse aus den von dir gewählten Kalendern und lässt dich einzelne Termine ausschließen. Titel, Datumsangaben, Dauer und verfügbare Notizen, Orte oder URLs können Teil einer von dir erstellten Vorbereitung werden. Eine lokale Vorbereitung kann außerdem einen bearbeitbaren System-Terminentwurf mit Titel, Uhrzeit, Zweck und Agenda öffnen. Di41og speichert ihn nicht automatisch und sendet keine Einladungen; du prüfst den Entwurf und wählst „Speichern“. Dein Kalenderanbieter verarbeitet gespeicherte Ereignisse und deren Synchronisierung entsprechend seinen Einstellungen.

Optionale Vorbereitungserinnerungen verwenden lokale Mitteilungen mit allgemeinem Wortlaut und einer Gesprächskennung, ohne Gesprächstitel, Transkripte oder Hinweise. Mitteilungen erfordern eine Berechtigung und starten keine Aufnahme. App Intents/Kurzbefehle erstellen oder öffnen lokale bearbeitbare Vorbereitungen; sie erfassen kein Audio, senden keine Einladungen und kontaktieren keine Teilnehmenden. Siri und Kurzbefehle verarbeiten deinen Aufruf und die angegebenen Parameter gemäß Apples Richtlinien und Einstellungen.

Ein optionales Widget für den Home-Bildschirm enthält ausschließlich statische Vorbereitungslinks. Es zeigt keine Gesprächstitel, Kalenderereignisse, Transkripte oder Hinweise an. Kein privater Zustand gelangt in seine Zeitleiste oder einen gemeinsamen App-Container. Das Antippen eines Links öffnet Di41og; es startet keine Erfassung.

Eine optionale Live-Aktivität zeigt Aufnahme- oder Pausenstatus, verstrichene oder verbleibende Zeit, die Agendaposition und eine App-Gesprächskennung auf unterstützten Systemoberflächen an. Gesprächstitel, Teilnehmende, Transkript, Aufgaben und Hinweise werden ausgelassen. Sie verwendet keinen Push-Mitteilungsserver und ermöglicht keine Erfassung, während die App im Hintergrund ist.

### Downloads des Sprechermodells

**Stimmen unterscheiden** ist bei neuen Einstellungen standardmäßig eingeschaltet. Du kannst die Funktion vor der Erfassung ausschalten. Die Vorbereitung von Modellen bei ausgeschaltetem Mikrofon oder der Start mit aktivierter Funktion kann bei der ersten Nutzung das Modell von Hugging Face und dessen Dateiauslieferungsdiensten laden. Diese Dienste erhalten Anfragen für Modelldateien und gewöhnliche Netzwerkinformationen, etwa eine IP-Adresse, ohne Mikrofon-Audio, Transkript oder Gesprächshintergrund. Siehe die [Datenschutzrichtlinie von Hugging Face](https://huggingface.co/privacy).

Die Analyse schätzt bis zu vier Stimmen lokal. Zuordnungen stellen keine Identität fest; von dir vergebene Namen und Korrekturen für Wortbereiche gehören zum Gespräch. Di41og speichert keine akustischen Embeddings oder wiederverwendbaren Stimmabdrücke, um eine Person über mehrere Gespräche hinweg zu identifizieren.

### Optionales Nachschlagen bei Wikipedia

Die lokale Begriffserkennung stellt keine Online-Anfrage. Das Antippen eines Begriffs sendet diesen ausgewählten Begriff in einer HTTPS-Suchanfrage an die englische oder deutsche Wikipedia. Der Begriff kann selbst Gesprächsinformationen enthalten. Die Anfrage enthält weder das Transkript noch andere Quellpassagen oder Gesprächsdatensätze. Wikipedia erhält den Begriff und gewöhnliche Anfrageinformationen, einschließlich einer IP-Adresse und einer App-Anfragekennung. Das Öffnen eines Artikels ist eine separate Browser- oder App-Anfrage. Siehe die [Datenschutzrichtlinie der Wikimedia Foundation](https://foundation.wikimedia.org/wiki/Policy:Privacy_policy). Der Entwickler erhält deine Suchanfragen nicht.

### Speicherung, Sicherungen und Löschung

Lokale Gesprächsarchive, Wissenstexte und wiederverwendbare Profile verwenden vollständigen Dateischutz auf iOS/iPadOS und sind als von Gerätesicherungen ausgeschlossen markiert; auch von der App verwaltete PDF-Exportcaches sind ausgeschlossen. Einstellungen und Kopien außerhalb des von der App verwalteten Speichers folgen den System- oder Anbietereinstellungen. Synchronisierungssicherungen liegen bewusst in dem von dir gewählten Ordner und können von diesem Anbieter gesichert oder synchronisiert werden.

Abgeschlossene Gespräche bleiben standardmäßig erhalten, bis sie gelöscht werden. Die optionale Aufbewahrung von 7, 30 oder 90 Tagen entfernt abgelaufene abgeschlossene Datensätze beim Öffnen der App oder bei einer Änderung der Aufbewahrungseinstellung; Entwürfe bleiben bis zur Löschung erhalten. Lösche Gespräche einzeln oder wähle nach dem Beenden einer aktiven Sitzung **Alle Gespräche löschen**. Für Wissensdokumente und gespeicherte Produkt- und Teamprofile gibt es separate Löschfunktionen. Das Löschen eines Profils entfernt keinen Kontext, der bereits in ein Gespräch kopiert wurde.

Bei der Deinstallation gelten die Regeln des Betriebssystems und der Geräteverwaltung. Schlüsselbundeinträge und extern kopiertes Material können einen anderen Lebenszyklus haben. Deaktiviere vor der Deinstallation die Synchronisierung und nutze die jeweiligen Löschfunktionen, wenn du diese Elemente entfernen möchtest. Anbieterkopien, Sicherungen und geteilte Exporte müssen separat entfernt werden.

### Kopieren, Exporte und Support

Du bestimmst, was du kopierst, exportierst oder teilst und wohin. Notizen können personenbezogene oder vertrauliche Informationen enthalten. Zum Teilen kann eine vorübergehende geschützte PDF-Datei erstellt werden. Gewöhnliche Notizen enthalten keine privaten Live-Hinweise. Die separate Funktion **Privater Analyseexport** erfordert eine ausdrückliche Entscheidung, um ursprüngliches Transkript, private Hinweise, Vorbereitung, Belege, menschliche Prüfeinträge und Prüfungsumfang in eine JSON-Datei aufzunehmen. Er enthält kein Rohaudio und wird nicht automatisch an den Entwickler gesendet. Die empfangende App, Zwischenablage, der Dateianbieter oder Dienst verarbeitet die Kopie gemäß seinen Richtlinien. Eine Löschung in Di41og ruft eine geteilte Kopie nicht zurück.

Wenn du dem Support eine E-Mail sendest, verarbeiten der Entwickler und der E-Mail-Dienst die von dir gewählte Nachricht und ihre Anhänge, um zu antworten. Kontakt: [starktdh@arcor.de](mailto:starktdh@arcor.de). Du musst kein vollständiges Transkript senden. Entferne private Angaben aus Beispielen und veröffentliche sie nicht in öffentlichen Issues.

Die Datenschutz- und Supportseiten werden auf GitHub gehostet und unterliegen der [GitHub-Datenschutzerklärung](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement). Apple kann über seine Werkzeuge und deine Einstellungen Informationen aus App Store, TestFlight und Diagnosen bereitstellen. Di41og hat weder einen vom Entwickler betriebenen Analysedienst noch einen Absturzberichtsdienst von Drittanbietern.

### Änderungen und Kontakt

Diese Erklärung wird aktualisiert, wenn sich die Datenverarbeitung wesentlich ändert. Bei Datenschutzfragen oder Fragen zu Supportinformationen, die du gesendet hast, schreibe an [starktdh@arcor.de](mailto:starktdh@arcor.de). Informationen zu Funktionen und Datensteuerung findest du im [Di41og-Support](support.md#deutsch).
