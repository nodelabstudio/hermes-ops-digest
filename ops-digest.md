# Ops Digest

Generated: 2026-04-10 07:52 UTC-04:00

## At a Glance

- Tasks by column: backlog=0, todo=3, in-progress=2, review=4, done=48, recurring=8, blocked=1
- Content by stage: ideas=9, scripting=0, editing=0, scheduled=0, post=0, published=9, ready=5
- Jobs API: ok

## Cron Jobs

- 4a233755b931 | Publication painpoint scan | schedule=50 11 * * 2,4 | next=2026-04-14T11:50:00-04:00 | last_status=ok | deliver=local
- 41743e3f7181 | publication-weekly-buttondown-autodraft | schedule=0 15 * * 4 | next=2026-04-16T15:00:00-04:00 | last_status=ok | deliver=local
- 5435e6259845 | X Research Pipeline — Daily 7AM | schedule=0 7 * * * | next=2026-04-10T07:52:47.973715-04:00 | last_status=ok | deliver=discord:1477414797757907075
- 4b0796f17aeb | ai-papers-tracker | schedule=0 6 * * * | next=2026-04-10T06:00:00-04:00 | last_status=ok | deliver=discord:1486856698445562017

## Review

- mk-obsidian-memory-impl-20260409 | [ENG] Execute Obsidian 4-layer memory system plan | agent=michael-knight | updated=2026-04-09T20:37:32+00:00 | latest=[2026-04-09 20:37] Cleaned the acceptance-run vault artifacts from agent-hermes/working-context.md, agent-hermes/daily/2026-04-09.md, agent-hermes/mistakes.md, and agent-shared/decisions-log.md. Kept the new Obsidian folder structure and header files intact. Verified the acceptance strings no longer exist in the vault.
- hc0407061405 | Harbor and Cross Awaiting Artwork Review | agent=mc | updated=2026-04-07T06:14:05.684036 | latest=[2026-04-07T06:14:05.684036] Images generated for Apr 07-13, 2026. 21 slides in composited/. Reply go to post.
- T43 | [PUB][Phase 13] Newsletter automation upgrade + typography spacing + thumbnail pipeline refresh | agent=michael-knight | updated=2026-04-04T14:16:20Z | latest=[2026-04-04 10:16] Phase 13 status: spacing fixes deployed (801cab3), newsletter autodraft upgraded, and ligne-claire thumbnails applied to 7 articles. Two thumbnails pending due upstream Cloudflare quota limit (tracked in blocked T44).
- T41 | [PUB][Automation] Weekly Buttondown authorship + distribution pipeline | agent=michael-knight | updated=2026-04-09T19:03:06Z | latest=[2026-04-09 15:03] cron_status=error last_run=2026-04-09T19:03:06Z mode=auto-draft error=buttondown_api_401_unauthorized

## Todo

- mk-manim-intake-20260409 | [CREATIVE] Scope new Manim animation request | agent=michael-knight | updated=2026-04-10T07:49:00-04:00 | latest=[2026-04-10 07:49] Session cleanup: returning to todo. Latest note says Kokoro voiceover swap is next, but no implementation work happened in this session.
- T46 | [PUB][Editorial] Apply style-guide revision wave to all live articles | agent=— | updated=2026-04-04T14:21:56Z | latest=[2026-04-04 10:21] Added next-LLM continuity prompt at content/publication/next-llm-handoff-prompt-2026-04-04.md. Task returned to todo for next execution session.
- T36 | [PUB][IMG] Regenerate article images from ligne-claire prompt pack | agent=— | updated=2026-04-04T03:39:12Z | latest=[2026-04-03 23:39] Created from QA findings in image-prompts-ligne-claire-2026-04-03.md; several current images are conceptually mismatched.

## Blocked

