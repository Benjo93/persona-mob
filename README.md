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

*No persona captured yet.*

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

- **Total actions**: 0
- **Tree size**: 0
- **Root hash**: `...`
- **Last published**: `2026-02-19T19:22:02.391169+00:00`

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
