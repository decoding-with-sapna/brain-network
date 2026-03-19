# brain-network

This project models the human brain as a complex network using graph theory and simulates disease progression through network perturbation.
It is inspired by the concept of a **Digital Twin of the Brain**, where computational models are used to study neurological behavior and disease impact.

##  Features
* Brain network construction from connectome data
* Centrality analysis (degree, betweenness)
* Global efficiency calculation
* Node removal (damage simulation)
* Disease spread modeling
* Visualization of network behavior

## Methodology
1. **Data Loading**
   * Connectome dataset is used to define brain region connections
2. **Graph Construction**
   * Nodes → Brain regions
   * Edges → Connectivity
3. **Network Analysis**
   * Identify important regions using centrality
4. **Perturbation Simulation**
   * Remove nodes to simulate brain damage
5. **Disease Spread**
   * Model how disease propagates across the brain network

## Key Insights
* Certain brain regions act as hubs and are critical for network stability
* Targeted damage causes significantly higher efficiency loss than random damage
* Disease spreads rapidly through highly connected regions

## Future Work
* Integration with real brain atlases (AAL, Nilearn)
* Weighted connectivity modeling
* Machine learning for disease prediction
* Personalized brain network simulation

##  Tech Stack
* Python
* NetworkX
* Pandas
* Matplotlib / Plotly
##  3D Disease Propagation Simulation
[Click here to view interactive simulation](images/brain_simulation.html)
