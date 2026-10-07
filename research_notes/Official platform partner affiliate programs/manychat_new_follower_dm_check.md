# Fact-check: "ManyChat is the only platform that can auto-DM new followers; Meta gave this only to ManyChat"

Checked: 2026-10-07. Method: WebSearch only. WebFetch and curl were blocked for manychat.com, help.manychat.com, community.manychat.com, creatorflow.so, nowbam.com, chatimize.com, developers.facebook.com, quickdm.app, replykaro.com and sumgenius.ai. Every quote below is a search-engine snippet or summary, not a page I read in full.

Labels: [VS] = vendor's own wording as shown in search snippet (vendor-sourced, unread in full); [3P] = third-party / competitor claim; [INF] = my inference.

## 1. ManyChat feature
- Names: "Follow to DM" / "Say Hi to New Followers" (Instagram only).
- Help article title: "Follow to DM on Instagram: Say Hi to New Followers [BETA]" -- https://help.manychat.com/hc/en-us/articles/23096654243740-Follow-to-DM-on-Instagram-Say-Hi-to-New-Followers-BETA [VS]
- Help article snippets [VS]: "Eligibility for this automation is determined by Meta, not Manychat"; beta "currently available only for Manychat accounts connected to Instagram via the new Unified Instagram onboarding flow"; triggers "only once per follower"; "Meta allows only one Follow to DM message per user per week. If a person follows multiple accounts using this feature, they'll receive a message only from the first account they followed." The last point suggests the feature runs on Meta's side, across tools [INF].
- ManyChat says it is a "Meta-approved feature" and that "Manychat is the exclusive partner to bring it to market first" (ManyChat blog/community: https://manychat.com/blog/introducing-follow-to-dm/ , https://community.manychat.com/product-updates/turn-every-follow-into-a-conversation-introducing-follow-to-dm-7628 , https://manychat.com/use-case/follow-to-dm ) [VS]. Note the wording: "exclusive partner to bring it to market FIRST". That is a launch exclusive, not a claim of permanent exclusivity.
- Launch: announced at Instagram/Meta "Instagram Summit". Date given by third parties: October 22, 2025 (CreatorFlow, nowbam.com) [3P; exact date not confirmed from a ManyChat page].
- Community threads show the trigger not firing for many users, for example "$1,000 USD BOUNTY - Fix ManyChat 'New Follower' Automation Issue" ( https://community.manychat.com/general-q-a-43/1-000-usd-bounty-fix-manychat-new-follower-automation-issue-8331 ). Third parties say Meta generally does not admit accounts under about 1k followers or with low engagement [3P].
- One third-party snippet (search summary) says ManyChat has "exclusive API access not available to the public". I could not tie this to a ManyChat or Meta page, so it is unverified.

## 2. Meta's public API
- The public Instagram Platform webhook fields documented in search snippets are: comments, mentions, story_insights, messages, messaging_postbacks, messaging_seen, messaging_referral, message_reactions, standby and similar. No public "follow" or "follows" webhook field was found ( https://developers.facebook.com/docs/instagram-platform/webhooks ). [Search-verified; doc page not fetched]
- The Make.com community and others confirm there is no new-follower webhook in the public API ( https://community.make.com/t/instagram-business-module-webhooks-new-follower-event-trigger/16511 ). [3P]
- Evidence of private or limited partner access: (a) ManyChat's "Meta-approved", "eligibility determined by Meta" and beta wording; (b) Chatfuel docs say its own "DM to Follow" is "currently in Alpha and available to a limited group of creators"; (c) Inro says "Meta has introduced follow-based messaging as a limited beta" and that Inro "has built the groundwork". [VS from each vendor] Conclusion [INF]: a gated, non-public Meta beta exists. ManyChat was the launch partner, and at least Chatfuel appears to have access by 2026.
- I found no Meta-authored page (newsroom or developer docs) that describes this feature or names ManyChat as exclusive. Not verified.
- Facebook Pages: no evidence of any follow-to-DM trigger for Facebook Page follows, ManyChat's included. The ManyChat feature is Instagram-only.

## 3. Competitors
| Tool | Follow-to-DM? | Source |
|---|---|---|
| Chatfuel | Docs: "Meta does not expose a 'new follower' event to any platform", but also "actively working on a DM to Follow feature ... currently in Alpha and available to a limited group of creators" | https://chatfuel.com/docs/instagram/dm-to-follow [VS] |
| Inro | Not available. "Built the groundwork" but held back because the Meta beta is unreliable | https://help.inro.social/en/articles/15631961-can-i-auto-dm-new-followers-follow-to-dm [VS] |
| GoHighLevel | No trigger; open feature request | https://ideas.gohighlevel.com/ad-reporting-and-attribution/p/trigger-of-new-instagram-follower [VS] |
| SendPulse, respond.io | No new-follower trigger found in search results | not confirmed either way |
| CreatorFlow, Zorcha | One third-party comparison (search summary) says both "support ... follow-to-DM". CreatorFlow's own blog points users to comment and follow-gate workarounds and calls the Meta trigger a gated beta | conflicting, unverified |
| LinkDM, InstantDM, ReplyKaro | Comment, story and keyword triggers; no follow trigger found | [3P] |
| Gramto, FollowToDM, Botize, Chrome-extension "IG DM sender" tools | Advertise a "Welcome DM" to new followers. Gramto's setup has "speed settings" and starts "within 30 minutes", which points to account-login automation or polling rather than the official API [INF]. Instagram's Terms prohibit automated access without permission, so these carry a risk of account action | https://gramto.ladesk.com/055632-How-to-Setup-Auto-DM-to-New-Followers [VS] |

## 4. Verdict: PARTLY TRUE (mostly misleading)
- True: ManyChat has an Instagram follow-to-DM feature. It runs on a Meta-gated beta that is not in the public API, and ManyChat launched it as Meta's exclusive *launch* partner (about Oct 2025).
- False or overstated:
  1. ManyChat's own wording is "exclusive partner to bring it to market **first**", not "only".
  2. By 2026, Chatfuel says it has an alpha of the same capability, and Inro says it built it but is holding it back. So the access is not ManyChat-only.
  3. The "(or Facebook)" part is not supported. No evidence was found of follow-triggered DMs for Facebook Pages.
  4. Unofficial tools (Gramto, FollowToDM and similar) also DM new followers through non-API methods, which carry ToS risk.
  5. Even in ManyChat, eligibility is decided by Meta per account, and users widely report the trigger not firing.
- Accurate rephrasing: "ManyChat was Meta's launch partner for a beta Instagram follow-to-DM trigger (late 2025). It is the main *official* way to do this today, but access is gated by Meta, it is Instagram-only, and other platforms such as Chatfuel are getting it in limited alpha."
- Confidence: medium-high on the verdict. Medium on details, because no vendor or Meta page could be read directly.
