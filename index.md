This site contains course materials for SISG Module QG4: WGS Data Analysis, June 11-13, 2025. 

- **Instructors:** Laura Raffield and Matthew Conomos

## Course Description
This module will provide an introduction to analyzing genotype data generated from whole genome sequencing (WGS). It will focus on extensions of standard GWAS analyses (e.g. rare-variant association tests) and “post-GWAS” follow-up analyses (e.g. conditional analysis, fine-mapping), and how WGS may improve results or be best utilized for these analyses; methods that incorporate variant annotation information will be highlighted.

Methods and examples will be informed by the instructors’ experience in large human genetics consortia (e.g. TOPMed), and, therefore, will focus on analyzing human data, but may be applicable/extendable to other organisms. A basic introduction to cloud computing will be provided, and students will perform hands-on exercises on a genomic analysis cloud platform.

### Learning Objectives
After attending this module, participants will be able to: 
1. Understand how to perform association analyses for rare variants measured in WGS data using aggregate tests
2. Access variant annotation resources and understand how to incorporate annotation information into analyses to improve power and inform results
3. Understand the theory of, and how and when to perform, various “post-GWAS” follow-up analyses 
4. Leverage multi-ancestry WGS data
5. Appreciate the utility of existing genomic analysis cloud platforms and get hands-on experience with cloud computing on one of these platforms

## Course Format

### Lectures
Course material will be presented through lectures. Slides for lectures are linked in the schedule below.

### Tutorials
Many of the lectures will be followed with hands-on tutorials/exercises. Students are encouraged to work through the tutorials together. Afterwards, the instructors will walk through the tutorials and lead a discussion.

