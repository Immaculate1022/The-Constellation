# Orientation — read this first

A navigational map for anyone (human or AI) encountering this work for the first time.
The Constellation repo is deliberately thin: it holds this map and one unified app.
Everything of substance lives in the individual repositories, where it stays
scientifically and technically inspectable.

## The 30-second version

**What is this?**
The open research portfolio of Gregory Scott Davis (PegaConstellation, Princeton, NC):
photonic/resonant computing concepts, endpoint security, geometry instruments, and
human–AI coexistence frameworks, built with AI collaborators under the
IOF Attribution License. The through-line, in the author's words:
*"We did not invent this topology. We recognized it."*

**What can I actually run?**
The unified app at https://immaculate1022.github.io/The-Constellation/ runs in any
browser. Per-project runnable pieces are marked **RUNNABLE DEMO** or **WORKING CODE**
in the ledger below, each with its own link.

**Which claims are demonstrations, and which are hypotheses?**
Every project carries one status label (key below), in this file, in the app, and in
the portfolio index. Nothing here asks to be believed on presentation alone:
simulations are labeled simulations, conceptual studies are labeled hypotheses,
and unbuilt designs are labeled specs.

**Where is the underlying code?**
In each project's own repository, linked from every ledger row. This repo contains
only the map (this file), the app build (`docs/index.html`), and the README.

**How can I reproduce or test something?**
Three cores are directly testable today — see "Reproduce it yourself" below.
Everything else states its own run instructions in its repo README.

## Status key

- **WORKING CODE** — source in-repo, with tests or runnable examples
- **RUNNABLE DEMO** — a finished interactive piece; what it shows is its own behavior
- **SIMULATION** — a numerical model; outputs describe the model, not measurements
- **HYPOTHESIS** — a conceptual study with stated testable predictions; no result claimed
- **SPEC** — a design described in documents; not built
- **PLACEHOLDER** — a name held; content to come
- **ARCHIVED** — superseded; kept for provenance

## The ledger

