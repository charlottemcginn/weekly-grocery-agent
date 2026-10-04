# Weekly Grocery Agent

A reusable prompt for a weekly grocery assistant that learns your food preferences, plans meals, reduces produce waste, and prepares an online grocery cart for your review.

**The assistant never places orders or enters checkout.** You review the cart and complete any purchase yourself.

## Use the prompt

1. Open [PROMPT.md](PROMPT.md) and copy its contents into an assistant with access to your grocery service and a supported scheduling feature.
2. Answer its setup questions and provide the food logs, purchase history, or meal recommendations you want it to use.
3. Complete a supervised first run before enabling the weekly schedule.

The assistant should explain which account connections, device availability, and scheduling capabilities your setup requires. This repository contains a prompt, not a running service.

## What it covers

- A private, reusable food profile and pantry record.
- Weekly stock check-ins and meal planning around your household and goals.
- Produce quantities based on consumption, leftovers, and waste.
- Grocery sourcing, package sizes, nutrition estimates, and budget checks.
- Cart preparation that preserves manual changes and avoids duplicate additions.
- Comparison of each prepared cart with the order actually placed and delivered, so later estimates reflect your edits without confusing purchases with consumption.

Keep personal profiles, nutrition records, credentials, and order history in private storage.
