# KLYDE Privacy Policy

Effective date: 2026-03-07

This Privacy Policy explains what data KLYDE processes, how it is used, and for what purposes.

## 1. About the app

KLYDE is a messenger with a P2P architecture and end-to-end encryption of message content.

Contact for privacy/data questions: `klyde.app@gmail.com`.

## 2. What data we process

### 2.1 Account and identifiers

- `peerId` (user identifier derived from key material)
- `UIN` (numeric identifier for easier contact discovery)
- user public key

### 2.2 Profile data

- nickname
- avatar (if set by user)

### 2.3 Technical/service data

- device FCM token (for push/wakeup notifications)
- service/network metadata required for connection and delivery (for example signaling metadata)
- Premium status data (if applicable)

### 2.4 User content

- text messages
- media/files sent by user

Message content is encrypted client-side (end-to-end).

## 3. Why data is used

Data is used to:

- register and route users (`peerId`, `UIN`)
- establish P2P connections and deliver messages
- send push/wakeup notifications (FCM)
- display profile and contacts
- show ads in free tier (Yandex Mobile Ads)
- store/transfer large encrypted attachments via cloud storage (Backblaze B2), when applicable

## 4. Third-party services

The app may use:

- Firebase Cloud Messaging (Google) — push/wakeup
- Yandex Mobile Ads SDK — advertising
- Backblaze B2 — storage of large encrypted attachments

Each provider processes data under its own privacy terms.

## 5. Android permissions

The app may request:

- `INTERNET`, `ACCESS_NETWORK_STATE` — network and connectivity
- `POST_NOTIFICATIONS` — notifications
- `CAMERA`, `RECORD_AUDIO` — photo/video/voice features
- `ACCESS_FINE_LOCATION` / `ACCESS_COARSE_LOCATION` — location sharing (user action only)
- `FOREGROUND_SERVICE`, `WAKE_LOCK`, `RECEIVE_BOOT_COMPLETED` — stable background connectivity
- exact alarm-related permissions for delivery watchdog behavior

Permissions are used only to provide app functionality.

## 6. Storage and security

- Local data (including keys, profile, message history) is stored on user device.
- Encrypted identity backup is available and protected by user passphrase.
- Message content is intended to be transmitted in encrypted form.

Important: transport-level metadata (for example timing, interaction events, network parameters) may be processed as required for service operation.

## 7. Advertising

Free tier may display ads via Yandex Mobile Ads.

We do not sell your message content to ad networks.

## 8. Retention

Retention depends on data type and user settings:

- local history remains on device until deleted by user/app
- server-side service data is retained as needed for features (for example UIN registry, wakeup mechanisms, premium status)

## 9. User rights

Users can:

- remove the app and local data
- delete chats/contacts inside the app
- manage permissions in Android settings
- contact us by email regarding data processing questions

## 10. Children

The app is not intended for children without required parental/legal consent in jurisdictions where such consent is mandatory.

## 11. Policy updates

We may update this Privacy Policy. The current version is published at the document location and is effective from the stated date.
