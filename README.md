# Packly Privacy Policy

**Last updated:** 2 September 2026

This Privacy Policy explains how Packly handles information when you use the Packly Android application published by GusanitoLabs.

## 1. Packly in brief

Packly helps you create and manage packing items, packing lists, and trips. The core features work without an account and without connecting to a cloud service.

Packly stores your core app data locally on your device. Google Drive backup and synchronization is an optional feature that you can enable yourself.

## 2. Information stored on your device

Packly stores the information needed to provide its local features, such as:

- packing items, quantities, notes, categories, and packing status;
- lists and the items assigned to them;
- trips, destinations, dates, and packing progress;
- app preferences and local synchronization state.

This local data is used to provide the app's features. Packly does not operate a developer-owned account system or a developer-owned database for this information.

## 3. Optional Google Drive synchronization

If you choose **Connect Google Drive** and grant permission, Packly uses Google authorization and the Google Drive API to synchronize a private snapshot of your Packly data.

The synchronization:

- is optional and is not required to use Packly's core features;
- requires your explicit authorization;
- requests only the Google Drive scope `https://www.googleapis.com/auth/drive.appdata`;
- stores the snapshot in your own Google Drive `appDataFolder`;
- uses a file named `packly_snapshot.json` in that private app-data space; and
- transfers only the Packly data needed to restore and synchronize your packing data, such as items, lists, trips, categories, preferences, and synchronization metadata.

The `appDataFolder` is private to the application and is not a normal user-visible folder in Google Drive. The snapshot belongs to the Google account that you authorize. Packly does not use a shared developer Google account, a service account, or a developer-owned cloud database for this feature.

## 4. Google account authorization

Google handles the account chooser, authorization prompt, and access-token issuance through Google services. Packly uses the authorization result to access the authorized Google Drive app-data space.

Packly does not require you to create a Packly account, does not use your Google account email as a Packly profile, and does not store your Google access token in Packly's local app data. Packly does not receive or retain your Google password.

Google's handling of information is governed by Google's policies, including the [Google Privacy Policy](https://policies.google.com/privacy).

## 5. Information sent to the developer

Packly does not send your packing items, lists, trips, notes, or Google Drive snapshot to the Packly developer. The optional synchronization is performed between the app and the Google Drive account that you authorize.

Packly does not use advertising, analytics, crash-reporting, or profiling services in the app. Packly does not sell personal information and does not share Packly content with third parties for their own marketing.

## 6. Network and technical permissions

Packly uses an Internet connection only when needed for the optional Google Drive authorization and synchronization feature. It also checks network availability to show offline status and retry guidance.

Packly may request Android notification permission for local packing-deadline reminders. These reminders are generated on the device; Packly does not send notification data to a developer-owned server.

## 7. Security

Packly sends Google Drive requests over HTTPS and does not store the Google access token in its own local data. The Android application disables automatic backup of its app data. No method of storage or transmission can be guaranteed to be completely secure, so you should also protect your device and Google account with the security controls provided by Android and Google.

## 8. Retention and deletion

### Local data

Your locally stored Packly data remains on your device until you delete or change it in the app, clear the app's data, or uninstall the app. The developer cannot remotely access or delete local device data.

### Google Drive snapshot

If Google Drive synchronization is enabled, the remote snapshot remains in your authorized Google Drive app-data space until you delete it. In Packly, use **Delete remote backup** to request deletion of the Packly snapshot. Packly attempts to verify that the remote snapshot is gone. If the device is offline or the deletion cannot be verified, retry when the connection is available.

You can also manage or revoke Packly's Google authorization from your Google Account settings. Revoking authorization stops future access; it does not necessarily delete an existing snapshot, so use **Delete remote backup** first when possible.

Packly does not maintain a separate copy of the remote snapshot on developer-controlled infrastructure. If you need help with the deletion controls, contact us at the address below. Please do not send passwords, access tokens, or private account credentials by email.

## 9. Children

Packly does not knowingly collect personal information from children. The app does not require an account or personal information for its core features. If you believe that a child has provided personal information to us, contact us so we can review the situation.

## 10. Changes to this policy

We may update this Privacy Policy when Packly's data practices or applicable requirements change. The current version will be published at this URL, together with its latest update date.

## 11. Contact

For questions about this Privacy Policy or Packly's data handling, contact:

**[the.gusanito.lab@gmail.com](mailto:the.gusanito.lab@gmail.com)**
