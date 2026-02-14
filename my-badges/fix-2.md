<img src="https://my-badges.github.io/my-badges/fix-2.png" alt="I did 2 sequential fixes." title="I did 2 sequential fixes." width="128">
<strong>I did 2 sequential fixes.</strong>
<br><br>

Commits:

- <a href="https://github.com/hesreallyhim/really-claude-code/commit/d08c7b2ec27f8b8a2e040518eef18741430d153b">d08c7b2</a>: fix: move marketplace.json out of .claude-plugin

The .claude-plugin/ directory signals to Claude Code that the repo is an
installable plugin. Since this repo is a marketplace index (not a plugin),
having marketplace.json inside .claude-plugin/ caused validation errors:
"Unrecognized keys: components, status, added"

Moving it to the repo root removes the false plugin signal.

Co-Authored-By: Claude Opus 4.6 <noreply@anthropic.com>
- <a href="https://github.com/hesreallyhim/really-claude-code/commit/7731dac1c0e883510c4969b245030262175f0235">7731dac</a>: Fix typo in plugin installation command


Created by <a href="https://github.com/my-badges/my-badges">My Badges</a>