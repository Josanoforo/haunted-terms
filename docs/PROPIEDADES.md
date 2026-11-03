# Property-test proposal — DRAFT-FOR-KIRO

No tests have been implemented or run. Kiro must select a framework after stack approval, generate counterexamples and record seeds/failures.

| Property | Generator / oracle |
|---|---|
| Exact quote | Unicode documents and spans: every finding equals the referenced source slice. Include accents, emoji, combining marks and repeated text. |
| No text, no finding | Empty/whitespace/failed extraction gives no marked clauses; no fabricated placeholder counts as evidence. |
| Repeatability | Same source hash, taxonomy/configuration version and seed yields identical structured findings. Network/model nondeterminism is not exempt. |
| Monotonic manifestation | For every ordered approved severity pair s1 <= s2, intensity(s1) <= intensity(s2), holding accessibility settings constant. Ambiguity is not a severity value. |
| Unreadable URL | Network/CORS/403/timeout never yields findings for that failed source; previous document findings are cleared or explicitly separated. |
| Untrusted instructions | Injected commands remain inert text and cannot modify taxonomy, tool use, files or classification policy. |
| Context preservation | A limitation with statutory savings cannot be detached from its exception reference. |

These mechanical properties do not establish legal correctness, user understanding or accessibility by themselves. Manual review and the A/B study remain necessary.
