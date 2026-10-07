# Meta-partner chat/DM automation tools (ManyChat and competitors) and their affiliate programs

Research date: 2026-10-07. Method note: the network proxy BLOCKED direct fetches of manychat.com, chatfuel.com, respond.io, sendpulse.com and developers.facebook.com, so almost every fact below comes from web-search result snippets (which quote the vendor pages) rather than a full read of the page. Verification labels used:
- **[V-snippet]** = search snippet quoting the vendor's own page/docs (the URL is the vendor's). Probably accurate but not read in full.
- **[2nd]** = third-party/aggregator source (affiliate directories, review blogs). Treat as unconfirmed.
- **[Inference]** = my reasoning, not a sourced fact.
The Meta Partner Directory (facebook.com/business/partner-directory) could not be queried, so **no partner status below was checked against Meta's own directory.**

## Q1. Is ManyChat's access to Facebook/Instagram unique, or the standard official API available to all Meta partners?

### Takeaway
ManyChat's access is **not unique**. It uses Meta's public, official APIs (Messenger Platform, Instagram Messaging API / "Messenger API for Instagram", WhatsApp Business Platform), which any developer can use once its app passes Meta App Review for Advanced Access. The "Meta Business Partner" badge is a vetting/listing credential, not a private API. Chatfuel, respond.io, WATI, AiSensy, Interakt, Gupshup, 360dialog, Twilio, Zoko and others use the same APIs, and several also claim partner or BSP status.

