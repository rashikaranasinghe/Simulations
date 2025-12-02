# Hybrid Zone Simulations

**1. Interactive Hybrid-Zone Triangle Plot**

A small R Shiny app that simulates and visualizes hybridization between two parental populations using a triangular (hybrid index vs. interspecific heterozygosity) plot.
Users can change the number of simulated individuals and the average hybrid index to explore how hybrid and parental samples distribute in the triangle. The app also displays 300 reference points (100 P1, 100 P2, 100 F1-like) for comparison.

View the app here: http://rrshinyapp.shinyapps.io/Triangle_plot_app

**2. STRUCTURE Plot Simulator (K = 2)**

This R Shiny app generates a hypothetical STRUCTURE-style barplot for two ancestral populations (K = 2).
It allows users to interactively adjust the number of individuals, the average ancestry (hybrid index), and the amount of variation in ancestry to visualize how admixture proportions can appear under different scenarios.

View the app here:  https://rrshinyapp.shinyapps.io/STRUCTURE_Plot_K2/

**3. STRUCTURE Plot Simulator (K = 3)**

This R Shiny app generates an interactive, simulated STRUCTURE-style barplot for three ancestral populations (K = 3). 
It allows users to explore how ancestry proportions vary across individuals given different average ancestry values and noise levels.

View the app here:  https://rrshinyapp.shinyapps.io/STRUCTURE_Plot_K3/

The Julia script above ("Simulatin of tri-hybridization") simulates hybridization dynamics among three species and tracks how their genomic ancestry proportions change across generations. It generates parental genotypes, models random mating to produce hybrid offspring, and calculates ancestry contributions from each species.