To run the tutorials, log into [NHLBI BioData Catalyst powered by Seven Bridges](https://platform.sb.biodatacatalyst.nhlbi.nih.gov) with your username and password -- we will use this platform for live demonstrations during the course.

- You will retain access to the Seven Bridges platform, including your SISG Project with all of the course materials even after the course ends. The SISG25 Workshop billing group will remain available to you for a short period of time, after which you will need to set up another payment method to run analyses. You can [request pilot cloud credits](https://biodatacatalyst.nhlbi.nih.gov/resources/cloud-credits) ($500 worth) from BioData Catalyst. Additionally, there is guidance available for [writing BioData Catalyst cloud costs into your grant proposal budget](https://bdcatalyst.gitbook.io/biodata-catalyst-documentation/written-documentation/getting-started/writing-biodata-catalyst-into-a-grant-proposal). 

All of the R code and data can also be downloaded from the [github repository](https://github.com/UW-GAC/SISG_2025) from which the site is built and run on your local machine. Download the complete workshop data and tutorials: [https://github.com/UW-GAC/SISG_2025/archive/main.zip](https://github.com/UW-GAC/SISG_2025/archive/main.zip)


## Course Schedule and Materials

The exact timing of the schedule is subject to change, depending on the amount of discussion we have in class. <br>
Coffee breaks are daily from 10:00am-10:30am and 3:00pm-3:30pm. Lunch break is daily from 12:00pm-1:30pm.

**Wednesday, June 11th**

| Topic | Materials |
| --- | --- |
| Introduction | [Slides]() |
| Intro to Cloud Computing for WGS Data Analysis | [Lecture Slides]() |
| Intro to GDS Tutorial | [.Rmd](https://github.com/UW-GAC/SISG_2025/blob/main/01_gds_intro.Rmd) \| [.html](https://htmlpreview.github.io/?https://github.com/UW-GAC/SISG_2025/blob/main/01_gds_intro.html) |
| GWAS Crash Course | [Lecture Slides]() |
| GWAS Tutorial | [.Rmd](https://github.com/UW-GAC/SISG_2025/blob/main/02_GWAS.Rmd) \| [.html](https://htmlpreview.github.io/?https://github.com/UW-GAC/SISG_2025/blob/main/02_GWAS.html) |
| _Extra_: Population Structure and Relatedness Tutorial | [.Rmd](https://github.com/UW-GAC/SISG_2025/blob/main/02.1_pop_structure_relatedness.Rmd) \| [.html](https://htmlpreview.github.io/?https://github.com/UW-GAC/SISG_2025/blob/main/02.1_pop_structure_relatedness.html)
| _Extra_: GWAS: Advanced Model Extenstions Lecture and Tutorial | [Slides]() \| [.Rmd](https://github.com/UW-GAC/SISG_2025/blob/main/02.2_advanced_GWAS.Rmd) \| [.html](https://htmlpreview.github.io/?https://github.com/UW-GAC/SISG_2025/blob/main/02.2_advanced_GWAS.html) |
| _Extra_: GENESIS Model Explorer Tutorial | [.Rmd](https://github.com/UW-GAC/SISG_2025/blob/main/02.3_GENESIS_model_explorer.Rmd) \| [.html](https://htmlpreview.github.io/?https://github.com/UW-GAC/SISG_2025/blob/main/02.3_GENESIS_model_explorer.html)

**Thursday, June 12th**

| Topic | Materials |
| --- | --- |
| Leveraging Multi-Ancestry Data | [Lecture Slides]() |
| LD Exercise | [.docx](https://docs.google.com/document/d/1Zkhwa2uwzvwTVpy-sAsYIkvwFDKlLEin/preview) \| [_NEJM_ 2020](https://drive.google.com/file/d/1AxGGz1r9KOM7i0xPE34b7KA7Ern7J6HB/view?usp=drive_link) \| [_Nature_ 2021](https://drive.google.com/file/d/171FkSo0lAkbuAAX1tzc1LhdOYuqWFeNJ/view?usp=drive_link)  \| [KEY](https://docs.google.com/document/d/1lIBwrP-79LcaHRCqTD3snZro5Ylb6cyA/preview) |
| Locus Zoom and Conditional Analysis Tutorial | [.Rmd](https://github.com/UW-GAC/SISG_2025/blob/main/03_conditional_analysis.Rmd) \| [.html](https://htmlpreview.github.io/?https://github.com/UW-GAC/SISG_2025/blob/main/03_conditional_analysis.html) |
| Variant Annotation | [Lecture Slides]() |
| UCSC Genome Browser and FAVOR Tutorial | [.docx](https://docs.google.com/document/d/1M1AeVvF0o7-g-ASouXGVXm96pf2ucxmI/preview) \| [chr16 SNPS](https://drive.google.com/file/d/1wIsk7rJlcfodfgQwLV-I8Ofh23GhqN5d/view?usp=drive_link) \| [KEY](https://docs.google.com/document/d/1PJcxgAPblVnGcfDsY_ns8A4mi8yFSshZ/preview) |
| Annotation Explorer Tutorial | [.Rmd](https://github.com/UW-GAC/SISG_2025/blob/main/04_annotation_explorer.Rmd) \| [.html](https://htmlpreview.github.io/?https://github.com/UW-GAC/SISG_2025/blob/main/04_annotation_explorer.html) |
| _5:00pm-6:00pm_: Tutorial Open Q&A Session | |

**Friday, June 13th**

| Topic | Materials |
| --- | --- |
| Multi-Variant Association Tests | [Lecture Slides]() | 
| Multi-Variant Association Tests Tutorial | [.Rmd](https://github.com/UW-GAC/SISG_2025/blob/main/05_aggregate_tests.Rmd) \| [.html](https://htmlpreview.github.io/?https://github.com/UW-GAC/SISG_2025/blob/main/05_aggregate_tests.html) |
| STAAR | [Lecture Slides]() | 
| STAAR Tutorial | [.Rmd](https://github.com/UW-GAC/SISG_2025/blob/main/06_STAAR.Rmd) \| [.html](https://htmlpreview.github.io/?https://github.com/UW-GAC/SISG_2025/blob/main/06_STAAR.html) |
| Recent Findings and Resources for WGS Analysis | [Lecture Slides]() |
| Open Q&A | |

## R packages used

- [GENESIS](http://bioconductor.org/packages/release/bioc/html/GENESIS.html)
- [SeqArray](http://bioconductor.org/packages/release/bioc/html/SeqArray.html)
- [SeqVarTools](http://bioconductor.org/packages/release/bioc/html/SeqVarTools.html)
- [SNPRelate](http://bioconductor.org/packages/release/bioc/html/SNPRelate.html)
- [Biobase](https://bioconductor.org/packages/release/bioc/html/Biobase.html)
- [GenomicRanges](https://bioconductor.org/packages/release/bioc/html/GenomicRanges.html)
- [GGally](https://cran.r-project.org/web/packages/GGally)


## Resources

A detailed tutorial and relevant R scripts for STAAR pipeline are available at [https://github.com/xihaoli/STAARpipeline-Tutorial](https://github.com/xihaoli/STAARpipeline-Tutorial).

If you are new to R, you might find the following material helpful:

- [Introduction to R](http://faculty.washington.edu/kenrice/rintro/) materials from SISG Module 3
- Graphics with [ggplot2](https://ggplot2.tidyverse.org/)
- Data manipulation with [dplyr](http://dplyr.tidyverse.org/)
