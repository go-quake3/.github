<p align="center"><img src="https://raw.githubusercontent.com/go-quake3/brand/main/social/go-quake3.png" alt="go-quake3" width="720"></p>

# go-quake3

**Pure-Go Quake III Arena (id Tech 3, 1999) — reserved.**

This organization is **reserved** for the eventual pure-Go port of
[Quake III Arena](https://en.wikipedia.org/wiki/Quake_III_Arena) (id
Tech 3, 1999), sibling of [`go-quake1`](https://github.com/go-quake1)
(id Tech 1) and [`go-quake2`](https://github.com/go-quake2) (id Tech 2).

The work has not started; the org is staked out so the
`go-quake{1,2,3}` family naming holds together. Watch
[`go-quake1`](https://github.com/go-quake1) for the active engine
work — Q3 will pick up the same discipline once the earlier ports
reach the playable bar. Q3's renderer is GPU-shader-driven, which
will lean on the [go-virtio](https://github.com/go-virtio) Venus
(Vulkan-over-virtio) stack instead of the soft renderer Q1 uses.

## Planned reference

[`ioquake3`](https://github.com/ioquake/ioq3) — the maintained
upstream fork of the id Software 1999 release, GPL-2.0. Same hand-
port-from-reference pattern as `go-quake1` ←
[tyrquake](https://disenchant.net/tyrquake/).

## Planned standards

Same as the [go-quake1](https://github.com/go-quake1) family:
pure Go (`CGO_ENABLED=0`), 100% statement coverage, reference-mirror
traceability, the godoom provable-test 4-gate protocol carried forward,
6-arch CI (`amd64` · `arm64` · `riscv64` · `loong64` · `ppc64le` ·
`s390x`), BSD-3 wrapper + GPL-2.0 engine carve-out.
