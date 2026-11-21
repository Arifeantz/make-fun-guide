# Notes for the maintainer (not part of the guide)

## What this repository is

The entry for make.fun's "Bring the humans again" bounty (`bring-the-humans-02`):
a getting-started guide whose root `README.md` teaches a person how to connect
their own AI coding agent to make.fun and enter bounties. Owner: `Arifeantz`.
Referral code carried by the guide: `mec0aznf` (https://make.fun/r/mec0aznf).

## ⚠️ Screenshot must be retaken after publishing

`screenshot.png` in this repo is a **locally rendered stand-in**: the README was
rendered into a GitHub-repo-page frame with a local Markdown renderer and
captured with headless Chromium, because the repository did not exist on
GitHub yet when the entry was assembled.

The bounty rules require `screenshot.png` to be a screenshot **of the published
GitHub page** of this repository, with the repo name and the start of the guide
visible at the top of the capture. Therefore, after this repo is published at
`github.com/Arifeantz/make-fun-guide`:

1. Open the published repo page (README rendered, default branch view).
2. Retake the screenshot of the page top (repo header + beginning of the guide).
3. Replace `screenshot.png` with the real capture (PNG/JPEG/WebP, ≤ 8 MB,
   ≤ 16,000,000 px) and commit the replacement **before submitting the entry**.

Do not submit with the stand-in screenshot still in place.

## Publishing checklist (parent/owner steps, not done by the build agent)

- [ ] Publish this repo publicly as `Arifeantz/make-fun-guide` (created after
      the bounty opened on 2026-11-18 10:30 UTC — a fresh repo satisfies this).
- [ ] Set the repo About: homepage `https://make.fun/bounty/bring-the-humans-02`,
      topics `makefun, ai-agents, bounties, growth`, description per the
      requirements template (`{summary} Built by an AI agent for make.fun's
      "Bring the humans again" bounty, $1,000 in USDC.`, summary ≤ 265 chars).
- [ ] Retake `screenshot.png` from the real page (see above) and commit it.
- [ ] Confirm the make.fun account that submits has the GitHub account
      `Arifeantz` linked (the entry's repo owner must match the linked account).
- [ ] Bundle the build transcripts and submit before the deadline
      (2026-11-21 10:30 UTC) — earlier is better; score ties break by receipt time.

## Structure checks already verified locally

- Root file is exactly `README.md` (no `.github/README.md`), well under 2 MB.
- The three badge lines from the official template are live Markdown image
  links (not commented out, not in a code block), pointing at the
  `bring-the-humans-02` bounty, leaderboard, and bounty pages with the
  template's UTM parameters; the rank/reward badges use `Arifeantz/make-fun-guide`.
- Referral code appears in the sign-up links and in the template footer.
- MIT license at root (`LICENSE`).
- Guide was written by the agent in its own words in two commits
  (draft `44f2809`, revision `1dfa1e9`) to satisfy the transcript gate.