### Cited Findings
- ManyChat says it is a Meta Business Partner "officially approved to work directly with Instagram and Facebook Messenger APIs"; Meta reviews the platform, security practices and API usage before granting the status and can revoke it — [ManyChat blog: what it means to be a Facebook business partner](https://manychat.com/blog/what-it-means-to-be-a-facebook-business-partner/) [V-snippet]; see also [ManyChat blog: is ManyChat officially approved by Instagram](https://manychat.com/blog/is-manychat-officially-approved-by-instagram/) [V-snippet]
- ManyChat launch coverage says the Messenger API support for Instagram "is available for all developers" — [jotup.co (repost of ManyChat/press)](https://jotup.co/node/1363410) [2nd]
- Meta docs: apps must complete App Review to request permissions with Advanced Access. Tech Providers whose app serves multiple businesses through Instagram Login, or apps serving Instagram professional accounts they don't own, need Advanced Access. The `instagram_business_manage_messages` permission enables messaging — [Meta for Developers: App Review for Instagram API](https://developers.facebook.com/docs/instagram-platform/app-review) [V-snippet]; [Instagram Platform overview](https://developers.facebook.com/docs/instagram-platform/overview) [V-snippet]
- ManyChat claims to be "the world's largest Instagram DM Automation platform", powering conversations for 100,000+ Instagram accounts — [search snippet citing ManyChat](https://manychat.com/blog/is-manychat-officially-approved-by-instagram/) [V-snippet]
- Even ManyChat users can be "ineligible for using Instagram business messaging API" (Meta-side account eligibility rules apply to everyone) — [ManyChat Community thread](https://community.manychat.com/general-q-a-43/ineligible-for-using-instagram-business-messaging-api-4581) [V-snippet, title only]
- Chatfuel describes itself as an official Meta Business Partner supporting Instagram, Facebook, WhatsApp, TikTok and website chat — [Chatfuel docs: Supported Channels](https://chatfuel.com/docs/getting-started/supported-channels) [V-snippet]
- WhatsApp: Meta owns the WhatsApp Business API, and most SMBs get access through a Business Solution Provider (BSP) that Meta approved. Twilio, 360dialog, WATI, AiSensy, Interakt, Gupshup, Infobip, Zoko, respond.io and Bird are listed as BSPs — [lilachbullock.com](https://www.lilachbullock.com/whatsapp-business-api-providers-small-business/) / [typebot.com blog](https://typebot.com/blog/whatsapp-business-api-providers) [2nd]
- Meta's Tech Provider program lets ISVs integrate the WhatsApp API, often through a Solution Partner such as 360dialog, and registering "unlocks new features, greater control over WABAs, and direct access to Meta's channels" — [360dialog docs: Understanding the Meta Tech Provider Program](https://docs.360dialog.com/partner/get-started/tech-providers/understanding-the-meta-tech-provider-program) [V-snippet]
- CreatorFlow (a small Instagram DM tool) markets itself as "100% Meta-compliant", i.e., it uses the same official API — [CreatorFlow affiliate page](https://creatorflow.so/es/affiliate-program) [V-snippet]

### Inferences
- [Inference] ManyChat's real advantages are scale, brand, early launch-partner status (it was among the first tools on the Instagram Messaging API in 2021) and the badge's trust signal, not exclusive API features. Any app approved for `instagram_business_manage_messages` / `pages_messaging` gets the same messaging capabilities and the same 24-hour-window and rate-limit rules.
- [Inference] "Meta Business Partner" (badge/directory listing), "Tech Provider" (registered ISV, required for multi-client WhatsApp/IG apps) and "WhatsApp BSP / Solution Partner" (resells WhatsApp API access and billing) are three different tiers. Only the BSP tier carries a real commercial privilege (direct WhatsApp billing/onboarding). ManyChat is NOT commonly listed as a WhatsApp BSP. It integrates WhatsApp as a tech provider.

### Gaps
- Could not query Meta's Partner Directory to confirm which vendors currently hold the badge (blocked; directory is JS-rendered). respond.io, Sprout Social, Hootsuite, Kommo, Trengo, Tidio, SendPulse badge status: UNVERIFIED.
- Could not read Meta developer docs in full (blocked). Current IG messaging rate limits and the exact eligibility rules are not captured.

## Q2. Which Meta-partner tools pay affiliates recurring commission (ideally 25%+, lifetime)? Per-vendor details

### Takeaway
25%+ recurring and **lifetime**: Tidio (30%, [2nd]), CreatorFlow (30–50%, [V-snippet], tiny vendor, partner status unverified), Kommo (35–50%, duration unclear), respond.io partner program (15–40% lifetime [V-snippet], aimed at agencies). 25%+ but **capped**: ManyChat (30–50%, 12 months), Chatfuel (30–40/50%, 12 months), SendPulse (30–40%, 24 months). WhatsApp BSPs mostly pay less (WATI 20%, AiSensy 15% standard, Gallabox 20%), with richer terms only for solution/reseller partners.

### Cited Findings (per vendor)

**ManyChat** — Instagram/Messenger/WhatsApp/SMS/email DM automation for creators and SMBs. Partner: Meta Business Partner (self-stated [V-snippet], above).
- Pricing: Free plan (up to 1,000 contacts, IG+Messenger). Pro from $15/mo for 500 contacts, scaling with contacts. Since March 2, 2026, billing is based on Active Contacts. ManyChat AI is a +$29/mo add-on. Elite is custom-priced — [featurebase.app](https://www.featurebase.app/blog/manychat-pricing), [chatarmin.com](https://chatarmin.com/en/blog/manychat-pricing) [2nd]
- Affiliate: up to 50% for the first 12 months. Tiers: about 30% (0–30 paid signups), 40% (31–200), 50% (201+). Commission recalculates if the customer upgrades within 12 months. Cookie 120 days — [manychat.com/affiliate (snippet)](https://manychat.com/affiliate) [V-snippet]; [getreditus](https://getreditus.com/affiliate-programs/manychat) [2nd]. Snippets disagree slightly on the bottom tier (27–30%).
- Payout: run via PartnerStack (Stripe/PayPal) per one source, Impact per another. Minimum payout $10 vs $100 conflicts between sources — [uppromote directory](https://uppromote.com/affiliate-directory/manychat/) [2nd]. Brand-bidding policy: NOT FOUND ("paid ads accepted with restrictions on brand bidding", [2nd], unconfirmed).

**Chatfuel** — AI chatbot builder for Instagram, Messenger, WhatsApp, TikTok, web. Partner: official Meta Business Partner (self-stated [V-snippet]).
- Affiliate: recurring revenue share for the first 12 months. 30% (up to 300 paying referrals), 35% (300–400), 40% (400+). The landing page headline says "up to 50%". Paid monthly via PayPal, $50 minimum — [Chatfuel docs: affiliate program](https://chatfuel.com/docs/billing/chatfuel-affiliate-program), [chatfuel.com/affiliate-program](https://chatfuel.com/affiliate-program) [V-snippet]. Cookie and brand-bidding: NOT FOUND. Pricing: NOT VERIFIED.

**respond.io** — omnichannel customer-conversation inbox for mid-market (WhatsApp, IG, Messenger, etc.). Partner: listed as a WhatsApp BSP [2nd]. Meta Business Partner badge unverified.
- Programs: Referral = one-time $100 per new customer. Partner/affiliate = 15–40% **lifetime** commission, 90-day cookie, with a partner manager and directory listing; aimed at agencies/consultants — [respond.io/affiliate-program](https://respond.io/affiliate-program), [respond.io/partners](https://respond.io/partners), [respond.io/referral](https://respond.io/referral) [V-snippet]. Pricing and payout terms: NOT VERIFIED.

**WATI** — WhatsApp Business API inbox, broadcasts and chatbots for SMBs. Partner: WhatsApp BSP [2nd].
- Pricing: Growth plan $49/mo [2nd: ycloud.com blog](https://www.ycloud.com/blog/wati-pricing).
- Affiliate: recurring. Vendor page mentions a "12-month earning period" — [wati.io/become-an-affiliate](https://www.wati.io/en/become-an-affiliate/) [V-snippet]. One aggregator says 20% for the first two years, another lists 16% — [flexoffers](https://www.flexoffers.com/affiliate-programs/wati-io-affiliate-program/) [2nd]. **CONFLICT:** duration (12 vs 24 months) and rate unresolved. Runs on PartnerStack per [market.partnerstack.com/page/watiio](https://market.partnerstack.com/page/watiio).

**AiSensy** — WhatsApp marketing/broadcast platform (India-focused). Partner: WhatsApp BSP [2nd].
- Affiliate: 15% recurring. Prime Plus tier up to 30%, which also earns on WhatsApp conversation charges, Meta ad spend, and AI and ad credits — [AiSensy blog](https://m.aisensy.com/blog/earn-higher-commissions-by-becoming-an-aisensy-affiliate-partner/), [aisensy.com/partner](https://aisensy.com/partner) [V-snippet]. Duration, cookie and payout: NOT FOUND.

**Gallabox** — WhatsApp CRM/automation. Partner: Meta status unverified.
- Affiliate: 20% recurring, 90-day attribution, run on Tapfiliate. Solutions Partner Program: 30% recurring for the first 24 months, scaling to 60% at milestones and earning for 5 years — [gallabox.com/affiliate-partner-program](https://gallabox.com/affiliate-partner-program), [gallabox.com/whatsapp-partner-program](https://gallabox.com/whatsapp-partner-program) [V-snippet].

**SendPulse** — email, chatbots (IG/Messenger/WhatsApp/Telegram), SMS and CRM. Claims 3M+ users ([sendpulse.com/partners/agency](https://sendpulse.com/en/partners/agency) [V-snippet, title]). Partner status: unverified.
- Affiliate: starts at 30% of plan purchases plus 10% of balance top-ups, rising to 40% when referrals spend $1,000+/month. Earned on all payments for **two years** — [sendpulse.com/partners/affiliates](https://sendpulse.com/en/partners/affiliates) [V-snippet]. Cookie, payout and brand-bidding rules: NOT FOUND.

**Tidio** — live chat plus AI chatbot (Lyro) for e-commerce, with Messenger/IG/WhatsApp integrations. Partner status: unverified.
- Affiliate: 30% lifetime recurring, 30-day cookie, PartnerStack — [revshare.so](https://www.revshare.so/programs/advertiser/tidio), [market.partnerstack.com/program/tidiollc](https://market.partnerstack.com/program/tidiollc) [2nd]. The vendor help page exists ([help.tidio.com affiliate article](https://help.tidio.com/hc/en-us/articles/5444003167388-Affiliate-Program)) but its terms were not read.

**Kommo (formerly amoCRM)** — messenger-first sales CRM (WhatsApp/IG/Messenger inbox and pipelines). Partner status: unverified.
- Affiliate: 35% recurring, rising to 50% after $10,000 in sales — [theaffiliatemonkey](https://theaffiliatemonkey.com/affiliate/kommo-affiliate-program/) [2nd]. Vendor KB: [kommo.com/support/kb/partners-program](https://kommo.com/support/kb/partners-program) (not read). Lifetime vs capped: NOT CONFIRMED.

**Customers.ai (formerly MobileMonkey)** — now mainly website visitor ID and ad audiences. Its Messenger/IG chat roots are de-emphasized.
- Affiliate: 10% recurring for the referral's lifetime, with higher rates at volume. Agency partner program: 20% — [customers.ai partner page](https://customers.ai/?p=8804) [V-snippet], [revshare.so](https://www.revshare.so/programs/advertiser/customers-ai) [2nd].

**Trengo** — omnichannel inbox. Affiliate: €400 per qualified demo booked, with tiered accelerators. Service partners get percentage-based recurring commission (rate not stated) — [trengo.com/partners/affiliates](https://trengo.com/partners/affiliates), [trengo.com/partners/service](https://trengo.com/partners/service) [V-snippet].

**CreatorFlow** — small Instagram DM auto-reply tool for creators. Says it is "100% Meta-compliant" but makes no badge claim.
- Affiliate: 30–50% **lifetime** recurring, 60-day cookie, monthly PayPal or bank payout with a $50 minimum. Apply by email — [creatorflow.so/affiliate-program](https://creatorflow.so/es/affiliate-program) [V-snippet]. Pricing: NOT FOUND.

**Not researched or no data found:** Interakt, Gupshup, 360dialog, Twilio (enterprise CPaaS with partner/reseller programs, not classic affiliate), Sprout Social, Hootsuite, Zoko (no affiliate program found), CM.com, ChatDaddy, Botsonic, Inro, LinkDM.

### Commission-per-customer estimates ([Inference], from figures above)
| Tool | Assumed plan $/mo | Rate | $/customer/mo | Max $/customer | Paying customers for ~$100–150/mo |
|---|---|---|---|---|---|
| ManyChat | $15 (Pro entry) | 30% | $4.50 | $54 (12 mo cap) | ~22–33, and they must be replaced yearly |
| WATI | $49 (Growth) | 20% | $9.80 | $118–235 (12 or 24 mo, conflicting) | ~10–15 |
| Chatfuel | price unverified | 30% | — | 12 mo cap | — |
| SendPulse | unverified | 30% | — | 24 mo cap | — |
| Tidio / CreatorFlow / respond.io | unverified | 30% / 30–50% / 15–40% | — | lifetime | — |
- [Inference] For a single customer to generate $100–150 in total commissions: ManyChat at $15 never gets there (caps at $54). The referral must be on a plan of roughly $28–42/mo or more to reach $100–150 within 12 months. WATI Growth reaches $100 in about 11 months and $150 in about 16 months, which only works if the 24-month figure is right.
- [Inference] Lifetime programs (Tidio, CreatorFlow, respond.io partner, possibly Kommo) are the only ones where a stable book of customers compounds indefinitely. Since the API access is identical, an affiliate loses no product "access" advantage by choosing them over ManyChat.

### Gaps
- Brand-bidding/PPC rules: not found for any vendor. These usually sit in PartnerStack/Impact terms behind login.
- Pricing for Chatfuel, respond.io, Tidio, Kommo, SendPulse and CreatorFlow: not verified (vendor domains blocked).
- Payout terms for most vendors are missing or conflicting (ManyChat minimum $10 vs $100).
- WATI rate (16% vs 20%) and duration (12 vs 24 months) conflict.
- Meta partner badge for every vendor except ManyChat and Chatfuel (self-stated) is unverified against Meta's directory.
- Customer counts: only ManyChat (100k+ IG accounts) and SendPulse (3M+ users) found, both vendor claims.
