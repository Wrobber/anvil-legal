# Anvil CRM — Privacy Policy

**Last updated: April 22, 2026**

Anvil CRM ("Anvil," "we," "our") is operated by Iros Solutions LLC, a West Virginia limited liability company. This policy describes how we collect, use, and protect your information when you use the Anvil CRM iOS application.

## 1. Information We Collect

### Account Information
When you create an account, we collect your email address and display name. Authentication is handled by Firebase Authentication (Google LLC).

### CRM Data You Provide
Contacts, organizations, deals, quotes, invoices, contracts, follow-up tasks, notes, tags, custom fields, photos, and documents you enter into the app. This data is stored in Google Firebase Firestore and Firebase Cloud Storage under your user account.

### Location Data
With your permission, we access your device location to display it on the map and find nearby contacts. Location data is used on-device and is not stored on our servers. Contact addresses may be geocoded using Geocodio to display map pins; in this case the address text is sent to Geocodio's API and the returned coordinates are stored in Firestore.

### Camera and Photo Library
With your permission, we access your camera and photo library to attach photos to contact, organization, and job profiles. Photos are uploaded to Firebase Cloud Storage.

### Device and Usage Data
We collect anonymized analytics events (e.g., features used, screen views) and crash reports through Firebase Analytics and Firebase Crashlytics. We also collect aggregate performance metrics through Firebase Performance Monitoring. This data includes your device model, OS version, and app version but does not include your CRM data.

### Spreadsheet Import Data
When you import a spreadsheet, column headers and a small number of sample values (up to 3 per column) may be sent to Anthropic's Claude API via a secure Firebase Cloud Function to assist with automatic column mapping. No full spreadsheet contents or CRM records are sent. This data is processed in real time and is not stored by Anthropic.

### Subscription Data
Subscription status and purchase history are managed by RevenueCat, Inc. RevenueCat receives your anonymous app user ID and transaction data from Apple. We do not receive or store your payment information.

### Payment Processing Data
If you accept payments from your customers through Anvil, payment processing is handled by Stripe, Inc. via Stripe Connect. Stripe collects your customers' payment information directly; we do not see or store credit card numbers. We receive transaction status, amounts, and Stripe account identifiers to display payment status within the app.

### Email Communications
When automated follow-up emails or triggered emails are sent on your behalf, they are delivered through SendGrid (Twilio Inc.). SendGrid receives the recipient email address, subject line, and email body content. SendGrid may collect delivery and engagement data (opens, bounces) for deliverability purposes.

### Bug Reports
When you submit a bug report from the app, the report contents (your description, app version, device info) are sent to Linear via a Cloud Function. No CRM data is included in bug reports.

## 2. How We Use Your Information

- To provide and maintain the Anvil CRM service
- To authenticate your account
- To sync your CRM data across sessions
- To geocode contact addresses for map display
- To send automated emails (quote follow-ups, triggered emails) on your behalf
- To process payments via Stripe Connect on your behalf
- To process subscriptions and enforce feature tiers
- To diagnose crashes and improve app stability
- To understand feature usage and improve the app
- To assist with automatic column mapping during spreadsheet imports (AI-assisted)
- To deliver bug reports to our issue tracker

## 3. Third-Party Services

| Service | Provider | Purpose | Privacy Policy |
|---------|----------|---------|----------------|
| Firebase Auth | Google LLC | Account authentication | https://firebase.google.com/support/privacy |
| Firebase Firestore | Google LLC | CRM data storage | https://firebase.google.com/support/privacy |
| Firebase Cloud Storage | Google LLC | Photo and document storage | https://firebase.google.com/support/privacy |
| Firebase Analytics | Google LLC | Anonymized usage analytics | https://firebase.google.com/support/privacy |
| Firebase Crashlytics | Google LLC | Crash reporting | https://firebase.google.com/support/privacy |
| Firebase Performance | Google LLC | Performance monitoring | https://firebase.google.com/support/privacy |
| RevenueCat | RevenueCat, Inc. | Subscription management | https://www.revenuecat.com/privacy |
| Stripe | Stripe, Inc. | Payment processing (Stripe Connect) | https://stripe.com/privacy |
| SendGrid | Twilio Inc. | Transactional email delivery | https://www.twilio.com/en-us/legal/privacy |
| Geocodio | Dotsquare LLC | Address geocoding | https://www.geocod.io/privacy |
| Linear | Linear Orbit, Inc. | Bug report tracking | https://linear.app/privacy |
| Apple MapKit | Apple Inc. | Map display | https://www.apple.com/legal/privacy |
| Apple WeatherKit | Apple Inc. | Weather data in briefs | https://www.apple.com/legal/privacy |
| Anthropic Claude API | Anthropic, PBC | AI-assisted column mapping during spreadsheet import | https://www.anthropic.com/privacy |

