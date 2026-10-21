# Bank Statement Analyser Pro

**Turn a folder of bank statements into an audit-ready workbook.**

Bank Statement Analyser Pro reads Indian bank statements (PDF, Excel, Word, text), checks that every running balance adds up, tags every transaction, pairs up transfers between your own accounts, and produces a multi-sheet Excel workbook you can hand to a client or work from directly. It is built for Chartered Accountants, tax auditors and accounting teams.

By Shaaz Fintech.

## Download

Get the latest installer from the [**Releases page**](../../releases/latest). Download `BankStatementAnalyser_Setup_vX.Y.Z.exe`, run it, and open **Bank Statement Analyser Pro** from the Start menu. It installs for your own Windows account and does not need administrator rights.

New installs start with a free trial.

**Requires:** Windows, 64-bit.

## What it does

- **Reads the statement for you.** Drop in one statement or hundreds. The bank and layout are detected automatically.
- **Checks the arithmetic.** Opening balance, every running balance, closing balance and printed totals are verified. Anything that does not add up is flagged instead of silently accepted.
- **Tags every transaction.** Cash, UPI, NEFT/RTGS/IMPS, cheques, bank charges, loan EMIs, insurance, interest, fixed deposits, reversals and more. Add your own tagging rules.
- **Finds your own-account transfers.** Money moving between your accounts (even when only one side is in the batch) is marked as a contra entry, so it does not inflate turnover.
- **Handles returned payments.** A debit that the bank reverses the same day is recognised as a reversal and taken out of turnover.
- **Builds the workbook.** Raw transactions, party-wise summaries, top parties, turnover reconciliation, category totals and an audit summary, with live formulas so your edits flow through.
- **Splits by financial year**, and signs and unlocks PDFs.

## Banks

Statements from **J&K Bank** (several layouts, including mPay and net-banking), **HDFC Bank**, **ICICI Bank**, **Axis Bank**, **Canara Bank** and **Punjab National Bank** have dedicated readers. Other banks are read through a general reader, which is less exact: always check the balance checks in the report.

## Your data

Your statements are processed on your own computer; the app does not upload them. The app also checks this page for a newer version when it starts.

## Updates

The app tells you when a new version is available: a bar appears at the top with a **Download** button. You can also come back to this page. See the [**changelog**](CHANGELOG.md) for what changed in each version.

## Getting help

Open an [issue](../../issues) here, or contact your Shaaz Fintech representative. Please do not post statements or other personal data in public issues.

---

This repository only holds installers and release notes. The application's source code is not published here.
