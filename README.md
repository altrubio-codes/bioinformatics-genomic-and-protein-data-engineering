# Bioinformatics - Genomics & Protein Data Engineering

A 14-day collection of beginner-friendly Python scripts designed to practice coding while exploring how DNA, RNA and protein sequences are managed, analyzed and processed.

This repository serves as a learning journal to consolidate basic Python programming tools (string manipulation, loops, file I/O, error handling) with fundamental biological concepts.

## 🧬 Core Focus Areas
* **DNA & RNA Text Processing (Days 1–7):** Cleaning raw sequence data, simulating transcription, calculating stability ratios, and parsing standard biological database file formats.
* **Proteins, Mutations & Data Engineering (Days 8–14):** Translating codons, calculating evolutionary mutation distances, predicting protein weights, and building robust end-to-end processing pipelines.

---

## 📅 Project Log & Concepts

### Week 1: DNA & RNA Text Processing
* **Day 1: DNA Sequence Cleaner (`dna_sequence_cleaner.py`)**
  * *Bio Concept:* Database text cleaning and raw sequence standardization.
  * *Python Tool:* String methods (`.upper()`, `.replace()`, `.strip()`) to handle whitespace and mixed cases.
* **Day 2: Transcription Simulator (`dna_transcription.py`)**
  * *Bio Concept:* Cellular transcription (converting DNA coding strands to single-stranded mRNA).
  * *Python Tool:* Character replacement tools (`.replace('T', 'U')`) to swap Thymine for Uracil.
* **Day 3: GC Content Calculator (`gc_calculator.py`)**
  * *Bio Concept:* Molecular stability prediction (G-C bonds have 3 hydrogen bonds vs 2 in A-T bonds).
  * *Python Tool:* Arithmetic operators, counting algorithms (`.count()`), and float percentage calculations.
* **Day 4: Reverse Complement Generator (`reverse_complement_generator.py`)**
  * *Bio Concept:* Double-helix antiparallel strand generation.
  * *Python Tool:* Dictionary matrix mapping for base pairing combined with reverse string slicing (`[::-1]`).
* **Day 5: Motif Finder (`motif_finder.py`)**
  * *Bio Concept:* DNA pattern recognition (finding regulatory sites or promoter regions).
  * *Python Tool:* Index-shifted `while` loops and string window matching.
* **Day 6: FASTA File Parser (`FASTA_parser.py`)**
  * *Bio Concept:* Reading standard biological database file formatting.
  * *Python Tool:* File I/O (`open()`, `with` statement) and line-by-line validation logic.
* **Day 7: Restriction Site Mapper (`restriction_site_mapper.py`)**
  * *Bio Concept:* Molecular cloning and locating EcoRI enzyme cutting zones.
  * *Python Tool:* Location indexing and conditional tracking blocks.

### Week 2: Proteins, Mutations & Data Engineering
* **Day 8: RNA Translator (`RNA_to_protein_translator.py`)**
  * *Bio Concept:* Ribosomal translation of genetic codes into amino acids.
  * *Python Tool:* Dictionary lookup maps using 3-character codon keys.
* **Day 9: Point Mutation Detector (`point_mutation_detector.py`)**
  * *Bio Concept:* Evolutionary mutation tracking and single-nucleotide variations.
  * *Python Tool:* Hamming Distance calculation using parallel `zip()` looping and sequence index comparisons.
* **Day 10: Consensus Sequence Creator (`consensus_sequence_creator.py`)**
  * *Bio Concept:* Genetic profile alignment and establishing democratic master gene records.
  * *Python Tool:* Multi-dimensional array structures and localized majority voting logic.
* **Day 11: Amino Acid Weight Calculator (`amino_acid_weight_calculator.py`)**
  * *Bio Concept:* Peptide molecular mass calculations.
  * *Python Tool:* Character iterations across a sequence matched against a specific weight dictionary.
* **Day 12: Random Sequence Generator (`random_sequence_generator.py`)**
  * *Bio Concept:* Constructing mock test genomes for baseline benchmarking.
  * *Python Tool:* Python’s built-in `random` module (`random.choice()`) and list joins.
* **Day 13: Hydrophobicity Plotter (`hydrophobicity_plotter.py`)**
  * *Bio Concept:* Protein folding and mapping environmental positioning (surface vs internal core).
  * *Python Tool:* Classification loops mapping peptide sequences to hydro-indexes.
* **Day 14: Final End-to-End Pipeline (`master_pipeline.py`)**
  * *Bio Concept:* Complete workflow automation from raw database records to finalized protein structures.
  * *Python Tool:* Combined file reading, automated cleaning, sequence transcription, and crash-protected `try-except` execution with automatic stop-codon termination.

---
