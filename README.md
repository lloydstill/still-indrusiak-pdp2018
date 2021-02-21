# Memory-Aware Genetic Algorithms for Task Mapping on Hard Real-Time Networks-on-Chip

### Abstract :page_facing_up:

>The problem of mapping hard real-time tasks onto networks-on-chip has previously been successfully addressed by genetic algorithms. However, none of the existing problem formulations consider memory constraints. State-of-the-art genetic mappers are therefore able to find fully-schedulable mappings which are incompatible with the memory limitations of realistic platforms. In this paper, we extend the problem formulation and devise a memory architecture, in the form of private local memories. We then propose three memory models of increasing complexity and realism, and evaluate the impact these additional constraints pose to the genetic search. We conduct extensive experiments using tasks and communications from a realistic benchmark application, and compare the proposed approach against a state-of-the-art baseline mapper.

### Published in :page_with_curl:

:newspaper: [26th Euromicro International Conference on Parallel, Distributed and Network-based Processing (PDP)](https://doi.org/10.1109/PDP44162.2018)

:calendar: 21–23 March 2018

:round_pushpin: Cambridge, :uk:

### Citing with `BibTeX` :bookmark_tabs:

```
@inproceedings{Still18,
  title={Memory-Aware Genetic Algorithms for Task Mapping on Hard Real-Time Networks-on-Chip},
  author={Still, Lloyd Robert and Indrusiak, Leandro Soares},
  booktitle={2018 26th Euromicro International Conference on Parallel, Distributed and Network-based Processing (PDP)},
  pages={601--608},
  year={2018},
  organization={IEEE}
}
```

### Compiling with `latexmk` :hammer_and_wrench:

:package: To install prerequisites run `brew install --cask mactex-no-gui`

:broom: To clean run `latexmk -C`

:gear: To compile run `latexmk -pdf still-indrusiak-pdp2018.tex`
