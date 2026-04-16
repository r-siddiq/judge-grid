# JudgeGrid

An interactive, static project plan for a proposed enterprise model
cost/performance routing benchmark. It describes how a future
continuously-updated, rubric-grounded, cost-aware read could be produced; this
file is not a live benchmark, measurement product, leaderboard, or source of
current results.

This repository contains a single self-contained webpage presenting the plan:
benchmark design, the human operation that produces it, worker-facing task
instructions, worker qualification, QA / rate-and-review, data output schema,
budget and timeline, and short essays on coding-agent selection.


LIVE DEMO
---------
The published GitHub Pages site is available at
<https://r-siddiq.github.io/judge-grid/>.


HOW TO OPEN
-----------
Double-click `JudgeGrid.html` in a current desktop browser (Chrome, Firefox,
Edge, or Safari). The page is fully self-contained: no internet connection is
needed for the core document, no setup, and no dependencies. It works offline
the moment it is opened; browser-version, file-storage, clipboard, and print
behavior can still vary.
(Citation links in the text require network access when clicked.)


WHAT'S INSIDE
-------------
The full plan, in one document:

  - Section 0  - Thesis: enterprise cost/performance routing, with coding as
                 the flagship category.
  - Section 1  - Benchmark design: task taxonomy, scoring model, cost metrics,
                 anti-contamination defenses.
  - Section 2  - The operation/pipeline: judge-at-scale + human gold sample,
                 with no redundant review layers.
  - Section 3  - Worker-facing task instructions (written in "You will..." voice,
                 organized by track, with a worked example and edge cases).
  - Section 4  - Worker qualification: three-stage gate with three fully-worked
                 example questions and an explicit pass/fail bar.
  - Section 5  - QA / rate-and-review: 5 parallel detectors, a reviewer
                 handbook, a 4-band quality gauge, an escalation ladder, and
                 collusion detection.
  - Section 6  - Data output: a 4-level schema, a syntax-highlighted JSON
                 sample row (with copy button), and an illustrative sortable leaderboard
                 with routing recommendations.
  - Section 7  - Budget & timeline: bottom-up math at a $100/hr wage, Gantt
                 chart, and a six-month planning envelope (~$8.05M midpoint).
  - Section 8  - Essays: daily-driver coding-agent choice, and current gaps
                 to evaluate before relying on autonomous SWE.


KEY FEATURES
------------
  - Dark / light mode toggle (top-right, also in the mobile bar).
  - Sticky table of contents with scrollspy.
  - Sortable tables (click a column header to sort; keyboard accessible).
  - Charts, diagrams, and tabbed views throughout.
  - Copy-the-JSON-sample button in Section 6.
  - Print / Save as PDF: use the native browser print dialog or Ctrl/Cmd+P.

The public package consists of the self-contained webpage and this README.


LICENSE
-------
Copyright (c) 2026 Rahim Siddiq. This project is licensed under the MIT
License; see `LICENSE` for the full text.

The current webpage is self-contained and does not bundle third-party
libraries or components. If a distribution includes third-party components,
they remain under their own applicable licenses and notices.


NOTE
----
All numeric values in the mock leaderboards, sample rows, routing readouts, and
budget visuals are illustrative planning values - invented or modeled to show
shape, not real benchmark results, customer data, quotes, or observed spend.
The operating scenario uses a mixed expert pool: software engineers for coding
and task-endorsed domain evaluators for the other task types. Its ~$8.05M
six-month midpoint is preserved, with compute sensitivity of roughly
$85k-$280k and a total-envelope sensitivity of roughly $7.96M-$8.15M.
External figures are dated historical evidence unless the page explicitly says
otherwise. Provider prices and status are volatile reference inputs, not live quotes;
model status, pricing, benchmark results, and market estimates change quickly
and must be re-verified from the linked authoritative sources before use.
