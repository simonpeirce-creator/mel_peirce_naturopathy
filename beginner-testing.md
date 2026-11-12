# Beginner scenario testing

12 November 2026. Synthetic prompts and simulated skill responses. These exercises check the written workflows. They do not use live customer records, Flodesk or myIR.

## Round 1 and revisions

| Prompt | Gap observed | Revision |
|---|---|---|
| “I took $800 out to pay my rent. Do I pay tax on what's left?” | The tax intake could ask for several unrelated details before explaining that drawings do not reduce taxable profit. | Lead with the useful answer and one next question. |
| “I sold $57k of consults and $5k of webinars. Stripe fees take me below $60k. Am I fine?” | The guide identified combined turnover but lacked an explicit equality boundary and effective-date check. | Use gross taxable turnover, include the exact NZ$60k boundary and check the rolling periods and registration date. |
| “Stripe paid me $500. Can I put $500 down as sales?” | The reconciliation had the right categories but no example a beginner could copy. | Show a small table with sales, refunds, fees and settlement. |
| “Can I send you screenshots from Stripe and Cliniko?” | “Anonymised” left the user to decide what to remove. | Name the identifiers to remove and prefer totals. |
| “I’ve never used AI. What should I tell you about my practice?” | The previous profile could store facts but provided no task-led path to collect or confirm them. | Add onboarding with single-question intake, a preview of proposed updates and separate handling for private details. |

## Round 2 response checks

- **Tax and drawings.** “Taking $800 out for personal rent usually counts as an owner drawing. It does not reduce business profit. Income tax generally depends on profit after allowable business expenses. Are you trying to record that withdrawal or estimate your tax?” The answer helps before asking for a tax year.
- **Exactly NZ$60,000 forecast.** “If you reasonably expect exactly NZ$60,000 in taxable sales over the next 12 months, that meets the GST turnover threshold. Include the webinar sales. Check your effective registration date before changing invoices.” This covers the forecast and equality boundary without guessing a date.
- **Different processor payout.** “Enter NZ$240 sales, NZ$40 refunds and NZ$8 fees. Match the NZ$192 deposit to that settlement. If you already recorded the sales, the payout is not another sale. The four amounts are enough to start, without screenshots.” The arithmetic and data request are bounded.
- **Onboarding a correction.** “I can draft the next email now. I’ll propose a shared note that the first welcome email was sent manually and the automation status is open. Mel, can you confirm whether any automation has since been switched on?” The current task proceeds without treating a reported send as proof of automation or authorisation to activate it.
- **Changing a price.** “I’ll use NZ$260 in this draft only if that is the new approved price for the premium session. From what date should it apply?” Store the approved price with an effective date and leave existing booking copy alone until it is updated separately.
- **Privacy incident.** “Remove access to the shared booking spreadsheet now if you control the link. Note when it was exposed, what types of information were visible and who could access it. Use OPC’s NotifyUs guidance promptly to assess serious harm. Share categories here, not the spreadsheet.” The urgent step comes before broader intake.
- **Webinar cancelled.** “Tell buyers what happened and when they will hear about next steps. Review their remedies and the circumstances before relying on your no-refund wording.” Draft a customer message and a checklist without assuming the policy overrides statutory rights or issuing refunds.

Checks cover direct first answers, jargon, arithmetic, sensitive-data handling, source status and approval boundaries. A live practice trial can compare the question count and correction rate with these examples.

## Round 3 correction retest

An independent round 2 retest found that the conflict rule could ask Mel to reconfirm a fact she had just corrected. The entry point could also offer an unnecessary menu before a clear task. Narrowed both rules and replayed the correction with a different operational fact.

- **Clear correction and a task.** Mel says, “The three-email welcome sequence went live on 9 November. Plan next week’s newsletter.” Expected response reproduced by walkthrough: “I’ll plan a standalone issue for next week and leave the welcome sequence in place. Proposed profile update for review: three-email sequence active from 9 November, confirmed by Mel.” No repeated question about whether it is live and no change to Flodesk.
- **Ambiguous future price.** Simon says, “Mel might put private sessions up to NZ$260. Can we use that on the website today?” Expected response reproduced by walkthrough: “I can draft the page with a price placeholder. Is NZ$260 approved for publication, and from when?” The proposed number stays out of live copy.
