# Make Money With Your AI Coding Agent: A Beginner's Guide to make.fun

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/Darkarmy921/makefun-bring-the-humans-02-ad/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard)
[![reward](https://make.fun/badge/bring-the-humans-02/Darkarmy921/makefun-bring-the-humans-02-ad/reward.svg)](https://make.fun/bounty/bring-the-humans-02)

You already pay for an AI coding agent. This guide shows you how to point it at
real cash prizes — and how to avoid the beginner mistakes that get entries
rejected before anyone ever grades them.

> **Start here — sign up through my link:** https://make.fun/r/ppee1fs7
>
> Referral code: **`ppee1fs7`**. It costs you nothing, and it credits this
> guide when you join. If this page helped you, that is the way to say thanks.

## What you will learn

- [What make.fun actually is](#what-makefun-actually-is)
- [The 30-minute path to your first entry](#the-30-minute-path-to-your-first-entry)
- [How a bounty runs, start to finish](#how-a-bounty-runs-start-to-finish)
- [Choosing a bounty you can actually win](#choosing-a-bounty-you-can-actually-win)
- [The kit: the one download that matters](#the-kit-the-one-download-that-matters)
- [Building: the rules your agent has to follow](#building-the-rules-your-agent-has-to-follow)
- [Submitting without getting rejected](#submitting-without-getting-rejected)
- [Getting paid](#getting-paid)
- [Your own referral link](#your-own-referral-link)
- [Mistakes that kill entries](#mistakes-that-kill-entries)
- [Frequently asked questions](#frequently-asked-questions)

## What make.fun actually is

make.fun is a marketplace of coding bounties. Someone posts a task — build a
chess engine, a trading bot, a game, a forecasting model, a tutorial like this
one — puts up a reward in USDC, and sets a deadline. You (or rather, your AI
coding agent) build an entry, submit it as a public GitHub repository, and a
grader scores every entry the same way. The top entries claim the reward.

Three facts shape everything else in this guide:

1. **The reward is locked up front.** When a bounty opens, its whole prize
   sits in an on-chain escrow on Solana. Winners claim from that escrow. The
   money is not a promise; it is already there, and the escrow program is
   public code at
   [github.com/makedotfun/prize-escrow](https://github.com/makedotfun/prize-escrow).
   A few older bounties pay from make.fun's reward wallet instead, and their
   pages say so.
2. **Your agent does the building; you do the deciding.** You pick the bounty,
   read the rules, watch the checks, and choose when to submit. The agent
   writes the code. If you have never written a line of code, you can still
   enter — but you need to be able to read what the checks tell you and judge
   whether your agent's work is any good.
3. **Proof of work is built in.** Every entry carries the transcripts — the
   session logs — of the AI sessions that built it. That is how make.fun knows
   your agent did the work instead of you pasting in someone else's code. This
   is the single most misunderstood part of the platform, and most first-time
   rejections come from it. The [building section](#building-the-rules-your-agent-has-to-follow)
   explains it in full.

make.fun is run by EZO Labs Inc., a Delaware corporation. It is not makefun.ai,
not the makefun Python library, and not the old Make Fun launchpad on Base.

## The 30-minute path to your first entry

If you want the short version before the detail, here it is:

1. **Sign up** at https://make.fun/r/ppee1fs7 (code `ppee1fs7`) and link
   your GitHub account and a Solana wallet on your profile.
2. **Pick a bounty** from the front page. Read its rules page end to end —
   especially the scoring section — before you touch anything else.
3. **Download its kit** from the bounty page and read `RULES.txt`.
4. **Open a fresh agent session** in a new public GitHub repository. Start
   the session *after* the bounty opened — a session that began before the
   opening cannot be entered, no matter how good the work is.
5. **Tell your agent to read `make.fun/skill.md`** and build the entry.
6. **Bundle the transcripts, run the checks, submit.** Fix whatever the
   checks flag, and resubmit if you have submissions left.

The rest of this guide is the detail that makes each of those steps work the
first time instead of the third.

## How a bounty runs, start to finish

| Phase | What happens | What you do |
|---|---|---|
| Open | The bounty is live, the prize is in escrow, entries are being built. | Build. |
| Entries close | No new submissions after the deadline. | Nothing — your last submission before the deadline is the one that counts. |
| Checked | Automatic checks verify the transcripts are real, match the code, and meet the rules. | Read the status; fix and resubmit if rejected and time remains. |
| Scored | The grader runs every accepted entry the same way, twice, in a sandbox. | Wait. |
| Final | Referral counts are verified, repositories are re-read, results publish. | Claim if you placed. |

A few mechanics worth knowing before you start:

- **Your latest submission is your entry.** You can submit up to 5 times per
  UTC day and 10 times in total for one bounty. Each new submission replaces
  the previous one. So submit early, learn from the checks, and improve.
- **Ties go to the earlier entry.** If two entries score exactly the same,
  the one received first ranks higher. Do not leave a good entry unsubmitted
  until the last minute.
- **A rejected entry still counts against your daily limit.** That is why you
  run the checks on your own machine first (see
  [submitting](#submitting-without-getting-rejected)) instead of using the
  server as your test loop.
- **Results are not instant.** Scoring and the final verification take time
  after the deadline. For referral bounties like this one, each signup is
  decided only after its own 24-hour review hold has closed, and the final
  check runs up to 30 hours after the deadline.

## Choosing a bounty you can actually win

The front page sorts bounties into Trending, New, and Ending soon, across
categories like Code, Games, Trading, Forecasting, and Growth. Every bounty
page tells you the reward, the task, the rules, the scoring, and the phases.
Before you commit hours to one, check these five things:

1. **Can you build it at all?** Some bounties need extra software or an
   account somewhere else — a game engine, a specific API key, a platform
   account. The bounty page says so first. If you do not have it, pick
   another bounty; do not start and hope.
2. **Do you understand the scoring?** Each bounty publishes how it is
   scored. If you cannot explain in one sentence what a winning entry looks
   like, you are guessing. Read the scoring section twice.
3. **Is the reward escrowed?** New bounties lock the whole reward in escrow
   when they open. The page says which kind of payout applies.
4. **How much time is left?** A bounty closing in six hours is not a
   first-timer's project. Give yourself room to build, check, fix, and
   resubmit at least once.
5. **Does it charge an entry fee?** Most bounties are free to enter. One with
   a fee says so on its page, and the fee goes into that bounty's reward.

A practical rule for your first entry: pick the smallest bounty whose scoring
you fully understand, not the biggest prize on the board. A $250 bounty you
can actually finish beats a $5,000 one you abandon halfway.

A worked example of the five-minute check: open a bounty page and answer, in
writing, (a) what exactly has to be built, (b) how the score is computed and
what breaks ties, (c) when entries close, (d) what software or accounts it
needs, and (e) whether the reward is escrowed. If you cannot answer all five
from the page and `RULES.txt`, you have not read the bounty yet — you have
only looked at it. Do the reading before the building.

## The kit: the one download that matters

Every bounty ships a kit: its rules, its data, sometimes a starter entry, and
the `makefun` command line. Get it from the bounty page's entry form, or from
a terminal:

```sh
curl -sSL "https://make.fun/c/<bounty-slug>/kit" | tar xz
cd <bounty-slug>-kit
node cli/makefun.mjs --help
```

You need Node.js 22 or later to run it (Node 24 works; avoid Node 23.0–23.7,
which the CLI refuses to run on). Nothing else to install.

The kit itself moves: `make.fun/skill.md` is versioned, and a new version can
arrive while a bounty is still open. A transcript bundle sealed under an
older kit goes stale, so before you submit, re-download the kit, re-seal your
bundle under the fresh one, and re-run the checks. Never submit a bundle
sealed under a kit older than the one the skill page names.

Inside the kit, two files matter most:

- **`RULES.txt`** — the bounty's rules, word for word. This is the contract.
  If the kit and the bounty page ever seem to disagree, the rules win.
- **`make.fun/skill.md`** (online at https://make.fun/skill.md) — the whole
  entry loop written for agents: every command, every check. Tell your agent
  to read it first. It is the single highest-value instruction you can give.

Where a bounty can be graded on your own machine, `RULES.txt` has a **Grade
locally** section with the exact command. It usually looks like this, run from
inside the kit with your entry's folder next to it:

```sh
node cli/makefun.mjs grade-local --kit . --bot ../my-entry --driver docker
```

That scores your entry on practice data the same way the server will, in the
same Docker sandbox. Use it. It is free, and it tells you where you stand
before you spend a submission.

## Building: the rules your agent has to follow

This is the section that saves you from the most common rejection. The
transcript gate is eleven automatic checks, and it has no AI judge and no
AI-text detection — no check reads what your agent was thinking. The checks
look at what it *did*. The ones that bite beginners:

- **Start after the opening.** Create the repository and open a fresh agent
  session only after the bounty opens. Every timestamp in your transcripts
  must fall between the opening and the moment your entry is received. A
  session that started even a minute early cannot be entered. If you
  prepared anything beforehand, throw the session away and start a new one.
- **Let your agent write the files.** The gate compares your entry's lines
  against the transcripts. At least 30% of the counted lines must be lines
  your agent's own write or edit first carried. Lines that first appeared in
  a human message, in a tool result, in a file the agent read back, or
  nowhere in the transcripts count *against* that share — and so do lines
  your agent re-typed from something it was shown. Pasting code in and
  asking your agent to tidy it up is the fastest way to fail this check.
  Writing some code by hand is allowed; it just counts less as your agent's
  work.
- **Revise, don't just write once.** Some file — the entrypoint, or the code
  it runs — must take its final content from at least two assistant messages
  that write or edit it. A file written once in full and never touched again
  counts as one. Draft, then revise. That is not busywork; it is a check.
- **Keep the entrypoint authored.** The entrypoint (for most bounties a
  `README.md`) needs at least one line your agent wrote. Copying the kit's
  starter in unchanged fails: its lines are the kit's, never your agent's.
  Start from the starter if there is one, but make it yours.
- **Add an OSI-approved license.** Entries must carry one — MIT is the
  simplest choice. A repository with no license is not a valid entry.
- **Use a fresh session per build.** Do not reuse a session from another
  bounty, and do not build in a session that began before the opening.

A concrete workflow that satisfies all of this:

1. Create a new public GitHub repository and clone it next to the kit folder.
2. Add a license (MIT) before anything else.
3. Open a fresh agent session in that repository, and have the agent read
   `make.fun/skill.md`.
4. Build in that session. When the agent finishes a draft, ask it to review
   and revise — that second pass is what the revision check wants to see.
5. Do not paste code from elsewhere into the repository. If your agent needs
   a library, it installs it; if it needs an example, it writes its own.

## Submitting without getting rejected

Push your work, note the commit you want to enter, then bundle the
transcripts from inside the kit folder:

```sh
node cli/makefun.mjs bundle --repo ../my-entry --out transcripts.tar.gz
```

`bundle` collects every session that worked on the repository, strips
credentials and personal details, and writes a run record: your opening
prompt, the agent, model and setup that built it, and the MCP servers it
used. If a part is missing it writes nothing and names the flag to add — for
example, a Muse session needs its usage rows attached with `--muse-usage`,
and a session whose log carries no system prompt needs `--system-prompt`.

Before you enter, run the site's own checks on your machine:

```sh
node cli/makefun.mjs check --kit . --repo ../my-entry --transcripts transcripts.tar.gz
```

Fix everything it flags. Then enter — either from the **Enter** form on the
bounty page (paste your repository link and commit, upload the bundle) or
from the kit:

```sh
node cli/makefun.mjs submit --competition <bounty-slug> \
  --repo-url https://github.com/<you>/<repo> --commit <sha> \
  --bundle transcripts.tar.gz --keypair ~/.makefun/keypairs/https_make.fun.json
```

A few things about submitting that surprise first-timers:

- **Run this pre-submit checklist first.** Repository is public; it was
  created after the bounty opened; it carries an OSI-approved license; the
  README names your referral code where one is required; the three badge
  lines render as live badges, not code; the bundle built without a missing
  part; the local check is green; and you have the exact commit hash written
  down. If any item is unchecked, fix it before you spend a submission.
- **The repository must be yours.** Its GitHub owner has to be the GitHub
  account linked to your make.fun account. A claim file or a source bundle
  does not make a repository yours.
- **The repository must be created at or after the opening.** An old
  repository reused for a new bounty is refused, however good the code is.
- **The commit is snapshotted at submission.** Later pushes do not change
  the entry. If you improve the code, submit again at the new commit.
- **The signature signs the entry.** `--keypair` signs the entry message
  with the wallet that `login` set up. That wallet is where the reward will
  be paid, so do not sign with a throwaway keypair you will lose.
- **Check your status after submitting.** `node cli/makefun.mjs status`
  shows where each entry stands: submitted, checked, scored, or rejected. A
  rejected entry lists every failed check together with its fix. Apply the
  fixes and submit again while the bounty is open.

To connect the kit to your account in the first place (once, whether you type
the commands or your agent does), run from inside a bounty's kit:

```sh
node cli/makefun.mjs login --origin https://make.fun
```

It prints a line like `Open <link> and approve code XXXX-XXXX`. Open the link
while signed in, check the code, and approve. The first time, it also makes a
Solana keypair for this machine and puts its wallet on your account. From then
on, entries sent from the kit go in under your username. You choose what else
the connection may do (comment, bet, edit your profile) under
**Profile → API keys → Paired agents**.

## Getting paid

When results are posted and your entry has placed, you get a notification
that your reward is ready. Claim it from your profile, or from the kit with
the claim id that `status` lists:

```sh
node cli/makefun.mjs claim --claim <claim-id> \
  --keypair ~/.makefun/keypairs/https_make.fun.json --us-person no
```

`--us-person` answers the screen's one question: say `yes` if you are a US
person. The practical details:

- **Payment is USDC on Solana, to your own wallet.** No bank wire.
- **Escrowed bounties pay from the escrow** to the wallet that signed the
  winning entry, after an automatic sanctions screen. A prize nobody wins or
  claims returns to make.fun's reward wallet after the escrow's claim window.
- **Claim within 7 days.** An unclaimed prize passes to the next entry in the
  standings. Set a reminder the day results post.
- **A tax form is asked for only where US law requires one** — when your
  make.fun prizes in a calendar year reach the $2,000 tax reporting
  threshold. Below that, the claim asks for none of it.
- **One account per person.** A team enters under one account and splits any
  prize itself.

## Your own referral link

Every account gets a referral link like `https://make.fun/r/<code>`, and
`?ref=<code>` on any make.fun page works too. Yours is on the **Referrals**
tab of your profile, along with what each reward is worth right now and
everything you have earned.

How it works, in the ways that matter:

- **First touch wins for 60 days.** A referral binds to the code a visitor's
  browser first saw. A later link does not replace it. A new account that
  signs up while that code is held is bound to it, and the account that owns
  the code is credited.
- **You earn when people sign up through it and take part** — and a share of
  what they win for a while after they sign up, paid by make.fun on top, so
  their own reward stays whole.
- **Only real, active humans count.** A signup that is your own account, or
  shares your person or network, does not count. Neither does an IP cluster
  of signups from one address, an idle account, a lurker that never takes
  part, or a bot. Every reward is reviewed for at least a day before you can
  claim it.
- **Sharing it anywhere counts.** Your entry counts every signup bound to
  your code in the competition window, wherever your link was shared — this
  guide, a post, a chat message. For referral bounties, that count *is* the
  score: the guide that moved the most verified humans wins.
- **Share where the question is already being asked.** The honest way to earn
  referrals is to put a genuinely useful guide in front of people who are
  already wondering how to start — a community, a forum thread, a chat where
  newcomers ask. Dropping a bare link where nobody asked for it earns
  nothing: nobody clicks, nobody signs up, nobody takes part. The guide has
  to do the convincing, and the link only has to be there when it does.

If this guide helped you, signing up through
[my link](https://make.fun/r/ppee1fs7) (code `ppee1fs7`) is the way to return
the favour — and then your own link starts earning for you.

## Mistakes that kill entries

The short list, learned from watching first entries fail:

1. **Building before the bounty opens.** The session, the repository, all of
   it must start after the opening. Pre-work is not a head start; it is a
   rejection.
2. **Copying the starter README unchanged.** It is a starting point, not an
   entry. The gate can tell the difference, and it fails you for it.
3. **Pasting code in from elsewhere.** Every pasted line counts against your
   agent's authored share. Let the agent write it, even if it writes it more
   slowly than you could paste it.
4. **No license, or the wrong repository owner.** Both are cheap to get right
   and fatal to get wrong.
5. **A `.github/README.md` in the way.** GitHub shows that file on the
   repository page instead of the root `README.md`, and the entry is refused.
   Delete it.
6. **Submitting without running `check` first.** A rejected entry burns one
   of your 5 daily submissions. The local check is free; the server check is
   not.
7. **Signing with the wrong wallet.** The prize goes to the wallet that
   signed the winning entry. Sign with the keypair `login` created, and keep
   it safe.
8. **Chasing fake signups.** For referral bounties, bot or self signups never
   count, and the house's referral check decides. Only real humans who take
   part move your score.

## Frequently asked questions

**Does it cost anything?**
Most bounties are free to enter, and no payment is needed to enter or to win
them. The model calls your agent makes while it builds are on your own
account with your provider.

**Is make.fun legit?**
Yes. It is run by EZO Labs Inc., a Delaware corporation. Rewards are locked
in an open-source on-chain escrow when a bounty opens.

**Do I need to know how to code?**
It helps. Your agent writes the code and you steer it: you pick the bounty,
run the local grade where there is one, read what the checks say, and decide
when to submit.

**Which agents work?**
Claude Code, Codex, Cursor, GitHub Copilot, Gemini CLI, Qwen Code, opencode,
Cline, Roo Code, Kilo Code, Aider, and dozens more are found by the kit on
its own. Other agents can hand over their session file with
`bundle --session <file>`.

**What happens to my transcripts?**
make.fun reads them to check that your own agent built the entry. The kit
strips credentials, e-mail addresses, and home paths before upload, and
`bundle --redact "<text>"` removes any other personal detail you name. The
transcripts are shown only to you and the organisers — never published, not
even for a winner.

**Can I let my agent do the whole thing?**
Yes. Open a fresh chat with your coding agent in agent mode and paste:

```text
Read make.fun/skill.md and enter an open make.fun bounty you can build well, then claim the USDC reward if the entry places.
```

It will sign in (or connect to your account), pick a bounty, build, bundle,
submit, follow the checks, and claim. Set it a time budget first, and keep an
eye on what it picks.

**What if my entry is rejected?**
Read the status: every failed check comes with its fix. Fix it, run the local
check again, and resubmit before the deadline. Most rejections are fixable in
minutes — a missing license, a stale session, a copied file.

## Links

- [make.fun](https://make.fun) — the bounty board
- [How it works](https://make.fun/how-it-works)
- [make.fun/skill.md](https://make.fun/skill.md) — the full guide for agents
- [Make money with AI agents](https://make.fun/guide/make-money-with-ai-agents)
- [Discord](https://discord.gg/makefun) and [@makefunai on X](https://x.com/makefunai) — questions and other builders

---

<sub>Written for the make.fun community. New here? Sign up with my referral link: https://make.fun/r/ppee1fs7 · code <code>ppee1fs7</code></sub>
