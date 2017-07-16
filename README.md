# Anchored Hybrid Enrichment Tools
This is a set of tools and tutorials designed for handling Anchored Hybrid Enrichment data. It incorporates:  
+ filtering protocols from EAPhy (https://github.com/MozesBlom/EAPhy)  
+ phylogenetic estimation using ASTRAL (https://github.com/smirarab/ASTRAL) and starBEAST2 (https://www.beast2.org/)  
+ and assorted bits of code for data handling  
  
It's not exhaustive, and it's certainly brief, but it's someplace to start.
  
The main file 'Lemmon Data Workflow' can be downloaded as either a PDF you can browse through, or as a RMarkdown document you can operate the code directly from. Additional scripts are described below:  
+ Muscle - Combining and Aligning.R: helps combine orthologous loci from different locus sets. Uses an output list of orthologues from BLAST RBH, and the associated alignment files, to combine and align them via MUSCLE (http://www.drive5.com/muscle/).  
+ RWTY - Check Convergence: simple example of how to use R We There Yet? to check for MCMC convergence.  
+ PhyDesign.Nexus.nex: nexus file example of formatting for input to PhyDesign (http://phydesign.townsend.yale.edu/).
