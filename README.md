# Gephi Hip-hop Network Visualization

This repository hosts the interactive network visualization (Gephi → Sigma.js web export) for the hip-hop artists collaboration network.

## Live visualization
Open the interactive page here:  
https://alessbenz.github.io/Gephi-hiphop-viz-network/network/

## What you’re seeing
- **Nodes**: artists  
- **Edges**: collaborations  
- **Node color**: community / cluster (modularity)  
- **Node size**: centrality (more connected artists appear larger)

Use **Search** to find an artist, click nodes to open the information pane, and use zoom controls to navigate.

## Repository contents
- `network/`  
  - `index.html` - visualization page  
  - `config.json` - UI text + legend labels + settings  
  - `data.json` - network data  
  - `css/`, `js/`, `images/` - web assets

## Related project
The analysis and data processing are in the companion R project repo:  
https://github.com/alessbenz/Statistical_Network_Project