## 4. Data Storage and Security

Your CRM data is stored in Firebase Firestore and Cloud Storage, secured by Firebase Security Rules that restrict access to your authenticated user account. Data is encrypted in transit (TLS) and at rest by Google Cloud infrastructure. We do not share, sell, or provide your CRM data to any third party except as described in Section 3 (third-party service providers acting on your behalf).

## 5. Data Retention

Your data is retained as long as your account is active. You may delete individual records at any time within the app. To request complete account and data deletion, use the "Delete Account" option in Settings > Account, or contact us at the email below.

## 6. Your Rights

### All Users
You have the right to:
- Access the personal data we hold about you
- Correct inaccurate data
- Delete your data and account
- Export your contacts (Gold tier feature)
- Withdraw consent for location, camera, or photo library access via iOS Settings

### California Residents (CCPA)
If you are a California resident, you have additional rights under the California Consumer Privacy Act:
- **Right to Know**: You may request a copy of the personal information we have collected about you in the preceding 12 months.
- **Right to Delete**: You may request deletion of your personal information, subject to certain exceptions.
- **Right to Opt-Out of Sale**: We do not sell your personal information to third parties.
- **Non-Discrimination**: We will not discriminate against you for exercising your CCPA rights.

To exercise these rights, contact us at privacy@anvilsales.com.

### European Economic Area Residents (GDPR)
If you are located in the EEA, our legal basis for processing your personal data is:
- **Performance of a contract**: To provide the Anvil CRM service you signed up for.
- **Legitimate interests**: To improve our service, diagnose issues, and understand usage patterns.
- **Consent**: For optional data collection such as location access, camera access, and analytics.

You have the right to access, rectify, erase, restrict processing, and port your data. You also have the right to lodge a complaint with your local data protection authority. Contact us at privacy@anvilsales.com to exercise these rights.

## 7. Children's Privacy

Anvil is not directed at children under 13. We do not knowingly collect information from children under 13. If we learn that we have collected personal information from a child under 13, we will delete it promptly.

## 8. Beta Testing Program

While you are using a beta (TestFlight) build of Anvil, the following additional terms apply. This section will be removed from the policy when the beta program ends.

### Additional Data Collection
Beta builds may collect more detailed diagnostic information than production builds, including verbose in-app logs, pre-release feature telemetry, and granular performance traces. This data is processed by the same providers listed in Section 3 (primarily Firebase Crashlytics, Firebase Analytics, and Firebase Performance).

### Apple TestFlight
Beta distribution is handled by Apple Inc. through TestFlight. When you install, use, or submit feedback through TestFlight, Apple collects crash logs, screenshots, feedback submissions, and aggregate install/launch metrics, and shares them with us in accordance with Apple's privacy policy: https://www.apple.com/legal/privacy/. We do not control what Apple collects through TestFlight.

### Screenshots and Bug Reports
Screenshots submitted through TestFlight's feedback tool or through Anvil's in-app bug reporter may contain real CRM data visible on your screen at the time of capture (contact names, addresses, notes, etc.). By submitting a screenshot, you consent to us viewing that data solely to diagnose the reported issue. Please review screenshots before submitting, and blur or crop sensitive fields when possible.

### Confidentiality of Pre-Release Features
Beta builds may contain features, UI, or behavior not yet public. Please do not share screenshots, videos, or descriptions of unreleased functionality publicly without written permission from Iros Solutions LLC. Private discussion with us for feedback purposes is always welcome.

### Data Lifecycle
Data you create during the beta is stored in the same Firebase project as production data and will carry over to the public release. You may delete your account and data at any time from Settings > Account.

## 9. Changes to This Policy

We may update this policy from time to time. We will notify you of material changes by posting the updated policy within the app or via email. Your continued use of the app after changes are posted constitutes acceptance of the revised policy.

## 10. Contact Us

If you have questions about this privacy policy or your data, contact us at:

**Email:** privacy@anvilsales.com
**Website:** https://anvilsales.com

Iros Solutions LLC
Morgantown, WV
