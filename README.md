# Human INS Gene – In-silico Primer Design

## About the Project

This project presents an in-silico primer design analysis for the human INS (insulin) gene using NCBI Primer-BLAST.

## Aim

To design candidate PCR primer pairs for the human INS gene using an in-silico approach.

## Tool and Database

- Tool: NCBI Primer-BLAST
- Database: NCBI Messenger RNA Reference Sequences
- Organism: Homo sapiens
- Input template: Query_1
- Template range: 1–600

## Methodology

1. The target sequence was selected for the human INS gene.
2. The sequence was used as the PCR template in NCBI Primer-BLAST.
3. Candidate forward and reverse primers were generated.
4. Primer parameters such as length, melting temperature (Tm), GC%, and product length were examined.
5. Primer specificity was checked against the selected NCBI database.

## Results

Five candidate primer pairs were obtained.

| Primer Pair | Forward Tm | Reverse Tm | Forward GC% | Reverse GC% | Product |
|---|---:|---:|---:|---:|---:|
| 1 | 60.60°C | 61.02°C | 63.16% | 60.00% | 284 bp |
| 2 | 61.58°C | 60.88°C | 63.16% | 52.38% | 221 bp |
| 3 | 61.62°C | 61.93°C | 52.38% | 60.00% | 273 bp |
| 4 | 62.68°C | 61.78°C | 57.14% | 57.14% | 243 bp |
| 5 | 62.65°C | 62.32°C | 59.09% | 57.14% | 225 bp |

## Specificity

The Primer-BLAST output reported that the primer pairs were specific to the input template, with no other targets found in the selected database.

## Conclusion

This project demonstrates the use of NCBI Primer-BLAST for in-silico primer design of the human INS gene. Five candidate primer pairs were obtained and their reported primer parameters were documented.

The results are computational predictions and would require experimental validation before laboratory use.

## Project Report

The detailed Primer-BLAST result is available in the repository as `primer-pairs.pdf`.
