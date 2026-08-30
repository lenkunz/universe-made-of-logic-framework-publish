# Sources to Load into NotebookLM

## Required framework sources

- [ ] `source/basics-2-coarse-is-not.md`
  - Why NotebookLM needs it: canonical current meaning of coarse constraint, retained history, and the exact distinction between stored constraint and rendered detail.

- [ ] `source/basics-1-resolution-costs.md`
  - Why NotebookLM needs it: foundational rule for when finer distinctions become consequential and need resolving cost.

## Bit-specific framework sources

- [ ] `source/where-the-framework-stands.md`
  - Why NotebookLM needs it: current status boundaries and vocabulary discipline.

- [ ] `source/the-index-of-the-framework.md`
  - Why NotebookLM needs it: cross-check terminology and avoid importing an older or narrower meaning.

## External sources

- [ ] Seagate — HAMR: https://www.seagate.com/innovation/hamr/
  - Why NotebookLM needs it: magnetic-state stability versus writability at high density.
  - Established observation / explanation this source supports: hard-drive storage depends on stable distinguishable magnetic states; HAMR temporarily heats high-stability media to write it.

- [ ] Seagate — magnetic storage organization: https://www.seagate.com/blog/how-magnetic-storage-devices-are-organized/
  - Why NotebookLM needs it: accessible physical-storage background.
  - Established observation / explanation this source supports: magnetic platters store data through small magnetized regions.

- [ ] Micron — Introduction to Memory: https://www.micron.com/content/dam/micron/educatorhub/intro-to-memory/micron-intro-to-memory-presentation.pdf
  - Why NotebookLM needs it: clear threshold-state illustration for SLC/MLC/TLC/QLC.
  - Established observation / explanation this source supports: NAND maps multiple physical threshold states to increasing bits per cell.

- [ ] Micron — NAND flash: https://www.micron.com/products/storage/nand-flash
  - Why NotebookLM needs it: vendor overview of NAND families and bits-per-cell tradeoffs.
  - Established observation / explanation this source supports: SLC/MLC/TLC/QLC use progressively more states per cell.

- [ ] Claude Shannon — “Probability of Error for Optimal Codes in a Gaussian Channel”: https://onlinelibrary.wiley.com/doi/abs/10.1002/j.1538-7305.1959.tb03905.x
  - Why NotebookLM needs it: mathematical background for reliable coding in noisy channels.
  - Established observation / explanation this source supports: coding/decoding can make logical communication reliable despite noisy physical transmission.

- [ ] ISO JPEG 2000: https://www.iso.org/standard/78321.html
  - Why NotebookLM needs it: clean distinction between exact and approximate image coding.
  - Established observation / explanation this source supports: image coding systems can support both lossless and lossy modes.

- [ ] ITU-T T.800 summary: https://www.itu.int/dms_pubrec/itu-t/rec/t/T-REC-T.800-202407-I!!SUM-HTM-E.htm
  - Why NotebookLM needs it: standards-level corroboration of the lossless/lossy distinction.
  - Established observation / explanation this source supports: JPEG 2000 supports lossless and lossy coding.

## Episode-specific source

- [ ] `02-notebooklm-source.md`
  - This is the detailed narrative/research dossier for the episode and should normally be loaded into NotebookLM with the sources above.

## Source discipline

Keep external observations / established explanation separate from framework interpretation.

Do not use the source list itself as an excuse to promote a structural analogy into established physics.
