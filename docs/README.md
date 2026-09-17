# docs

Abstracted diagrams of recurring workflows.

- `weekly-publish-pipeline.html` — anatomy of the weekly report run: the three
  source tiers and their unequal failure lanes, the completeness gate that can
  abort, the ordered publish stack and its 2xx barrier, the shared-contract
  dependency graph across the daily and weekly cadences, and the gate/artifact
  link split.
- `staged-import-engine.html` — full-resolution anatomy of the staged import
  engine: a system map of every module in seven lanes, the dedup-key × case
  matrix, the funnel with real counts, a sequence diagram of one push chunk,
  a 25-state record lifecycle, the preflight and close gates with the failure
  each check would have caught, the unattended control plane, and every test
  file tiled by what it guards. `staged-import-engine.jpg` is a rendered copy.

Client names, account identifiers, table names, channel IDs, repository names
and domains are deliberately omitted — these describe shape, not configuration.
Open the HTML file in a browser; it is self-contained apart from webfonts.
