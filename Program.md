# Detailed program


## September 19<sup>th</sup>, 2017
**16:00-18:30**
* Optional extra session to check on familiarity with minimal computer usage operation in Linux and R


## September 20<sup>th</sup>, 2017
**09:30-11:30** 
* Introduction of participants and expectations
* Bioinformatics for cancer immunology and immuno oncology
* Prediction of tumor neoantigens
* HLA typing
* Exercise 1 and questions: HLA typing
  * *Patient_1_RNAseq.fastq*

**11:00-11:30**
*Coffee Break*

**11:30-12:30**
* Solution: exercise 1 and questions
  * *Patient_1_HLA_typing.txt*
  * *Patient_1_HLA_typing_coverage_plot.pdf*
* Variant annotation
* Exercise 2 and questions: variant annotation
  * *Patient_1_mutations.vcf*

**12:30-14:00**
*Lunch Break*

**14:00-16:00**
* Solution: exercise 2 and questions
  * *Patient_1_VEP_37_mutations.txt*
  * *Patient_1_VEP_37_proteins.txt*
* Peptide-MHC binding prediction
* Exercise 3 and questions: peptide-MHC binding prediction

**16:00-16:30**
*Tea Break*

**16:30-18:00**
* Solution: exercise 3 and questions
  * *Patient_1_NetMHCpan_binders.txt*
* Wrap-up and questions
* Exercise 4: neoantigen prioritization
  * *Patient_1_normalized_expression.txt*
* Brainstorming: strategies for neoantigen prioritization


## September 21<sup>st</sup>, 2017

**09:30-11:30** 
* Morning wrap-up
* Solution: exercise 4 and questions
  * *Patient_1_candidate_neoantigens.txt*
* Discussion about antigen prioritization
* The immune system
* Computational quantification of tumor-infiltrating immune cells
* Exercise 1: SVR deconvolution of PBMC data
 * *Mixture_Newman_PBMC.txt*
 * *Signature_CIBERSORT_LM22.txt*

**11:00-11:30**
*Coffee Break*

**11:30-12:30**
* Assessing deconvolution performance
* Exercise 1: SVR deconvolution of PBMC data (continued…)
* Exercise 2: RMSE
* Exercise 3: deconvolution performance (optional)

**12:30-14:00**
*Lunch Break*

**14:00-16:00**
Solution: exercise 1:
 * *Decon_1_Deconvolution_SVM_PBMC.R*
 * *Decon_SVR_PBMC_cell_fractions.txt*
* Solution: exercise 2
  * *Decon_2_RMSE.R*
* Solution: exercise 3
  * *Decon_3_Assess_Performance.R*
* Deconvolution Methods
* Exercise 4: assess SVR performance on PBMC data
  * *CellFractions_Newman_PBMC.txt*
* Exercise 5: Run and assess DeconRNASeq on PBMC data
* Questions: deconvolution
* Brainstorming: deconvolution challenges

**16:00-16:30**
*Tea Break*

**16:30-18:00**
* Solution: exercise 4
  * *Decon_4_Assess_Deconvolution_SVR_PBMC.R*
  * *Decon_SVR_PBMC_cell_fractions.pdf*
* Solution: exercise 5
  * *Decon_5_Assess_Deconvolution_DeconRNASeq_PBMC.R*
  * *Decon_DeconRNASeq_PBMC_cell_fractions.txt*
  * *Decon_DeconRNASeq_PBMC_cell_fractions.pdf*
  * *Decon_DeconRNASeq_PBMC_noBnaive_cell_fractions.txt*
  * *Decon_DeconRNASeq_PBMC_noBnaive_cell_fractions.pdf*
* Solution: deconvolution questions
* Exercises 6, 7, or 8 (at your choice)
  * *Mixture_ShenOrr_WholeBlood.txt*
  * *CellFractions_ShenOrr_WholeBlood.txt*
  * *TCGA_CRC_TPM.txt*
  * *TCGA_CRC_MSI_status.txt*
* Wrap-up and questions
* Discussion about deconvolution challenges 

## September 22<sup>nd</sup>, 2017

**09:30-11:30** 
* Morning wrap-up
* Solution: exercise 6
  * *Decon_6_Assess_Deconvolution_SVR_Blood.R*
  * *Decon_SVR_Blood_cell_fractions.txt*
  * *Decon_SVR_Blood_cell_fractions.pdf*
  * *Decon_SVR_Blood_mRNA_cell_fractions.txt*
  * *Decon_SVR_Blood_mRNA_cell_fractions.pdf*
* Solution: exercise 7
  * *Decon_7_Deconvolution_DeconRNASeq_CRC.R*
  * *Decon_DeconRNASeq_CRC_cell_fractions.txt*
  * *Decon_DeconRNASeq_CRC_CD8_fractions_vs_MSI_status.pdf*

**11:00-11:30**
*Coffee Break*

**11:30-12:30**
* TBA...

**12:30-14:00**
*Lunch Break*

**14:00-16:00**
* TBA...

**16:00-16:30**
*Tea Break*

**16:30-18:00**
* TBA...
* Final wrap-up

