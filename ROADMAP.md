# A/OS — Public Roadmap (open artifacts)

Purpose: lightweight visibility for VCs/reviewers; no secrets, no hard dates.

## Near-term
- [x] DecisionTrace Schema v0.1 (draft) — release v0.1.0
- [x] Evidence Export Packs v0.1 (draft) — release v0.1.0
- [ ] Schema v0.1.1: add `policy_citations` (policy_id, version, decision_id); clarify `actor` shape; tighten `isolation_key`.
- [ ] Examples: add `blocked` and `hold` traces; finance_approve + access_approve NDJSON.
- [ ] Evidence packs v0.1.1: Splunk sourcetype note, Sentinel table mapping, replayable sample bundle.
- [ ] PolicyGates Checklist v0.1 (new repo): categories, approval patterns, GateScopes.
- [ ] Docs: `SECURITY.md` (vuln disclosure) + `CONTRIBUTING.md` (how to propose changes).
- [ ] CI: JSON Schema check on PRs; NDJSON line-lint.

## Next
- [ ] DecisionTrace Schema 1.0.0 RC with changelog & migration notes.
- [ ] OTel exporter sample (minimal Python/TS) for DecisionTrace → OTel JSON.
