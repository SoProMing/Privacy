---
layout: default
title: KVMHub Privacy Policy
permalink: /apps/kvmhub/privacy/
---

# KVMHub Privacy Policy

Effective date: October 21, 2026

KVMHub is a local-network keyboard and pointer sharing app. The Mac App Store
edition is a controller: it can control separately installed, receive-only
KVMHub software on another computer, but it cannot receive remote input. This
policy describes the information handled by the controller and those receiver
packages.

## Data collection

The developer does not collect, receive, sell, rent, or use personal data from
the KVMHub app or receiver software. They have no developer-operated backend,
account system, advertising, analytics SDK, or tracking technology.

KVMHub's **Get Receivers** button opens
[the public receiver page](https://www8.2hands.de/kvmhub/) in the user's web
browser. The app does not download, install, launch, execute, or update the
receiver packages. As with an ordinary website visit, the website and its
hosting provider may process standard web-request information such as the IP
address, date and time, requested file, and browser user agent under the
website's privacy terms. This web-request information is not keyboard or
pointer input and is not sent by the KVMHub app itself.

## Information stored locally

On macOS, KVMHub stores app preferences and display arrangements locally. It
stores its installation identity, cryptographic private key, and the public
identities of receiver computers you approve in the macOS Keychain.

The shared receive-only Windows and Linux packages also store their display
name, installation identity, private signing key, trusted-controller
information, pairing date, and stable display identifiers locally. Windows
protects the private identity with Windows Data Protection API. Linux stores
the receiver configuration in a user-only file. These packages do not upload
their configuration to the developer or a cloud service.

## Information shared on your local network

KVMHub and its receivers use Bonjour on your local network for discovery.
Before pairing, participating devices on the same local network can see the
advertised device name, installation identity, protocol version, and
capability information needed for discovery.

Pairing requires matching a six-digit code on both computers. After pairing,
KVMHub exchanges display layout, role and session status, and the keyboard,
pointer, button, and scroll events needed for active control over an
authenticated and encrypted connection directly between the approved
computers. Plain-text clipboard sharing is enabled by default for newly paired
computers, can be disabled for an individual peer, and exchanges content only
while that computer is actively under control and both endpoints allow it. It
is limited to the active paired computer and does not include images or files.
Known concealed and transient clipboard items are skipped where the operating
system exposes that information.

KVMHub does not send this information to the developer or to a cloud service.
Keyboard and pointer events are used to perform the requested live control and
are not recorded by KVMHub. Clipboard contents are held only long enough to
transfer them directly, are not logged or persisted by KVMHub, and remain in
the operating system clipboard after the session just like a local copy.

## Permissions

The Mac App Store controller requests Local Network access to discover and
connect to receivers, and Input Monitoring to observe the keyboard and pointer
input that the user chooses to forward. Its Core Graphics event tap is passive
and listen-only: it always returns each observed system event unchanged. During
active remote control, app-owned input-capture surfaces come to the foreground,
receive ordinary input locally, and show an always-visible remote-control
status on the active screen while the observed events are forwarded to the
receiver. For the duration of that session, KVMHub temporarily enables the
public AppKit `autoHideDock` and `disableProcessSwitching` presentation options
and restores the app's exact previous presentation options when control ends.
This is a best-effort measure for application switching, not a promise that
macOS-reserved or global shortcuts can be redirected. The App Store controller
does not request Accessibility access, inspect other apps' interface content,
post synthetic input, or accept remote input on the Mac on which it is
installed.

The separately installed receiver needs platform-specific permission to apply
input locally. The macOS receiver requests Accessibility access solely to
apply received input on that receiver Mac. Windows may show its standard
network-access prompt, and Linux receiver setup may require access to the
system's input-injection interface. The separately distributed, bidirectional
Developer ID edition also uses Accessibility for its full input-routing and
receive-control features. These permissions are not requested by the Mac App
Store controller and are used only for local discovery, connection, and the
requested live control.

On macOS 15.4 and later, macOS may separately ask before KVMHub reads the
General pasteboard. You can allow, ask each time, or deny that access in Privacy
& Security. Denying clipboard access disables clipboard synchronization but
does not interrupt keyboard or pointer control.

## Data retention and deletion

Preferences and saved peer information remain on the computer until you clear
them, use Forget Pairing, delete the applicable local configuration, or remove
the app. Forget Pairing removes the selected trusted peer from KVMHub. Removing
the app does not necessarily remove every item stored by macOS in the Keychain
or Privacy & Security settings, or configuration retained by a Windows or
Linux receiver; those items may need to be removed manually on that computer.

## Children

KVMHub is a general-purpose utility and is not directed to children. Because
the developer does not collect data through the app, KVMHub does not knowingly
collect personal information from children.

## Changes and contact

Material changes will be published at the privacy-policy URL shown on the
KVMHub App Store page. Questions can be sent through
[the 2hands contact page](https://www8.2hands.de/contact/).
