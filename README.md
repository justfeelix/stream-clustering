# Stream Clustering (LMU Munich, SoSe 2026)

Practical course on stream clustering at the Database Systems and Data Mining chair (DBS), LMU Munich.
Over five blocks, teams implemented stream clustering algorithms on a shared evaluation framework and
compared them. This repository holds the final report; each algorithm lives in its own repository.

## Components

| Block | Algorithm | Repository | My contribution |
|---|---|---|---|
| 0 | D-Stream (grid-based density clustering) | [dstream-hajuj](https://github.com/justfeelix/dstream-hajuj) | Individual implementation |
| 1 | DenStream (density-based micro-clusters) | [denstream](https://github.com/justfeelix/denstream) | MicroCluster class |
| 2 | CEDGM | [cedgm](https://github.com/justfeelix/cedgm) | Core architecture |
| 3 | DenSOINN | [densoinn](https://github.com/justfeelix/densoinn) | Offline phase and evaluation |
| 4 | LiarTree (anytime clustering) | [liartree](https://github.com/justfeelix/liartree) | Noise handling |

## Report

- `main.pdf`: compiled report
- `main.tex` and `report/`: LaTeX sources (one chapter per block)

Build: `cd report && latexmk -pdf main.tex`

## Notes

- Team projects: commit histories include my teammates' work.
- The shared evaluation framework (`baseframework`) belongs to the course and is not published here.
- Datasets are not included; see the README of each repository.
