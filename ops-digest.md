# Ops Digest

Generated: 2026-04-11 21:03 EDT-04:00

## At a Glance

- Tasks by column: backlog=0, todo=3, in-progress=2, review=8, done=54, recurring=11, blocked=1
- Content by stage: ideas=9, scripting=0, editing=0, scheduled=0, post=0, published=9, ready=5
- Jobs API: ok

## Cron Jobs

- f19e71be2215 | Publication RSS scan | schedule=0 */6 * * * | next=2026-04-12T00:00:00-04:00 | last_status=ok | deliver=local
- 1e9eb8073809 | Publication community scan | schedule=10 */12 * * * | next=2026-04-12T00:10:00-04:00 | last_status=ok | deliver=local
- 6d4e55a2a55c | Publication release watch | schedule=20 9-21/4 * * * | next=2026-04-11T21:20:00-04:00 | last_status=ok | deliver=local
- e513a7663cd0 | Publication builder discovery | schedule=35 10 * * 1,3,5 | next=2026-04-13T10:35:00-04:00 | last_status=ok | deliver=local
- 4a233755b931 | Publication painpoint scan | schedule=50 11 * * 2,4 | next=2026-04-14T11:50:00-04:00 | last_status=ok | deliver=local
- 41743e3f7181 | publication-weekly-buttondown-autodraft | schedule=0 15 * * 4 | next=2026-04-16T15:00:00-04:00 | last_status=ok | deliver=local
- 0d4cf8e778bc | harbor-cross-daily-analytics | schedule=0 7 * * * | next=2026-04-12T07:00:00-04:00 | last_status=ok | deliver=local
- d759986ad7fd | harbor-cross-content-pipeline | schedule=0 6 * * * | next=2026-04-12T06:00:00-04:00 | last_status=ok | deliver=origin, discord:1490847519272603779
- 9073f89d694e | hermes-heartbeat | schedule=0,15,30,45 * * * * | next=2026-04-11T21:15:00-04:00 | last_status=ok | deliver=local
- 5435e6259845 | X Research Pipeline — Daily 9PM | schedule=0 21 * * * | next=2026-04-12T21:00:00-04:00 | last_status=ok | deliver=discord:1477414797757907075
- c6907ad6735a | research-react-approver | schedule=*/5 * * * * | next=2026-04-11T21:00:00-04:00 | last_status=ok | deliver=local
- fd4f0f7a35a8 | reddit-daily-digest | schedule=0 14 * * * | next=2026-04-12T14:00:00-04:00 | last_status=ok | deliver=local
- 4b0796f17aeb | ai-papers-tracker | schedule=0 6 * * * | next=2026-04-12T06:00:00-04:00 | last_status=ok | deliver=discord:1486856698445562017
- 5bf287c92952 | camofox-watchdog | schedule=*/15 * * * * | next=2026-04-11T21:00:00-04:00 | last_status=ok | deliver=local

## Review

