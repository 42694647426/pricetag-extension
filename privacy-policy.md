# Privacy Policy for PriceTag Extension

**Effective Date:** March 23, 2026

## Introduction
This Privacy Policy outlines how the PriceTag Chrome Extension ("PriceTag", "we", "our", or "us") handles the information of our users ("you"). Our primary goal is to provide a seamless price-tracking experience while prioritizing your privacy and data security.

## Data Collection and Usage
PriceTag is designed with privacy in mind. We minimize the data we collect and keep as much data local to your device as possible.

### 1. Data Stored Locally
*   **Tracked Items:** The URLs, product names, CSS selectors, and tracked prices of the items you choose to monitor are stored locally on your device within your browser's local storage (`chrome.storage.local`).
*   **API and SMTP Keys:** If you utilize the advanced AI parsing (Gemini API) or the email notification features, your API keys and SMTP configuration/email addresses are stored locally on your device. We do not transmit these keys or emails to our own servers. They are sent directly to the respective API endpoints (Google Gemini and Google Apps Script).

### 2. Network Requests
To check for price updates, PriceTag makes direct HTTP/HTTPS requests from your browser to the URLs of the products you are tracking. 
*   These requests originate directly from your IP address.
*   We do not route these requests through a proxy or intermediate server owned by us.
*   If you use the AI parsing feature, the HTML snippets of the pages you track are sent to the Google Gemini API according to the API key you provide. Please refer to Google's Privacy Policy regarding data sent to the Gemini API.
*   If you use the Email alert feature, an email payload is sent to the Google Apps Script endpoint you configured.

### 3. Personal Data
We do not collect, store, sell, or rent your personal data (such as your name, browsing history outside of tracked URLs, or demographic information). We do not run analytics trackers or third-party advertising SDKs in the extension.

## Data Sharing and Disclosure
We do not sell, trade, or otherwise transfer your locally stored data to outside parties. All data remains within your browser profile unless explicitly transmitted to third-party services (like the Gemini API or your personal Google Apps Script endpoint) as configured and requested by you to utilize specific features of the extension.

## Your Consent
By using the PriceTag extension, you consent to this privacy policy.

## Changes to Our Privacy Policy
If we decide to change our privacy policy, we will post those changes on this page. Minor changes will be made without notice, while significant changes will be communicated via an extension update notice.

## Contacting Us
If there are any questions regarding this privacy policy, you may contact the developer via the Chrome Web Store support tab.
