# Positive square energy of maximal outerplanar graphs — reproduction snapshot

Author: **Jonas J. Gebendorfer**  
Snapshot: **8 November 2026**

This repository distributes the fixed reproduction package accompanying
AI-assisted mathematical work on positive square energy of maximal
outerplanar graphs. The archive contains proof sources, exact certificates,
finite-domain data, replay programs and review evidence. Its publication
does not assert a new independent human review, formal certification or
priority claim.

## Download and archive identity

Download [Aletheion-MOP-Repro-2026-11-08.zip](Aletheion-MOP-Repro-2026-11-08.zip)
from the repository root. On its GitHub file page, choose **Download raw file**.
Preserve the extracted directory structure. The original archive has:

- **893 ZIP entries**
- **23,102,507 bytes**
- SHA-256: `3fbf164359767e88cb451bb276cdd30990261436f1366cde07813375588a7db6`

`ARCHIVE_MEMBERS.json` indexes the archive except that self-index.
`REPRO_MEMBERS.json` identifies its mathematical source/code subset.
Archive and member hashes establish byte identity, not mathematical truth.

## Start a replay

Use Python 3.12 with NumPy. The observed review environment was CPython
3.12.14 with NumPy 2.3.5. Keep assertions enabled: **do not use `python -O`**.
On Windows, extract to a short path. Run these commands from the extracted
archive root:

```text
python -B repro_check_integrity.py
python -B repro_replay_b71.py --output fresh_B71
```

The output directory `fresh_B71` must not already exist. The second command
runs the complete finite quick/positive/masked/assembly recipe. It does not
perform a complete new numerical replay of every unbounded compact family.

Read the archive's `README.md` for the individual finite stages, the full
compact replay commands, smoke-test scopes and required separation of Python
processes/arithmetic backends. Full compact replays may take many hours.

## Evidence and scope

The review freshly executed the finite 328 positive targets, 130 masked
targets in 29 groups, and the 11,885-row finite assembly, together with the
other checks identified in the archive's observed-scope records.

The original complete slow private- and double-family compact certificates,
their source-bound results and raw partitions are retained. Those two
multi-hour compact computations were **not** freshly repeated in full by
this review. Small numerical smoke tests and conditional signed-tail checks
are explicitly distinguished from full family verification. **No fresh full
global numerical replay is claimed.**

The work and checking used AI assistance. Separate checking passes are not
independent human peer review or proof-assistant certification. The written
graph reductions, matrix arguments, analytic tails, finite coverage and
published input hypotheses remain necessary; a stored `PASS`, a checksum or
a successful process alone does not establish them. Consult the mathematical
manuscript and the complete source proofs when assessing those implications.