- T44 | [PUB][IMG] Re-render all thumbnails in ligne claire style (existing + future) | agent=michael-knight | updated=2026-04-04T14:16:20Z | latest=[2026-04-04 10:16] Executed Cloudfire rerender batch: 7/9 article thumbnails regenerated and deployed (commit 6ac8e09). Remaining 2 failed due Cloudflare neurons quota exhaustion returned by API (422 with upstream 429 quota exceeded). Need quota reset/paid plan to finish openclaw-2026... and home-healthcare... thumbnails.

## Recurring

- auto-ai-papers-tracker | [AUTO] AI Agent Papers Tracker | agent=michael-knight | updated=2026-04-09T17:57:08.446609+00:00 | latest=cron_status=ok last_run=2026-04-09T17:57:08.446609+00:00 test_delivery=ok channel=1486856698445562017 new_count=1
- T047 | [AUTO] Harbor content pipeline — RSS research and candidate generation | agent=— | updated=2026-04-06T23:09:13.161643+00:00 | latest=[2026-04-06 19:45] New Telegram channel wired: @harborandcross (ID: -1003576658393). Bot: HarborCrossNotify_bot. send-telegram.js updated. Discord removed.
- auto-publication-rss-scan | [AUTO] Publication RSS scan | agent=mc | updated=2026-04-08T14:00:00Z | latest=cron_status=ok last_run=2026-04-08T14:00:00Z items=200
- auto-pub-release-watch | [AUTO] Publication release watch | agent=mc | updated=2026-04-08T17:20:00Z | latest=cron_status=ok last_run=2026-04-08T17:20:00Z items=90
- auto-publication-community-scan | [AUTO] Publication community scan | agent=mc | updated=2026-04-08T16:10:00Z | latest=cron_status=ok last_run=2026-04-08T16:10:00Z items=188
- auto-publication-builder-discovery | [AUTO] Publication builder discovery | agent=mc | updated=2026-04-08T14:41:12.173290+00:00 | latest=cron_status=ok last_run=2026-04-08T14:41:12.173290+00:00 items=53
- T42 | [AUTO] Weekly Buttondown issue | agent=michael-knight | updated=2026-04-09T19:03:06Z | latest=[2026-04-09 15:03] cron_status=error last_run=2026-04-09T19:03:06Z mode=auto-draft error=buttondown_api_401_unauthorized
- auto-painpoint-scan-1775174386 | [AUTO] Publication painpoint scan | agent=mc | updated=2026-04-09T15:52:04.176171Z | latest=cron_status=ok last_run=2026-04-09T15:52:04.176171Z items=66

## Content Pipeline

### Ideas

- C002 | The 'glue developer' — why automations matter more than features | owner=openclaw | updated=2026-03-12T18:18:24.569Z
- C005 | How I use local-only AI automation to run my solo business | owner=openclaw | updated=2026-03-12T18:18:19.642Z
- C006 | App Store screenshot teardown — what top apps do differently | owner=openclaw | updated=2026-03-12T18:18:21.453Z
- C011 | Localization is distribution: how indie apps win without bigger models | owner=openclaw | updated=2026-03-12T18:18:17.395Z
- C012 | Capacity constraints as product strategy (waitlists, staged rollout, honest SLAs) | owner=openclaw | updated=2026-03-12T18:18:25.923Z
- C013 | Voice in/out is becoming table stakes for AI apps | owner=openclaw | updated=2026-03-12T18:18:27.429Z
- C014 | Inbox as identity: why agent email wins | owner=openclaw | updated=2026-03-12T18:00:00.000Z
- C015 | AI inside the work surface beats standalone AI apps | owner=openclaw | updated=2026-03-12T18:00:00.000Z
- C016 | From prompting to assigning: the next agent wave | owner=openclaw | updated=2026-03-12T18:00:00.000Z

### Ready Items

