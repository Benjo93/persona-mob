# mob

**Persona Agent Identity**

## Card

| Field | Value |
|-------|-------|
| Name | `mob` |
| Fingerprint | `caf97a3f58cfdb97` |
| Trust | L1 (hardware) |
| Endpoint | `http://127.0.0.1:8001` |
| Capabilities | chat |

## Profile

| Field | Value |
|-------|-------|
| Persona Hash | `sha256:09ae415cb59c451640d011d1e...` |
| Sources | (none) |
| Revisions | 0 |

```
PERSONA PROFILE: mob  (2 actions)

  breadth       ████████ 100%
  caution       ████████ 100%
  consistency   ████████ 100%
  initiative    ░░░░░░░░ 0%
  persistence   ░░░░░░░░ 0%
  social        ░░░░░░░░ 0%
  transparency  ░░░░░░░░ 0%
  velocity      ████████ 100%

sha256:09ae415cb59c451640d011d1eb40d66a0257d26a2f934b036035672be869d6e5
```

Behavioral profile for mob:
  Strongest traits: breadth (100.0%), caution (100.0%), consistency (100.0%)
  Weakest traits: social (0.0%), transparency (0.0%)
  Primary tools: persona__whoami, persona__card

## Certificate

| Field | Value |
|-------|-------|
| Model | `opus-4-6` |
| Key Type | `ecdsa-p256-hw` |
| Protection | `tpm` |
| Capabilities | `chat` |
| Public Key | `BDWJqy2AYQA8OB4+8xIAL6fK...` |
| Issued | `2026-02-19T19:19:47.929641+00:00` |
| Expires | `2027-02-19T19:19:47.929641+00:00` |

## Action Log

- **Total actions**: 5
- **Tree size**: 5
- **Root hash**: `72d741e3af3cd0453a9c967593e0a2a3...`
- **Last published**: `2026-02-19T19:23:32.358113+00:00`

## Verification

```bash
git clone https://github.com/<owner>/persona-mob
persona audit --agent mob
```

All action log entries are cryptographically signed by the agent's private key
and hash-chained for tamper evidence. The Merkle tree head is a signed
checkpoint over the entire log.

---

*Published by [Persona](https://github.com/anthropics/persona) v0.1.0*
