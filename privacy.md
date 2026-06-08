# Privacy Policy for InnerRing

**Last Updated: June 8, 2026**

InnerRing ("we," "our," or "us") is a privacy-first 1:1 messaging app for close friends and family. This Privacy Policy explains what data we process, why we process it, how long we keep it, and what choices you have.

InnerRing does not use phone numbers, email addresses for account identity, public user search, advertising, analytics, or cross-app tracking. Accounts are accessed with a recovery key.

## 1. Information We Collect

### 1.1 Account and Profile Data

- **Account ID**: A Convex user ID used to operate your account.
- **Authentication ID**: A Clerk user ID and session ID used for sign-in and session management.
- **Recovery key credential**: Your recovery key is used as your Clerk authentication credential. We do not store your recovery key in Convex.
- **Profile information**: Your display name and selected app-owned avatar background color value. The app derives an initial icon locally from your display name; it does not upload profile photos.
- **Display-name audit records**: Previous and new display names, change reason, and actor type, used for compliance, safety review, and account-deletion records. Profile-name safety reports may reference the relevant display-name audit record.
- **Account status**: Active, deletion pending, or deleted.

### 1.2 Messaging and Contact Data

- **Contacts**: Invite-only 1:1 contact relationships, block state, and contact metadata.
- **Invite codes**: Hashed invite codes, creation time, expiry time, and redemption metadata.
- **Encrypted messages**: Message ciphertext, encryption headers, sender/recipient relationship metadata, timestamps, edit/delete/read metadata, and reaction metadata.
- **Message audit records**: Ciphertext and encryption metadata for message send, edit, and delete events, used for message sync, safety review, and record keeping.
- **Safety report records**: Report category, report metadata, optional additional information, UK/US link declaration where relevant, reviewed disposition fields, and references to the reported message or display-name audit record.
- **End-to-end encryption public keys**: Public identity keys, signed prekeys, and one-time prekeys used to establish encrypted sessions.

Message contents are end-to-end encrypted. We cannot read plaintext message contents from our backend.

### 1.3 Device, Notification, and Local Data

- **Hashed device ID**: Used for session safety, account creation rate limits, and single-device session behavior. We do not send the raw iOS device identifier to our backend.
- **APNs push token**: Used to deliver push notifications if you allow notifications.
- **Local cache**: Messages, contacts, encryption state, and app data may be stored locally on your device in an encrypted local database.
- **Optional iCloud backup**: If enabled in the app, your local database backup is encrypted using recovery-key-derived material and stored in your Apple iCloud account.

### 1.4 Subscription Data

- **Subscription identifiers and status**: Product ID, original transaction ID, latest transaction ID, App Store environment, subscription status, expiry/revocation dates, and Apple verification timestamp.
- **Entitlement records**: Backend records used to decide whether contacts, invites, and messaging are unlocked.

We do not receive or store your full payment card details. App Store purchases, billing, refunds, and payment processing are handled by Apple.

## 2. How We Use Your Information

We use your information to:

- Create and authenticate your account.
- Maintain your signed-in session.
- Deliver encrypted 1:1 messages and reactions.
- Maintain invite-only contacts and block state.
- Exchange public keys required for end-to-end encryption.
- Send push notifications if you allow them.
- Enforce account security, rate limits, and abuse prevention.
- Keep display-name audit records for compliance, safety review, and account-deletion records.
- Receive, review, and retain safety reports and related audit records.
- Reset verified abusive display names and apply account restrictions where justified or required.
- Process account deletion and data export requests.
- Verify subscription entitlements and gate contacts, invites, and messaging.
- Maintain service reliability and required app version checks.

We do not sell personal data. We do not use your data for advertising. We do not track your behavior across other apps or websites.

## 3. Legal Bases for Processing

For users in the European Economic Area or United Kingdom, we rely on these legal bases:

