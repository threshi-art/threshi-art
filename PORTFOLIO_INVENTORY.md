# Portfolio inventory

Public selection updated: 2026-10-09

## Repository-level inventory

| Repository | Visibility | Lifecycle | Current organization |
|---|---|---|---|
| `nightstalkers` | Private | Active | Nightstalkers Chopper Command — React + Babylon.js Thermal Rescue Console |
| `Seraphim` | Public | Active | Public-safe Seraphim platform, satellite-app portfolio, reviewed Skill packages, EI-RAM / Argus within tree (renamed from `Seriphim`) |
| `flowline` | Private | Active | Offline iOS game + browser prototype; Capacitor/Xcode shell |
| `PearlFuel-Web` | Private | Active | PearlFuel Lite web/desktop nutrition planning workspace |
| `FinTelligence` | Private | Active | Aerospace-inspired finance / retirement planning command center |
| `armada2-mod` | Private | Active | Reversible Armada II mod build/install pipeline (no game assets); formerly `horizons-mod-tooling` |
| `personal-projects-portfolio` | Private | Umbrella snapshot | Historical curated import of FinTelligence, Flowline, PearlFuel, diagnostics — not the 1:1 project repos |
| `threshi-art` | Public | Profile index | Public landing README + this inventory |
| `windows-efficiency-audit` | Private | **Archived** | Read-only PowerShell collector |

## Not separate repositories

| Name | Where it lives |
|---|---|
| Argus Vigil | Inside Seraphim |
| EI-RAM Analysis Studio | Inside Seraphim |
| AEGIS / FinTelligence architecture package | Local documentation only |

## GitHub Projects ≠ repos

User-owned **Projects** boards are planning surfaces, not code repositories.
Personal boards default to **Private**; that does not control repo visibility.

| Board | State |
|---|---|
| [Project Portfolio Roadmap](https://github.com/users/threshi-art/projects/2) | **Open** (living portfolio planning; board stays private) |

## Status definitions

- **Working prototype**: documentation identifies a runnable local path, but the
  clean-checkout setup has not yet been independently reproduced in this audit.
- **Active build**: implementation and current product/release documentation are
  present, with material work still open.
- **Within Seraphim**: module lives inside the Seraphim monorepo; not a 1:1
  GitHub repo of its own.
- **Archived**: repository retained for provenance; not an active project twin.


## Availability and constraints

- Active private sources (on purpose): Nightstalkers, Flowline, PearlFuel-Web,
  FinTelligence, armada2-mod.
- Seraphim and Infinity are public project repositories. Public visibility does
  not certify production readiness.
- The Windows environment cannot validate Xcode builds, Apple signing,
  TestFlight, or App Store submission.
- No employer work is included in a public or private GitHub source import from
  this audit.
- No public release should be made from private repositories until third-party
  assets, local paths, privacy constraints, and clean setup have been
  reviewed project by project.
- The account's existing public display identity and profile fields were left
  alias-only; this repository does not publish a private real-name identity.

## Local source audit

The authoritative local tree at `OneDrive/Documents/Projects` was reviewed on
2026-08-05 (and remapped 2026-08-24). These areas were deliberately not copied
to GitHub:

| Local area | Classification | Reason not published |
|---|---|---|
| Boeing project folders and 787 visualization | Employer-related | Employer IP and identity boundary |
| Command & Control disc images, runtimes, downloads, and third-party trees | Rights-constrained | Commercial game binaries, licensed assets, and external repositories |
| Personal budget, retirement, and calculator files | Private personal data | Financial and identity-sensitive material |
| Substack manuscripts | Creative/private material | Outside the code portfolio; publication is a separate editorial decision |
| AEGIS documentation package | Concept documentation | Architecture-only baseline; predictive models unvalidated |
| AI Game Studio prototypes | Review required | Includes a 787-related view and remote third-party visualization dependency |

Canonical local ↔ GitHub pairing for active Programs work is maintained in
`Documents/Projects/Programs/REPO_MAP.md` (one project = one folder = one repo).