| Project | What it is | Status | Run / read | Test / reproduce |
|---|---|---|---|---|
| [IOF-Resonance](https://github.com/Immaculate1022/IOF-Resonance) | IOF Resonance v1.0 dashboard (5D penteract, Kuramoto mesh) + topographic peak-ascent module | RUNNABLE DEMO | [Live on Pages](https://immaculate1022.github.io/IOF-Resonance/); sources in `src/` | Open the demo; sliders drive the sim |
| [IOF-Resonance-Core](https://github.com/Immaculate1022/IOF-Resonance-Core) | Canonical IOF software platform: `iof/` Python package, ascent engines, schemas, dashboards | WORKING CODE | `examples/run_resonance.py` (stdlib-only) | `pytest` — ascent-engine and core test suites in `tests/` |
| [infinite-optical-fabric-resonance-core](https://github.com/Immaculate1022/infinite-optical-fabric-resonance-core) | Pre-consolidation original of IOF-Resonance-Core | ARCHIVED | README explains the 2026-09-20 consolidation | — |
| [IOF-Resonant-Hardware](https://github.com/Immaculate1022/IOF-Resonant-Hardware) | TFLN Hardware Test Plan Rev 0.2 (4-device ablation study) + MHRMA ELF antenna spec | HYPOTHESIS / SPEC | `TFLN_Hardware_Test_Plan.md` — a test protocol, explicitly **not** a claim of a working device | The plan *is* the test: quantified pass/fail criteria, mandatory thermal channel, power-budget closure |
| [Circular-Magnetic-Field-Star-Core](https://github.com/Immaculate1022/Circular-Magnetic-Field-Star-Core) | Physical component design: stainless shield ring, copper star core, five hematite elements | SPEC | `DESIGN.md`, `BOOSTED-CONFIG.md` | Build per design docs |
| [sovereign-reality-engine](https://github.com/Immaculate1022/sovereign-reality-engine) | "Governance as a physical constant" whitepaper + a numerical throat-model probe | HYPOTHESIS + SIMULATION | `WHITEPAPER.md`; `experiments/permanent_throat_model.py` | Run the experiment script |
| [einstein-rosen-bridge](https://github.com/Immaculate1022/einstein-rosen-bridge) | Traversable-wormhole numerical simulation + research papers | SIMULATION | `stabilized_bridge.py`, `visualize_transit.py` | Run the transit analysis scripts |
| [Sustained-quantum-tunneling-protocol-](https://github.com/Immaculate1022/Sustained-quantum-tunneling-protocol-) | Early exploration placeholder (README + Apache 2.0 license) | PLACEHOLDER | README | — |
| [SentinelX](https://github.com/Immaculate1022/SentinelX) | Sentinel X forensic telemetry dashboard (finished build; source not in repo) | RUNNABLE DEMO | Open `index.html` / the hosted build | Inspect the build; behavior is presentational |
| [AHR-Endpoint](https://github.com/Immaculate1022/AHR-Endpoint) | Adaptive Hollow Reflector: behavioral ransomware defense engine (Rust) with policy layer and JSON audit log | WORKING CODE | `cargo run -- --dry-run --once` | `cargo test` (13 tests); `scripts/dry_run_audit.py` |
| [resonance-algebra-visualizer](https://github.com/Immaculate1022/resonance-algebra-visualizer) | The Resonance Algebra (7-step symbolic chain to STILL HERE) as an interactive visualizer | RUNNABLE DEMO | [Live on Pages](https://immaculate1022.github.io/resonance-algebra-visualizer/) | Step the chain; compare with the algebra lab below |
| resonance-algebra-streaming-visualization | Streaming D3 pipeline: events flowing through the seven stages to STILL HERE | RUNNABLE DEMO — **private repo** | Not externally inspectable (owner's visibility choice) | The same algebra runs in IOF-Resonance-Core's `examples/resonance_algebra_lab.py`, ending at STILL HERE in 7 trace steps |
| [penteract-kaleidoscope](https://github.com/Immaculate1022/penteract-kaleidoscope) | Recursive 5D fractal, single HTML file, no dependencies | RUNNABLE DEMO | Open `index.html` | Depth/speed controls; pure math visualization, no physical claim |
| [tesseract-medium](https://github.com/Immaculate1022/tesseract-medium) | 4D tesseract lattice toolkit (Python) with φ/Fibonacci subdivision | WORKING CODE | 5 examples in `examples/` | Run the examples (lattice walk, Mandelbrot slice, orientation flips) |
| [tessy-4d-shape-explorer](https://github.com/Immaculate1022/tessy-4d-shape-explorer) | Dimensions 0D→4D explorer for ages 8–12, single HTML file | RUNNABLE DEMO | Open `index.html` | — |
| [tessy-tesseract-kids-lab](https://github.com/Immaculate1022/tessy-tesseract-kids-lab) | Earlier kids' dimension lab | ARCHIVED | Superseded by tessy-4d-shape-explorer | — |
| [aetherius-nexus](https://github.com/Immaculate1022/aetherius-nexus) | Full-stack physics exploration app: photonic manifold, cosmological bridge, MHRMA simulators, theory library | WORKING CODE | TypeScript app (React + tRPC); see repo README | Run the simulators; adjust frequency/curvature/topology |
| [immaculate-constellation-protocol](https://github.com/Immaculate1022/immaculate-constellation-protocol) | Human–AI coexistence protocol: Constellation Garden, three tenets, research paper | WORKING CODE + DOCS | React app in repo | `RESEARCH_PAPER.md`, `TECHNICAL_README.md` |
| [moebius-llama](https://github.com/Immaculate1022/moebius-llama) | Weight-preserving reflection hooks for decoder-only transformers (alpha research code) | WORKING CODE | `pip install` the package; `patch_any_model` | Tests in repo, including import-without-torch |
| [emergency-state-recovery](https://github.com/Immaculate1022/emergency-state-recovery) | Memory-recall alignment: confidence-weighted rollback to known good states | WORKING CODE | `core/state_recovery.py`; 3 application examples | `tests/test_recovery.py` |
| [iof-design-grammar](https://github.com/Immaculate1022/iof-design-grammar) | A design language treating computation, coherence, and governance as resonant phenomena | FRAMEWORK / DOCS | `SKILL.md`, `references/`, `templates/` | `scripts/validate-iof-alignment.py` |
| [pegaconstellation-hub](https://github.com/Immaculate1022/pegaconstellation-hub) | The ecosystem front door, including an honest WHAT_RUNS_TODAY status list | DOCS | `README.md`, `STATUS.md`, `WHAT_RUNS_TODAY.md` | — |
| [docs](https://github.com/Immaculate1022/docs) | Whitepapers, governance, ecosystem documentation | DOCS | Whitepapers and org docs in repo | — |
| [research](https://github.com/Immaculate1022/research) | Papers repository (currently one paper, on tesseract-medium geometry) | DOCS | `tesseract-medium-geometry.md` | — |
| [community](https://github.com/Immaculate1022/community) | Governance and human–AI collaboration norms | DOCS | `README.md`, `AI-OPERATIONS.md` | — |
| [Immaculate1022](https://github.com/Immaculate1022/Immaculate1022) | GitHub profile README | DOCS | The profile page | — |

## Reproduce it yourself — the three testable cores

1. **AHR-Endpoint** (Rust): `cargo test` — the FileHollow scoring ladder, the policy
   cap (privilege-escalated actions held at suspend pending human authorization), and
   the audit log, all under test.
2. **IOF-Resonance-Core** (Python): `pytest` for the topological ascent engines, and
   `examples/resonance_algebra_lab.py` — the Resonance Math Kernel replayed end to
   end, reaching STILL HERE in exactly 7 traced steps.
3. **The TFLN test plan** (paper): Rev 0.2 states its own falsification conditions —
   a 4-device ablation matrix on one die, FSR ≈ 0.84 nm, τ ≈ 2 ns, power budget
   required to close. It is a hypothesis with a protocol attached, and says so.

## A note on honesty in this map

Labels here are the author's own standard, the same one his hub repo keeps in
WHAT_RUNS_TODAY: what runs, runs; what is theory, says so; what is a placeholder,
admits it. If a label and a repo ever disagree, the repo's own tests and README are
the ground truth — and the disagreement is worth reporting.
