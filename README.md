# Influence of system type and management practices on bacterial and fungal community structure in hydroponic systems: insights from commercial facilities in Ohio
Fiama Guevara, Timothy Frey, Antonino Malacrinò, and Maria Soledad Benitez Ponce

## Abstract
Hydroponics is a method of growing plants using a mineral nutrient-enriched solution in a controlled environment. Unlike soil-based systems, where soil acts as the primary source of microbial inoculum, hydroponic systems rely on the nutrient solution composition and controlled environment conditions to influence microbial growth, survival, and dynamics. Few studies have  evaluated the occurrence of bacteria in the root zone and nutrient solution of hydroponically grown crops, however fungal communities have not been deeply described. This research aimed to characterize the diversity and structure of bacterial and fungal communities in commercial hydroponic systems, as well as to determine how system design and management practices drive microbial variation. Leaves, roots, growth media and nutrient solution samples were collected from commercial facilities in Ohio with different system designs (NFT, DWC, Ebb & flow, and Vertical Drip), and analyzed using amplicon metagenomics of ribosomal markers (16S rRNA and ITS1). Analysis of community composition revealed that bacterial and fungal community structure differed across habitats (leaves, roots, growth media, and nutrient solution). Factors such as system type, plant age, nutrient solution parameters (pH, EC, and temperature), and environmental factors (humidity) significantly influenced microbial community variation in hydroponics. This research enhances our understanding of microbial communities associated with hydroponics and provides valuable insights for developing strategies to manage hydroponic systems to improve agricultural crop production.


## Disclaimer
This repository contains the code for downstream analyses inlcuding alpha, beta diversity and identification of the bacterial and fungal core genera. Raw reads were processed using the [nf-core/ampliseq workflow version 2.5.0](https://nf-co.re/ampliseq/2.9.0/docs/usage). Illumina raw reads (16S and ITS) are available at NCBI SRA under the BioProject number *`PRJNA1070607`*.

## Code
## 1. Alpha, beta diversity and distance-based redundancy analysis (db-RDA)
In this section you could find community composition analyses and db-RDA analysis to determine the influence of nutrient solution management parameters and environment factors in bacterial and fungal community structure.

## 2. Core taxa membership
Code to reproduce core genera analysis.

## 3. Output files
In this section you could find the ASV count tables, phyloseq objects and metadata files for 16S and ITS datasets. 
