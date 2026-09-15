# v114 UX Flow Hardening

- Manual meal screen only navigates after a successful save.
- Photo meal registration returns to the meal list after successful persistence.
- Added non-blocking toast feedback for successful actions.
- Added contextual back navigation for secondary screens.
- Added an actionable empty state for meal history.
- Weekly Review now shows review-data completeness and a single next action.
- Success Patterns now shows evidence confidence (low / growing / sufficient).
- Existing localStorage key `dietLabRefV2` and normalization/migration behavior are preserved.
- QA: 29/29 PASS; local HTTP/PWA asset checks PASS.
