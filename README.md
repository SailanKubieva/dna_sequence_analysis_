# DNA Sequence Analysis with Biopython

A compact notebook covering the basics of working with sequence data in Python:

- reading and writing FASTA files with `Bio.SeqIO`
- GC content (overall and sliding window)
- six-frame ORF finder with translation
- codon usage plot

The sequence is synthetic (seeded random genome with planted genes), so the notebook runs
offline and gives reproducible results. A final section shows how to use a real NCBI sequence
via `Bio.Entrez`.

## Run it

```bash
pip install biopython matplotlib jupyter
jupyter notebook dna_sequence_analysis.ipynb
```

## Skills shown

Python, Biopython, FASTA handling, basic sequence statistics, plotting with matplotlib.
