# Spatial Transcriptomics Workshop - Teaching Materials

## Teaching Materials for 2025 Spatial Transcriptomics seminar to NIDDK TriLab Bioinformatics Group (Fri Jun 13 2025 1-2:30pm)
Updated slides: [STworkshop_2025.pdf](https://github.com/user-attachments/files/20731274/STworkshop_2025.pdf)

## Teaching Materials for 2024 Spatial Transcriptomics workshop  
Prepared by Margaret Ho (NIAID BCBB Science Support)  

## Day 1: Introduction to spatial transcriptomics methods and concepts for STx data analysis (Nov 4 2024 1-3 pm, online session)  
[Part 1 - Slides ](https://github.com/user-attachments/files/17620116/STworkshop_2024_Part1_v4.pdf)

## Day 2: Hands-on workshop using R and Seurat to analyze an example spatial transcriptomics dataset (Nov 15 2024 1-3pm, online session)  

### Slides For Day 2
[Part 2 - Slides](https://github.com/user-attachments/files/17778721/STworkshop_.2024_Part2_v3.pdf)

### Code For Day 2 to demonstrate Visium (sequencing based) STx data analysis
See Quarto Markdown (Seurat_Visium_Tutorial.qmd) document containing R code for analyzing an example Visium (sequencing-based) STx dataset with Seurat  
[Part 2 - R Code (Quarto Markdown Document)](https://github.com/margaretc-ho/BCBB_STx_workshop_2024/blob/fa6ba621c9ee5b98c162f61c45d6487519d9072e/Seurat_Visium_tutorial.qmd)    
Ideally, please run the SETUP section in $${\color{red}red}$$ to install necessary R packages and libraries and download Visium data and scRNA-seq reference dataset before our session starts to make things easier. But no worries if you didn't get to it ahead of time.   

PDF (showing the code and output) also available [here](https://github.com/user-attachments/files/17425039/Seurat_spatialvignette.pdf)


### Additional Code to demonstrate Xenium (image based) STx data analysis (optional)
See Quarto Markdown document and HTML output in this zip file [Seurat_Xenium_tutorial_Biowulf_2024.zip](https://github.com/user-attachments/files/17548625/Seurat_Xenium_tutorial_Biowulf_2024.zip)

## HPC instructions for Workshop Participants 

### Running RStudio Server on Biowulf HPC
Biowulf has [official instructions](https://hpc.nih.gov/apps/rstudio-server.html) for setting up your interactive session, creating a tunnel, and accessing R Studio Server using local host, assigned port and web browser. For additional ease, I created an detailed instructions [PDF](https://github.com/margaretc-ho/BCBB_STx_workshop_2024/blob/98990cab36794cf9ad5786222eacaef35f6b779b/RStudioServer_on_Biowulf_instructions_082324MH.pdf).
I recommend that you request at least 25G of memory for your interactive session for Visium datasets and more (~40GB) for larger datasets such as Visium HD and Xenium.

### Running RStudio Server on NIAID Skyline
For running RStudio Server on Skyline, please see Poorani Subramanian's excellent instructions [here](https://github.com/niaid/hpcR/tree/main/rstudio_server)  
