# Privacy Policy for InnerRing

**Last Updated: July 16, 2026**

InnerRing ("we," "our," or "us") is a privacy-first 1:1 messaging app for close friends and family. This Privacy Policy applies to the InnerRing app and its public legal pages. It explains what data we process, why we process it, how long we keep it, and what choices you have.

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
- **Message audit records**: Ciphertext and encryption metadata for message send, edit, and delete events, used for safety review and record keeping.
- **Safety report records**: Report ID, reporter and reported-user IDs, report category, optional additional information, UK/US link declaration where relevant, timestamps, reviewed disposition fields, and references to the reported message or display-name audit record. A message report includes a plaintext snapshot of the selected received message. A profile-name report includes a snapshot of the selected display name.
- **End-to-end encryption public keys**: Public identity keys, signed prekeys, and one-time prekeys used to establish encrypted sessions.

Ordinary message contents are end-to-end encrypted, and we cannot read their plaintext from our backend. If you voluntarily submit a message report, the app sends a plaintext snapshot of that selected message to our backend for safety review. That reported snapshot is no longer protected from us by message end-to-end encryption, although it is protected in transit by HTTPS/TLS and handled as restricted safety-report data.

### 1.3 Device, Notification, and Local Data

- **Hashed device ID**: Used for session safety, account creation rate limits, and single-device session behavior. We do not send the raw iOS device identifier to our backend.
- **App integrity records**: Apple App Attest key and assertion data, including the hashed device ID, attestation public key and public-key hash, Apple attestation receipt, environment, challenges, assertion counters, and consumed token identifiers. These records are used to confirm that account and session requests come from a valid copy of InnerRing on Apple hardware and to prevent replay and automated abuse.
- **Push notification data**: An APNs push token and notification payload data. Payloads may include sender display name and avatar color, sender/contact/message IDs, and, when payload size permits, encrypted message ciphertext, an encryption header, and an encryption session ID. Push notifications do not include plaintext message bodies.
- **Local cache**: Messages, contacts, encryption state, and app data may be stored locally on your device in an encrypted local database.
- **Optional iCloud backup**: If enabled in the app, your local database backup is encrypted using recovery-key-derived material and stored in your Apple iCloud account.

### 1.4 Subscription Data

- **Subscription identifiers and status**: Product ID, original transaction ID, latest transaction ID, App Store environment, subscription status, expiry/revocation dates, and Apple verification timestamp.
- **Entitlement records**: Backend records used to decide whether contacts, invites, and messaging are unlocked.

We do not receive or store your full payment card details. App Store purchases, billing, refunds, and payment processing are handled by Apple.

### 1.5 Support, Complaint, and Legal-Page Data

- **Emails you send us**: Your email address, email metadata, and any content or attachments you choose to send when contacting support or making a safety or privacy complaint.
- **Formal-request verification records**: A verification ID, hashed verification code, issue and expiry times, and, after successful verification, the verification time and InnerRing account ID that used the code. We do not store the plaintext verification code.
- **Administrator notification emails**: Account-deletion and safety-report metadata sent to our administrator through Resend and the administrator's email provider. Safety notifications may include report and user IDs, report source and category, optional additional information, UK/US link declaration, and submission time. They do not include the reported plaintext message snapshot.
- **Legal-page technical data**: GitHub may process ordinary web-hosting data such as IP address, browser or device information, requested page, and request time when you visit our public legal pages. We do not place advertising or analytics trackers on those pages.

## 2. How We Use Your Information

We use your information to:

