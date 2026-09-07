# D0 Publication and Maintenance Log

This log records authorised public-content maintenance for TruncAI-OTiX. It contains no private data, credentials, operational endpoints, Worker runtime code or security configuration.

## 2026-09-07 — Public website snapshot versioning

- **Authority:** C3-PUB-D0 under Prompt Maestro TruncAI-OTiX V2.2.
- **Purpose:** preserve a versioned public copy of the content already served at https://truncaiotix.com and remove the traceability gap between the live website and the public repository.
- **Scope:** README update plus `site/index.html`, `site/robots.txt`, `site/sitemap.xml` and `site/llms.txt`.
- **Source state read:** Cloudflare Worker `truncaiotix-web`, active deployment `d1d3eb77-12b2-4718-ab88-1c36a86a0cd6`, version `c2555c0b-0720-43ad-b10a-66ebb468597d` (version 3).
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
- The active Cloudflare Worker deployment and version remained unchanged after verification.
- Claim boundary remains V2.1: local, synthetic, non-operational, C2 maximum; 113/113 accumulated internal tests; E08 and E10 INCONCLUSIVE.
- **Evidence limitation:** the snapshot commit created through the connected GitHub API is reported by GitHub as unsigned. Commit IDs, blob IDs, source SHA-256 values and public re-fetch verification provide the recorded integrity evidence; no cryptographic commit-signature claim is made.