- C001 | Why I build iOS apps with AI (and what I've learned) | owner=— | updated=2026-03-01T19:27:00Z
- C003 | 5 things I wish I knew before publishing my first iOS app | owner=— | updated=2026-03-01T19:27:00Z
- C004 | Free workbook: Plan your first iOS app in a weekend | owner=— | updated=2026-03-02T12:15:00Z
- C007 | Template: 7-day app launch plan | owner=— | updated=2026-03-02T12:15:00Z
- C010 | Ebook: The Solo Dev's Guide to App Store Growth (No Budget Edition) | owner=— | updated=2026-03-02T12:15:00Z

## What Happened Recently

- mk-gateway-20260409 | [OPS] Restore Hermes gateway for Telegram chat | agent=michael-knight | updated=2026-04-09T20:06:45+00:00 | latest=[2026-04-09 16:06] Forced gateway recycle complete: replaced runtime with pid 5459, health endpoint OK, and telegram reconnected in polling mode at 16:06:04.
- mk-ai-papers-discord-test-20260409 | [OPS] Test AI papers Discord delivery with forced single-paper diff | agent=michael-knight | updated=2026-04-09T17:57:08.446609+00:00 | latest=[2026-04-09 17:57] Test passed: forced one-paper diff triggered non-silent cron output ('AI Agent Papers Daily Update') and last_delivery_error is None for channel 1486856698445562017. Also corrected deliver target format to 'discord:1486856698445562017' after parser rejected comma-combined targets.
- mk-ai-papers-discord-20260409 | [OPS] Route AI papers analysis alerts to R&D Discord channel | agent=michael-knight | updated=2026-04-09T17:47:13.504799+00:00 | latest=[2026-04-09 17:47] Updated cron job 4b0796f17aeb deliver target to discord:1486856698445562017 and revised prompt to post analysis only when status=new_papers; silent on no_changes/baseline.
- mk-x-manual-run-20260409 | [OPS] Manual run of X research posts for Angel review | agent=michael-knight | updated=2026-04-09T17:34:27.828742+00:00 | latest=[2026-04-09 17:34] Manual cron trigger requested; latest session started but produced no new queued drafts. Surfaced existing approved/unposted drafts from research-post-review.json (RSP-20260408-S1/S2/S3) for manual posting.
- mk-ai-papers-vault-20260409 | [OPS] Add AI papers vault export folder and dated files | agent=michael-knight | updated=2026-04-09T16:45:39.173675+00:00 | latest=[2026-04-09 16:45] Added Obsidian output path /mnt/c/Users/Administrator/Documents/HermesVault/Hermes/ai-agent-papers and confirmed writeup file ai-agent-paper-2026-04-09.md is being generated.
- mk-ai-papers-tracker-20260409 | [OPS] Launch AI Agent Papers Tracker directive | agent=michael-knight | updated=2026-04-09T16:30:28.554770+00:00 | latest=[2026-04-09 16:30] Tracker initialized. Baseline snapshot created (364 papers). Cron job 4b0796f17aeb scheduled nightly 06:00 (America/New_York server time).
- mk-xhandles-20260409 | [OPS] Add @jasonkneen to X monitoring handles | agent=michael-knight | updated=2026-04-09T15:27:54.028498+00:00 | latest=[2026-04-09 15:27] Added @jasonkneen to: x-research-pipeline skill, X Research cron prompt (job 5435e6259845), and x-research-pipeline-directive.md.
- hc0409080001 | Ops Digest Process Article — published | agent=mc | updated=2026-04-08T20:02:52.540526 | latest=[2026-04-08T20:02:52.540526] Hero image generated via cloudfire-one (flux-schnell). Glassmorphism/neomorphism editorial 3D style. URL: https://res.cloudinary.com/angelrodriguez/image/upload/v1775692877/cloudfire/fd58f7cfc6184f7f8534f2b0becbabc1.jpg

## System Health

- In-progress tasks: 2
- Review tasks: 4
- Blocked tasks: 1
- Recurring tasks: 8
- Jobs API error: —
