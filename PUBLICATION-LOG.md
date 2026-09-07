# D0 Publication and Maintenance Log

This log records authorised public-content maintenance for TruncAI-OTiX. It contains no private data, credentials, operational endpoints, provider-internal deployment/version identifiers, Worker runtime code or security configuration.

## 2026-09-07 — D0 operational-metadata sanitisation

- **Authority:** C3-PUB-D0 under Prompt Maestro TruncAI-OTiX V2.2.
- **Purpose:** remove provider-internal deployment/version identifiers from the public log so that public traceability does not expose operational infrastructure identifiers.
- **Scope:** `PUBLICATION-LOG.md` only; no public claim, website content, DNS, WAF, security, credentials, access or authentication change.
- **Rollback:** the pre-change public state remains recoverable through Git history; a complete pre-sanitisation copy is preserved in the controlled project archive.
- **Result:** public Git commit identifiers and public-content hashes remain available as provenance evidence; Cloudflare deployment/version identifiers are withheld from D0.

## 2026-09-07 — V2.1 D0 public evidence capsule

- **Authority:** explicit owner approval under C3-PUB-D0 and Prompt Maestro TruncAI-OTiX V2.2.
- **Purpose:** provide a public evidence index, controlled claims matrix, high-level architecture, machine-readable manifest and deterministic integrity record without exposing D2 technical material.
- **Release:** `V2.1-D0.1`.
- **Scope:** `PUBLIC-EVIDENCE-INDEX.md`, `PUBLIC-CLAIMS-MATRIX.md`, `PUBLIC-ARCHITECTURE.md`, `PUBLIC-MANIFEST.json`, `CHECKSUMS.sha256`, README discoverability and this publication record.
- **Disclosure exclusions:** personal or legal-entity identity, source code, exact schemas, algorithms, fixtures, datasets, detailed tests, SBOM, prompts, security internals, credentials, IP strategy, valuation and transaction material.
- **DNS, WAF, security, credentials, access and authentication change:** none.

### Evidence boundary

- The public repository can demonstrate D0 provenance, claim consistency, publication history and file integrity.
- The 113/113 regression and 10,000 virtual-case campaign remain internally evidenced, synthetic and not independently reproducible from D0.
- E08 continuity and E10 real human-review evidence remain INCONCLUSIVE and are not counted as PASS.
- No production readiness, external or industrial validation, certification, regulatory conformity or absolute-security claim is made.

## 2026-09-07 — Official public repository discoverability

- **Authority:** C3-PUB-D0 under Prompt Maestro TruncAI-OTiX V2.2.
- **Purpose:** make the existing D0 repository directly discoverable and navigable from the canonical website and machine-readable summary.
- **Scope:** `README.md`, `site/index.html` and `site/llms.txt`; no technical source, private tests, D2 material or personal identifiers were disclosed.
- **Repository content commits:** `9cb0eff03df5b9409b92b7a47fea089511d9d27f` and responsive-navigation follow-up `ebf02d00e4ce937f25c8e55aece9558959b1bab0`.
- **Cloudflare deployment evidence:** provider-internal deployment identifier withheld from D0; retained in controlled project evidence.
- **DNS, WAF, security, credentials, access and authentication change:** none.

### Published D0 hashes

| Public path | Bytes | SHA-256 | HTTP result |
|---|---:|---|---|
| `/` | 47,345 | `c20ae6b7266a525107002baa1f2404e1a2532e5ccea765656e185fcff71b941a` | 200 |
| `/llms.txt` | 3,912 | `0c2e669622ad7893813bac71e37f05486c278078f68ae4d6a0bd8d27ddc1af13` | 200 |

### Result

- The website exposes the official repository in navigation, hero, D0 disclosure, contact and footer areas.
- The HTML declares the relationship through `rel="me"` and Schema.org `sameAs`; the HTTP `Link` response header also exposes the repository relationship.
- `llms.txt` includes direct links to the repository, README, publication log and versioned website snapshot.
- The repository README links back to the canonical website and states that the repository is D0 public disclosure, not the controlled technical source or external validation.
- HTTP requests using browser, Claude, OpenAI, Bing/Copilot and Perplexity user-agent strings returned the same HTML bytes and SHA-256 value; user-agent simulation does not prove retrieval through those products' internal web tools.
- `HEAD` returned 200 without a response body, an unknown path returned 404, and `www` resolved to the canonical apex URL.
- **Evidence limitation:** public search-engine indexing and product-specific retrieval remain outside direct project control. A Copilot internal web-retrieval attempt also failed for GitHub Raw, so it did not isolate a truncaiotix.com server fault. The public repository does not independently reproduce the 113/113 internal test claim because technical source and evaluation artefacts remain D2 controlled.

## 2026-09-07 — Public website snapshot versioning

- **Authority:** C3-PUB-D0 under Prompt Maestro TruncAI-OTiX V2.2.
- **Purpose:** preserve a versioned public copy of the content already served at https://truncaiotix.com and remove the traceability gap between the live website and the public repository.
- **Scope:** README update plus `site/index.html`, `site/robots.txt`, `site/sitemap.xml` and `site/llms.txt`.
- **Source state read:** active Cloudflare deployment/version recorded in controlled project evidence; provider-internal resource name and identifiers withheld from D0.
- **Repository snapshot commit:** `1037cab056da13a430e99ede84d1bff2325a98b1`.
- **Repository state before change / rollback:** `f062c76b81611156d33b89ad93a5f80215ae2d78`.
- **Cloudflare change:** none.
- **DNS, WAF, security, credentials, access and authentication change:** none.

### Source and public-verification hashes

| Public path | Bytes | SHA-256 | HTTP result |
|---|---:|---|---|
| `/` | 45,840 | `105a9fa182428ba1ede5bdb1d5d1f453399f1b6800d02205b935ea9c1aa771c1` | 200 |
| `/robots.txt` | 356 | `bf4ad63640bde8e8789716a377c45a3be2577835dfee541f0c330ba1df19162c` | 200 |
| `/sitemap.xml` | 159 | `5f950bf759f6c66938b55e4032ccbd49edb439afb6c3a96c5c377802c02dc34f` | 200 |
| `/llms.txt` | 3,279 | `ac2cd66a07d2c2351fb2a4f42cd59b9bdad6459a598676689b14a248d68c8445` | 200 |

### Result

- `main` advanced by fast-forward; no history rewrite was used.
- The four files are present in the public repository with the same byte sizes as the live assets.
- Live public hashes match the source asset metadata.
- `https://www.truncaiotix.com/` resolves to the canonical `https://truncaiotix.com/` content.
- A non-existent path returns HTTP 404.
- The active Cloudflare deployment and version remained unchanged after verification; provider-internal identifiers are retained only in controlled evidence.
- Claim boundary remains V2.1: local, synthetic, non-operational, C2 maximum; 113/113 accumulated internal tests; E08 and E10 INCONCLUSIVE.
- **Evidence limitation:** the snapshot commit created through the connected GitHub API is reported by GitHub as unsigned. Commit IDs, blob IDs, source SHA-256 values and public re-fetch verification provide the recorded integrity evidence; no cryptographic commit-signature claim is made.
