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

## Try it

- App: [app.nostras.app](https://app.nostras.app) (install it as a PWA
  from your browser)
- Relay: `wss://nostras.app`
- Landing page: [nostras.app](https://nostras.app)

## Source code

NOSTRAS is open source. The client, the relay and the DVM live in
[nostras-app/nostras-app](https://github.com/nostras-app/nostras-app), under the AGPL-3.0, with a commercial
license available for closed or rebranded builds.

You can read the code, but you don't have to trust it. Every feature
NOSTRAS offers is built on standard, publicly specified NIPs, so you can
check what it actually sends over the wire with any tool that speaks
Nostr. And because it never holds your keys or funds, the code is never
in a position to touch your identity or your money.

AI features (summarize, translate, ask, spam check) are encrypted between
you and the NOSTRAS DVM, and each model it offers says who can see your
text. To run them on your own hardware, see
[docs/local-ai.md](https://github.com/nostras-app/nostras-app/blob/master/docs/local-ai.md).

## Support

Questions, bugs and feature requests from users: please
[open an issue](../../issues) here. Code contributions and code-level
issues go to the [source repository](https://github.com/nostras-app/nostras-app); see its CONTRIBUTING.md.

## License

The NOSTRAS source code is licensed under the AGPL-3.0, with a commercial
license available. See [LICENSING.md](https://github.com/nostras-app/nostras-app/blob/master/LICENSING.md) in
the source repository.
