<img src="https://my-badges.github.io/my-badges/fix-2.png" alt="I did 2 sequential fixes." title="I did 2 sequential fixes." width="128">
<strong>I did 2 sequential fixes.</strong>
<br><br>

Commits:

- <a href="https://github.com/hesreallyhim/github-api-usage-monitor/commit/a04f01cc552e23d62aad8aeec1b03fe9227211e9">a04f01c</a>: fix: address code review findings (batch 2)

- Fix path construction in spawnPoller: use path.join() instead of
  manual string concatenation with separator logic
- Improve state validation: validate individual BucketState entries
  inside isValidState, remove misleading TODO comment
- Make parseRateLimitResponse resilient to partial failures: skip
  invalid resources with continue instead of returning null

Co-Authored-By: Claude Opus 4.5 <noreply@anthropic.com>
- <a href="https://github.com/hesreallyhim/github-api-usage-monitor/commit/c05b819071c6839ed5696adde49212cbaad78f14">c05b819</a>: fix: address code review findings (batch 1)

- Fix debug log bug in post.ts: first field was showing last_used
  instead of first_used
- Strengthen isARealObject to reject arrays (!Array.isArray check)
- Deduplicate sleep() utility: extract to utils.ts, remove copies
  from poller.ts and state.ts

Co-Authored-By: Claude Opus 4.5 <noreply@anthropic.com>


Created by <a href="https://github.com/my-badges/my-badges">My Badges</a>