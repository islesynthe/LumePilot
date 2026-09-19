# LumePilot Distribution Changelog

## 2026-09-19 — R52 Resource Publication

- Product Version: `0.10.0`
- Global Build: `124`
- Release Channel: `PREVIEW`
- Publication Environment: `INTERNAL_PREVIEW`
- Production Distribution: `NOT_ENABLED`
- Resource Build: `52`
- Resource source SHA: `9e125bbf63b897d19e5331b9c7966bf69a1cdf19`
- `minimumShellBuild`: `124`
- Supported Resource Revision: `supported-rb52`
- Legacy Resource Revision: `legacy-rb52`
- Signer key ID: `lumepilot-resource-test-2026-01`
- Publication base: `https://update.isynthe.com/test/`
- Cumulative renderer Resource includes the bounded Sync V2 legacy dependency
  admission liveness fix and the Cloud Avatar / Flow Light micro polish already
  present on `main`.

| Target | Resource | Manifest SHA-256 | Signature SHA-256 | Principal renderer SHA-256 |
| --- | --- | --- | --- | --- |
| Supported arm64 / macOS 12+ | `supported-rb52` | `2ae46ada9d7d973ed7144df4483e8e8a87d1bf7f2886fa9a205492552037f994` | `5d3b7d56f26776f5e096a481a2aba7fafafa6988f4152ccbd5cb204c499a9b53` | `dda2862c61e19400b0a67f769c080ea6a0afb398b6d55cc02446a7de1e6b490a` |
| Legacy x64 / macOS 11+ | `legacy-rb52` | `04c4afa41665ab1f6227bbf95154339304ac0f9dbc39658760ba952d778e8266` | `8bba2fe1de94a6eacbdb596183030b8471b065f0021c0d7128b3b92042f89b29` | `dda2862c61e19400b0a67f769c080ea6a0afb398b6d55cc02446a7de1e6b490a` |

This is an Internal Preview Resource publication. Production signing,
production distribution, and production-ready status are not claimed; H-1
remains `OPEN / MAJOR`.

## 2026-09-19 — TEST Resource Revision 51

- Product Version: `0.10.0`
- Global Build: `124`
- Release Channel: `PREVIEW`
- Source `main` SHA: `d92c7ec3d447530f66853813eec3a79cf81a7bbc`
- `minimumShellBuild`: `124`
- TEST signer: `lumepilot-resource-test-2026-01`
- Cumulative renderer Resource including the R50 protected-quote convergence
  fix, post-R50 Cloud Sync UI refinements, License & Entitlement Foundation
  Phase 1, and Stage 2 dependency diagnostics with blocker list/count parity.
- The publication tooling correction aligns dry-run minimum-shell validation
  with the existing Resource publisher contract; it is not a renderer payload
  feature.

| Target | Resource | Manifest SHA-256 | Signature SHA-256 | Principal renderer SHA-256 |
| --- | --- | --- | --- | --- |
| Supported arm64 / macOS 12+ | `supported-rb51` | `50e15a01dcf621851e182b04eb0b2c10244fec1a2500489fd57e11024ad897cf` | `48fe74f96dd5360899622a5210bf0d40512cedd699526fdef389c8c74cffea29` | `a062cee6e84de32af9c114e214991e21645d796bb9a272f393a4f84ed05df5cc` |
| Legacy x64 / macOS 11+ | `legacy-rb51` | `26b92c87cd95c9752004be8d618a0c7b28c2b643b6f11f075769230817a7cdfb` | `a5c85b12b11c2c11bae881947d5d5191a0a52016cff71f84978ec2f898991584` | `a062cee6e84de32af9c114e214991e21645d796bb9a272f393a4f84ed05df5cc` |

This is a TEST Resource publication. Production signing, notarization, and
production-ready status are not claimed.

## 2026-09-18 — TEST Resource Revision 50

- Product Version: `0.10.0`
- Global Build: `124`
- Release Channel: `PREVIEW`
- Source `main` SHA: `618abba4`
- `minimumShellBuild`: `124`
- TEST signer: `lumepilot-resource-test-2026-01`
- Structured Sync V2 protected quote convergence correction included.

| Target | Resource | Manifest SHA-256 | Signature SHA-256 | Principal renderer SHA-256 |
| --- | --- | --- | --- | --- |
| Supported arm64 / macOS 12+ | `supported-rb50` | `8a7c3249bc4611a008aa4e8cbf02265a38b92021471fb7516eeb8d2898cfb8a9` | `d0c83de3f3130a8e75e88a00a3e73937dc094cdd1383b0209192554ff9047bf4` | `a07f1f54b57bb91b9bee016c73ad285fafc9a5abf3b1dfb19a3ae4bbb16283d4` |
| Legacy x64 / macOS 11+ | `legacy-rb50` | `039bc3c9d9d8ba3b8e12fede3db7f04ff6b3ea2e70314766684f71837f14bfd2` | `7f1b41fc3e2aaae32108df047b31a5d63ed900ac009ec8ac4a00943ef3ecbd76` | `a07f1f54b57bb91b9bee016c73ad285fafc9a5abf3b1dfb19a3ae4bbb16283d4` |

