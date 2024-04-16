# P8139_final

Instruction for the final project:
• Each student will do a final project of his/her choices. Final reports are due on Friday 5/05/24 by 5pm. The format of the final report is single-spaced, font size 11 and no more than 10 pages, with figures, tables and references included, like a journal article.
• Data sources:
You can use TCGAbiolinks to download SNP data or DNA methylation data for your final projects
from TCGA (the Cancer Genome Atlas) project using the ‘GDCquery’ and ‘GDCdownload’
functions.
(https://bioconductor.org/packages/release/bioc/vignettes/TCGAbiolinks/inst/doc/download_pre
pare.html)
• For the data you are going to use for your final project, you need to pay attention to the following
items:
(a) What is the experimental design?
(b) What are the samples used? Tumor tissues and adjacent-normal tissues, i.e., paired case-control samples? Or tumor tissues and independent normal tissues, i.e., independent case-control samples? What are the sample size?
(c) What are the necessary data preprocessing steps for DNA methylation data? Google to figure this out yourself. If so, list the detailed process steps.
(d) What is your research question? What is your data analysis plan? That is, what tests are you going to use to answer your research questions? Two-sample t-test? Paired t-test? Regressions?
Are there multiple comparisons issues that you need to take care of? How do you plan to
handle that?
(e) How to make figures and tables out of these high-dimensional data to best present your results?
(f) What is your conclusion?