# Primary Idea: Digital Udhaar (Credit) Ledger

**What it is:** A simple web/mobile app that replaces the paper udhaar notebook for karyana store owners — add a customer, record what they owe, mark payments, and always know who owes how much.

**Why this one (not the other 3):**
- Happens daily, not occasionally.
- Has a real, admitted cost: ~₹500-700/month lost from forgotten or disputed entries, worse around Diwali.
- My dad described wanting exactly this, unprompted, before I asked.
- Can be built end-to-end in a week with the stack I already know (React/Node/Express + MongoDB or SQL).
- Matches the "no subscription, but will pay one-time if it saves money" signal from my interview — this is easiest to pitch as a one-time setup, not a monthly fee.

## MVP features (build this week)
1. Add a customer (name, optional phone number)
2. Add an udhaar entry (item/amount, date) against a customer
3. Mark a payment received (reduces their balance)
4. See each customer's current balance at a glance
5. Customer list sorted by highest amount due
6. Simple login so only the shop owner can edit entries

## Features to add later (after the MVP works)
1. WhatsApp reminder to a customer when their udhaar crosses a set limit
2. Printable/shareable monthly statement per customer
3. Voice-based entry (faster than typing for quick counter use)
4. Daily/weekly summary of total outstanding udhaar across all customers
5. "Collect before X" due-date reminders (e.g., before salary day)
6. Merge with Idea 2 (billing tool): when a customer says "likh do, baad mein de dunga" during billing, auto-add straight to their udhaar instead of a separate step
7. Phase 2: fold in Idea 3 (low-stock alerts) and Idea 4 (promotions) once the core ledger is in daily use

> This is a working draft based on today's interview with myself/family. Finalize after the real 5-owner interviews (due 2 Nov) — if the idea changes based on what they say, update this file.
