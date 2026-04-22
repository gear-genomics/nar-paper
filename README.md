# GEAR Genomics: a user-friendly, open-source web platform enabling interactive genomic analysis for molecular biologists

This repository provides a GEAR web application snapshot for all the tools included in the publication.

## GEAR web applications

The GEAR web applications are hosted at https://www.gear-genomics.com/\<app\>/

| App URL | Purpose | Input(s) | Output(s) | Backend service |
|---|---|---|---|---|
| [/alfred/](https://www.gear-genomics.com/alfred/) | Sequencing QC | JSON | Visualization of QC results | Alfred CLI |
| [/bgen/](https://www.gear-genomics.com/bgen/) | Sequencing barcode generator | Number of barcodes and length | Set of barcodes | Client-only |
| [/bistro/](https://www.gear-genomics.com/bistro/) | Barcode diversity | Barcode sequences | Visualization of barcode distribution | Client-only |
| [/halo/](https://www.gear-genomics.com/halo/) | Genomic haplotype viewer | JSON | Visualization of Strand-Seq data | Halo CLI |
| [/indigo/](https://www.gear-genomics.com/indigo/) | Chromatogram variant calling | Trace file | Single-nucleotide variants and InDels | Tracy |
| [/maze/](https://www.gear-genomics.com/maze/) | Sequence alignment | Two DNA sequences | Dotplot visualization | Client-only |
| [/padlock/](https://www.gear-genomics.com/padlock/) | Padlock probe design for ISS | Probe design parameters | Designed probes, UCSC links | Dicey |
| [/pearl/](https://www.gear-genomics.com/pearl/) | Sanger chromatogram assembly | Trace files, reference genome | Trace assembly | Tracy |
| [/primer3plus/](https://www.gear-genomics.com/primer3plus/) | Design primers for a DNA sequence | Primer design parameters | Picked primers | Primer3 |
| [/rdml-tools/](https://www.gear-genomics.com/rdml-tools/) | Tools to analyze qPCR data | RDML file(s) | RDML analysis results | RDML-Python |
| [/sabre/](https://www.gear-genomics.com/sabre/) | Sequence alignment browser | MSA in FASTA format | MSA browser | Client-only |
| [/sage/](https://www.gear-genomics.com/sage/) | Sanger chromatogram alignment | Trace file, reference genome | Interactive alignment viewer | Tracy |
| [/salt/](https://www.gear-genomics.com/salt/) | Sequence alignment computation | Two DNA sequences | Sequence alignment | Client-only |
| [/silica/](https://www.gear-genomics.com/silica/) | In-silico PCR | Primer sequences, genome | Amplicon and primer hits | Dicey |
| [/teal/](https://www.gear-genomics.com/teal/) | Trace file viewer | Trace file | Interactive viewer | Tracy |
| [/wally/](https://www.gear-genomics.com/wally/) | NGS alignment plotter | BAM/CRAM file | Alignment plot | Wally |
| [/wily-dna-editor/](https://www.gear-genomics.com/wily-dna-editor/) | DNA manipulation | DNA sequence | DNA editor | Client-only |

**Abbreviations:** QC: Quality control, CLI: Command-line interface, InDels: Insertions and Deletions, MSA: Multiple sequence alignment, ISS: In situ sequencing

