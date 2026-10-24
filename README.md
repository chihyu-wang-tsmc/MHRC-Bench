# MHRC-Bench

**Source:** HuggingFace dataset [`Zanehpn/MHRC-Bench`](https://huggingface.co/datasets/Zanehpn/MHRC-Bench)
**Downloaded:** 2026-10-23 — **test files only**

Hardware code completion: fill in 1-5 masked lines given left/right context.

`<lang>/test_content_classfied.jsonl` holds the problems (`left_context`, `right_context`, `groundtruth`, `category`):

| Language | Problems |
|---|---|
| chisel | 323 |
| systemverilog | 508 |
| vhdl | 496 |
| hls (C/C++) | 456 |
| **total** | **1783** |

`<lang>/test.jsonl` holds the mask positions. vhdl has 513 there, 17 more than its content file — that is how it is published upstream. `crossfile_context` is empty everywhere.

**Not downloaded:** `train` / `valid` (~3.1GB) and `original_repo` / `collected_repos.tar.gz` (35GB).

---

Snapshot kept for benchmark work; see [chihyu-wang-tsmc/code-benchmarks](https://github.com/chihyu-wang-tsmc/code-benchmarks) for the full benchmark index. Licensing follows the upstream source.
