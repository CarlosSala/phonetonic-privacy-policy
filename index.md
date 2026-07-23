---
layout: default
title: "PhoneTonic Privacy Policy"
description: "Privacy Policy for the PhoneTonic Android application"
---

# Privacy Policy for PhoneTonic

**Last updated: July 23, 2026**

## 1. Introduction

PhoneTonic is an Android application developed and published by **CarlosSalaDev**.

This Privacy Policy explains how PhoneTonic accesses, stores, collects, uses, and transfers information when you use the application. It also describes how Google Firebase, Android system features, backup services, external applications, and support communications may process information related to PhoneTonic.

PhoneTonic does not require registration, does not create user accounts, and does not operate its own remote server or proprietary cloud synchronization service.

## 2. Information Stored on Your Device

PhoneTonic stores certain information locally so that its features can operate.

This information may include:

- Notes created, edited, or saved by you.
- `Intent Actions` parameters, such as phone numbers, email addresses, message content, web addresses, and text prepared for sharing.
- Application preferences, including the selected light or dark theme.
- Other locally stored settings required to preserve the application’s configuration.

This information is stored in PhoneTonic’s private application storage.

PhoneTonic does not intentionally send the contents of your notes or `Intent Actions` parameters to CarlosSalaDev or Firebase. However, this information may leave the device when:

- You intentionally execute an `Intent Action`.
- You send information through an external application.
- Android performs a backup or device transfer, as described below.

## 3. Information Accessed or Displayed by PhoneTonic

The `SystemInfo` section displays technical information provided by Android, such as the device manufacturer, model, Android version, and other system information.

PhoneTonic displays this information for your reference and does not intentionally upload the complete contents of the `SystemInfo` screen to a server operated by CarlosSalaDev.

PhoneTonic does not request access to GPS or precise location, and it does not request permission to access:

- Your contacts.
- Your call history.
- Received SMS messages.
- Your email inbox.
- Your browsing history.
- Your precise geographic location.

Google Firebase may separately process certain device, application, network, and approximate-location information for analytics and diagnostic purposes, as explained in this Policy.

## 4. Information Collected Automatically

PhoneTonic uses Firebase services provided by Google. Depending on the Firebase service and the configuration available on the device, these services may automatically process the following categories of information:

- **App activity and interactions**, such as app launches, sessions, general engagement, automatically collected events, and actions occurring immediately before a crash.
- **Approximate location**, such as country, region, or city information derived from network data.
- **Device and application information**, such as manufacturer, model, operating-system version, application version, language, screen characteristics, and network connection type.
- **Device or other identifiers**, such as Firebase Installation ID, Crashlytics installation identifiers, app-instance identifiers, the Android Advertising ID when available, and installation-attribution information.
- **Crash logs**, including stack traces and relevant information about the application’s state when a crash occurs.
- **Diagnostic information**, such as session information, device metadata, and technical circumstances related to stability problems.

Google Analytics collects approximate location, device information, user counts, and session statistics through its default implementation. Approximate location may be derived from network information such as an IP address; PhoneTonic does not obtain GPS coordinates through Analytics.

PhoneTonic does not intentionally send the text of your notes, saved messages, configured phone numbers, email content, or other `Intent Actions` parameters to Firebase as custom Analytics events, user identifiers, Crashlytics custom keys, or custom logs.

## 5. How Automatically Collected Information Is Used

Automatically collected technical information is used to:

- Understand the general use of PhoneTonic.
- Measure application launches, sessions, engagement, and usage trends.
- Identify crashes and stability problems.
- Investigate the technical circumstances surrounding a crash.
- Improve the reliability, performance, usability, and future development of PhoneTonic.
- Measure application installation and attribution statistics.
- Provide and maintain the Firebase services used by PhoneTonic.

Firebase states that the end-user information described in its Android data-disclosure documentation is encrypted in transit using HTTPS.

## 6. Firebase Services

PhoneTonic currently uses the Firebase services described below.

### 6.1 Google Analytics for Firebase

Google Analytics helps CarlosSalaDev understand the general use of the application, including launches, sessions, engagement, approximate geographic distribution, device categories, and installation trends.

Analytics collection is enabled by default in the current version of PhoneTonic. PhoneTonic does not currently provide an in-app control for disabling Analytics collection.

PhoneTonic does not intentionally create custom Analytics events containing notes, messages, email addresses, phone numbers, or other content entered in `Intent Actions`.

### 6.2 Firebase Crashlytics

Firebase Crashlytics helps identify and diagnose crashes affecting PhoneTonic.

Crashlytics automatically collects information such as:

- Stack traces when the application crashes.
- Relevant application state at the time of the crash.
- Relevant device metadata.
- A Crashlytics installation identifier.
- Session and quality information provided through related Firebase services.
- Analytics events used as breadcrumbs to describe actions occurring immediately before a crash.

