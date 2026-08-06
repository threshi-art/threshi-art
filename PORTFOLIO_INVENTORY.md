# Portfolio inventory

Last audited: 2026-08-05

## Repository-level inventory

| Repository | Visibility | Imported history | Current organization |
|---|---|---|---|
| `windows-efficiency-audit` | Public | Curated source extraction | Read-only PowerShell collector, launcher, syntax check, privacy documentation |
| `horizons-mod-tooling` | Private | Preserved local audited-baseline commit and tag | Authored scripts, tests, docs, checksums, and patch delta; no game binaries or assets |
| `personal-projects-portfolio` | Private | One curated source import | FinTelligence, Flowline, PearlFuel Lite, Windows Efficiency Audit |
| `Seriphim` | Private | Curated source imports | Seraphim platform, satellite-app portfolio, and reviewable EI-RAM engine import |
| `umgc-cs-portfolio` | Private | Curated coursework imports plus later Project 4 evidence work | Course folders, issue catalog, milestones, roadmap, and a draft polish PR |
| `threshi-art` | Public | Profile created during portfolio curation | Public landing page and evidence-based inventory |

## Status definitions

- **Working prototype**: documentation identifies a runnable local path, but the
  clean-checkout setup has not yet been independently reproduced in this audit.
- **Active build**: implementation and current product/release documentation are
  present, with material work still open.
- **Starter scaffold / placeholder**: planning or directory structure exists;
  it is not represented as implemented functionality.
- **Completed coursework archive**: a submitted or archived academic deliverable,
  not production software. Some projects include instructor-provided starter
  code extended by student work.

## Availability and constraints

- Windows Efficiency Audit is the first public source repository. Its PowerShell
  parser check passes; broad clean-machine functional validation remains open.
- All other substantive source repositories remain private.
- The Windows environment cannot validate Xcode builds, Apple signing,
  TestFlight, or App Store submission.
- No employer work is included in a public or private GitHub source import from
  this audit.
- No public release should be made from the private monorepositories until
  third-party assets, local paths, academic-use constraints, and clean setup
  have been reviewed project by project.
- The account's existing public display identity and profile fields were left
  alias-only; this repository does not publish a private real-name identity.

## Local source audit

The authoritative local tree at `OneDrive/Documents/Projects` was reviewed on
2026-08-05. These areas were deliberately not copied to GitHub:

| Local area | Classification | Reason not published |
|---|---|---|
| Boeing project folders and 787 visualization | Employer-related | Employer IP and identity boundary |
| Command & Control disc images, runtimes, downloads, and third-party trees | Rights-constrained | Commercial game binaries, licensed assets, and external repositories |
| Personal budget, retirement, and calculator files | Private personal data | Financial and identity-sensitive material |
| Loki University standards library | Third-party reference material | PDFs and templates without publication provenance |
| English2 example compiler code | Unverified historical sample | Authorship and course-source provenance not established |
| Substack manuscripts | Creative/private material | Outside the code portfolio; publication is a separate editorial decision |
| AEGIS documentation package | Concept documentation | Architecture-only baseline; predictive models unvalidated |
| AI Game Studio prototypes | Review required | Includes a 787-related view and remote third-party visualization dependency |

Flowline's local folder contains an uncommitted workspace; the GitHub portfolio
uses the earlier curated private snapshot instead of manufacturing local commit
history.
