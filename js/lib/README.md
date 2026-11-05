# Bundled runtime libraries

These files load locally with the xite. Keep the matching MIT license files when updating them.

| File | Source | SHA-256 |
| --- | --- | --- |
| `epixframe.min.js` | [https://cdn.jsdelivr.net/gh/EpixZone/epixframe@v1.0.0/dist/epixframe.min.js](https://cdn.jsdelivr.net/gh/EpixZone/epixframe@v1.0.0/dist/epixframe.min.js) | `d619dec8e2559726b41232560ff1bef6b8cba195ba350ff55a90a493187b677a` |
| `ethers.umd.min.js` | [https://cdnjs.cloudflare.com/ajax/libs/ethers/6.13.4/ethers.umd.min.js](https://cdnjs.cloudflare.com/ajax/libs/ethers/6.13.4/ethers.umd.min.js) | `fd66c04651929c6a37806a37e8217e6b6aac07c7e816ad478f52690b7429bc61` |
| `epixkit.js` | [https://github.com/EpixZone/epixkit/blob/5f966dbcbc507641bb6a79b660805525d803f262/epixkit.js](https://github.com/EpixZone/epixkit/blob/5f966dbcbc507641bb6a79b660805525d803f262/epixkit.js) | `cfa2fb3d1c3e269f81116bf1a5977da5b8e35f2c2bf2aa1b62fdb5d79799d657` |

EpixKit is copied from merged commit `5f966dbcbc507641bb6a79b660805525d803f262`. EpixFrame and ethers preserve the bytes served by the existing pinned CDN URLs on 2026-11-05. The cached EpixFrame URL differs from the current GitHub `v1.0.0` tag, so this change keeps the deployed bytes rather than changing its behavior.

After updating source files, use the normal authorized xite signing and publishing process so the signed file manifest includes these assets. Do not edit the existing signature by hand.