This is a TEST Resource publication. Production signing, notarization, and
production-ready status are not claimed.

## 2026-09-17 — TEST Resource Revision 49

- Product Version: `0.10.0`
- Global Build: `124`
- Release Channel: `PREVIEW`
- Source `main` SHA: `d3a4141e`
- `minimumShellBuild`: `124`
- TEST signer: `lumepilot-resource-test-2026-01`

| Target | Resource | Manifest SHA-256 | Signature SHA-256 | Principal renderer SHA-256 |
| --- | --- | --- | --- | --- |
| Supported arm64 / macOS 12+ | `supported-rb49` | `8cb358f04b66d33dafcc21b115f510df46145c480c170aac4ac22844cf116e73` | `ab8f10ff2d3b3d099d584c7cbfe5325d8ff15c5f7cf53e1da249787463ba0eca` | `f09901ec7dcf1a1954cc5db0574d8110f8d6ce3de0562483e60f9d3e632459d1` |
| Legacy x64 / macOS 11+ | `legacy-rb49` | `89e34e0d4fd0d78ea7b4e778fcaefe7fc46d74a06ee8a386c8dc71146bd5d809` | `83aee4d79458fd89ef4711d41cfcabfa5fdee29b63558d15164cfe5b8b04eda1` | `f09901ec7dcf1a1954cc5db0574d8110f8d6ce3de0562483e60f9d3e632459d1` |

This is a TEST Resource publication. Production signing, notarization, and
production-ready status are not claimed.

## 2026-09-17 — TEST Resource Revision 48

- Product Version: `0.10.0`
- Global Build: `124`
- Release Channel: `PREVIEW`
- Source `main` SHA: `ebc4caae`
- `minimumShellBuild`: `124`
- TEST signer: `lumepilot-resource-test-2026-01`

| Target | Resource | Manifest SHA-256 | Signature SHA-256 | Principal renderer SHA-256 |
| --- | --- | --- | --- | --- |
| Supported arm64 / macOS 12+ | `supported-rb48` | `51d7f9e5219ec173fc9e78588a16d69db5c0b53a21b8ea51ac1fe8405b630544` | `2c18ce37c155fef7832f5529150b76718ad8d7cb198dd6ce2927821b00458017` | `8506e19704fb3c22f464faa819cb5d4f19434c66d8a78db7e9b7682b948ec150` |
| Legacy x64 / macOS 11+ | `legacy-rb48` | `63011f8e5f4f3f645b1f67a510cc8cbb6339a9b2e95e384fde460d95c5815db1` | `3b37f7d649ac673c2175bcdde6bf7f4d3909594217bde4fdd9e930a842ecf1b7` | `8506e19704fb3c22f464faa819cb5d4f19434c66d8a78db7e9b7682b948ec150` |

This is a TEST Resource publication. Production signing, notarization, and
production-ready status are not claimed.

## 2026-09-17 — TEST Resource Revision 47

- Product Version: `0.10.0`
- Global Build: `124`
- Release Channel: `PREVIEW`
- Source `main` SHA: `4aff7eb630c16e345aba9f7c6cbdcd5d39912498`
- `minimumShellBuild`: `124`
- TEST signer: `lumepilot-resource-test-2026-01`

| Target | Resource | Manifest SHA-256 | Principal renderer SHA-256 |
| --- | --- | --- | --- |
| Supported arm64 / macOS 12+ | `supported-rb47` | `a76193b35d58086526ad4a3957035519544033b1d49f55323645345da6b9229b` | `fdef8bbdeef58950babf3bfd9bc139ce24a80b6ac017e71c5586062e589198b8` |
| Legacy x64 / macOS 11+ | `legacy-rb47` | `504e79c91a86128013fed758a8af4d4655ce7a2ae957334f1fc8d062e8959c81` | `fdef8bbdeef58950babf3bfd9bc139ce24a80b6ac017e71c5586062e589198b8` |

This is a TEST Resource publication. Production signing, notarization, and
production-ready status are not claimed.

## 2026-09-17 — TEST Resource Revision 46

- Product Version: `0.10.0`
- Global Build: `124`
- Release Channel: `PREVIEW`
- Source `main` SHA: `b4478c3218678fa211490a027e3176a9f1c42834`
- `minimumShellBuild`: `124`
- TEST signer: `lumepilot-resource-test-2026-01`

| Target | Resource | Manifest SHA-256 | Principal renderer SHA-256 |
| --- | --- | --- | --- |
| Supported arm64 / macOS 12+ | `supported-rb46` | `c12c5d1d9d12ed81fa2bbeba3b14d086aee5139439d0826cf10ee5e6873f6787` | `cb1486874c79b315c04bf173948cc16b640c6327533a5b0cd944917327436cce` |
| Legacy x64 / macOS 11+ | `legacy-rb46` | `0c985e7c2ba6e77e1f3d0f4c767377b44d128cb269018d3331749d6bc4813fa7` | `cb1486874c79b315c04bf173948cc16b640c6327533a5b0cd944917327436cce` |

This is a TEST Resource publication. Production signing, notarization, and
production-ready status are not claimed.
