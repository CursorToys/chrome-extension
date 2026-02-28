# Privacy Policy for CursorToys Sidekick

**Last Updated:** February 28, 2026

## 1. Introduction

This Privacy Policy explains how **CursorToys Sidekick** ("the Extension") handles information. We take your privacy seriously—mostly because we believe your code and data are your business, not ours. The Extension is designed to facilitate the transfer of snippets from your browser to your Cursor editor.

## 2. Information Collection and Use

* **No Personal Data Collection:** The Extension does not collect, store, or transmit any personal identification information (PII) to external servers.
* **User-Generated Content:** When you use the "Send to Cursor" feature, the Extension captures the selected text, the page URL, and the page title. This data is sent directly to your local installation of Cursor via a URI handler (`cursor://` or `vscode://`).
* **Local Storage:** Any custom HTML mappings or selectors you "teach" the Extension are stored locally in your browser's `chrome.storage.local`. We do not have access to these mappings.

## 3. Data Transmission

* **Direct Link:** All data transmission occurs locally on your machine or through deep-linking protocols between your browser and your code editor.
* **No Third-Party Sharing:** We do not sell, trade, or otherwise transfer your data to outside parties. There is no cloud backend associated with CursorToys Sidekick that stores your snippets.

## 4. Permissions Justification

* **Storage:** Used solely to save your custom UI mappings locally.
* **ActiveTab/Scripting:** Used to read the text you select and inject the "Send to Cursor" buttons on mapped elements.
* **ContextMenus:** Used to provide the right-click "Send to Cursor" functionality.

## 5. Security

We follow industry standards to protect the information processed by the Extension. Since no data is stored on our servers, the risk of a data breach from our side is effectively zero.

## 6. Changes to This Policy

We may update our Privacy Policy from time to time. Any changes will be posted on this page with an updated "Last Updated" date.

## 7. Contact Us

If you have any questions about this Privacy Policy, you can reach out via our GitHub repository: [[CursorToys](https://github.com/CursorToys/chrome-extension/issues)].
