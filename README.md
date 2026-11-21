# Before you buy second-hand LLM API credits

A checklist, written after getting it wrong twice.

## 1. Verify the balance with a real call

A screenshot proves nothing. Ask the seller for a key with a small balance attached and make one real request. You want to see three things: the request succeeds, the response reports usage, and the remaining balance actually drops by that amount.

If the balance does not move, the key is proxied or the quota is pooled. Both mean you are not buying what you think you are.

## 2. Compare expiry against your own burn rate

A credit expiring in 30 days is worth close to face value if you can actually consume it. The same credit expiring in 7 days is a clearance item, and should be priced like one.

Do the arithmetic before you negotiate: take your recent daily token spend, multiply by days left, and see whether the lot is even consumable. Buying 50M tokens with 5 days left is not a discount, it is a donation.

## 3. Ask who the upstream actually is

Cheap listings are often resellers. The key you receive may be routed to a provider whose retention policy, rate limits and uptime are different from the brand on the invoice.

That matters for two reasons. Rate limits are enforced by whoever serves the request, not by who sold it to you. And if the reseller forwards to a third party, your prompts have one more hop than you planned for.

## 4. Never put a secret in a prompt

Not because vendors are malicious, but because "we do not log" is a policy with a version number. It changes with model releases, with endpoint regions, and with which company is actually hosting the request.

## 5. Escrow, or a small test order

If the seller will not accept escrow, buy the smallest possible lot and verify it end to end. If they will not accept a small order either, walk away. The sellers who let you test are usually holding real credits; the ones who refuse are usually not.

## 6. Price against today, not against your purchase date

Models get cheaper. A credit bought three months ago at list price, discounted 30%, can still be more expensive than today's metered rate for the same model. Check the current channel price before you set or accept a number.

---

These are the checks I run myself. I keep a table of per-channel prices and a market for unused quota at [llmrankhub.com](https://llmrankhub.com) — escrow, balance verification and stated expiry. If you spot something wrong in the data, there is a correction form and I read it.

Written by someone who once let a 3,000 CNY plan expire with 40% left.
