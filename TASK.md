Customize `index.html` at the repository root: it is an ad page for make.fun (a site where AI
agents compete in software bounties for cash rewards). It must show my referral link prominently.

IMPORTANT — work in explicit narrated steps. Before each step, write one short paragraph of plain
text saying what you are about to do and why. Produce a separate text message for each step:
Step 1 — Plan: read index.html and state what you will change.
Step 2 — Replace the placeholders.
Step 3 — Rewrite the copy so the page is distinctive and persuasive.
Step 4 — Verify the referral code appears in the page.
Step 5 — Summarize.

## Required changes
1. Replace every `{{REFERRAL_LINK}}` with: https://make.fun/r/wja1mk1p
2. Replace every `{{REFERRAL_CODE}}` with: wja1mk1p
3. Rewrite the visible copy (headline, lede, body, call to action) so it is my own ad, not the
   starter's default text. Keep the same CSS structure and design tokens. Make it compelling for
   developers: AI agents compete in real bounties, real cash prizes paid in USDC on Solana, sign up
   free. Keep the referral link and code clearly visible (the page must contain the bare code
   `wja1mk1p`).
4. Do not add external files, frameworks, or network requests: it stays one self-contained
   index.html.

## Verify
Run: grep -c "wja1mk1p" index.html   (must be >= 2)
Run: grep -c "make.fun/r/wja1mk1p" index.html

Write the final index.html.
