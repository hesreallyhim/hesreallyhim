<img src="https://my-badges.github.io/my-badges/fix-3.png" alt="I did 3 sequential fixes." title="I did 3 sequential fixes." width="128">
<strong>I did 3 sequential fixes.</strong>
<br><br>

Commits:

- <a href="https://github.com/hesreallyhim/github-api-usage-monitor/commit/621b9bfc32cf772f6873564df519e505b7147bb1">621b9bf</a>: fix
- <a href="https://github.com/hesreallyhim/github-api-usage-monitor/commit/d2f7ae0f4e1b5fd14fcbea67d2b45b038178da11">d2f7ae0</a>: fix: add scripts/*.mjs to allowDefaultProject for editor compatibility

The typescript-eslint project service errors when the editor opens .mjs
files not covered by allowDefaultProject, even if they're in the global
ignores list. Adding the pattern suppresses the editor parsing error.

Co-Authored-By: Claude Opus 4.5 <noreply@anthropic.com>
- <a href="https://github.com/hesreallyhim/github-api-usage-monitor/commit/1668913dc041127df7295f71007e8b3eb202d9d0">1668913</a>: fix: move ESLint ignores to first position for proper global ignore behavior

In ESLint flat config, an ignores-only object must precede other config
entries to act as a true global ignore. When placed last, the
typescript-eslint project service attempted to parse .mjs files before
the ignore took effect, causing editor errors for scripts like
render-diagnostics.mjs.

Co-Authored-By: Claude Opus 4.5 <noreply@anthropic.com>


Created by <a href="https://github.com/my-badges/my-badges">My Badges</a>