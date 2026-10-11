# Hermes Drive Uploader (Personal)

This is a private-use desktop automation application for its owner's Google Drive. It is not a public service and does not accept signups.

## Purpose
The application uploads files selected by the owner to the owner's Google Drive through the official Google Drive API. It may retrieve uploaded files to verify their contents and create read-only sharing links when the owner explicitly requests sharing.

## Privacy policy
The requested Google permission is `https://www.googleapis.com/auth/drive.file`: access is limited to files created by this application or explicitly selected for it. The application does not request Gmail, contacts, or full-Drive access.

OAuth credentials are kept in private local credential storage on the owner's computer. Files and operational receipts are stored locally and in the owner's Google Drive as requested. This public information page does not receive OAuth tokens, uploaded files, or personal account information. Google and GitHub process their own service traffic under their respective policies.

Google user data is not sold, used for advertising, or transferred to unrelated parties. A file is made accessible through a sharing link only when the owner requests it. Local receipts contain the remote file identifier, verification status and file metadata required for operation; they do not contain credential secrets.

The owner can revoke this application's access in Google Account security settings, remove local credentials, and delete files or sharing permissions in Google Drive. Revoking access does not itself delete previously uploaded files. This application follows the Google API Services User Data Policy, including Limited Use requirements.

For questions, contact the owner using this repository's Issues page. This policy describes the intended application behavior; deployment remains subject to authentication and operational verification.
