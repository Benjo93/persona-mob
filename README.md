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
| Persona Hash | `sha256:d3f08899bc4a83cd70293cd1c...` |
| Sources | (none) |
| Revisions | 0 |

```
PERSONA PROFILE: mob  (5 actions)

  breadth       ██████░░ 80%
  caution       ████████ 100%
  consistency   ███░░░░░ 40%
  initiative    ░░░░░░░░ 0%
  persistence   ░░░░░░░░ 0%
  social        ██░░░░░░ 20%
  transparency  ██░░░░░░ 20%
  velocity      █░░░░░░░ 16%

sha256:d3f08899bc4a83cd70293cd1ca193c629cef1bed5d766f60a78e8a071a3fbd80
```

Behavioral profile for mob:
  Strongest traits: caution (100.0%), breadth (80.0%), consistency (40.0%)
  Weakest traits: initiative (0.0%), persistence (0.0%)
  Primary tools: persona__whoami, persona__card, persona__publish

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

- **Total actions**: 14
- **Tree size**: 14
- **Root hash**: `6d49e18dc05823e4546a8b79912e3c4d...`
- **Last published**: `2026-02-19T19:43:31.551798+00:00`

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
