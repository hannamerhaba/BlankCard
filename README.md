# BlankCard

One Visa card with your own rules, plus an AI advisor that suggests but never decides.

This is a Sprint Week prototype. Open `index.html` in a browser; there is nothing to install or build.

## What it shows

- **Home**: monthly overview (debit paid, credit outstanding, balance), recent payments with a way to change the payment tool within 24 hours (a red dot means the advisor has a better card), and a "Try a payment" simulator.
- **Cards**: your cards stacked like a wallet. Drag a card to set the priority (top is used first) and tap it for its budget and categories.
- **Guard (Repayment Guard)**: keeps the direct debit account funded before card repayments, and lists what is due in the next 10 days.
- **Advisor**: rewards earned, cashback suggestions and a weekly spending digest.
- **Settings**: how much the advisor may do on its own, separately for payments and for moving money, plus card management. Budgets and transfer limits always stay with the user.

## Please note

- All data is sample data. No real bank, card or payment network is connected.
- The advisor is scripted. It does not call any AI service.
- Reset the demo Settings.
- Cross-issuer routing and the 24-hour change of a past payment are proposals. Visa Flexible Credential today routes among accounts at one issuer.
- Bank, card and Visa logos and card images belong to their owners and are used only to illustrate the concept. This is not an official Visa product.
