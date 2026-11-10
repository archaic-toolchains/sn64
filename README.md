# SN Systems N64 tools 1.0.0.2

`asn64.exe`, `cc1n64.exe` and `cc1pln64.exe` from marijnvdwerf/sn64 release `1,0,0,2`.

Release `2026-11-10` holds the files byte for byte as their upstream served them,
so every sha256 below is the one recompile-toolchains and rebrew pin.

| Asset | Upstream URL | sha256 | Bytes | Pinned by |
|---|---|---|---|---|
| `asn64.exe` | https://github.com/marijnvdwerf/sn64/releases/download/1%2C0%2C0%2C2/asn64.exe | `53e3a9f8b7b9a06c8f5a781f01074441df3469e6bbe2df5438ba4e2d8fcf3819` | 89,600 | `gcc-2.8.1-sn`, `gcc-2.8.1-sn-cxx` |
| `cc1n64.exe` | https://github.com/marijnvdwerf/sn64/releases/download/1%2C0%2C0%2C2/cc1n64.exe | `d90df1028c46d826e37146dbcc3e3385f78c59e05a9ddd952daa94c9ad379d9c` | 1,447,936 | `gcc-2.8.1-sn`, `gcc-2.8.1-sn-cxx`, `gcc-2.8.1-snew-cxx` |
| `cc1pln64.exe` | https://github.com/marijnvdwerf/sn64/releases/download/1%2C0%2C0%2C2/cc1pln64.exe | `85e3e9fa05640af67115279a992a616a1a1fec8cf56b2e58191196fbbc51853a` | 1,842,176 | `gcc-2.8.1-sn-cxx`, `gcc-2.8.1-snew-cxx` |

## Source & provenance

- Retrieved 2026-11-10 from the upstream URLs above; each file's sha256 matched
  its pin before it was kept.
- Licence: proprietary (SN Systems). Kept unchanged for preservation and binary-matching work.
