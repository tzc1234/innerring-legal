# Privacy Policy for InnerRing

**Last Updated: May 12, 2026**

InnerRing ("we," "our," or "us") is a privacy-first 1:1 messaging app for close friends and family. This Privacy Policy explains what data we process, why we process it, how long we keep it, and what choices you have.

InnerRing does not use phone numbers, email addresses, public user search, advertising, analytics, or cross-app tracking. Accounts are accessed with a recovery key.

## 1. Information We Collect

### 1.1 Account and Profile Data

- **Account ID**: A Convex user ID used to operate your account.
- **Authentication ID**: A Clerk user ID and session ID used for sign-in and session management.
- **Recovery key credential**: Your recovery key is used as your Clerk authentication credential. We do not store your recovery key in Convex.
- **Profile information**: Your display name and optional avatar.
- **Account status**: Active, deletion pending, or deleted.

### 1.2 Messaging and Contact Data

- **Contacts**: Invite-only 1:1 contact relationships, block state, and contact metadata.
- **Invite codes**: Hashed invite codes, creation time, expiry time, and redemption metadata.
- **Encrypted messages**: Message ciphertext, encryption headers, sender/recipient relationship metadata, timestamps, edit/delete/read metadata, and reaction metadata.
- **End-to-end encryption public keys**: Public identity keys, signed prekeys, and one-time prekeys used to establish encrypted sessions.

Message contents are end-to-end encrypted. We cannot read plaintext message contents from our backend.

### 1.3 Device, Notification, and Local Data

- **Hashed device ID**: Used for session safety, account creation rate limits, and single-device session behavior. We do not send the raw iOS device identifier to our backend.
- **APNs push token**: Used to deliver push notifications if you allow notifications.
- **Local cache**: Messages, contacts, encryption state, and app data may be stored locally on your device in an encrypted local database.
- **Optional iCloud backup**: If enabled in the app, your local database backup is encrypted using recovery-key-derived material and stored in your Apple iCloud account.

## 2. How We Use Your Information

We use your information to:

- Create and authenticate your account.
- Maintain your signed-in session.
- Deliver encrypted 1:1 messages and reactions.
- Maintain invite-only contacts and block state.
- Exchange public keys required for end-to-end encryption.
- Send push notifications if you allow them.
- Enforce account security, rate limits, and abuse prevention.
- Process account deletion and data export requests.
- Maintain service reliability and required app version checks.

We do not sell personal data. We do not use your data for advertising. We do not track your behavior across other apps or websites.

## 3. Legal Bases for Processing

For users in the European Economic Area or United Kingdom, we rely on these legal bases:

- **Contract**: Account creation, authentication, contacts, invites, encrypted messaging, message sync, and E2EE key exchange are necessary to provide the app.
- **Consent or user choice**: Push notifications and optional iCloud backup are controlled by you through iOS/app settings.
- **Legitimate interests**: Security, abuse prevention, rate limits, service reliability, deletion audit records, and preserving the remaining participant's conversation history after account deletion.
- **Legal obligation**: Responding to valid privacy rights requests and complying with applicable law.

In more detail:

- Account creation uses contract because an account is required to provide the service.
- Authentication and session management use contract because they are required for secure account access.
- Messaging, contacts, invites, message sync, and E2EE key exchange use contract because they are the core app service.
- Push notifications use consent or user choice because delivery depends on iOS notification permission.
- Optional iCloud backup uses consent or user choice because you choose whether to enable it and control the backup through your Apple account.
- Abuse prevention, security, rate limits, service reliability, and app version enforcement use legitimate interests.
- Deletion request records use legal obligation and legitimate interests so we can process deletion requests and keep limited proof of handling.
- Admin deletion notification emails use legitimate interests while deletion finalization is manually processed.
- Support emails use consent or legitimate interests because you choose to contact us and we need to respond.

## 4. Where Your Data Is Stored

- **Convex**: Backend database, server functions, file/avatar storage, and real-time sync.
- **Clerk**: Authentication, recovery-key credential processing, account sessions, and Clerk user IDs.
- **Apple Push Notification service (APNs)**: Push notification delivery.
- **Resend**: Email delivery for account deletion notifications to our administrator.
- **Apple iCloud**: Optional user-controlled encrypted backup storage, if you enable iCloud backup.
- **Your device**: Encrypted local cache and encryption state.

All network communication uses HTTPS/TLS. Local data is protected by iOS security features and the app's encrypted database design.

## 5. Service Providers and International Transfers

We use trusted service providers to operate InnerRing. They process data only as needed to provide the app and related infrastructure.

- **Convex**: Processes account IDs, display names, avatar references, invite metadata, contacts, encrypted messages, message metadata, hashed device IDs, push tokens, public E2EE keys, deletion request records, and backend storage data. Purpose: backend database, server functions, avatar/file storage, real-time sync, and service reliability. The production Convex database is located in Ireland. Reference: [Convex Privacy Policy](https://www.convex.dev/legal/privacy), [Convex Data Processing Agreement](https://www.convex.dev/legal/dpa), and [Convex Subprocessors](https://www.convex.dev/legal/subprocessors).
- **Clerk**: Processes authentication credentials, Clerk user IDs, session IDs, and authentication metadata. Purpose: account authentication and session management. Reference: [Clerk Privacy Policy](https://clerk.com/legal/privacy), [Clerk Data Processing Addendum](https://clerk.com/legal/dpa), and [Clerk Subprocessors](https://clerk.com/legal/subprocessors).
- **Resend**: Processes account deletion notification email content sent to our administrator, currently limited to user ID and request timestamp. Purpose: operational notification so deletion requests can be processed. Reference: [Resend Privacy Policy](https://resend.com/legal/privacy-policy), [Resend Data Processing Addendum](https://resend.com/legal/dpa), and [Resend Subprocessors](https://resend.com/legal/subprocessors).
- **Apple/APNs**: Processes push tokens and notification delivery data. Purpose: push notification delivery when you allow notifications. Reference: [Apple Privacy Policy](https://www.apple.com/legal/privacy/).
- **Apple iCloud**: Processes optional encrypted backup files if you enable iCloud backup. Purpose: user-controlled backup and restore. Reference: [Apple Privacy Policy](https://www.apple.com/legal/privacy/) and [iCloud Terms of Service](https://www.apple.com/legal/internet-services/icloud/).

These providers may process data in countries outside your country of residence. Where required, we rely on Data Processing Agreements, Standard Contractual Clauses, the EU-U.S. Data Privacy Framework, or equivalent safeguards provided by these services. Provider backup and retention behavior is governed by their service terms and data processing terms.

## 6. Data Sharing and Disclosure

We share data only as needed to provide the service:

- **Message recipients**: People you choose to contact can receive your encrypted messages and see your profile information needed for the conversation.
- **Service providers**: Convex, Clerk, Resend, Apple/APNs, and Apple iCloud as described above.
- **Legal requirements**: If required by law, court order, or valid governmental request.

We do not share plaintext message content because message contents are end-to-end encrypted and unavailable to us on the backend.

## 7. Your Rights and Choices

Depending on where you live, you may have rights to access, export, correct, delete, restrict, or object to processing of your personal data.

Because InnerRing does not collect email addresses or phone numbers, identity-sensitive requests must be made from within the app while signed in. We cannot safely verify account ownership through email support alone.

### 7.1 Access and Export

InnerRing is designed to support in-app data export while signed in. Server-side exports may include account data, contact metadata, invite metadata, encrypted message records, message metadata, reaction metadata, device/session metadata, and deletion request status.

Server-side exports may include encrypted message records and metadata, but not plaintext message contents. Plaintext message history may exist only on your device and in your encrypted iCloud backup if enabled.

### 7.2 Correction

You can update your display name and avatar in the app.

### 7.3 Notifications

You can allow or disable push notifications in iOS Settings.

### 7.4 Account Deletion

You can request account deletion in the app while signed in. Deletion requests are processed within 7 days. You may cancel your deletion request in the app before it is processed.

For security, deletion requests are not accepted by unauthenticated email. If you lose your recovery key and are signed out, we may be unable to verify ownership, recover, export, or delete the account.

## 8. Data Retention

### 8.1 Active Accounts

We retain account, contact, encrypted message, message metadata, device, session, and E2EE public-key data while your account is active and the data is needed to provide the service.

### 8.2 Messages and Reactions

Encrypted messages and related metadata are retained while either conversation participant keeps the conversation. If a message is deleted, message ciphertext is cleared or removed, but minimal deletion metadata may remain to sync deletion state and preserve conversation integrity.

Message events and reaction tombstones may be retained as needed for message sync, read/edit/delete state, and Double Ratchet encryption correctness.

### 8.3 Account Deletion

When your account deletion is processed, we delete or remove access to:

- Your Clerk authentication account.
- Active sessions.
- Push notification tokens and device records, including hashed device IDs.
- Avatar storage.
- Invite codes created by you.
- E2EE signed prekeys and one-time prekeys.
- Public identity keys stored on your Convex user record.

We anonymize your profile as "Deleted User" and prevent future account access.

Because conversations involve two participants, encrypted historical messages and minimal conversation metadata may remain available to the other participant after your account deletion. We retain this limited data under our legitimate interests to preserve the other participant's conversation history and the integrity of the messaging service.

We limit the privacy impact of this retention by deleting your authentication account, sessions, push tokens, hashed device IDs, avatar, invite codes, E2EE prekeys, and public identity keys. Your profile is shown as "Deleted User," your account cannot be accessed again, and message contents remain end-to-end encrypted on the backend.

The retained conversation data may include user IDs, contact relationship IDs, timestamps, encrypted message records, message events, and read/edit/delete/reaction metadata. This retained data is pseudonymous personal data, not fully anonymous data.

### 8.4 Deletion Request Records

We retain limited deletion request records, such as user ID, request time, status, and completion time, for up to 24 months for audit, security, and legal defense purposes.

### 8.5 Backups

Backend providers may retain deleted data temporarily in disaster-recovery backups according to their own retention practices. These backups are not used to restore deleted accounts as active accounts.

Optional iCloud backups are controlled by you through your Apple iCloud account. We cannot access or delete your iCloud backup for you.

## 9. Beta and TestFlight

During beta testing and TestFlight use, we may reset or delete test data to maintain the service. Do not use beta builds for critical or sensitive communications that you cannot afford to lose.

## 10. Children's Privacy

InnerRing is not intended for children under 13. We do not knowingly collect personal data from children under 13. If you believe a child has provided personal data, contact us.

## 11. California Privacy Rights

California residents may have rights under the California Consumer Privacy Act, including the right to know, delete, correct, and opt out of sale or sharing. We do not sell personal information.

## 12. European Privacy Rights

If you are in the EEA or UK, you may have GDPR or UK GDPR rights including access, rectification, erasure, restriction, portability, objection, and withdrawal of consent where processing is based on consent.

Identity-sensitive rights requests must be initiated from within the app while signed in because we do not collect phone numbers or email addresses for account verification.

## 13. Changes to This Privacy Policy

We may update this Privacy Policy from time to time. We will update the "Last Updated" date when changes are made. Material changes may also be communicated in the app.

## 14. Contact Us

If you have questions about this Privacy Policy, contact us at:

**Email**: innerring.app@gmail.com

For account deletion and data export, use the in-app controls while signed in. Email is for general privacy questions only and is not sufficient to verify account ownership.