- Create and authenticate your account.
- Maintain your signed-in session.
- Deliver encrypted 1:1 messages and reactions.
- Maintain invite-only contacts and block state.
- Exchange public keys required for end-to-end encryption.
- Send push notifications if you allow them.
- Enforce account security, rate limits, and abuse prevention.
- Verify app and device integrity for account creation and session activation.
- Keep display-name audit records for compliance, safety review, and account-deletion records.
- Receive, review, and retain safety reports and related audit records.
- Send limited account-deletion and safety-report notifications to our administrator.
- Reset verified abusive display names and apply account restrictions where justified or required.
- Process account deletion and data export requests.
- Verify that a signed-in account controls an email-based formal request and limit incorrect-code attempts.
- Verify subscription entitlements and gate contacts, invites, and messaging.
- Maintain service reliability and required app version checks.
- Respond to support messages and safety or privacy complaints.
- Host the public legal pages.

We do not sell personal data. We do not use your data for advertising. We do not track your behavior across other apps or websites.

## 3. Legal Bases for Processing

For users in the European Economic Area or United Kingdom, we rely on these legal bases under applicable data-protection law:

- **Contract and steps requested before entering a contract**: Account creation, authentication, contacts, invites, encrypted messaging, message sync, E2EE key exchange, subscription entitlement checks, push-notification delivery you request, and optional iCloud backup you request are necessary to provide those features.
- **Legitimate interests**: Security, abuse prevention, rate limits, service reliability, safety reporting, account restrictions, audit records, administrator notifications, support and complaint handling, legal claims, and preserving the remaining participant's conversation history after account deletion. Our interests are providing a secure service, protecting users, investigating misuse, proving how requests and incidents were handled, and maintaining the integrity of shared conversations.
- **Legal obligation**: Responding to valid privacy-rights requests, making legally required safety reports or disclosures, retaining records where law requires it, and complying with binding legal process.
- **Vital interests**: In exceptional urgent-safety situations, we may process or disclose available report information where necessary to protect someone's life or physical safety.

In more detail:

- Account creation uses contract because an account is required to provide the service.
- Authentication and session management use contract because they are required for secure account access.
- Messaging, contacts, invites, message sync, and E2EE key exchange use contract because they are the core app service.
- Push-notification delivery uses contract because it is an optional service you request and remains controlled by iOS notification permission.
- Optional iCloud backup uses contract because it is a feature you choose to request and control through your Apple account.
- Abuse prevention, security, rate limits, service reliability, safety reporting, display-name audit records, account restrictions, and app version enforcement use legitimate interests.
- App Attest verification and related security records use legitimate interests to prevent unauthorized clients, replay attacks, and automated abuse.
- Authority escalation, mandatory reporting, and legally required retention use legal obligation where applicable.
- Deletion request records use legal obligation and legitimate interests so we can process deletion requests and keep limited proof of handling.
- Formal-request verification records use legal obligation and legitimate interests to verify account control, prevent unauthorized identity-sensitive actions, and document how a request was handled.
- Administrator deletion and safety-report notification emails use legitimate interests so pending requests and reports can be reviewed and handled.
- Support and complaint emails use legitimate interests because we need to receive, respond to, and keep proportionate records of correspondence you choose to send.

### 3.1 Sensitive and Criminal-Offence Information in Safety Reports

A safety report may incidentally contain sensitive information, including health, sexual-life, sexual-orientation, racial or ethnic, religious, political, or alleged criminal-offence information about the reporter, the reported person, or another individual.

Where UK law applies, we process special-category information only where an additional UK GDPR Article 9 condition applies, such as substantial public interest for preventing or detecting unlawful acts or safeguarding children and individuals at risk, legal claims, or vital interests. We process criminal-offence information only where authorized under UK GDPR Article 10 and the Data Protection Act 2018, including applicable Schedule 1 conditions. We use this information only where necessary and apply restricted access, defined retention, review procedures, and disclosure controls.

## 4. Where Your Data Is Stored

