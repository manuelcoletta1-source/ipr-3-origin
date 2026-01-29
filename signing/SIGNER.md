# Signer — ED25519 (Events)

This repository publishes the **public ED25519 key** used to sign new events.

## What it signs
- `events/*` (append-only)
- evidence packs / receipts derived from this repository

## What it does NOT do
- It does **not** change IPR-3 anchors
- It does **not** rewrite canonical time
- It does **not** grant rights automatically

## Public key
See `signing/ed25519.pub.txt`
