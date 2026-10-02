# Simulation Engineering Toolkit 02 — Rust and Python: Porting a Simulator Core with PyO3

Moving the core of a SimPy simulator into Rust without changing a single answer: when a rewrite pays and when it does not, PyO3 and maturin, what should cross the boundary, releasing the GIL, everything it took to be bit-exact (operation order, SimPy's event order, fsum, Python's random stream, a JSON-parsing trap), differential and golden tests, and measured speed-ups.

Topics: PyO3, maturin, GIL, Bit-exact, Differential tests, Speed-ups.

**Live site:** https://brendanjameslynskey.github.io/SimEng_02_Rust_Python_PyO3/

Part of the [Simulation Engineering Toolkit series](https://github.com/BrendanJamesLynskey/SimEng_Hub_Toolkit). Companion code: [Rust_DES_Kernel](https://github.com/BrendanJamesLynskey/Rust_DES_Kernel). Interview questions: [Interview_Rust](https://github.com/BrendanJamesLynskey/Interview_Rust). Every concept used here is explained, with links, in the [series glossary](https://brendanjameslynskey.github.io/SimEng_Hub_Toolkit/#glossary).

Slides and text: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
