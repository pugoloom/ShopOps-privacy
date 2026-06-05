# ShopOps Privacy Policy

Last updated: May 27, 2026

ShopOps is a Chrome extension for managing shop inventory, sales, expenses, reports, and audit history using Google Drive and Google Sheets files owned by the user.

## Single Purpose

ShopOps provides lightweight business record management for a user's shops. It does not monitor browsing activity, display advertising, or provide unrelated services.

## Data Accessed And Created

ShopOps handles the following data only when the user signs in or uses its features:

- Google account email address for sign-in identity and audit log attribution.
- A Google Drive workspace created for ShopOps, including the `ShopOps_Do_Not_Delete` folder and its business folders.
- Google Sheets files created for inventory, sales, expenses, reports, internal configuration, and audit logs.
- Business information entered by the user, which may include shop name, address, phone number, GSTIN, product records, stock quantities, pricing, sales amounts, payment mode, expense amounts, and notes.
- CSV or XLSX inventory files expressly selected by the user for import, and exported CSV files generated at the user's request.

ShopOps uses the `drive.file` Google OAuth permission so it can access only files it creates or that the user uses with ShopOps. It does not request access to all Google Sheets or all Google Drive files.

## How Data Is Used

ShopOps uses data only to:

- Authenticate the user and attribute actions in the audit log.
- Create and maintain the user's Drive/Sheets workspace.
- Display, add, edit, import, export, validate, repair, and report on business records requested by the user.
- Preserve the currently selected workspace and shop in the installed extension for the user's convenience.

## Storage And Transfers

Business records are stored in the user's own Google Drive and Google Sheets. The installed extension stores the signed-in email address and active workspace metadata in Chrome local storage for convenience. ShopOps also stores workspace metadata in its hidden `_internal_config` sheet so the same Google account can reconnect to existing ShopOps files after reinstalling the extension.

ShopOps communicates with Google APIs over HTTPS to perform the user-facing features described above. The current extension does not transmit business records to a ShopOps-operated server and does not include third-party analytics or advertising services.

## Sharing And Sale Of Data

ShopOps does not sell user data. It does not use or transfer user data for personalized advertising, credit decisions, lending, or data brokerage.

ShopOps transfers data only to Google APIs as necessary to provide its features, or where required by applicable law or necessary to protect against abuse or security threats.

## Human Access

ShopOps does not provide the developer with routine access to user business records. Human access would occur only with the user's explicit consent for a specific support request, when required by law, or when necessary for security purposes.

## Google API Limited Use

ShopOps' use and transfer of information received from Google APIs will adhere to the Chrome Web Store User Data Policy, including the Limited Use requirements.

## User Control And Deletion

Users own and control their Drive and Sheets data. A user can review, export, move, or delete the `ShopOps_Do_Not_Delete` workspace in Google Drive. Users can use **Settings > Sign out** to revoke the current Google token, revoke ShopOps access from their Google Account permissions, and remove the extension from Chrome to remove its locally stored app state.

## Contact

For privacy or support questions, contact: pugoloom@gmail.com
