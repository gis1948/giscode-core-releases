# GisCode Core — release downloads

GisCode Core is a local-first AI coding agent for Windows. This repository holds
the published binaries, their checksums and the licence files. The source lives
in a private tree; the site is <https://jusoorai.com/products/giscode-core/>.

## Download

Latest: **v0.1.0-alpha.1** — single-file Windows executable, no installer.

<https://jusoorai.com/downloads/> (or the Releases section on the right).

Every release carries `SHA256SUMS.txt`. Verify before you run anything:

```
certutil -hashfile GisCode.exe SHA256
```

## Requirements

- Windows 10 or 11, 64-bit.
- A model to talk to. GisCode runs against a local model (LM Studio, or any
  GGUF served locally) or an OpenAI-compatible API endpoint you configure in
  Settings. No model and no key means the app opens and cannot do work.

## This is an alpha, and it is unsigned

- The binary is **not code-signed**, so Windows SmartScreen will warn you on
  first run. That warning is correct: it tells you Windows cannot verify the
  publisher. The checksum above is how you verify the bytes instead.
- Expect rough edges. It is labelled early alpha on the site for a reason.

## Licence

Apache License 2.0 — see `LICENSE` and `NOTICE`. The licence covers the code,
not the brand: the GisCode name and the Gis logo stay with Jusoor Company LLC,
as `TRADEMARK.md` sets out.

## Problems

Open an issue in this repository. There is no phone line and no ticket desk.
