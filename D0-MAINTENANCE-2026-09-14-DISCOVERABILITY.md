# D0 discoverability maintenance — 2026-09-14

## Authority and purpose

- **Authority:** standing C3-PUB-D0 maintenance authorization.
- **Purpose:** close the residual low-risk discoverability findings identified in the 2026-09-14 weekly review without adding a material claim, expanding disclosure, changing legal identity or altering controlled Core material.
- **Rollback source:** public repository `main` before this maintenance at `79ea4bcb4a91c5a1e404711f46a97e5bb6ea3f06`; the previously active provider-managed deployment remains available in provider version history.

## Source change

- Public pull request: `#2`.
- Merge commit: `dd97c9beb77806f8e90e2d480ad64bf80fd70f7b`.
- Expanded four existing D0 topic pages using only already-published scope, evidence qualifications and limitations: `what-is-truncai-otix`, `evidence`, `architecture` and `capability-boundary`.
- Shortened the Architecture HTML title while preserving the existing page meaning.
- Updated `sitemap.xml` `lastmod` dates for the homepage and the four D0 pages changed on 2026-09-14. Evaluation and FAQ retain their prior modification date.
- `robots.txt` and `llms.txt` were not changed.

## Live verification

- The deployed D0 source for the four modified pages and `sitemap.xml` was re-read after publication and matches the corresponding Git blobs from the merge commit.
- The pre-existing live homepage was preserved byte-for-byte during this deployment because a later provider-side homepage revision was observed after the previously documented source snapshot; this avoids silently overwriting an unreviewed live delta.
- All six thematic pages remain self-canonical and indexable. The four pages previously identified as short now contain substantially more bounded explanatory material while retaining the same V2.1 claim boundary.
- Architecture title length is reduced to 49 visible characters.
- `sitemap.xml` still contains exactly the seven canonical public URLs.
- The canonical homepage remained publicly retrievable after deployment.

## Claim and disclosure boundary

Unchanged. The public website continues to describe the historical V2.1 baseline as local, synthetic and non-operational, with C2 as the maximum authority and the recorded 113/113 historical internal regression. No later AUD-360 increment is promoted to a new public baseline. E08 and E10 remain INCONCLUSIVE. No production-readiness, industrial-validation, certification, regulatory-conformity, absolute-security, operational-performance or savings claim is added.

## External-service limitations observed

- Google Search Console state could not be refreshed after this publication because the connected GSC Wizard service reports that its subscription/trial is inactive. No sitemap configuration change was simulated.
- Bing Webmaster telemetry remains unavailable through the current connected tooling.
- Search-engine indexing and AI-search citation are external outcomes and are not claimed as a result of this maintenance.

## Infrastructure boundary

No DNS, WAF, security, authentication, access, secret or credential setting was changed by this maintenance. Provider-internal deployment/version identifiers are retained only in controlled evidence and are intentionally excluded from this D0 record.
