---
layout: default
title: KVMHub Privacy Policy
permalink: /apps/kvmhub/privacy/
---

# KVMHub Privacy Policy

Effective date: October 5, 2026

KVMHub is a local-network keyboard and pointer sharing app. This policy
describes the information handled by KVMHub.

## Data collection

The developer does not collect, receive, sell, rent, or use personal data from
KVMHub. The app has no developer-operated backend, account system, advertising,
analytics SDK, or tracking technology.

## Information stored locally

On macOS, KVMHub stores app preferences and display arrangements locally. It
stores its installation identity, cryptographic private key, and the public
identities of computers you approve in the macOS Keychain.

The shared receive-only Windows and Linux packages also store their display
name, installation identity, private signing key, trusted-controller
information, pairing date, and stable display identifiers locally. Windows
protects the private identity with Windows Data Protection API. Linux stores
the receiver configuration in a user-only file. These packages do not upload
their configuration to the developer or a cloud service.

## Information shared on your local network

KVMHub advertises and discovers peers with Bonjour on your local network.
Before pairing, nearby devices on the same local network can see the advertised
device name, installation identity, protocol version, and capability
information needed for discovery.

Pairing requires matching a six-digit code on both computers. After pairing,
KVMHub exchanges display layout, role and session status, and the keyboard,
pointer, button, and scroll events needed for active control over an
authenticated and encrypted connection directly between the approved
computers.

KVMHub does not send this information to the developer or to a cloud service.
Keyboard and pointer events are used to perform the requested live control and
are not recorded by KVMHub.

## macOS permissions

Depending on the role you enable, KVMHub may request Local Network,
Accessibility, and Input Monitoring access. These permissions are used only to
discover approved peers and to capture or deliver the keyboard and pointer
events needed for remote control.

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
