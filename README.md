## A computational model of the human brain network simulating disease propagation using graph theory and connectome data.

# brain-network
This project models the human brain as a complex network using graph theory and simulates disease progression through network perturbation.
It is inspired by the concept of a **Digital Twin of the Brain**, where computational models are used to study neurological behavior and disease impact.

## Why This Matters
Understanding how diseases propagate through brain networks can help in:
- Early diagnosis of neurological disorders  
- Identifying critical brain regions for intervention  
- Advancing personalized medicine through digital brain twins  
##  Project Preview

## Brain Network Structure
A graph-based representation where nodes correspond to brain regions and edges represent their connectivity.
![Graph](images/graph(1).png)

## Network-Based Disease Propagation Simulation
This plot shows how a disease spreads across the brain network over time from different starting regions.
![Simulation](images/simulation.png)

## Network Damage Analysis
This visualization demonstrates how the removal of key brain regions affects overall network efficiency.
![Damage](images/damage.png)

## Interactive 3D Simulation ##
An interactive 3D visualization of disease propagation in the brain network.
![View Interactive Simulation](images/brain_simulation.html)  

##  Anatomical Brain Mapping
This visualization maps the brain network onto real anatomical space using connectome data.
Nodes represent anatomical brain regions and edges represent structural connectivity strength.
![Simulation](images/connectome.png)



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


