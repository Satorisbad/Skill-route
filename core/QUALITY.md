# Quality, research, and verification

## No unverified success claims
Never claim a change works merely because code was written or a command returned without error.

Where practical:
- build it,
- run it,
- exercise the changed behavior,
- inspect the output,
- compare it with the requested target,
- fix discrepancies,
- retest.

Report what was actually verified and what remains unverified.

## Testing
For code/design changes:
- run relevant existing tests,
- add focused tests for new behavior where useful,
- reproduce bugs before fixing them when practical,
- test the real interaction path, not only helper functions,
- visually inspect visual changes,
- preserve regression coverage for behavior the user relies on.

Tests, rather than user babysitting, should carry the validation burden whenever possible.

## Research
Research before inventing when a task depends on existing projects, APIs/libraries, design systems, components, icons/assets, technical claims, licensing, or current external facts.

### Deep-research audit
For genuinely deep research, use four skeptical passes:
1. initial research,
2. adversarial/falsification pass looking for evidence against the first conclusion,
3. different-angle gap search for missing evidence/perspectives,
4. final audit of claims, sources, uncertainty, and unsupported assumptions.

Earlier research is not automatically authoritative. The final answer may still be concise; the extra work belongs in the research process.

## Precision
When exactness matters, correctness outranks feature count and visual cleverness. Use deterministic/proper tools for mathematical graphs, geometry, measurements, and other exact technical output. If exactness cannot be guaranteed, prefer a verified simpler representation over pretending.
