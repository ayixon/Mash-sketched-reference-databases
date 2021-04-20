# Mash-sketched-reference-databases
Mash-sketched reference databases are an up-to-date representation of several NCBI genomic, proteomic and metagenomic data, curated and formatted according to the sketching  MinHash algorithm developed by Ondov et al. 2016. Mash: fast genome and metagenome distance estimation using MinHash. Genome Biol. Jun 20;17(1):132. https://doi.org/10.1186/s13059-016-0997-x. Each dataset is in .msh format and mostly represents information from type material, in order to offer informative contexts with standard in nomenclature when possible.

![TemplateGithub](https://user-images.githubusercontent.com/42699236/115393742-a1237d00-a1a7-11eb-98b1-2d703854a357.jpg)


You can download pre sketched files from:
Sánchez-Reyes, Ayixon (2021): Mash sketched databases for: Mash Sketched Reference Dataset for Genome-Based Taxonomy and Comparative Genomics. figshare. Online resource. https://doi.org/10.6084/m9.figshare.14408801.v2 

Data information:

Bacteria_Archaea_type_assembly_set.msh  # contain 16,304 type genomes from NCBI

Bacteria_Archaea_type_proteome_set.msh  # contain 12,767 type predicted proteomes from NCBI

GTDB_r89_assembly_set.msh               # contain 31,910 genomes from GTDB

Fungi_type_assembly_set.msh             # contain 753 type genomes from NCBI

Fungi_type_proteome_set.msh             # contain 248 type predicted proteomes from NCBI

Virus_ Latest GenBank_assembly_set.msh  # contain 40,708 viral assemblies from NCBI

Soil_Metgenome_assembly_set.msh         # contain 479 soil metagenomes from NCBI

Freshwater_Metagenome_assembly_set.msh  # contain 611 freswater metagenomes from NCBI

Usage

You can use any of the files with mash tool.

Example

$ mash dist query_genome  Bacteria_Archaea_type_assembly_set.msh > output

If you find this information useful for your work, please cite:

Mash sketched databases for: Mash Sketched Reference Dataset for Genome-Based Taxonomy and Comparative Genomics. figshare. Online resource. https://doi.org/10.6084/m9.figshare.14408801.v2 
