<h1 align="center">KernelGrove — earlier releases</h1>

> **KernelGrove has moved to [serg4life/KernelGrove](https://github.com/serg4life/KernelGrove).**
> It is now open source (Apache-2.0), and new versions — from 1.0b4 on — are
> published there: [latest release](https://github.com/serg4life/KernelGrove/releases/latest).

This repository is archived. It only keeps the assets of the first betas,
1.0b1–1.0b3, and it stays online because those versions still depend on it:

| Release | Why it is kept |
|---|---|
| `v1.0b1` – `v1.0b3` | The installers of those versions. |
| `db-v1` | The bindings database. Versions 1.0b1–1.0b3 read `releases/latest/download/manifest.json` from this repository on first run, and that manifest points here. |
| `tools-v1` | `dtc` and the preprocessor that the Windows installers of those versions download, with their licences and the `dtc` source. |

Nothing here will be updated. To install KernelGrove, use the
[new repository](https://github.com/serg4life/KernelGrove/releases/latest).

`bindings.db` is built from the Linux kernel's own device tree bindings and
sources, which keep their own licences (GPL-2.0 and dual GPL/MIT/BSD variants).
See [NOTICE.md](NOTICE.md).
