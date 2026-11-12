# Host type governs influenza evolutionary strategy across reservoir and spillover hosts

#### Maria A. Maltepes*<sup>1</sup>, Alexey Markin<sup>2</sup>, Stephen Shank<sup>3</sup>, Jordan T. Ort<sup>4</sup>, Jared Sabre<sup>5</sup>, Lambodhar Damodaran<sup>3,5</sup>, Grant Park<sup>1</sup>, Kathryn Kistler<sup>6,7</sup>, Tavis K. Anderson<sup>2</sup>, Louise H. Moncla<sup>3</sup>

<sup>1</sup>Department of Biology, UPenn, Philadelphia. <sup>2</sup>National
Animal Disease Center, Agricultural Research Service, United States Department
of Agriculture. <sup>3</sup>Department of Pathobiology, UPenn, Philadelphia.
<sup>4</sup>Department of Microbiology, Perelman School of Medicine, UPenn,
Philadelphia. <sup>5</sup>Office of Information Technology, UPenn, Philadelphia.
Department of Biology, Emory University, Atlanta. <sup>6</sup>Fred Hutchinson
Cancer Research Center, Seattle. <sup>7</sup>Howard Hughes Medical Institute,
Seattle.

## Abstract

Despite its high propensity for host switching, the evolutionary mechanisms
underlying influenza host adaptation remain unclear. H3Nx influenza viruses are
uniquely generalist, with long-term lineages that circulate in avian, human,
swine, equine, and canine hosts. Using 13,295 H3Nx sequences, we quantified
host-specific adaptive evolution, and developed a pipeline to map reassortment
events onto trees with measures of statistical uncertainty. We find that while
H3Nx viruses in mammals undergo adaptive evolution in HA and NA, viruses in
birds experience very little directional selection. Instead, avian lineages
exhibit high rates of reassortment, frequently generating novel reassortant
lineages that persist transiently and turn over rapidly. 29.8-47.4% of all avian
reassortant lineages are purged within the first year of circulation, and
reassortment shows no fitness benefit in birds. In contrast, reassorted lineages
in swine are more likely to persist long-term, suggesting that reassortment in
swine may be broadly beneficial. Segment-specific reassortment patterns were
also distinct between avian and mammalian viruses, with NA reassorting more
frequently than expected in birds, but less frequently than expected in swine.
Reassortment events are enriched between mammalian, but not avian, host
switches, suggesting that reassortment may be most beneficial for mediating host
switches among mammalian species. Together, our data suggest that host
differences drive fundamentally different evolutionary outcomes for influenza
viruses, transitioning from reassortment-dominant evolution in their avian
reservoir, to varying degrees of adaptation upon establishment in mammals.

## Overview
This is a repository for all files related to the evolutionary characterization
of H3Nx viruses across diverse hosts. Sequence data for phylogenetic analyses
were sourced from NCBI and the GISAID repository. The corresponding
acknowledgements table for all GISAID sequences can be found in this repo.

## Project Structure
**[`global_h3nx_build`](global_h3nx_build/): contains the config and Snakefiles
for the global H3Nx ML trees from this project. The auspice folders contains
results JSONs that can be visualized in Nextstrain. Sequence data has been
removed to comply with GISAID usage regulation. 
**[`mk-test`](mk-test/): contains scripts from https://github.com/blab/adaptive-evolution and results
from the the adaptive mutation analysis performed on different H3Nx host groups.
These results are shown in figure 1.
**[`treesort-analyses`](treesort-analyses/): contains scripts and results from
the reassortment analyses performed on different H3Nx host groups. Reassortment
was quantified using TreeSort.

## External links
**[`Nextstrain build`](https://nextstrain.org/groups/moncla-lab/h3nx/ha)
**[`TreeSort pipeline`](https://github.com/moncla-lab/treesort-pipeline)

