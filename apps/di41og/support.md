---
layout: default
title: Di41og Support
permalink: /apps/di41og/support/
---

# Di41og Support

[English](#english) · [Deutsch](#deutsch)

## English

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

The interface is available in English and German and follows your system or per-app language preference. Conversation speech is independent of the interface language.

Automatic language selection follows English and German. Short phrases, background noise, and overlapping speech can be ambiguous. Pause a live session to choose a fixed language there, or change the default language in Settings after ending the session.

**Distinguish speakers** estimates up to four voices and is enabled by default for new settings. First use may download a model; later sessions can use its cached copy. If labels are unavailable, check the speaker status and network connection for an initial download. The labels are estimates, and you assign any names yourself.

For an incorrectly attributed passage, select the relevant word range and correct its voice label. This preserves the source words and timing; it does not identify the speaker or teach the app a cross-conversation voice identity. Review overlapping speech manually.

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

## Deutsch

**Di41og-Support**

Bei Fragen oder Feedback schreibe an [starktdh@arcor.de](mailto:starktdh@arcor.de).

Lies die [Di41og-Datenschutzerklärung](privacy.md#deutsch), um dich über lokale Speicherung und die separaten Wahlmöglichkeiten für Zusammenfassungsverarbeitung, verschlüsselte Synchronisierung, Kalenderspeicherung, Computeraudio und Teilen zu informieren.

### Erste Schritte

Erstelle ein Gespräch oder wähle **Spontanes Gespräch starten**. Vorbereitung, Vorlagen, Anzahl der Teilnehmenden und ein Zeitlimit sind optional. Bestätige vor dem Beginn die Zustimmung der Teilnehmenden und erlaube den Mikrofonzugriff, wenn du dazu aufgefordert wirst.

Lass Di41og beim Zuhören im Vordergrund. Du kannst eine Sitzung pausieren oder beenden; beim Wechsel in den Hintergrund pausiert die Erfassung. Audio von Telefongesprächen auf demselben iPhone wird nicht unterstützt.

### Verfügbarkeit der KI auf dem Gerät

Di41og erfordert iOS oder iPadOS 26 oder neuer. Live-KI-Funktionen benötigen zusätzlich Hardware mit Apple Intelligence-Unterstützung, unterstützte Systemeinstellungen und ein aktiviertes, einsatzbereites Modell. Mit **Verfügbarkeit prüfen** in den Di41og-Einstellungen siehst du den aktuellen Status.

Für die Spracherkennung gelten eigene Anforderungen an das Gerät und die installierten Sprachressourcen. Zum Laden fehlender Apple-Sprach- oder KI-Ressourcen kann eine Netzwerkverbindung erforderlich sein. Die App wechselt nicht automatisch zu einem Cloud-Anbieter. Unterstützte Transkription, manuelle Vorbereitung, lokale Dokumentensuche, Zeitmesser und transkriptbasierte Notizen lassen sich auch ohne KI auf dem Gerät weiter nutzen.

Ein KI-Hinweis ist vom Mikrofonstatus getrennt. Eine abgelehnte Analyse bedeutet für sich genommen nicht, dass das Zuhören gestoppt wurde. Prüfe die Live-Zuhöranzeige; wenn die Erfassung pausiert ist, lies die Begründung und wähle **Fortsetzen**, wenn du bereit bist.

### Sprachen und Sprecherzuordnung

Die Oberfläche ist auf Deutsch und Englisch verfügbar und folgt deiner bevorzugten System- oder App-Sprache. Die Gesprächssprache ist von der Sprache der Oberfläche unabhängig.

Die automatische Sprachauswahl berücksichtigt Englisch und Deutsch. Kurze Äußerungen, Hintergrundgeräusche und überlappende Sprache können mehrdeutig sein. Pausiere eine laufende Sitzung, um dort eine feste Sprache auszuwählen, oder ändere nach dem Beenden der Sitzung die Standardsprache in den Einstellungen.

**Stimmen unterscheiden** schätzt bis zu vier Stimmen und ist bei neuen Einstellungen standardmäßig aktiviert. Bei der ersten Nutzung kann ein Modell geladen werden; spätere Sitzungen können die zwischengespeicherte Kopie verwenden. Wenn keine Zuordnungen verfügbar sind, prüfe den Sprecherstatus und die Netzwerkverbindung für einen ersten Download. Die Zuordnungen sind Schätzungen; etwaige Namen vergibst du selbst.

Wenn eine Passage falsch zugeordnet wurde, wähle den betreffenden Wortbereich und korrigiere die Stimmenzuordnung. Dabei bleiben Quellenwortlaut und Zeitangaben erhalten. Dadurch wird die sprechende Person nicht identifiziert; die App lernt auch keine über Gespräche hinweg wiederverwendbare Stimmenidentität. Prüfe überlappende Sprache manuell.

### Verarbeitung von Zusammenfassungen und Prüfungsumfang

Abschließende Zusammenfassungen nutzen standardmäßig Apples Modell auf dem Gerät. Prüfe Darstellungen einzelner Arbeitsstränge und ihre Originalzitate; Hinweise auf einen unvollständigen Prüfungsumfang bedeuten, dass im Entwurf Abschnitte oder Zusammenhänge fehlen können. Eine Quellenangabe schafft Nachvollziehbarkeit und belegt weder eine Einigung noch ein vollständiges Protokoll. Bearbeite die Notizen und prüfe den ursprünglichen Gesprächswortlaut, bevor du dich darauf verlässt.

In den Einstellungen kannst du ausdrücklich einen Ollama-Server und ein Modell für abschließende Zusammenfassungen wählen und freigeben. Diese Auswahl sendet begrenzten Transkript- und Ausgangstext, den Gesprächstitel, Kapitelmetadaten und mit Belegen verknüpfte Zielanker an diesen Prozessor, wenn du später ein Gespräch beendest oder eine neue Zusammenfassung anforderst. Spracherkennung auf dem Gerät, Live-Hinweise und lokale Wissensantworten ändern sich dadurch nicht. Kehre zur Option auf dem Gerät zurück oder deaktiviere die Erlaubnis, um spätere Anfragen an alternative Zusammenfassungsprozessoren zu stoppen.

Prüfe bei Ollama die genaue Serveradresse, das installierte Modell und die Regeln für Verarbeitung und Aufbewahrung. Die Modellprüfung kontaktiert diesen Server, ohne Gesprächstext zu senden. Die Integration von Private Cloud Compute ist vorbereitet, aber im aktuellen Build deaktiviert; ihre Freigabe ist gesperrt. Sie erfordert Apples verwaltete Entwicklerberechtigung, einen konfigurierten neuen Build und iOS/macOS 27 oder neuer. Eine in den Einstellungen angezeigte Option ist weder ein nutzbarer Dienst noch ein Nachweis für eine genehmigte Berechtigung. Es gibt keinen automatischen erneuten Versuch über einen anderen Anbieter.

Bewertungen von Hinweisen als „Hilfreich“ oder „Nicht hilfreich“ bleiben lokal beim jeweiligen Gespräch. Optionales Lernen verändert die Einstellungen für Hinweise; beim Ausschalten bleibt der Verlauf erhalten. Bewertungen und private Hinweise sind enthalten, wenn du später vollständige Gespräche synchronisierst.

### Wissensbibliothek und Unterstützung mit Lebenslaufmaterial

Importiere ein PDF mit auswählbarem Text oder eine Text- oder Markdown-Datei. Suche und Antworten mit Quellenangaben verwenden lokal extrahierten Text. Ein gescanntes PDF ohne extrahierbaren Text benötigt zuerst eine Texterkennung an anderer Stelle. Verschlüsselte, passwortgeschützte oder zu große Dokumente können abgelehnt werden. Der Import unterstützt je Dokument bis zu 10 MB, 300 PDF-Seiten und 500.000 extrahierte Zeichen.

Wähle aus, welche Dokumente verwendet werden, und aktiviere **Andere gespeicherte Gespräche einbeziehen** nur, wenn du dies möchtest. Die Antwortunterstützung für Lebenslauf- und Projektmaterial liefert Quellenzitate statt erfundener Erfahrungen. Wenn Apple Intelligence nicht verfügbar ist oder die Anfrage ablehnt, kannst du weiterhin lokale Suchtreffer lesen. Das Entfernen eines importierten Eintrags löscht seinen extrahierten Bibliothekstext, nicht die ursprüngliche Datei. Wissensdokumente sind von der Gesprächssynchronisierung getrennt.

### Kalender, Erinnerungen und Sperrbildschirm

Verbinde Kalender nur bei Bedarf, wähle die einzubeziehenden Kalender aus und schließe einzelne Termine aus. Um eine Vorbereitung als Termin anzulegen, öffne ihren System-Terminentwurf, prüfe Titel, Uhrzeit, Zweck und Agenda und wähle anschließend „Speichern“. Es wird keine Einladung automatisch versendet. Dein Kalenderdienst kann gespeicherte Ereignisse synchronisieren.

Vorbereitungserinnerungen erfordern deine ausdrückliche Mitteilungsberechtigung und verwenden allgemeinen Text. Kurzbefehle und App Intents können eine bearbeitbare Vorbereitung erstellen oder öffnen; sie starten kein Zuhören. Optionale Live-Aktivitäten zeigen Aufnahmestatus, Zeitmesser und Agendaposition ohne Titel, Transkript, Aufgaben oder Hinweise. Sie halten keine Aufnahme aufrecht, während Di41og im Hintergrund ist.

### Vorbereitungswidget für den Home-Bildschirm

Das optionale Widget bietet statische Links für eine neue Vorbereitung oder den bevorstehenden Entwurf. Es öffnet Di41og, ohne eine Erfassung zu starten, und zeigt keine privaten Gesprächs- oder Kalenderinhalte an. Es hält keine privaten Daten in einem gemeinsamen Widget-Container vor.

### Verschlüsselte Gesprächssynchronisierung

Wähle in den Synchronisierungseinstellungen einen Ordner in „Dateien“, sichere seinen Wiederherstellungsschlüssel und verbinde das andere Gerät mit demselben Ordner und Schlüssel. Synchronisiere manuell, nachdem du das aktive Gespräch beendet hast. Die Ordnersynchronisierung enthält vollständige Gesprächsdatensätze, einschließlich privater Hinweise und Bewertungen; importierte Wissensdokumente und wiederverwendbare Profile bleiben getrennt.

Wenn der Ordner bereits verschlüsselte Datensätze enthält, verwende seinen bestehenden Wiederherstellungsschlüssel. Der Entwickler kann einen verlorenen Schlüssel nicht wiederherstellen. Konflikte des Dateianbieters oder gleichzeitige Änderungen müssen geprüft werden; verwirf die Kopie eines anderen Geräts nicht nur, um eine Fehlermeldung zu beseitigen. Das Deaktivieren der Synchronisierung lässt die verschlüsselten Sicherungen im gewählten Ordner bestehen. Entferne Anbieterdateien, Kopien auf anderen Geräten und Sicherungen bei Bedarf separat.

### Computeraudio auf einem Mac

Die iPad-App auf einem kompatiblen Mac mit Apple Chip kann sich mit der separat installierten Di41og-Mac-Audiobegleitapp unter macOS 26 oder neuer koppeln. Wähle in der Systemauswahl der Begleitapp einen Bildschirm oder eine App, erstelle eine Kopplung und wähle **Di41og zum Koppeln öffnen**. Bestätige in Di41og die Zustimmung der Teilnehmenden und starte das Gespräch ausdrücklich. Die Begleitapp verwendet ausgewähltes Systemaudio statt des Mikrofons und erstellt keine Audiodatei.

Bei Pause, Trennung, Quellenwechsel, Entkopplung oder Beenden stoppt die Erfassung. Dieselbe vorbereitete Kopplung unterstützt ein ausdrückliches Fortsetzen; das bloße Wiederverbinden startet kein Audio. **Stoppen und entkoppeln** macht die Kopplung ungültig. Wenn die Quelle ausfällt, prüfe die macOS-Berechtigung für Bildschirm- und Systemaudioaufnahme und erstelle bei Bedarf eine neue Kopplung. Die Begleitapp umgeht keine geschützten Quellen und zeichnet kein Audio von Telefongesprächen auf dem iPhone auf.

### Themen, Vorlagen und Online-Begriffe

KI-Themen und Vorlagenvorschläge sind Interpretationen. Öffne ihre belegenden Transkriptzitate und entscheide, ob der Vorschlag hilfreich ist. Das Annehmen einer Live-Vorlage erhält deine vorhandenen Ziele, die Agenda und den aktuellen Zeitmesser. Empfehlungen zur Dauer verwenden die optionale Anzahl der Teilnehmenden, die du angibst.

Die Begriffserkennung läuft lokal. Eine Online-Suche bei Wikipedia beginnt erst, wenn du einen Begriff antippst. Offline kann das Nachschlagen nicht verfügbar sein, während andere Funktionen auf dem Gerät mit installierten Ressourcen weiterarbeiten.

### Deine Daten verwalten

Prüfe die Aufbewahrungseinstellung unter **Deine Daten, deine Kontrolle**. Du kannst Gespräche einzeln löschen oder die aktive Sitzung beenden und **Alle Gespräche löschen** wählen. Für gespeicherte Produkt- und Teamprofile sowie importierte Wissensdokumente gibt es separate Funktionen. Eine lokale Löschung ruft keine Exporte zurück und entfernt nicht sofort jede synchronisierte Kopie bei einem Anbieter oder auf einem Gerät. Deaktiviere die Synchronisierung vor der Deinstallation, wenn du ihren Geräteschlüssel und ihre Konfiguration entfernen möchtest; entferne geteilte Dateien und externe Kopien an ihren jeweiligen Speicherorten.

### Bevor du den Support kontaktierst

Bitte gib Folgendes an:

- Die Di41og-Version und den Build, falls verfügbar.
- Dein Gerätemodell und die Betriebssystemversion.
- Eine kurze Beschreibung des Problems und die Schritte, mit denen es sich reproduzieren lässt.
- Ob das Problem Erfassung, Transkription, Stimmenkorrekturen, KI auf dem Gerät, einen ausdrücklich aktivierten Zusammenfassungsprozessor, Wissen, Synchronisierung, Kalender oder Teilen betrifft. Lass bei Synchronisierungs- oder Modellproblemen Wiederherstellungsschlüssel, Kopplungsschlüssel, Zugangsdaten und private Serverangaben weg.
- Den betreffenden Status- oder Fehlerwortlaut, nachdem private Angaben entfernt wurden.

Du musst kein vollständiges Transkript und keine Aufnahme senden, um ein Problem zu melden. Entferne persönliche Namen, vertrauliche Gesprächsinhalte, Unternehmensangaben und andere private Informationen aus Bildschirmfotos oder Beispielen. Veröffentliche dieses Material nicht in öffentlichen GitHub-Issues oder Kommentaren.

[Zurück zu Di41og](index.md#deutsch)
