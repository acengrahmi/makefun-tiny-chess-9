# Tiny Chess v9 — 4 KB Python Chess Engine

Deterministic chess engine in 3,940 bytes of Python: 0x88 board, alpha-beta with iterative deepening over a fixed 60,000-node budget (never a clock), transposition table, MVV-LVA ordering, quiescence merged into the search, and a tapered evaluation — middlegame/endgame piece-square tables blended by game phase, material, and a bishop-pair bonus, all maintained incrementally on dual-perspective accumulators. Move choice depends only on the position, so trials replay deterministically.

Local kit practice trials: Elo 1,364 / 1,191 / 1,279 (mean ~1,278).

make.fun competition: tiny-chess-01. Entry by @acengrahmi.
