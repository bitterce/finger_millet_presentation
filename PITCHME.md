## Finger Millet Genomic Analysis
Céline Bitter and Masaomi Hatekayama

---

### Introduction


<img width="700" alt="fingermillet" src="https://user-images.githubusercontent.com/48200405/72526126-991ab600-385d-11ea-897d-a620bfdf276b.jpg">

---

#### Objective
@ul[list-square-bullets list-spaced-bullets text-08](false)
- Allopolyploidie poses many challenges in finding true variants, due to the high number of homeologs between the subgenomes
- Finger millet is a tetrapolyploid crop species, with subgenome A and subgenome
- EAGLE-RC is able to map reads to the subgenomes seperately and evaluates the likelihood of the data under a given hypothesis
@ulend

---

#### Methods - planning the pipeline

<img width="750" alt="methods" src="https://user-images.githubusercontent.com/48200405/72679900-cd83b180-3aab-11ea-8f07-02323a82c236.jpg">

---

#### Methods - EAGLE-RC
<p float="left">
 <img width="400" alt="EAGLE-RC_workflow" src="https://user-images.githubusercontent.com/48200405/72600685-05ec8980-390c-11ea-93a2-ff26c650b296.jpg">
 <img width="320" alt="EAGLE-RC_merged" src="https://user-images.githubusercontent.com/48200405/72601596-9a0b2080-390d-11ea-9b8c-9b057dd24b4f.jpg">
</p>

---

####  Methods - applying the pipeline
<img width="900" alt="fingermillet_pipeline" src="https://user-images.githubusercontent.com/48200405/72592710-10eaee00-38fb-11ea-99e3-96ba2d0c2905.jpg">

---

#### Results (before EAGLE-RC)
<p float="left">
 <img align="right" width="290" alt="number_of_mapped_reads_on_B" src="https://user-images.githubusercontent.com/48200405/72685159-0d17c100-3adf-11ea-9544-2fce2b94b91e.png">
 <img align="right" width="290" alt="number_of_reads" src="https://user-images.githubusercontent.com/48200405/72685087-777c3180-3ade-11ea-9bb3-5a2e3e2a5981.png">
 <img align="right" width="290" alt="number_of_mapped_reads_on_A" src="https://user-images.githubusercontent.com/48200405/72685112-c1fdae00-3ade-11ea-81ad-90f47a70a56c.png">
</p>

<p float="left">
 <img align="right" width="290" alt="number_of_mapped_reads_on_A" src="https://user-images.githubusercontent.com/48200405/72685157-0ab56700-3adf-11ea-9823-d1e245aa3103.png">
 <img align="right" width="290" alt="number_of_mapped_reads_on_B" src="https://user-images.githubusercontent.com/48200405/72685115-c5913500-3ade-11ea-89cb-47929b767e6b.png">
</p>


---

#### Results (after EAGLE-RC)
<p float="left">
 <img width="290" alt="number_of_reads" src="https://user-images.githubusercontent.com/48200405/72685087-777c3180-3ade-11ea-9bb3-5a2e3e2a5981.png">
 <img width="290" alt="number_of_mapped_reads_on_A" src="https://user-images.githubusercontent.com/48200405/72685112-c1fdae00-3ade-11ea-81ad-90f47a70a56c.png">
 <img width="290" alt="number_of_mapped_reads_on_B" src="https://user-images.githubusercontent.com/48200405/72685159-0d17c100-3adf-11ea-9544-2fce2b94b91e.png">
</p>

<p float="right">
 <img align="right" width="290" alt="number_of_mapped_reads_on_A" src="https://user-images.githubusercontent.com/48200405/72685157-0ab56700-3adf-11ea-9823-d1e245aa3103.png">
 <img align="right" width="290" alt="number_of_mapped_reads_on_B" src="https://user-images.githubusercontent.com/48200405/72685115-c5913500-3ade-11ea-89cb-47929b767e6b.png">
</p>

---

#### Challenges vs what I have learned
@ul[list-square-bullets list-spaced-bullets text-08](false)
- Bottelneck in pipeline (BWA, EAGLE-RC, GATK) :x:
- Reducekd disc space on server :x:
- Planning and organisation :heavy_check_mark:
- Github :heavy_check_mark: 
- Application of a functional genomics workflow :heavy_check_mark:
@ulend

---

#### Outlook
@ul[list-square-bullets list-spaced-bullets text-08](false)
- Finish the pipeline (from EAGLE-RC to BEAGLE)
- Start pipeline for remaining 3 groups 
- At the beginning of pipeline, state what could go wrong and name workarounds
- Compare sequencing data to linguistic data  
@ulend

---
#### Acknowledgement



