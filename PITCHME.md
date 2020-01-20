## Finger Millet Genomic Analysis
Céline Bitter 
(Supervior: Dr. Masaomi Hatekayama)

---

@snap[north span-50 text-center]
### Introduction
@snapend

<img width="700" alt="fingermillet" src="https://user-images.githubusercontent.com/48200405/72526126-991ab600-385d-11ea-897d-a620bfdf276b.jpg">

---

@snap[north span-50 text-center]
### Objective
@snapend

@ul[list-square-bullets list-spaced-bullets text-08](false)
- Challenges in finding true variants in allopolyploids
	- Often huge genome size
	- High number of homeologs between subgenomes
- Finger millet is a tetrapolyploid crop species
	- Subgenome A and subgenome B
	- Finding SNP is subgenomes
- EAGLE-RC used to classify reads
	- Maps reads to the subgenomes seperately
	- Evaluates the likelihood of the data under a given hypothesis
@ulend

---

@snap[north span-100 text-center]
### Methods - planning the pipeline
@snapend

<img width="850" alt="methods" src="https://user-images.githubusercontent.com/48200405/72679900-cd83b180-3aab-11ea-8f07-02323a82c236.jpg">

---

@snap[north span-100 text-center]
### Methods - EAGLE-RC
@snapend

<p float="left">
 <img width="420" alt="EAGLE-RC_workflow" src="https://user-images.githubusercontent.com/48200405/72600685-05ec8980-390c-11ea-93a2-ff26c650b296.jpg">
 <img width="340" alt="EAGLE-RC_merged" src="https://user-images.githubusercontent.com/48200405/72601596-9a0b2080-390d-11ea-9b8c-9b057dd24b4f.jpg">
</p>

---

@snap[north span-100 text-center]
###  Methods - applying the pipeline
@snapend

<img width="900" alt="fingermillet_pipeline" src="https://user-images.githubusercontent.com/48200405/72592710-10eaee00-38fb-11ea-99e3-96ba2d0c2905.jpg">

---

#### Results (before EAGLE-RC)

<p float="left">
 <img align="right" width="290" alt="percentage_of_mapped_reads_on_A" src="https://user-images.githubusercontent.com/48200405/72685548-333f6000-3ae3-11ea-92f7-0d715924efc3.png">
 <img align="right" width="290" alt="number_of_mapped_reads_on_A" src="https://user-images.githubusercontent.com/48200405/72685551-39cdd780-3ae3-11ea-831a-4862b949204f.png">
 <img align="right" width="290" alt="number_of_reads" src="https://user-images.githubusercontent.com/48200405/72685552-3cc8c800-3ae3-11ea-84a8-31998d39a1a4.png">
</p>

<p float="left">
 <img align="right" width="290" alt="percentage_of_mapped_reads_on_B" src="https://user-images.githubusercontent.com/48200405/72685557-44886c80-3ae3-11ea-9310-ee4a477e2e50.png">
 <img align="right" width="290" alt="number_of_mapped_reads_on_B" src="https://user-images.githubusercontent.com/48200405/72685560-4c481100-3ae3-11ea-91b5-cd80888056b4.png">
</p>

---?image=assets/img/number_of_reads.png

---

@snap[north span-100 text-center]
#### Results (after EAGLE-RC)
@snapend

<p float="left">
 <img align="right" width="280" alt="percentage_of_mapped_reads_after_EAGLE-RC_on_A" src="https://user-images.githubusercontent.com/48200405/72685695-574f7100-3ae4-11ea-9c22-0af5dd2c747b.png">
 <img align="right" width="280" alt="number_of_mapped_reads_after_EAGLE-RC_on_A" src="https://user-images.githubusercontent.com/48200405/72685700-5f0f1580-3ae4-11ea-9ab8-556cbb7be8f8.png">
 <img align="right" width="280" alt="number_of_reads" src="https://user-images.githubusercontent.com/48200405/72685087-777c3180-3ade-11ea-9bb3-5a2e3e2a5981.png">
</p>

<p float="left">
 <img align="right" width="280" alt="percentage_of_mapped_reads_after_EAGLE-RC_on_B" src="https://user-images.githubusercontent.com/48200405/72685703-6cc49b00-3ae4-11ea-91b1-9f495baf3136.png">
 <img align="right" width="280" alt="number_of_mapped_reads_after_EAGLE-RC_on_B" src="https://user-images.githubusercontent.com/48200405/72685705-7817c680-3ae4-11ea-80c8-5328ac569633.png">
</p>

---
@title[Results (Number of SNPs, GATKv4)]

@snap[north span-100 text-center]
#### Results (Number of SNPs)
@snapend

@snap[west span-50]
![IMAGE](img/snps_A.png)
@snapend

@snap[east span-50]
![IMAGE](img/snps_B.png)

---

### Discussion
@snap[text-04]
before EAGLE-RC
@snapend
<nbsp float="left">
 <img width="250" alt="percentage_of_mapped_reads_on_A" src="https://user-images.githubusercontent.com/48200405/72685548-333f6000-3ae3-11ea-92f7-0d715924efc3.png">
 <img width="250" alt="percentage_of_mapped_reads_on_B" src="https://user-images.githubusercontent.com/48200405/72685557-44886c80-3ae3-11ea-9310-ee4a477e2e50.png">
</nbsp>
@snap[text-04]
after EAGLE-RC
@snapend
<nbsp float="left">
 <img width="250" alt="percentage_of_mapped_reads_after_EAGLE-RC_on_A" src="https://user-images.githubusercontent.com/48200405/72685695-574f7100-3ae4-11ea-9c22-0af5dd2c747b.png">
 <img width="250" alt="percentage_of_mapped_reads_after_EAGLE-RC_on_B" src="https://user-images.githubusercontent.com/48200405/72685703-6cc49b00-3ae4-11ea-91b1-9f495baf3136.png">
</nbsp>

---

@snap[north span-100 text-center]
### Challenges vs what I have learned
@snapend

@ul[list-square-bullets list-spaced-bullets text-08](false)
- Bottelneck in pipeline (BWA, EAGLE-RC, GATK)
- Limited disc space on server
- Planning and organisation
- Github / GitPitch 
- Application of a functional genomics workflow
@ulend

---

@snap[north span-50 text-center]
### Outlook
@snapend

@ul[list-square-bullets list-spaced-bullets text-08](false)
- Finish the pipeline (from EAGLE-RC to BEAGLE)
- Start pipeline for remaining 3 groups 
- At the beginning of pipeline, state what could go wrong and name workarounds
- Compare sequencing data to linguistic data  
@ulend

---
@snap[north span-100 text-center]
### Acknowledgement
@snapend

@ul[list-square-bullets list-spaced-bullets text-10](false)
- Prof. Kentaro Shimizu
- Dr. Masaomi Hatekayama
- Dr. Chiara Barbieri
- And to everyone somehow involved in this project!
@ulend
@snap[text-14]
Thanks everyone for your attention! 
@snapend