- **Contract**: Account creation, authentication, contacts, invites, encrypted messaging, message sync, and E2EE key exchange are necessary to provide the app.
- **Consent or user choice**: Push notifications and optional iCloud backup are controlled by you through iOS/app settings.
- **Legitimate interests**: Security, abuse prevention, rate limits, service reliability, safety reporting, account restrictions, deletion and display-name audit records, and preserving the remaining participant's conversation history after account deletion.
- **Legal obligation**: Responding to valid privacy rights requests, retaining legally required safety records, and complying with applicable law.

In more detail:

- Account creation uses contract because an account is required to provide the service.
- Authentication and session management use contract because they are required for secure account access.
- Messaging, contacts, invites, message sync, and E2EE key exchange use contract because they are the core app service.
- Push notifications use consent or user choice because delivery depends on iOS notification permission.
- Optional iCloud backup uses consent or user choice because you choose whether to enable it and control the backup through your Apple account.
- Abuse prevention, security, rate limits, service reliability, safety reporting, display-name audit records, account restrictions, and app version enforcement use legitimate interests.
- Authority escalation, mandatory reporting, and legally required retention use legal obligation where applicable.
- Deletion request records use legal obligation and legitimate interests so we can process deletion requests and keep limited proof of handling.
- Admin deletion notification emails use legitimate interests while deletion finalization is manually processed.
- Support emails use consent or legitimate interests because you choose to contact us and we need to respond.

## 4. Where Your Data Is Stored

- **Convex**: Backend database, server functions, and real-time sync.
- **Clerk**: Authentication, recovery-key credential processing, account sessions, and Clerk user IDs.
- **Apple Push Notification service (APNs)**: Push notification delivery.
- **Apple App Store**: Subscription purchases, subscription entitlement verification, renewal/cancellation/refund status, and App Store Server Notifications.
- **Resend**: Email delivery for account deletion notifications to our administrator.
- **Apple iCloud**: Optional user-controlled encrypted backup storage, if you enable iCloud backup.
- **Your device**: Encrypted local cache and encryption state.

All network communication uses HTTPS/TLS. Local data is protected by iOS security features and the app's encrypted database design.

## 5. Service Providers and International Transfers

We use trusted service providers to operate InnerRing. They process data only as needed to provide the app and related infrastructure.

- **Convex**: Processes account IDs, display names, display-name audit records, selected app-owned avatar color values, invite metadata, contacts, encrypted messages, message metadata, message audit records, safety report records, hashed device IDs, push tokens, public E2EE keys, and deletion request records. Purpose: backend database, server functions, real-time sync, service reliability, safety review, and abuse prevention. The production Convex database is located in Ireland. Reference: [Convex Privacy Policy](https://www.convex.dev/legal/privacy), [Convex Data Processing Agreement](https://www.convex.dev/legal/dpa), and [Convex Subprocessors](https://www.convex.dev/legal/subprocessors).
- **Clerk**: Processes authentication credentials, Clerk user IDs, session IDs, and authentication metadata. Purpose: account authentication and session management. Reference: [Clerk Privacy Policy](https://clerk.com/legal/privacy), [Clerk Data Processing Addendum](https://clerk.com/legal/dpa), and [Clerk Subprocessors](https://clerk.com/legal/subprocessors).
- **Resend**: Processes account deletion notification email content sent to our administrator, currently limited to user ID and request timestamp. Purpose: operational notification so deletion requests can be processed. Reference: [Resend Privacy Policy](https://resend.com/legal/privacy-policy), [Resend Data Processing Addendum](https://resend.com/legal/dpa), and [Resend Subprocessors](https://resend.com/legal/subprocessors).
- **Apple/APNs**: Processes push tokens and notification delivery data. Purpose: push notification delivery when you allow notifications. Reference: [Apple Privacy Policy](https://www.apple.com/legal/privacy/).
- **Apple App Store**: Processes purchase and subscription transaction data. Purpose: App Store billing, subscription management, refunds, entitlement verification, and subscription status notifications. Reference: [Apple Privacy Policy](https://www.apple.com/legal/privacy/) and [Apple Media Services Terms and Conditions](https://www.apple.com/legal/internet-services/itunes/).
- **Apple iCloud**: Processes optional encrypted backup files if you enable iCloud backup. Purpose: user-controlled backup and restore. Reference: [Apple Privacy Policy](https://www.apple.com/legal/privacy/) and [iCloud Terms of Service](https://www.apple.com/legal/internet-services/icloud/).

These providers may process data in countries outside your country of residence. Where required, we rely on Data Processing Agreements, Standard Contractual Clauses, the EU-U.S. Data Privacy Framework, or equivalent safeguards provided by these services. Provider backup and retention behavior is governed by their service terms and data processing terms.

## 6. Data Sharing and Disclosure

We share data only as needed to provide the service:

- **Message recipients**: People you choose to contact can receive your encrypted messages and see your profile information needed for the conversation.
- **Service providers**: Convex, Clerk, Resend, Apple/APNs, and Apple iCloud as described above.
- **Apple App Store**: Subscription purchase and entitlement information as described above.
- **Authorities or legal recipients**: Information may be disclosed if required by law, court order, competent authority request, or mandatory safety-reporting obligation.
- **Legal requirements**: If required by law, court order, or valid governmental request.

We do not routinely share plaintext message content because message contents are end-to-end encrypted and unavailable to us on the backend. If you submit a message report, the reported message content and report information you voluntarily provide may be reviewed and disclosed where legally required.

## 7. Your Rights and Choices

Depending on where you live, you may have rights to access, export, correct, delete, restrict, or object to processing of your personal data.

Because InnerRing does not use email addresses or phone numbers for account identity, identity-sensitive requests must be made from within the app while signed in. We cannot safely verify account ownership through email support alone.

### 7.1 Access and Export

InnerRing is designed to support in-app data export while signed in. Server-side exports may include account data, device/session metadata, subscription identifiers and entitlement status, contact and conversation metadata, invite metadata, message metadata, reaction metadata, E2EE public-key metadata, and deletion request status.

Server-side exports do not include plaintext message contents because we cannot decrypt ordinary messages. Standard server-side exports also exclude raw ciphertext, encryption headers, X3DH headers, encryption session IDs, and sealed safety-report context because these are technical cryptographic records or internal safety/legal records rather than ordinary account export data. Plaintext message history may exist only on your device and in your encrypted iCloud backup if enabled. If you voluntarily submit a message report, the reported content is handled as sealed safety-report context and is not included in ordinary export files.

### 7.2 Correction

You can update your display name and select a different app-owned avatar background color in the app.

### 7.3 Notifications

You can allow or disable push notifications in iOS Settings.

### 7.4 Account Deletion

You can request account deletion in the app while signed in. Deletion requests are processed within 7 days. You may cancel your deletion request in the app before it is processed.

For security, deletion requests are not accepted by unauthenticated email. If you lose your recovery key and are signed out, we may be unable to verify ownership, recover, export, or delete the account.

## 8. Data Retention

### 8.1 Active Accounts

We retain account, contact, encrypted message, message metadata, device, session, subscription entitlement, and E2EE public-key data while your account is active and the data is needed to provide the service.

### 8.2 Messages and Reactions

Encrypted messages and related metadata are retained while either conversation participant keeps the conversation. If a message is deleted for everyone, the message may be hidden from the chat view while backend message rows, metadata, ciphertext, and audit records are retained as needed for delivery, sync, security, safety review, legal compliance, and record keeping.

Message events and reaction tombstones may be retained as needed for message sync, read/edit/delete state, and Double Ratchet encryption correctness.

### 8.3 Account Deletion

When your account deletion is processed, we delete or remove access to:

- Your Clerk authentication account.
- Active sessions.
- Push notification tokens and device records, including hashed device IDs.
- Invite codes created by you.
- E2EE signed prekeys and one-time prekeys.
- Public identity keys stored on your Convex user record.

We anonymize your profile as "DELETED USER" and prevent future account access.

Because conversations involve two participants, encrypted historical messages and minimal conversation metadata may remain available to the other participant after your account deletion. We retain this limited data under our legitimate interests to preserve the other participant's conversation history and the integrity of the messaging service.

We limit the privacy impact of this retention by deleting your authentication account, sessions, push tokens, hashed device IDs, invite codes, E2EE prekeys, and public identity keys. Your profile is shown as "DELETED USER" with the default app-owned avatar color, your account cannot be accessed again, and message contents remain end-to-end encrypted on the backend.

The retained conversation data may include user IDs, contact relationship IDs, timestamps, encrypted message records, message events, and read/edit/delete/reaction metadata. This retained data is pseudonymous personal data, not fully anonymous data.

Safety reports, authority-escalated records, display-name audit records, message audit records, and related retention-held records may be retained after account deletion where needed for safety review, legal compliance, abuse prevention, mandatory reporting, or record keeping.

### 8.4 Subscription Entitlement Records

We retain Apple-verified subscription entitlement records after account deletion as needed to verify purchases and refunds, handle billing disputes, prevent fraud, and maintain accounting and audit records. These records may include your deleted-user account ID, product ID, App Store transaction identifiers, subscription environment, entitlement status, expiry or revocation dates, and verification timestamps.

### 8.5 Deletion Request Records

We retain limited deletion request records, such as user ID, request time, status, and completion time, for up to 24 months for audit, security, and legal defense purposes.

### 8.6 Display-Name Audit Records

We retain display-name audit records for 1 year by default. If a safety report references a display-name audit record and the safety report has a longer retention period, we may retain the display-name audit record for the same period as that safety report.

### 8.7 Safety Report and Message Audit Records

Closed safety reports are retained for 1 year by default. Authority-escalated reports may be retained for longer where required by law, safeguarding obligations, competent-authority instructions, or internal safety retention policy. Message audit records and display-name audit records linked to safety reports may be retained for the same period as the related safety report.

### 8.8 Backups

Backend providers may retain deleted data temporarily in disaster-recovery backups according to their own retention practices. These backups are not used to restore deleted accounts as active accounts.

Optional iCloud backups are controlled by you through your Apple iCloud account. We cannot access or delete your iCloud backup for you.

## 9. Beta and TestFlight

During beta testing and TestFlight use, we may reset or delete test data to maintain the service. Do not use beta builds for critical or sensitive communications that you cannot afford to lose.

## 10. Children's Privacy

InnerRing is not intended for children under 13. We do not knowingly collect personal data from children under 13. If you believe a child has provided personal data, contact us.

## 11. California Privacy Rights

California residents may have rights under the California Consumer Privacy Act, including the right to know, delete, correct, and opt out of sale or sharing. We do not sell personal information.

We do not share personal information for cross-context behavioral advertising, and we do not use advertising, analytics, or cross-app tracking.

## 12. European Privacy Rights

If you are in the EEA or UK, you may have GDPR or UK GDPR rights including access, rectification, erasure, restriction, portability, objection, and withdrawal of consent where processing is based on consent.

Identity-sensitive rights requests must be initiated from within the app while signed in because we do not collect phone numbers or email addresses for account verification.

## 13. Changes to This Privacy Policy

We may update this Privacy Policy from time to time. We will update the "Last Updated" date when changes are made. Material changes may also be communicated in the app.

## 14. Contact Us

If you have questions about this Privacy Policy, contact us at:

**Email**: [innerring.app@gmail.com](mailto:innerring.app@gmail.com)

For account deletion and data export, use the in-app controls while signed in. Email is for general privacy questions only and is not sufficient to verify account ownership.
