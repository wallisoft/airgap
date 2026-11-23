# AirGap

Dependency-free **air-gapped data transfer**. Move text, a key, or a small file between two devices with **no
network, ever** — an animated QR run (screen → camera) or a USB/file hand-off. No server, no account, no backend.

**Try it:** **[juska.uk](https://juska.uk)** — or download the single file there and run it offline, forever.

## How it works

- **Send** — the data is chunked into a fountain-cycled run of QR codes shown full-screen.
- **Receive** — the other device's camera reads the run, order-independent and drop-tolerant, and reassembles it.
- **USB / file** — or export the payload to a file and carry it across on removable media.

Pure client-side HTML. The QR encoder is hand-rolled and verified against a real decoder; scanning uses the
browser's native `BarcodeDetector` (Chrome / Android). (Working name — see note on trademark clearance before
any store release.)

## Licence

Dual-licensed: free software under **GPL-3.0** (see [LICENSE](LICENSE)); a **commercial licence** is available
for closed / proprietary use (see [LICENSE-COMMERCIAL.md](LICENSE-COMMERCIAL.md)). Contact hello@tiny-web.uk.

From the makers of **[Visualised](https://visualised.io)** — Wallisoft, Eastbourne.
