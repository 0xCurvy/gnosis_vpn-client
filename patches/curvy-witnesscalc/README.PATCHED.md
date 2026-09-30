# curvy-witnesscalc 0.1.0-rc.7 — Gnosis ceremony pins (LOCAL TEST ONLY)

Unmodified published `curvy-witnesscalc` 0.1.0-rc.7 except for the five `zkey_file` /
`zkey_sha256` pins in `src/lib.rs`, which point at the Gnosis trusted-setup ceremony keys
(same values as rs-sdk 0.1.0-rc.9). The version stays rc.7 so it satisfies
hopr-strategy 5.1.0's `=0.1.0-rc.7` requirement via `[patch.crates-io]`.

For testing gnosis_vpn-client against the Gnosis PIX staging aggregator before rs-sdk rc.9
and hopr-strategy are published. Do not publish or commit this crate; drop the patch once
the real releases are in.
