# NOSTRAS

A Nostr client, paired with a self-hosted relay, built for people who want
their identity and their data under their own control — not a platform's.

## What is NOSTRAS?

NOSTRAS is a [Nostr](https://nostr.com) client distributed as an installable
Progressive Web App (PWA) — no app store required — paired with a
purpose-built relay/node that adds real functionality (search, translation,
AI-assisted features) on top of the open protocol, not instead of it.

- **Non-custodial, always.** NOSTRAS never holds your keys or your funds.
  Bring your own signer (NIP-46, NIP-07) and your own Lightning wallet
  (NIP-47 / NWC).
- **Protocol-native services.** Search, translation, and other "extra"
  features are implemented as standard Nostr Improvement Proposals (NIPs) —
  not proprietary APIs — so they stay interoperable with the rest of the
  Nostr network.
- **Relay choice stays yours.** NOSTRAS defaults to its own relay, but you
  can point it at any relay you trust.

## Status

NOSTRAS is in active development and not yet publicly released. This
repository will be updated as that changes.

## Why isn't the source code here?

This repository is for documentation and support — it does not contain
NOSTRAS's implementation.

The audit surface for a Nostr client isn't its source, it's its conformance
to the open protocol itself: every feature NOSTRAS offers is built on
standard, publicly-specified NIPs, verifiable by observing what it actually
sends over the wire. Non-custodial key and wallet handling means NOSTRAS is
never in a position to touch your identity or your funds, regardless of
what its code looks like.

## Support

Questions, bugs, and feature requests: please [open an issue](../../issues).

## License

All rights reserved. This repository contains documentation only — no
license is granted to any NOSTRAS source code, which is not included here.
