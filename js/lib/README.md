# Bundled runtime libraries

These files load locally with the xite. Keep the matching MIT license files when updating them.

| File | Source | SHA-256 |
| --- | --- | --- |
| `epixframe.min.js` | [https://github.com/EpixZone/epixframe/releases/tag/v1.1.0](https://github.com/EpixZone/epixframe/releases/tag/v1.1.0) | `db23deb8a6056e7ea6b17581ef6296451c2991d1a1a85f3df518674d6a7c4b00` |
| `ethers.umd.min.js` | [https://cdnjs.cloudflare.com/ajax/libs/ethers/6.13.4/ethers.umd.min.js](https://cdnjs.cloudflare.com/ajax/libs/ethers/6.13.4/ethers.umd.min.js) | `fd66c04651929c6a37806a37e8217e6b6aac07c7e816ad478f52690b7429bc61` |
| `epixkit.js` | [https://github.com/EpixZone/epixkit/blob/abcae466f0345a12893c8ed2667a41c5a0a4a580/epixkit.js](https://github.com/EpixZone/epixkit/blob/abcae466f0345a12893c8ed2667a41c5a0a4a580/epixkit.js) | `0170d61295d5e8d47e7425302b305585a2e614edfb4e4434f74c2b41591f6a6b` |

EpixKit is copied from merged commit `abcae466f0345a12893c8ed2667a41c5a0a4a580`. EpixFrame is `dist/epixframe.min.js` from the `v1.1.0` release. ethers preserves the bytes served by its pinned CDN URL on 2026-11-05.

After updating source files, use the normal authorized xite signing and publishing process so the signed file manifest includes these assets. Do not edit the existing signature by hand.
