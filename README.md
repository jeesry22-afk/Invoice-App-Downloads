# Quotely Android downloads

**Download the current APK:** [Quotely Version 1.0.1](https://github.com/jeesry22-afk/Invoice-App-Downloads/raw/refs/heads/main/Quotely-Android-v1.0.0-preview.27.apk)

Preview 27 adds Android notifications for client quotation approvals, rejections, and simulated payments. Tapping an alert opens the related document; an alert received while Quotely is open appears in the app. Android may ask for notification permission. The Dashboard bell continues to show updates. Phone alerts require the Firebase sender to be configured on the server.

This build uses the updated demo exchange rate of PHP 62 per USD for new conversions. Business setup includes an account-scoped action to label older paid invoices whose source currency was never saved; amounts and payments are unchanged. The Dashboard loading layout matches its greeting and illustration, and quotation review links have no separate header. You can delete individual updates from the Dashboard bell, which keeps the newest 100 per account. The quotation and invoice web links use Quotely's blue theme. The payment page has no separate top header, and the six-digit code step has no in-page back button. Account pages recover from brief connection failures after Android has left the app idle.

You can choose PHP, USD, or EUR in Business setup. The simulated invoice checkout displays the converted amount when a client changes payment currency. Before a demo payment is recorded, the client must verify the email address for their receipt with a six-digit code. Codes expire after 10 minutes, with limits on attempts and resends. Invoice details refresh when you return to the app or tap Refresh. No real money is transferred.

This build also includes Google sign-in, cloud records, quotation and invoice emails, client currency conversion on documents, quotation review links, a simulated payment page with wallet and demo card choices, and email receipts. Demo card details should be fictional; expiration and CVC stay in the browser.

On Android, open the APK after downloading it and allow installation from your browser or file manager if prompted. You can install it over the previous preview without uninstalling. Keep a copy of important records because in-app backup and restore are not yet available. This preview is signed with an Android development key, not a production Play Store release.

SHA-256: `04E2AD2FC648894696991BA484FC2162B7900692A894F1446838191038894228`

The app source code is kept in a separate private repository. This repository contains public download information and the current APK.
