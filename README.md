# Mash-sketched-reference-databases
Mash-sketched reference databases are an up-to-date representation of several NCBI genomic, proteomic and metagenomic data, curated and formatted according to the sketching  MinHash algorithm developed by [Ondov et al. 2016](https://doi.org/10.1186/s13059-016-0997-x). Each dataset is in .msh format and mostly represents information from type material, in order to offer informative contexts with standard in nomenclature when possible.

![TemplateGithub](https://user-images.githubusercontent.com/42699236/115393742-a1237d00-a1a7-11eb-98b1-2d703854a357.jpg)


You can access and download all pre sketched files from:
> Sánchez-Reyes, Ayixon; Fernández-López, Maikel Gilberto (2021): Mash sketched databases for: Mash Sketched Reference Dataset for Genome-Based Taxonomy and Comparative Genomics. figshare. [Online resource](https://doi.org/10.6084/m9.figshare.14408801.v6)

# Data information:

°[Bacteria_Archaea_type_assembly_set.msh](https://figshare.com/ndownloader/files/30851626)   => 16,304 type genomes from NCBI

°[Bacteria_Archaea_type_proteome_set.msh](https://figshare.com/ndownloader/files/27631017)   => 12,767 type predicted proteomes from NCBI

°[GTDB_r202_assembly_set.msh](https://figshare.com/ndownloader/files/30863182)               => 31,910 genomes from GTDB 

°[Fungi_type_assembly_set.msh](https://figshare.com/ndownloader/files/30871351)              => 753 type genomes from NCBI 

°[Fungi_type_proteome_set.msh](https://figshare.com/ndownloader/files/27631026)              => 248 type predicted proteomes from NCBI

°[Virus_Sept21_GenBank_assembly_set.msh](https://figshare.com/ndownloader/files/30863599)    =>  40,708 viral assemblies from NCBI

°[Soil_Metgenome_assembly_set.msh](https://figshare.com/ndownloader/files/27631032)         => 479 soil metagenomes from NCBI 

°[Freshwater_Metagenome_assembly_set.msh](https://figshare.com/ndownloader/files/27631020)  => 611 freswater metagenomes from NCBI 

°[Fungal_Database.2022_genomic.fna.gz.msh](https://figshare.com/ndownloader/files/39553258) => 4,293 filamentous and yeast-like fungal genomes

# Usage

You can use any of the files with mash tool (see the work by Ondov et al., 2016 About Mash)

Example

$ mash dist query_genome    Bacteria_Archaea_type_assembly_set.msh > output

# If you find this information useful for your work, please cite:

Sánchez-Reyes, A., & Fernández-López, M. G.. (2024). Sketched reference databases for genome-based taxonomy and comparative genomics. Brazilian Journal of Biology, 84(Braz. J. Biol., 2024 84), e256673. https://doi.org/10.1590/1519-6984.256673

Mash sketched databases for: Mash Sketched Reference Dataset for Genome-Based Taxonomy and Comparative Genomics. figshare. Online resource. https://doi.org/10.6084/m9.figshare.14408801.v6 

Ondov et al. 2016. Mash: fast genome and metagenome distance estimation using MinHash. Genome Biol. Jun 20;17(1):132. https://doi.org/10.1186/s13059-016-0997-x
