# Urban Representations

**Urban Representations** is a pilot research project on computational analysis of visual and narrative representations of cities.

The project explores whether stable structures of urban representation can be identified without assigning thematic categories in advance. At the pilot stage, the analysis uses photographs of **Saint Petersburg, Vitebsk, and Novi Sad** collected from **Wikimedia Commons** by geographic coordinates.

The visual analysis is based on the **museum-map** module developed by **Anna Chizhik and Katarina Čokrlić**. The module combines CLIP embeddings with color and composition features, applies UMAP and HDBSCAN, and builds a graph of visual similarity between images.

The current repository contains the pilot implementation and interactive visualization. The interface allows users to explore clusters, compare cities and locations, inspect nearest visual neighbors, and display cross-city relations.

Wikimedia Commons is used here as an open and reproducible source for methodological testing, not as a representative sociological sample. A subsequent stage is planned around respondent-generated photographs and short city-related stories, allowing visual analysis to be combined with NLP and multimodal comparison.

## Data

Wikimedia Commons  
https://commons.wikimedia.org/

## Method

museum-map  
https://github.com/Frantsuzova/museum-map

## Pilot

https://frantsuzova.github.io/urban-representations/

## Authors

**Anna Chizhik**  
**Katarina Čokrlić**