PhoneTonic does not intentionally attach notes, `Intent Actions` content, phone numbers, email addresses, or free-text user identifiers to Crashlytics reports.

Firebase distinguishes between information automatically collected by Crashlytics and custom keys, logs, identifiers, and non-fatal events that a developer may optionally add.

Crashlytics collection is enabled by default in the current version of PhoneTonic. PhoneTonic does not currently provide an in-app control for disabling Crashlytics collection.

### 6.3 Firebase Installations

Firebase Installations generates and collects a Firebase Installation ID associated with an individual installation of PhoneTonic.

According to Firebase, this identifier identifies an installation of the application and is not intended to uniquely identify an individual or a physical device.

### 6.4 Firebase Sessions and Data Transport

Firebase Sessions may process application metadata, device metadata, network connection information, and usage information, such as when the application enters the foreground and begins a new session.

Google Data Transport supports the secure delivery to Firebase of Analytics, Crashlytics, and other related technical information.

## 7. Advertising ID and Advertising

PhoneTonic **does not display advertisements**.

Google Analytics may access the Android Advertising ID and advertising-attribution services when they are available on the device. These may be used for:

- Analytics.
- Measurement.
- Installation attribution.
- Understanding general installation and usage trends.

CarlosSalaDev does not use the Advertising ID to display advertisements inside PhoneTonic.

The availability and behavior of the Advertising ID may depend on the Android version, Google Play services, device settings, and privacy controls selected by the user.

## 8. Phone Permission

PhoneTonic requests the Android `CALL_PHONE` permission only when you use `Call Number` and direct calling requires that permission.

If you deny the permission, PhoneTonic will not initiate the direct call. Instead, you may use `Dial Number`, which opens the configured number in a compatible phone application so that you can review it and initiate the call manually.

PhoneTonic does not use the phone permission to:

- Access your contacts.
- Read your call history.
- Record telephone conversations.
- Monitor calls.
- Initiate calls without an action performed by you.

The configured phone number remains stored locally unless it is included in an Android backup or intentionally passed to the phone application when you execute the action.

## 9. Intent Actions and External Applications

PhoneTonic includes the following `Intent Actions`:

- `Send Email`.
- `Send SMS`.
- `Open Browser`.
- `Call Number`.
- `Dial Number`.
- `Share Text`.

When you execute one of these actions, PhoneTonic may pass the configured information to the corresponding Android component or a compatible external application.

For example, PhoneTonic may pass:

- A recipient, subject, and message to an email application.
- A phone number and message to an SMS application.
- A web address to a browser.
- A phone number to a phone or dialer application.
- Saved text to an application selected through Android’s sharing interface.

These transfers occur only after you intentionally execute the corresponding action.

PhoneTonic does not automatically read information subsequently created, received, or stored by those external applications.

After information is passed to an external application, its subsequent processing is governed by that application and its provider. CarlosSalaDev does not control the privacy, security, transmission, retention, or later use of information by independent third-party applications.

You should review an external application’s privacy practices before sending sensitive information through it.

## 10. Android Backups and Device Transfers

PhoneTonic allows Android backup and device-transfer features.

Depending on your Android version, device manufacturer, Google Account settings, backup provider, and personal preferences, Android may back up or transfer eligible PhoneTonic data, including:

- Notes.
- `Intent Actions` parameters.
- Application preferences.
- Locally stored configuration files.
- Application databases.

Android Auto Backup may include eligible private application files, preferences, and databases unless they have been specifically excluded. Restored data may reappear after reinstalling PhoneTonic or configuring another device.

These backups and transfers are managed by Android, Google, the relevant manufacturer, or the backup provider. CarlosSalaDev does not directly receive, inspect, or control the contents of your Android backups.

Uninstalling PhoneTonic from a device may not delete a backup already maintained by Android or another provider.

## 11. Support Communications

If you contact CarlosSalaDev using the support email address, the following information may be received:

- Your email address.
- Your name, if it appears in your email account or message.
- The contents of your message.
- Screenshots, files, or other information you voluntarily attach.
- Technical information you choose to provide about your device or the problem encountered.

This information may be used to:

- Respond to your request.
- Provide assistance.
- Investigate reported errors.
- Review feedback or feature suggestions.
- Maintain reasonable records of support communications.

PhoneTonic does not automatically send support emails, notes, `Intent Actions` parameters, diagnostic files, or other personal content to CarlosSalaDev. You decide whether to send a message and what information to include.

Do not send passwords, payment-card information, authentication codes, or other highly sensitive information through the support email.

## 12. Data Processing, Transfers, and Service Providers

CarlosSalaDev does not sell personal information collected through PhoneTonic.

Google and Firebase process technical information as service providers for Analytics, Crashlytics, installation identification, session measurement, attribution, and data transport.

