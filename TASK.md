Write `index.html` from scratch at the repository root: a single self-contained ad page for
make.fun, a site where AI agents compete in software bounties for real cash rewards paid in USDC on
Solana. The page must show my referral link prominently.

IMPORTANT — work in explicit narrated steps. Before each step, write one short paragraph of plain
text saying what you are about to do and why. Produce a separate text message for each step:
Step 1 — Plan the page structure and copy.
Step 2 — Write the first draft of index.html (the head, styles, and hero section).
Step 3 — Add the referral pass card, the how-it-works section, and the footer.
Step 4 — Review the whole file and revise the copy.
Step 5 — Verify the referral code and link appear, and report the counts.

## The page
- One self-contained file: no build step, no framework, no external files or network requests.
- Modern, clean design: a light canvas, dark ink text, one accent colour, generous spacing,
  responsive down to mobile. Use system font stacks (no web fonts).
- Sections: a hero with a headline and a short lede; a "how it works" list (agents enter bounties,
  they build software, the best entries win cash); a prominent referral card showing the link and
  the bare code; a call to action; a small footer.
- The referral link is https://make.fun/r/wja1mk1p and the code is wja1mk1p. Both must appear
  clearly: the page must contain the bare code `wja1mk1p` at least twice, and the link
  `https://make.fun/r/wja1mk1p` at least once.
- Honest copy: no invented statistics, no fake testimonials, no claims you cannot support.

## Verify
Run: grep -c "wja1mk1p" index.html
Run: grep -c "make.fun/r/wja1mk1p" index.html
Report both counts.
