# My AI Engineering Path
<!-- Managed by the ai-engineering-from-scratch learning skills.
     Repo: https://github.com/rohitg00/ai-engineering-from-scratch -->

## Mission
Ship an AI product. Build goal: an agent.

## Placement
- Date: 2026-10-03
- Score: self-selected
- Entry point: Phase 0: Setup & Tooling
- Pace: as fast as possible

## Path
| Phase | Name | Status | Est. hours |
|-------|------|--------|------------|
| 0 | Setup & Tooling | Do | 14 |
| 1 | Math Foundations | Do | 23 |
| 2 | ML Fundamentals | Do | 21 |
| 3 | Deep Learning Core | Do | 15 |
| 4 | Computer Vision | Do | 27 |
| 5 | NLP: Foundations to Advanced | Do | 30 |
| 6 | Speech & Audio | Do | 18 |
| 7 | Transformers Deep Dive | Do | 14 |
| 8 | Generative AI | Do | 14 |
| 9 | Reinforcement Learning | Do | 13 |
| 10 | LLMs from Scratch | Do | 26 |
| 11 | LLM Engineering | Do | 19 |
| 12 | Multimodal AI | Do | 65 |
| 13 | Tools & Protocols | Do | 43 |
| 14 | Agent Engineering | Do | 55 |
| 15 | Autonomous Systems | Do | 20 |
| 16 | Multi-Agent & Swarms | Do | 28 |
| 17 | Infrastructure & Production | Do | 32 |
| 18 | Ethics, Safety & Alignment | Do | 31 |
| 19 | Capstone Projects | Do | 620 |

Total (Do): ~1128 hours across 20 phases.

## Progress log
| Date | Lesson | Quiz | Note |
|------|--------|------|------|
| 2026-10-03 | 00-setup-and-tooling/01-dev-environment | 1/3 | Built .venv with uv (Python 3.13), torch 2.14 + MPS works (mps 2x cpu). Mixed up install order; used __version__ as GPU check. |
| 2026-10-03 | 00-setup-and-tooling/02-git-and-collaboration | 3/3 | Warm-up 2/2 (install order now solid). Sandbox ~/Downloads/git-sandbox: add/commit, branch isolation. Course repo origin = upstream, no fork yet. |

## Review queue
- 00-setup-and-tooling/01-dev-environment: bottom-up install order (system first); GPU check = torch.backends.mps.is_available() on Mac, not __version__
