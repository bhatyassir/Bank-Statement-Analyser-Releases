# Changelog

What changed in each version of Bank Statement Analyser Pro, newest first. The installer for every version is on the [Releases page](../../releases).

## 3.0.3 – 21 Oct 2026
- **Update notice in the desktop app.** A bar at the top tells you when a newer version is available, with a Download button. It is hidden until a newer version exists, and you can dismiss it until the next one.

## 3.0.2 – 21 Oct 2026
- **Update notice in the web app.** The same "new version available" bar.
- **Returned payments are recognised.** A debit and an equal credit with the same narration on the same day (for example a failed standing instruction that bounced back) are both tagged *Reversal / Return*, so they no longer inflate turnover or the category they came from.
- **Fixed deposits.** Closing a deposit before maturity or at maturity is tagged *Closure Proceeds*, and its interest *Interest Earned*. Opening a deposit from net or mobile banking is treated as a transfer to yourself, not an expense.
- **Insurance.** JBY, SBY and HLIC premium debits are tagged *Insurance*.
- **Transfers to your own accounts.** HDFC IMPS and UPI transfers made to your own name are tagged as contra entries even when the other account's statement is not loaded. Payments that merely mention your name as the beneficiary are not treated as self-transfers.
- **Statement readers.** Many accuracy improvements for Axis, ICICI, Canara, HDFC, J&K Bank (Basic, mPay, mPay2 and net-banking) and others: more layouts read correctly, dates are shown uniformly as dd-mm-yyyy, and wrapped narrations no longer lose or gain text.

## 3.0.1 – 20 Oct 2026
- Maintenance release.

## 3.0.0 – 9 Oct 2026
- **Automatic 14-day free trial** on new installs.
- Licence and end-user agreement screens.
- Installer builds are produced with version details embedded in the program file.
- Assorted fixes to statement readers, tagging and the processing pipeline.

## 2.5.2 – 19–28 Sep 2026
- **Top Parties** analysis sheet with volume rankings and key figures.
- **Party Transactions** sheet with live totals linked to the raw transactions.
- Better detection of counterparties that use trade names.
- Re-tagging after edits now carries through to the formulas.
- Read only the statements for a chosen financial year.
- Support for Mintifi loan statements.
- Cleaner dashboard: compact key figures next to the turnover reconciliation, hidden empty cards, short bank and account names, a collapsible accounts panel.
- Plainer accounting terms (*Client Mapping*, *Categorisation Rules*).
- PDF signer improvements.
