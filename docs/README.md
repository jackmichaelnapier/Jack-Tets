# docs

Abstracted diagrams of recurring workflows.

- `weekly-publish-pipeline.html` — anatomy of the weekly report run: the three
  source tiers and their unequal failure lanes, the completeness gate that can
  abort, the ordered publish stack and its 2xx barrier, the shared-contract
  dependency graph across the daily and weekly cadences, and the gate/artifact
  link split.
- `staged-import-engine.html` — anatomy of the staged import engine: two feeds
  normalised into one model, four dedup keys, the hold / screen / price /
  validate chain that yields a go-list, the preflight and close gates that
  bracket a resume-safe push, the state a single record moves through with its
  two recovery loops, and the rule that any prose a code path depends on
  becomes a test.

Client names, account identifiers, table names, channel IDs, repository names
and domains are deliberately omitted — these describe shape, not configuration.
Open the HTML file in a browser; it is self-contained apart from webfonts.