- **Convex**: Backend database, server functions, and real-time sync.
- **Cloudflare**: App Attest verification and secure routing between the app and Convex.
- **Clerk**: Authentication, recovery-key credential processing, account sessions, and Clerk user IDs.
- **Apple App Attest**: Apple device and app-integrity attestation.
- **Apple Push Notification service (APNs)**: Push notification delivery, including the notification payload data described in section 1.3.
- **Apple App Store**: Subscription purchases, subscription entitlement verification, renewal/cancellation/refund status, and App Store Server Notifications.
- **Resend**: Email delivery for account-deletion and safety-report notifications to our administrator.
- **Google Gmail**: Receipt and storage of support, complaint, and privacy correspondence sent to our public contact address.
- **GitHub Pages**: Hosting of the public legal pages.
- **Apple iCloud**: Optional user-controlled encrypted backup storage, if you enable iCloud backup.
- **Your device**: Encrypted local cache and encryption state.

All network communication uses HTTPS/TLS. Local data is protected by iOS security features and the app's encrypted database design.

## 5. Service Providers and International Transfers

We use trusted service providers to operate InnerRing. They process data only as needed to provide the app and related infrastructure.

- **Convex**: Processes account IDs, display names, display-name audit records, selected app-owned avatar color values, invite metadata, contacts, encrypted messages, message metadata, message audit records, safety report records, hashed device IDs, App Attest security records, push tokens, public E2EE keys, deletion request records, and formal-request verification records. Purpose: backend database, server functions, real-time sync, service reliability, safety review, request verification, rate limits, security, and abuse prevention. The production Convex database is located in Ireland. Reference: [Convex Privacy Policy](https://www.convex.dev/legal/privacy), [Convex Data Processing Agreement](https://www.convex.dev/legal/dpa), and [Convex Subprocessors](https://www.convex.dev/legal/subprocessors).
- **Cloudflare**: Processes App Attest requests and related network data, which may include IP address, hashed device ID, challenges, key identifiers, attestation and assertion objects, and request hashes. Purpose: verify Apple App Attest evidence before protected account or session operations reach Convex. Reference: [Cloudflare Privacy Policy](https://www.cloudflare.com/privacypolicy/) and [Cloudflare Data Processing Addendum](https://www.cloudflare.com/cloudflare-customer-dpa/).
- **Clerk**: Processes authentication credentials, Clerk user IDs, session IDs, and authentication metadata. Purpose: account authentication and session management. Reference: [Clerk Privacy Policy](https://clerk.com/legal/privacy), [Clerk Data Processing Addendum](https://clerk.com/legal/dpa), and [Clerk Subprocessors](https://clerk.com/legal/subprocessors).
- **Resend**: Processes administrator notification emails. Deletion notifications include the user ID and request timestamp. Safety notifications may include the report ID, reporter and reported-user IDs, source type, category, optional additional information, UK/US link declaration, and submission timestamp. They do not include the reported plaintext message snapshot. Purpose: notify our administrator so deletion requests and safety reports can be processed. Reference: [Resend Privacy Policy](https://resend.com/legal/privacy-policy), [Resend Data Processing Addendum](https://resend.com/legal/dpa), and [Resend Subprocessors](https://resend.com/legal/subprocessors).
- **Google Gmail**: Processes email addresses, email metadata, messages, and attachments you send to our public contact address. Purpose: support, complaint handling, and privacy correspondence. Reference: [Google Privacy Policy](https://policies.google.com/privacy) and [Google Terms of Service](https://policies.google.com/terms).
- **Apple/APNs**: Processes push tokens and notification payloads. Payloads may include sender display name and avatar color, sender/contact/message IDs, and encrypted message ciphertext, encryption header, and session ID. They do not include plaintext message bodies. Purpose: push notification delivery when you allow notifications. Reference: [Apple Privacy Policy](https://www.apple.com/legal/privacy/).
- **Apple App Attest**: Processes app and device-integrity attestation requests, key identifiers, and cryptographic challenge data. The App Attest framework generates subsequent assertions locally on your device. Purpose: help verify that protected requests originate from a valid InnerRing app instance on Apple hardware. Reference: [Apple Privacy Policy](https://www.apple.com/legal/privacy/).
- **Apple App Store**: Processes purchase and subscription transaction data. Purpose: App Store billing, subscription management, refunds, entitlement verification, and subscription status notifications. Reference: [Apple Privacy Policy](https://www.apple.com/legal/privacy/) and [Apple Media Services Terms and Conditions](https://www.apple.com/legal/internet-services/itunes/).
- **Apple iCloud**: Processes optional encrypted backup files if you enable iCloud backup. Purpose: user-controlled backup and restore. Reference: [Apple Privacy Policy](https://www.apple.com/legal/privacy/) and [iCloud Terms of Service](https://www.apple.com/legal/internet-services/icloud/).
- **GitHub Pages**: Processes ordinary web-hosting request data when you visit our public legal pages. Purpose: host and securely deliver those pages. Reference: [GitHub General Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement).

These providers may process data in countries outside your country of residence. Where required, transfers are supported by an applicable adequacy decision, the EU Standard Contractual Clauses, the UK International Data Transfer Agreement or UK Addendum, or another legally permitted safeguard. Contact us if you want information about the safeguard applicable to a particular provider. Provider backup and retention behavior is governed by their service terms and data-processing terms.

## 6. Data Sharing and Disclosure

We share data only as needed to provide the service:

- **Message recipients**: People you choose to contact can receive your encrypted messages and see your profile information needed for the conversation.
- **Service providers**: Convex, Cloudflare, Clerk, Resend, Google Gmail, Apple/App Attest/APNs, Apple iCloud, and GitHub Pages as described above.
- **Apple App Store**: Subscription purchase and entitlement information as described above.
- **Authorities or legal recipients**: Information may be disclosed if required by law, court order, competent authority request, or mandatory safety-reporting obligation.

We do not routinely share plaintext message content because message contents are end-to-end encrypted and unavailable to us on the backend. If you submit a message report, the reported message content and report information you voluntarily provide may be reviewed and disclosed where legally required.

## 7. Your Rights and Choices

Depending on where you live, you may have rights to access, receive a portable copy of, correct, delete, restrict, or object to processing of your personal data. Where processing is based on consent, you may withdraw that consent at any time without affecting processing that was lawful before withdrawal.

Use the in-app controls while signed in for account access, export, correction, and deletion. You may contact us about another privacy right or make a formal privacy request by email. Because InnerRing does not use email addresses or phone numbers for account identity, we may need you to verify control of the account from within the signed-in app before we disclose, change, or delete account data. Email alone is not proof of account ownership. We will not ask for your recovery key.

When verification is required, we may email you a single-use code that remains valid for 24 hours. Entering the code while signed in links that email request to your InnerRing account. This verifies control of the pseudonymous account, not your legal identity. Incorrect attempts are rate limited, and a replacement code invalidates the previous code.

### 7.1 Access and Export

InnerRing is designed to support in-app data export while signed in. Server-side exports may include account data, device/session metadata, subscription identifiers and entitlement status, contact and conversation metadata, invite metadata, message metadata, reaction metadata, E2EE public-key metadata, and deletion request status.

Server-side exports do not include plaintext ordinary-message contents because we cannot decrypt them. Standard self-service exports include successful formal-request verification receipts but exclude their code hashes. They also exclude raw ciphertext, encryption headers, X3DH headers, encryption session IDs, App Attest keys, receipts, challenges, counters, replay-token records, and restricted safety-report context. Plaintext ordinary-message history may exist only on your device and in your encrypted iCloud backup if enabled. If you voluntarily submit a message report, its plaintext snapshot is restricted safety-report context and is not included in the ordinary self-service export.

The self-service export is not a decision that all excluded information falls outside a legal right of access. If you make a formal access request, we will assess the applicable law, the rights of other people, security risks, and any legal exemptions before deciding what additional information can be provided.

### 7.2 Correction

You can update your display name and select a different app-owned avatar background color in the app.

### 7.3 Notifications

You can allow or disable push notifications in iOS Settings.

### 7.4 Account Deletion

You can request account deletion in the app while signed in. Deletion requests are processed within 7 days. You may cancel your deletion request in the app before it is processed.

For security, deletion requests are not accepted by unauthenticated email. If you lose your recovery key and are signed out, we may be unable to verify ownership, recover, export, or delete the account.

### 7.5 Objection and Restriction

**You may object to processing based on our legitimate interests and may ask us to restrict processing in circumstances provided by law.** Contact us using the email address in section 14. We will consider your request against our reasons for processing, legal obligations, safety needs, and the rights of other people.

### 7.6 Complaints to a Regulator

Please contact us first if you have a privacy concern so we can try to resolve it. If you are in the United Kingdom, you also have the right to complain to the [Information Commissioner's Office](https://ico.org.uk/make-a-complaint/). If you are in the EEA, you may complain to the data-protection authority where you live, work, or believe an infringement occurred.

### 7.7 Required Information and Automated Checks

Account, authentication, device-integrity, public-key, and core messaging metadata are contractually required to create an account and provide secure messaging. If you do not provide them, we cannot create or authenticate the account or provide the affected feature. Push notifications, optional iCloud backup, safety-report additional information, and support emails are optional, except that a short explanation is required when you select the "Other" safety-report category.

InnerRing uses automated security, rate-limit, app-integrity, subscription-entitlement, and app-version checks. These checks can reject or temporarily limit account creation, session activation, verification-code attempts, invites, contacts, or messaging. They do not use advertising profiles or cross-app tracking. Safety-report outcomes and account safety restrictions are reviewed by a person rather than decided solely by an automated profile. Contact us if you believe an automated check was applied incorrectly.

## 8. Data Retention

### 8.1 Active Accounts

We retain account, contact, encrypted message, message metadata, device, session, App Attest security, subscription entitlement, and E2EE public-key data while your account is active and the data is needed to provide the service.

### 8.2 Messages and Reactions

Ordinary encrypted messages and related metadata are retained while the backend contact and conversation records remain. If a sender deletes a message for everyone, the current message ciphertext is cleared and the message is hidden from the chat view, but the backend message row and operational metadata remain. Message audit records containing earlier ciphertext are normally retained for 1 year and may be kept longer when linked to a safety report or legal hold.

Message events and reaction tombstones may be retained as needed for message sync, read/edit/delete state, Double Ratchet encryption correctness, abuse prevention, service reliability, and record keeping.

### 8.3 Account Deletion

When your account deletion is processed, we delete or remove access to:

- Your Clerk authentication account.
- Active sessions.
- Push notification tokens and app-linked device records, including their hashed device IDs.
- Invite codes created by you.
- E2EE signed prekeys and one-time prekeys.
- Public identity keys stored on your Convex user record.

We anonymize your profile as "DELETED USER" and prevent future account access.

Because conversations involve two participants, encrypted historical messages and minimal conversation metadata may remain available to the other participant after your account deletion. We retain this limited data under our legitimate interests to preserve the other participant's conversation history and the integrity of the messaging service.

We limit the privacy impact of this retention by deleting your authentication account, sessions, push tokens, app-linked device records, invite codes, E2EE prekeys, and public identity keys. Your profile is shown as "DELETED USER" with the default app-owned avatar color, your account cannot be accessed again, and message contents remain end-to-end encrypted on the backend.

App Attest security records are associated with an app installation and hashed device ID rather than directly with an InnerRing account. They may remain after account deletion where needed to verify device integrity, prevent replay, enforce rate limits, and investigate abuse.

The retained conversation data may include user IDs, contact relationship IDs, timestamps, encrypted message records, message events, and read/edit/delete/reaction metadata. This retained data is pseudonymous personal data, not fully anonymous data.

Safety reports, authority-escalated records, display-name audit records, message audit records, and related retention-held records may be retained after account deletion where needed for safety review, legal compliance, abuse prevention, service reliability, mandatory reporting, or record keeping.

### 8.4 Subscription Entitlement Records

We retain Apple-verified subscription entitlement records after account deletion as needed to verify purchases and refunds, handle billing disputes, prevent fraud, and maintain accounting and audit records. These records may include product ID, App Store transaction identifiers, subscription environment, entitlement status, expiry or revocation dates, and verification timestamps. The subscription record does not contain an InnerRing user ID, but Apple may retain its own transaction-to-account relationship under Apple's policies.

### 8.5 Deletion Request Records

We retain limited completed or cancelled deletion-request records, such as user ID, request time, status, and completion or cancellation time, for approximately 1 year for audit, security, and legal-defense purposes. Cleanup runs on a schedule, so deletion may occur shortly after the anniversary. Pending requests remain until completed or cancelled.

### 8.6 Formal-Request Verification Records

Unused formal-request verification records expire after 24 hours and are normally deleted 30 days after expiry. A replacement code overwrites and invalidates the previous code. Successful verification receipts, including the verification ID, account ID, and verification time, are retained for approximately 1 year to document request handling, manage complaints, and establish or defend legal claims. Cleanup runs on a schedule, so deletion may occur shortly after the retention period.

### 8.7 Display-Name Audit Records

We retain display-name audit records for 1 year by default. If a safety report references a display-name audit record and the safety report has a longer retention period, we may retain the display-name audit record for the same period as that safety report.

### 8.8 Safety Report and Message Audit Records

Open safety reports are retained until reviewed and closed or placed under an applicable hold. Closed safety reports are retained for 1 year by default. Authority-escalated reports may be retained for longer where required by law, safeguarding obligations, competent-authority instructions, or internal safety retention policy. Message audit records and display-name audit records linked to safety reports may be retained for the same period as the related safety report.

### 8.9 Backups

Backend providers may retain deleted data temporarily in disaster-recovery backups according to their own retention practices. These backups are not used to restore deleted accounts as active accounts.

Optional iCloud backups are controlled by you through your Apple iCloud account. We cannot access or delete your iCloud backup for you.

### 8.10 Support and Complaint Emails

We retain support, privacy, and safety-complaint correspondence only while needed to respond, document the outcome, meet legal or safeguarding obligations, resolve disputes, and establish or defend legal claims. Administrator notification emails and provider copies are also subject to the relevant email provider's retention and backup practices.

## 9. Beta and TestFlight

During beta testing and TestFlight use, we may reset or delete test data to maintain the service. Do not use beta builds for critical or sensitive communications that you cannot afford to lose.

## 10. Children's Privacy

InnerRing is not intended for children under 13. We do not knowingly collect personal data from children under 13. If you believe a child has provided personal data, contact us.

## 11. California Privacy Rights

California residents may have rights under the California Consumer Privacy Act, including the right to know, delete, correct, and opt out of sale or sharing. We do not sell personal information.

We do not share personal information for cross-context behavioral advertising, and we do not use advertising, analytics, or cross-app tracking.

## 12. European Privacy Rights

If you are in the EEA or UK, you may have GDPR or UK GDPR rights including access, rectification, erasure, restriction, portability, objection, and withdrawal of consent where processing is based on consent.

Use signed-in in-app controls where available. You may also contact us by email to make a formal request, but we may require verification through the signed-in app before taking an identity-sensitive action.

## 13. Changes to This Privacy Policy

We may update this Privacy Policy from time to time. We will update the "Last Updated" date when changes are made. Material changes may also be communicated in the app.

## 14. Contact Us

If you have questions about this Privacy Policy, contact us at:

**Email**: [innerring.app@gmail.com](mailto:innerring.app@gmail.com)

For account deletion and the ordinary self-service export, use the in-app controls while signed in. You may use email for privacy questions, complaints, or formal rights requests, but email alone is not sufficient to verify account ownership.