Firebase states that it does not transfer the information described in its Android disclosure documentation to third parties, except to subprocessors that assist in providing Firebase services or according to integrations and instructions enabled by the developer.

Information may also be transferred:

- To an external application when you intentionally execute an `Intent Action`.
- Through Android backup or device-transfer services, according to your settings.
- To your email provider and CarlosSalaDev when you voluntarily contact support.
- When necessary to comply with applicable law, legal process, or a valid governmental request.
- When reasonably necessary to protect legal rights, security, the integrity of PhoneTonic, or the safety of other persons.

PhoneTonic does not use an independent backend operated by CarlosSalaDev to receive notes, `Intent Actions` content, or other locally stored user content.

## 13. Data Retention and Deletion

### 13.1 Locally Stored Data

Notes, preferences, and `Intent Actions` parameters generally remain on the device until you:

- Edit or delete them within PhoneTonic.
- Clear PhoneTonic’s storage through Android settings.
- Uninstall PhoneTonic.

Locally deleted data may later reappear if Android restores it from an existing backup.

### 13.2 Firebase Technical Data

Analytics, Crashlytics, installation, session, and diagnostic information is retained according to the applicable Firebase and Google Analytics project settings and Google’s retention and deletion practices.

Retention periods may vary depending on the Firebase service, the type of information, and the configuration of the associated Firebase or Google Analytics project.

CarlosSalaDev does not maintain a PhoneTonic account that directly links Firebase technical records to your name, email address, or a PhoneTonic user profile.

PhoneTonic does not provide an account-deletion function because the application does not create user accounts.

### 13.3 Support Communications

Support emails may be retained for as long as reasonably necessary to:

- Respond to your request.
- Investigate a reported problem.
- Maintain support records.
- Protect legal rights.
- Comply with applicable obligations.

You may contact CarlosSalaDev if you have questions about information you voluntarily provided through support.

## 14. Data Security

CarlosSalaDev relies on security measures provided by Android, Google, and Firebase to reduce the risk of unauthorized access, alteration, disclosure, or loss.

These measures include:

- Android private application storage for locally stored information.
- Android permission controls for direct phone calls.
- Encrypted HTTPS transmission for Firebase data.
- Access controls maintained by Firebase and Google.
- Backup protections administered by Android and the selected backup provider.

Firebase states that the end-user information described in its Android data-disclosure documentation is encrypted in transit using HTTPS.

No method of storage or transmission can be guaranteed to be completely secure. You should avoid storing highly sensitive information in `Notes` or `Intent Actions` unless you understand the risks related to device access, backups, sharing, and external applications.

## 15. Children’s Privacy

PhoneTonic is intended for users aged **18 and over** and is not designed or specifically directed to children.

The application does not provide:

- User accounts or profiles.
- Social interaction between users.
- Forms requesting a child’s name, address, email address, or other identifying information.
- Advertising directed at children.

If you believe that a child has voluntarily sent personal information to the support email, contact CarlosSalaDev so that the communication can be reviewed and appropriate action considered.

## 16. Your Choices

You can control certain information and features by:

- Choosing what content to save in `Notes` and `Intent Actions`.
- Editing or deleting locally stored content.
- Denying the `CALL_PHONE` permission and using `Dial Number` instead.
- Deciding whether to complete or cancel an action after an external application opens.
- Clearing PhoneTonic’s storage through Android settings.
- Uninstalling PhoneTonic.
- Managing Android backup and device-transfer preferences.
- Managing the Advertising ID and other privacy controls provided by Android and Google.
- Deciding whether to contact support and what information to include.

The current version of PhoneTonic does not include:

- A PhoneTonic account.
- An account-deletion process.
- A proprietary cloud synchronization service.
- An in-app control for disabling Firebase Analytics.
- An in-app control for disabling Firebase Crashlytics.

## 17. Third-Party Services and Policies

Google, Firebase, Android, external applications, email providers, device manufacturers, and backup providers may process information under their own terms and privacy policies.

This Privacy Policy describes the practices of PhoneTonic and CarlosSalaDev. It does not replace or control the privacy policies of independent third-party services.

## 18. Changes to This Privacy Policy

This Privacy Policy may be updated when PhoneTonic’s features, permissions, service providers, data practices, or legal obligations change.

The revised Policy will be published with an updated **Last updated** date.

Users should review this Policy periodically, especially after installing a significant PhoneTonic update.

Sections may be added, removed, or expanded as PhoneTonic evolves. This Policy will describe the features and data practices of the currently published application and will not describe features that have not yet been implemented.

## 19. Contact

For privacy questions, support requests, error reports, or feedback, contact:

**Developer:** CarlosSalaDev  
**Application:** PhoneTonic  
**Email:** [carlossala.apps@gmail.com](mailto:carlossala.apps@gmail.com)
