[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.12789172.svg)](https://doi.org/10.5281/zenodo.12789172)



# hamilton-etal_2024_naturecommunications

**Resilient water infrastructure partnerships in institutionally complex systems face challenging supply and financial risk tradeoffs**

Andrew L. Hamilton<sup>1,a,\*</sup>, Patrick M. Reed<sup>1</sup>, Rohini S. Gupta<sup>1</sup>, Harrison B. Zeff<sup>2,3</sup>, and Gregory W. Characklis<sup>2,3</sup>

<sup>1 </sup> School of Civil and Environmental Engineering, Cornell University, Ithaca, NY, USA

<sup>2 </sup> Department of Environmental Sciences and Engineering, Gillings School of Global Public Health, University of North Carolina at Chapel Hill, Chapel Hill, NC, USA

<sup>3 </sup> Center on Financial Risk in Environmental Systems, Gillings School of Global Public Health, UNC Institute for the Environmenta, University of North Carolina at Chapel Hill, Chapel Hill, NC, USA

<sup>a </sup> Current Affiliation: Confluency

\* corresponding author:  andrew.hamilton.water@gmail.com

## Abstract
As regions around the world invest billions in new infrastructure to overcome increasing water scarcity, better guidance is needed to facilitate cooperative planning and investment in institutionally complex and interconnected water supply systems. This work combines detailed water resource system ensemble modeling with multiobjective intelligent search to explore infrastructure investment partnership design in the context of ongoing canal rehabilitation and groundwater banking in California. Here we demonstrate that severe tradeoffs can emerge between conflicting goals related to water supply deliveries, partnership size, and the underlying financial risks associated with cooperative infrastructure investments. We show how hydroclimatic variability and institutional complexity can create significant uncertainty in realized water supply benefits and heterogeneity in partners’ financial risks that threaten infrastructure investment partnership viability. We demonstrate how multiobjective intelligent search can design partnerships with substantially higher water supply benefits and a fraction of the financial risk compared to status quo planning processes. This work has important implications globally for efforts to use cooperative infrastructure investments to enhance the climate resilience and financial stability of water supply systems.

## Journal reference
Hamilton, A.L., Reed, P.M., Gupta, R.S., Zeff, H.B., & Characklis, G.W. (2024). Resilient water infrastructure partnerships in institutionally complex systems face challenging supply and financial risk tradeoffs. Accepted to Nature Communications.

## Code reference
Hamilton, A., Zeff, H., & Gupta, R. (2024). ahamilton144/CALFEWS: Final version for Nature Communications paper on CA infrastructure partnership planning. In Nature Communications (v2.1.1). Zenodo. https://doi.org/10.5281/zenodo.12789172

## Data reference

### Input data
Hamilton, A., Zeff, H., & Gupta, R. (2024). ahamilton144/CALFEWS: Final version for Nature Communications paper on CA infrastructure partnership planning. In Nature Communications (v2.1.1). Zenodo. https://doi.org/10.5281/zenodo.12789172

### Output data
Hamilton, A., Zeff, H., & Gupta, R. (2024). ahamilton144/CALFEWS: Final version for Nature Communications paper on CA infrastructure partnership planning. In Nature Communications (v2.1.1). Zenodo. https://doi.org/10.5281/zenodo.12789172

## Contributing modeling software
| Model | Branch | Version | Repository Link | DOI |
|------------|---------|------|-------------|-----------|
| CALFEWS | MORDM_experiment_paper1 | v2.1 | [https://github.com/ahamilton144/CALFEWS/releases/tag/v2.1](https://github.com/ahamilton144/CALFEWS/releases/tag/v2.1) | [https://doi.org/10.5281/zenodo.12789172](https://doi.org/10.5281/zenodo.12789172) |
| Borg MOEA, Master-Worker | alh_checkpointing_python | | [http://borgmoea.org/](http://www.moeaframework.org/) | |
| MOEA Framework | | 2.12 | [http://moeaframework.org/](http://moeaframework.org/) | |
| Pareto.py | master |  | [https://github.com/matthewjwoodruff/pareto.py](https://github.com/matthewjwoodruff/pareto.py) | |


## Reproduce my experiment  
To reproduce this experiment:

1. Download the CALFEWS software/data release linked above. Unzip the source code directory CALFEWS-2.1.zip, which contains all CALFEWS code and data needed to reproduce this analysis.
2. To repeat the multi-objective optimization, you will need access to the other softwares linked above as well. The Borg MOEA software requires a license, which can be obtained at the link above (free for academics).
3. Python is required to run all analysis from this work. The Python environment is described in the project README (see next step).
4. Follow the **README.md in the head directory of CALFEWS-2.1 source code**. This provides detailed instructions on installing software and running the multi-objective optimization and uncertain reevaluations. This readme can also be viewed on the MORDM_experiment_paper1 branch of the repository: [https://github.com/ahamilton144/CALFEWS/tree/MORDM_experiment_paper1](https://github.com/ahamilton144/CALFEWS/tree/MORDM_experiment_paper1)
6. The optimization experiment requires access to a large-scale supercomputing cluster. I used Bridges-2 at the Pittsburgh Supercomputing Center, using an allocation through the NSF ACCESS program. Due to the stochastic nature of multi-objective evolutionary algorithms, your results will differ somewhat unless you use the same cluster, software environments, and random seeds as described in the README. However, results should be more or less consistent across experiments as long as sufficient convergence is achieved.

## Reproduce my figures
To reproduce the figures used in this publication:

1. The source code directory CALFEWS-2.1 contains all code needed to reproduce the analysis and figures from the paper. Only the CALFEWS software and Python are needed for these steps.
2. The CALFEWS software/data release linked above also includes a zipped file (results.zip) with all results data from the optimization and reevaluation steps that are needed for further analysis and figure creation. Unzip these results if you want to reproduce the analysis from the paper.
3. Alternatively, if you reproduce the full experiment yourself (see section above), the analysis and figures can be run on this new data for comparison.
4. Follow the README.md in the head directory of CALFEWS-2.1 source code. This provides detailed instructions for running the scripts needed to process the data and reproduce the figures.





