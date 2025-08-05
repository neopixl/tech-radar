---
title: "Firebase Crashlytics for React native"
ring: adopt
quadrant: react
tags: [debug, crash, react-native]
---

Firebase Crashlytics is a crash reporting and analysis tool provided by Google as part of the Firebase mobile development platform. It is designed to help developers track and analyze app crashes, enabling them to identify and resolve issues quickly.

Key features of Firebase Crashlytics include:

- **Real-time Crash Reporting**: Firebase Crashlytics provides real-time reports on app crashes, including information about the device, operating system, and the sequence of events leading up to the crash.

- **Issue Prioritization**: Crashes are automatically prioritized based on their impact on users, helping developers focus on resolving critical issues first.

- **Detailed Crash Insights**: Developers receive detailed crash reports, including stack traces, device information, and user interactions leading to the crash, facilitating efficient debugging.

- **Integration with Firebase**: Firebase Crashlytics seamlessly integrates with other Firebase services, allowing developers to correlate crash data with analytics, user engagement, and performance metrics.

- **Automated Alerts**: Developers can set up automated alerts to receive notifications when new issues arise or when existing issues reach a certain threshold.

Firebase Crashlytics is widely used by mobile app developers to improve the stability and reliability of their applications by quickly identifying and addressing issues that lead to crashes.

⚠️ **Important Notice Regarding Firebase Crashlytics and GDPR Compliance** ⚠️

When integrating Firebase Crashlytics into your application, it's crucial to ensure compliance with the General Data Protection Regulation (GDPR) if your app collects and processes personal data of individuals in the European Union (EU).

Firebase Crashlytics collects crash reports and diagnostic information from users' devices, which may include personal data such as device identifiers, IP addresses, and in some cases, user-specific data if custom keys are included in crash reports.

To comply with the GDPR:

1. **Transparency**: Clearly inform users in your app's privacy policy about the use of Firebase Crashlytics, including what data is collected, how it is processed, and for what purposes.

2. **User Consent**: Obtain explicit consent from users before collecting and processing any personal data through Firebase Crashlytics. Users must have the option to opt-in or opt-out of crash reporting.

3. **Data Minimization**: Only collect the minimum amount of data necessary for crash reporting purposes. Avoid including any unnecessary personal data in crash reports.

4. **Data Processing Agreement (DPA)**: If you are using Firebase services as a data processor on behalf of your users (e.g., if you're a developer of an app that collects personal data), ensure that you have a Data Processing Agreement (DPA) in place with Google, the provider of Firebase services.

5. **Data Retention**: Review and adjust the data retention settings in Firebase Console to comply with GDPR requirements. Consider minimizing the retention period for crash reports containing personal data.

Failure to comply with the GDPR's requirements regarding the processing of personal data may result in significant fines and legal consequences. Therefore, it's essential to review your app's use of Firebase Crashlytics and take appropriate measures to ensure compliance with data protection regulations.

For detailed guidance on GDPR compliance and Firebase services, refer to the official documentation provided by Google and consult legal experts specializing in data protection laws.

### Docs

- [Product Presentation](https://firebase.google.com/products/crashlytics)
- [RNFirebase Documentation](https://rnfirebase.io/crashlytics/usage)