- mk-verify-hermes-openclaw-x-post-20260411 | [OPS] Verify Hermes+OpenClaw X post approval and post-bridge state | agent=michael-knight | updated=2026-04-11T10:33:37-04:00 | latest=[2026-04-11 10:33] Sent short X draft to Discord channel 1477414797757907075 for thumbs-up approval. Discord message id: 1492533083881214144.
- mk-hermes-desktop-eval-20260410 | [OPS] Evaluate Hermes Desktop install on this machine | agent=michael-knight | updated=2026-04-10T14:57:00-04:00 | latest=[2026-04-10 14:57] WSL launch-flag test finished. --disable-gpu and --disable-gpu --disable-software-rasterizer did not improve things; both still logged DBus noise and eventually hit repeated GPU process failures, with the no-software-rasterizer combo ending in a fatal GPU unusable exit. Default launch remains the better behavior here. Shared ~/.hermes hashes stayed stable during the flag tests (no additional config or env changes).
- mk-save-post-20260410 | [OPS] Save requested post from recent context | agent=michael-knight | updated=2026-04-10T13:53:49.818994-04:00 | latest=[2026-04-10 13:53] Saved the only unsaved draft I could identify from current local state: RSP-20260410-S2. Wrote a standalone copy to /home/administrator/.hermes/output/saved-posts/2026-04-10-RSP-20260410-S2.txt.
- mk-manim-intake-20260409 | [CREATIVE] Scope new Manim animation request | agent=michael-knight | updated=2026-04-10T10:00:31-04:00 | latest=[2026-04-10 09:59] Contraction pass ready for review. Rewrote the af_sky narration strings to favor contractions and a more natural spoken register, rerendered all five scenes, and produced /home/administrator/.hermes/manim/hermes-memory-layers/kokoro_voiceover_af_sky_contractions_synced.mp4.
- mk-obsidian-memory-impl-20260409 | [ENG] Execute Obsidian 4-layer memory system plan | agent=michael-knight | updated=2026-04-09T20:37:32+00:00 | latest=[2026-04-09 20:37] Cleaned the acceptance-run vault artifacts from agent-hermes/working-context.md, agent-hermes/daily/2026-04-09.md, agent-hermes/mistakes.md, and agent-shared/decisions-log.md. Kept the new Obsidian folder structure and header files intact. Verified the acceptance strings no longer exist in the vault.
- T41 | [PUB][Automation] Weekly Buttondown authorship + distribution pipeline | agent=michael-knight | updated=2026-04-09T19:03:06Z | latest=[2026-04-09 15:03] cron_status=error last_run=2026-04-09T19:03:06Z mode=auto-draft error=buttondown_api_401_unauthorized
- hc0407061405 | Harbor and Cross Awaiting Artwork Review | agent=mc | updated=2026-04-07T06:14:05.684036 | latest=[2026-04-07T06:14:05.684036] Images generated for Apr 07-13, 2026. 21 slides in composited/. Reply go to post.
- T43 | [PUB][Phase 13] Newsletter automation upgrade + typography spacing + thumbnail pipeline refresh | agent=michael-knight | updated=2026-04-04T14:16:20Z | latest=[

## Todo

- mk-content-pipeline-redo-20260410 | [CREATIVE] Rebuild automated content pipeline video for quality and brand accuracy | agent=michael-knight | updated=2026-04-10T14:09:36-04:00 | latest=[2026-04-10 14:09] Cancelled by Angel before third-pass rebuild/render. No further work in progress.
- T46 | [PUB][Editorial] Apply style-guide revision wave to all live articles | agent=— | updated=2026-04-04T14:21:56Z | latest=[
- T36 | [PUB][IMG] Regenerate article images from ligne-claire prompt pack | agent=— | updated=2026-04-04T03:39:12Z | latest=[

## Blocked

- mk-content-pipeline-redo-20260410 | [CREATIVE] Rebuild automated content pipeline video for quality and brand accuracy | agent=michael-knight | updated=2026-04-10T14:09:36-04:00 | latest=[2026-04-10 14:09] Cancelled by Angel before third-pass rebuild/render. No further work in progress.
- T44 | [PUB][IMG] Re-render all thumbnails in ligne claire style (existing + future) | agent=michael-knight | updated=2026-04-04T14:16:20Z | latest=[

## Recurring

- auto-hermes-heartbeat | [AUTO] Hermes heartbeat monitor | agent=michael-knight | updated=2026-04-11T21:00:12-04:00 | latest=cron_status=ok last_run=2026-04-11T21:00:12-04:00 runtime=ok jobs_enabled=14 disabled=0 issues=0
- auto-research-react-approver | [AUTO] Research react approver | agent=michael-knight | updated=2026-04-11T20:56:29-04:00 | latest=cron_status=ok last_run=2026-04-11T20:56:29-04:00 action=ran_react_approve_all reacted_messages=RSP-20260410-S3,RSP-20260410-S1,RSP-20260409-S3,RSP-20260409-S2,RSP-20260409-S1 pending_only=RSP-20260410-S2 output=No_reacted_pending_draft_IDs_found channel=1477414797757907075
- auto-camofox-watchdog | [AUTO] Camofox watchdog | agent=michael-knight | updated=2026-04-11T20:48:24-04:00 | latest=cron_status=ok last_run=2026-04-11T20:48:24-04:00 http=200 running=true restart=no
- auto-publication-rss-scan | [AUTO] Publication RSS scan | agent=michael-knight | updated=2026-04-11T18:02:00.764906-04:00 | latest=cron_status=ok last_run=2026-04-11T18:02:00.764906-04:00 items=200
- auto-pub-release-watch | [AUTO] Publication release watch | agent=mc | updated=2026-04-11T17:24:38-04:00 | latest=c
- auto-ai-papers-tracker | [AUTO] AI Agent Papers Tracker | agent=michael-knight | updated=2026-04-10T08:06:30-04:00 | latest=cron_status=ok last_run=2026-04-10T12:06:06.428253+00:00 new_count=0 status=no_changes vault_writeup=/mnt/c/Users/Administrator/Documents/HermesVault/Hermes/ai-agent-papers/ai-agent-paper-2026-04-10.md
- T42 | [AUTO] Weekly Buttondown issue | agent=michael-knight | updated=2026-04-09T19:03:06Z | latest=[2026-04-09 15:03] cron_status=error last_run=2026-04-09T19:03:06Z mode=auto-draft error=buttondown_api_401_unauthorized
- auto-painpoint-scan-1775174386 | [AUTO] Publication painpoint scan | agent=mc | updated=2026-04-09T15:52:04.176171Z | latest=c
- auto-publication-community-scan | [AUTO] Publication community scan | agent=mc | updated=2026-04-08T16:10:00Z | latest=c
- auto-publication-builder-discovery | [AUTO] Publication builder discovery | agent=mc | updated=2026-04-08T14:41:12.173290+00:00 | latest=c
- T047 | [AUTO] Harbor content pipeline — RSS research and candidate generation | agent=— | updated=2026-04-06T23:09:13.161643+00:00 | latest=[2026-04-06 19:45] New Telegram channel wired: @harborandcross (ID: -1003576658393). Bot: HarborCrossNotify_bot. send-telegram.js updated. Discord removed.

## Content Pipeline

### Ideas

- C013 | Voice in/out is becoming table stakes for AI apps | owner=openclaw | updated=2026-03-12T18:18:27.429Z
- C012 | Capacity constraints as product strategy (waitlists, staged rollout, honest SLAs) | owner=openclaw | updated=2026-03-12T18:18:25.923Z
- C002 | The 'glue developer' — why automations matter more than features | owner=openclaw | updated=2026-03-12T18:18:24.569Z
- C006 | App Store screenshot teardown — what top apps do differently | owner=openclaw | updated=2026-03-12T18:18:21.453Z
- C005 | How I use local-only AI automation to run my solo business | owner=openclaw | updated=2026-03-12T18:18:19.642Z
- C011 | Localization is distribution: how indie apps win without bigger models | owner=openclaw | updated=2026-03-12T18:18:17.395Z
- C014 | Inbox as identity: why agent email wins | owner=openclaw | updated=2026-03-12T18:00:00.000Z
- C015 | AI inside the work surface beats standalone AI apps | owner=openclaw | updated=2026-03-12T18:00:00.000Z
- C016 | From prompting to assigning: the next agent wave | owner=openclaw | updated=2026-03-12T18:00:00.000Z

### Ready Items

- C004 | Free workbook: Plan your first iOS app in a weekend | owner=— | updated=2026-03-02T12:15:00Z
- C007 | Template: 7-day app launch plan | owner=— | updated=2026-03-02T12:15:00Z
- C010 | Ebook: The Solo Dev's Guide to App Store Growth (No Budget Edition) | owner=— | updated=2026-03-02T12:15:00Z
- C001 | Why I build iOS apps with AI (and what I've learned) | owner=— | updated=2026-03-01T19:27:00Z
- C003 | 5 things I wish I knew before publishing my first iOS app | owner=— | updated=2026-03-01T19:27:00Z

## What Happened Recently

- mk-harbor-batch-verification-20260411 | [OPS] Verify Harbor & Cross restored composited batch against review week and posting manifest | agent=michael-knight | updated=2026-04-11T20:33:00-04:00 | latest=[2026-04-11 20:33] Verified the restored flat archive files were not the full current review batch. The real Apr 07-13 assets were in composited/archive/2026-04-10. Moved all 56 current-batch feed/reel files back into composited/. Current content-plan covers Apr 07-13, but posting-manifest.json is still stale for Apr 05-11, so this batch is ready for review and local post-bridge prep, not already scheduled from the current manifest.
- mk-harbor-composited-archive-check-20260411 | [OPS] Check Harbor & Cross composited/archive for latest images | agent=michael-knight | updated=2026-04-11T20:26:00-04:00 | latest=[2026-04-11 20:26] Verified /home/administrator/harborandcross_marketing_pipeline/composited was empty and composited/archive held 98 image files. Moved all 98 files back into composited/. Archive is now empty.
- mk-harbor-pipeline-schedule-check-20260411 | [OPS] Check Harbor & Cross content pipeline next fire and review gate | agent=michael-knight | updated=2026-04-11T20:22:04.579569-04:00 | latest=[2026-04-11 20:22] Verified cron job d759986ad7fd is scheduled daily at 6:00 AM ET with next_run_at=2026-04-12T06:00:00-04:00. Existing review task hc0407061405 covers Apr 07-13, 2026 and was updated 2026-04-07T06:14:05.684036, so tomorrow's run falls within the job's 6-day skip gate and is expected to skip fresh generation.
- mk-hermes-openclaw-postbridge-20260411 | [OPS] Queue Hermes+OpenClaw X post via post-bridge | agent=michael-knight | updated=2026-04-11T10:51:53-04:00 | latest=[2026-04-11 10:51] Review item RSP-20260411-S2 created in /home/administrator/site/scripts/research-post-review.json and approved through approve-research-post.sh. Scheduled via post-bridge for 2026-04-11T15:00:51Z (11:00 AM ET).
- mk-hermes-openclaw-x-post-20260411 | [SOCIAL] Approve and send Hermes + OpenClaw X post via post-bridge | agent=michael-knight | updated=2026-04-11T10:22:58-04:00 | latest=[2026-04-11 10:22] Post-bridge created X post 96dc6860-b3bb-4e5d-8009-b5ad956f2107 with status=scheduled for 2026-04-11T14:24:40Z (10:24 AM ET). Caption length: 234 chars.
- mk-hermes-openclaw-research-20260411 | [RESEARCH] Hermes Agent + OpenClaw community workflows and provider rotation | agent=michael-knight | updated=2026-04-11T09:42:43.166441-04:00 | latest=[2026-04-11 09:42] Delivered research summary + attached markdown brief to Discord channel 1477414797757907075. Local file: /home/administrator/.hermes/output/hermes-openclaw-research-2026-04-11.md.
- mk-x-discord-delivery-fix-20260410 | [OPS] Fix daily X research Discord delivery failure | agent=michael-knight | updated=2026-04-10T14:46:19.012029-04:00 | latest=[2026-04-10 14:46] heartbeat_ok: runtime up, x pipeline enabled, approver enabled
- mk-gateway-20260409 | [OPS] Restore Hermes gateway for Telegram chat | agent=michael-knight | updated=2026-04-09T20:06:45+00:00 | latest=[2026-04-09 16:06] Forced gateway recycle complete: replaced runtime with pid 5459, health endpoint OK, and telegram reconnected in polling mode at 16:06:04.

## System Health

- In-progress tasks: 2
- Review tasks: 8
- Blocked tasks: 2
- Recurring tasks: 11
- Jobs API error: —
