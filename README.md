# TrueRate

A pricing clarity tool for owner-operator trades businesses: plumbers, HVAC techs, electricians, and handymen running one to five trucks.

Most trades owners are excellent at the work and were never shown the money math. They set their hourly rate from gut feel and what the guy down the road charges, and they price jobs the same way. TrueRate helps them stop guessing and price from what their work actually costs them.

This is an early test version (MVP). It does two things, and it does them in plain language with no accounting background required.

## What it does

**1. Find your rate.** A short, nine-question setup that figures out two numbers: what one billable hour really costs you to produce, and the least you should charge for it to keep a healthy share of every dollar. Your own pay is treated as a cost the business has to cover, not as whatever is left over at the end of the month.

**2. Price a job, three ways.** Once your rate is set, you can:
- **Build a price** from scratch by entering the hours and parts for a job.
- **Check a price** you already have in mind and find out if it is a good call.
- **Flat rate** check: enter what you charge for a job as a set price, the way a lot of owners already think, and the tool works backward to show what that price is really earning you.

If a price would leave you keeping too little of each dollar, the tool says so in plain words and shows you the price that protects you.

It also drafts honest, plain-language wording you can hand to a customer, with parts named as what they are.

## How to use it

Open the live link on your phone. Run "Find my rate" once. After that, price jobs any time. Your numbers save on your device, so the next time you open it you go straight to your results.

## Running it yourself

This is a single file. There is no install, no account, no build step.

- **To try it:** open `index.html` in any web browser.
- **To host it for testers:** this repo is set up for GitHub Pages. The live version is served from `index.html`.

## A note on saved numbers

TrueRate saves your inputs in your browser on your own device. Nothing is sent anywhere. If you open it in a different browser or clear your browser data, you will set up your rate again.

## What is not in this version yet

This is a test build meant to gather real feedback before adding more. Not yet included:
- An AI advisor that talks you through your numbers (the connection point for it is already built in)
- Good, better, best pricing options for a single job
- Sanity checks that flag when an entered number looks too low or unrealistic
- Anything based on your trade or your location
- Estimating helpers that turn square footage, fixtures, or run length into hours and parts

These are on the list for after testers tell us what matters most.

---

Built by KB Training & Development Group.
