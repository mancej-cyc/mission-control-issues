# Artifacts

Self-contained HTML documents. Each one is a single file with inline CSS, inline SVG diagrams and
`data:`-URI images - no scripts, no frames, no external requests - so it opens correctly from
`file://` with no network.

| Artifact | What it is |
| --- | --- |
| [`mission-control-feature-guide.html`](mission-control-feature-guide.html) | A high-level guide to Mission Control's major features - the Board and control plane, the session desk (conversation, diff, files), Dispatch and the five task kinds, the backlog and its task sources, Foreman, Workflows and Personas, Retro and repository memory, and Ensembles - with 20 screenshots captured from a real built daemon driving a token-free demo fleet. |

## Reading them

GitHub's blob viewer shows HTML as source, and refuses to display files this large, so use one of:

- **Download and open it.** Press the `Download raw file` button on the file page, then open the
  file in a browser. This is the reliable path, and it needs no network once downloaded.
- **Render it in place** through a third-party proxy, e.g.
  `https://htmlpreview.github.io/?<the raw file URL>`. Convenient, but it routes the file through
  someone else's service.
