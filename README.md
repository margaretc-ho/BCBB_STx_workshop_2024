# Teaching Materials for 2024 Spatial Transcriptomics workshop  
Prepared by Margaret Ho (NIAID BCBB Science Support)  

## Day 1: Introduction to spatial transcriptomics methods and concepts for STx data analysis (Nov 4 2024 1-3 pm, online session)  
[Part 1 - Slides (draft) ](https://github.com/user-attachments/files/17415223/STworkshop_2024draft_101024.pdf)  
 
## Day 2: Hands-on workshop using R and Seurat to analyze an example spatial transcriptomics dataset (Nov 15 2024 1-3pm, online session)  
[Part 2 - Slides (draft) ](https://github.com/user-attachments/files/17415203/STworkshop_part2_.2024draft_101524.pdf)    

See Quarto Markdown (Seurat_Visium_Tutorial.qmd) document containing R code for analyzing an example STx dataset with Seurat  
[Part 2 - R Code (Quarto Markdown Document - draft)](https://github.com/margaretc-ho/BCBB_STx_workshop_2024/blob/babcca31b9506e6cc79dfed7bddb581033074f0e/Seurat_Visium_tutorial.qmd)    
Ideally, please run the SETUP section in $${\color{red}red}$$ to install necessary R packages and libraries and download Visium data and scRNA-seq reference dataset before our session starts to make things easier. But no worries if you didn't get to it ahead of time.   

Knitted document (Seurat_Visium_tutorial.html) also available [here](https://github.com/margaretc-ho/BCBB_STx_workshop_2024/blob/babcca31b9506e6cc79dfed7bddb581033074f0e/Seurat_Visium_tutorial.html)   

## HPC instructions for Workshop Participants 

### Running RStudio Server on Biowulf HPC
Please see the official instructions at https://hpc.nih.gov/apps/rstudio-server.html for setting up your interactive session, creating a tunnel, and accessing R Studio Server using local host, assigned port and web browser
I also created an detailed instructions [PDF](https://github.com/margaretc-ho/BCBB_STx_workshop_2024/blob/98990cab36794cf9ad5786222eacaef35f6b779b/RStudioServer_on_Biowulf_instructions_082324MH.pdf).
I recommend that you request at least 25G of memory for your interactive session for Visium datasets and more (~40GB) for larger datasets such as Visium HD and Xenium.

### Running RStudio Server on NIAID Skyline
For running RStudio Server, please see Poorani Subramanian's excellent instructions here https://github.com/niaid/hpcR/tree/main/rstudio_server
