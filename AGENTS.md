# Instructions for AI maintainers

Read `PROJECT_GOVERNANCE.md` before implementation work.

Mandatory:
- select workflow mode first;
- preserve legacy behavior;
- AUDIT/STRESS/DIAGNOSTIC do not authorize fixes;
- no full rewrite without explicit permission;
- use REUSE_FIRST with license/provenance review;
- do not commit secrets;
- keep analytical outputs reproducible;
- report exact TEST_LEVEL and residual risks.

Project-specific: preserve metric definitions and source-data provenance. Do not silently replace historical calculations when adding a new methodology; version the method.
