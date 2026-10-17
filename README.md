# Stream Clustering (Implementation of different algorithms and  their evaluations)

Practical course on stream clustering at the Database Systems and Data Mining chair (DBS), LMU Munich.
Over five blocks, teams implemented stream clustering algorithms on a shared evaluation framework and
compared them. This repository holds the final report; each algorithm lives in its own repository.

## Components

| Block | Algorithm | Repository 
|---|---|---
| 0 | D-Stream (grid-based density clustering) | [dstream-hajuj](https://github.com/justfeelix/dstream-hajuj) 
| 1 | DenStream (density-based micro-clusters) | [denstream](https://github.com/justfeelix/denstream) 
| 2 | CEDGM | [cedgm](https://github.com/justfeelix/cedgm) 
| 3 | DenSOINN | [densoinn](https://github.com/justfeelix/densoinn) 
| 4 | LiarTree (anytime clustering) | [liartree](https://github.com/justfeelix/liartree) 

## Report

- `main.pdf`: compiled report
- `report/`: LaTeX sources, one chapter per block (submodule:
  [stream-clustering-report](https://github.com/justfeelix/stream-clustering-report))

Clone with sources: `git clone --recurse-submodules https://github.com/justfeelix/stream-clustering.git`

Build: `cd report && latexmk -pdf main.tex`

## Notes

- Team projects: commit histories include my teammates' work.
- The shared evaluation framework (`baseframework`) was written by the course supervisor and is included in the component repositories with permission.
- Datasets are not included; see the README of each repository.
