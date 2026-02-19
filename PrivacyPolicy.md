# Anvil CRM — Privacy Policy

**Last updated: February 20, 2026**

Anvil CRM ("Anvil," "we," "our") is operated by [Your Legal Entity Name]. This policy describes how we collect, use, and protect your information when you use the Anvil CRM iOS application.

## 1. Information We Collect

### Account Information
When you create an account, we collect your email address and display name. Authentication is handled by Firebase Authentication (Google LLC).

### CRM Data You Provide
Contacts, organizations, opportunities, quotes, invoices, follow-up tasks, notes, tags, custom fields, photos, and documents you enter into the app. This data is stored in Google Firebase Firestore and Firebase Cloud Storage under your user account.

### Location Data
With your permission, we access your device location to display it on the map and find nearby contacts. Location data is used on-device and is not stored on our servers. When you use route optimization (Gold tier), your contacts' coordinates are sent to the Mapbox API to calculate optimal routes.

### Camera and Photo Library
With your permission, we access your camera and photo library to attach photos to contact and organization profiles. Photos are uploaded to Firebase Cloud Storage.

### Device and Usage Data
We collect anonymized analytics events (e.g., features used, screen views) and crash reports through Firebase Analytics and Firebase Crashlytics. This data includes your device model, OS version, and app version but does not include your CRM data.

### Spreadsheet Import Data
When you import a spreadsheet, column headers and a small number of sample values (up to 3 per column) may be sent to Anthropic's Claude API via a secure Firebase Cloud Function to assist with automatic column mapping. No full spreadsheet contents or CRM records are sent. This data is processed in real time and is not stored by Anthropic.

### Subscription Data
Subscription status and purchase history are managed by RevenueCat, Inc. RevenueCat receives your anonymous app user ID and transaction data from Apple. We do not receive or store your payment information.

## 2. How We Use Your Information

- To provide and maintain the Anvil CRM service
- To authenticate your account
- To sync your CRM data across sessions
- To calculate routes and display maps
- To process subscriptions and enforce feature tiers
- To diagnose crashes and improve app stability
- To understand feature usage and improve the app
- To assist with automatic column mapping during spreadsheet imports (AI-assisted)

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
| Mapbox | Mapbox, Inc. | Route optimization (Gold tier) | https://www.mapbox.com/legal/privacy |
| Apple MapKit | Apple Inc. | Map display | https://www.apple.com/legal/privacy |
| Apple WeatherKit | Apple Inc. | Weather data in briefs | https://www.apple.com/legal/privacy |
| Anthropic Claude API | Anthropic, PBC | AI-assisted column mapping during spreadsheet import | https://www.anthropic.com/privacy |

## 4. Data Storage and Security

Your CRM data is stored in Firebase Firestore and Cloud Storage, secured by Firebase Security Rules that restrict access to your authenticated user account. Data is encrypted in transit (TLS) and at rest by Google Cloud infrastructure. We do not share, sell, or provide your CRM data to any third party.

## 5. Data Retention

Your data is retained as long as your account is active. You may delete individual records at any time within the app. To request complete account and data deletion, contact us at the email below.

## 6. Your Rights

You have the right to:
- Access the personal data we hold about you
- Correct inaccurate data
- Delete your data and account
- Export your contacts (Gold tier feature)
- Withdraw consent for location, camera, or photo library access via iOS Settings

## 7. Children's Privacy

Anvil is not directed at children under 13. We do not knowingly collect information from children under 13.

## 8. Changes to This Policy

We may update this policy from time to time. We will notify you of material changes by posting the updated policy within the app or via email.

## 9. Contact Us

If you have questions about this privacy policy or your data, contact us at:

**Email:** [your-email@anvilcrm.com]
