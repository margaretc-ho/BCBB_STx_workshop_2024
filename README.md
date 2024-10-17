# Teaching Materials for 2024 Spatial Transcriptomics workshop
Prepared by Margaret Ho (BCBB Science Support)

## Day 1 Introduction to spatial transcriptomics methods and concepts for STx data analysis (Nov 4 2024 1-3 pm, online session)
[Part 1 - Slides (draft) ](https://github.com/user-attachments/files/17415223/STworkshop_2024draft_101024.pdf)

## Day 2 Hands-on workshop using R and Seurat to analyze an example spatial transcriptomics dataset (Nov 15 2024 1-3pm, online session)

[Part 2 - Slides (draft) ](https://github.com/user-attachments/files/17415203/STworkshop_part2_.2024draft_101524.pdf)  

[Part 2 - R Code (Quarto Markdown Document - draft)](https://github.com/margaretc-ho/BCBB_STx_workshop_2024/blob/babcca31b9506e6cc79dfed7bddb581033074f0e/Seurat_Visium_tutorial.qmd)  

See Quarto Markdown (.qmd) document containing R code for analyzing an example STx dataset with Seurat

## HPC instructions for Students

### Running RStudio Server on Biowulf HPC
Please see the official instructions at https://hpc.nih.gov/apps/rstudio-server.html for setting up your interactive session, creating a tunnel, and accessing R Studio Server using local host, assigned port and web browser
I also created an instructions PDF [RStudioServer_on_Biowulf_instructions_082324MH.pdf](https://github.com/user-attachments/files/17080127/RStudioServer_on_Biowulf_instructions_082324MH.pdf)
which adds a bit more detail. I recommend that you request at least 25G of memory for your interactive session for Visium datasets and more (~40GB) for larger datasets such as Visium HD and Xenium.

### Running RStudio Server on NIAID Skyline
For running RStudio Server, please see Poorani Subramanian's excellent instructions here https://github.com/niaid/hpcR/tree/main/rstudio_server

#### Example Datasets:
