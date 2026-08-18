# Verification

Measured results for Property & Buildings.

Every figure came from running the software while the data room was prepared. None of it is copied
out of a document, and each figure is reproducible by a buyer from the delivered files.

---

## Results

| Measure | Value |
|---|---|
| Platforms | 3, all with working installers |
| Tools | 3, all dependency-free |
| Source | about 7.5 MB across 380 files |
| Unit tests passing | 320 |
| End-to-end tests passing | 7, driving the real built applications |
| Tests failing | 0 |
| Copyleft dependencies | 0, across 1,000 packages |

## Worth knowing

One verification path was not exercised: the local model service was not running during verification, so that path is untested. The data room states this rather than omitting it.

## How this was produced

The software was run from the delivered files. Where a product ships with an installer, the
installer was built. Where a product declares a type check or a build step, both were run. Test
counts are the totals reported by the products' own test commands.

## What is not claimed

A verification record that lists only passes is not a verification record. The package's
open-items document lists every known gap, and it is part of the data room rather than something
a buyer has to discover. Where a test command did not run, where a path went unexercised, or
where behaviour at scale is unproven, the data room says so plainly.

That document is available under a signed non-disclosure agreement, together with the full
verification record and the provenance file. See [ACQUISITION.md](ACQUISITION.md).
