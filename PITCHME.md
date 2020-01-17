## Finger Millet Genomic Analysis
Céline Bitter and Masaomi Hatekayama

---

### Introduction


<img width="700" alt="fingermillet" src="https://user-images.githubusercontent.com/48200405/72526126-991ab600-385d-11ea-897d-a620bfdf276b.jpg">

---

### Objective

- Allopolyploidie poses many challenges in finding true variants, due to the high number of homeologs between the subgenomes
- Finger millet is a tetrapolyploid crop species, with subgenome A and subgenome B
- EAGLE-RC is able to map reads to the subgenomes seperately and evaluates the likelihood of the data under a given hypothesis

---

### Methods - planning the pipeline

<img width="820" alt="EAGLE-RC_pipeline" src="https://user-images.githubusercontent.com/48200405/72508625-eb4bdf00-383d-11ea-8f62-5677be147f9e.jpg">

---

###  Methods - applying the pipeline
<img width="900" alt="fingermillet_pipeline" src="https://user-images.githubusercontent.com/48200405/72592710-10eaee00-38fb-11ea-99e3-96ba2d0c2905.jpg">

---

### Methods - BWA
<p float="left">
 <img width="350" alt="BWA" src="https://user-images.githubusercontent.com/48200405/72598182-3847b800-3907-11ea-9975-0eb7484486a2.jpg">
 <img width="350" alt="BWA_tree" src="https://user-images.githubusercontent.com/48200405/72598188-3a117b80-3907-11ea-8905-2f9042ff0682.jpg">
</p>

---

### Methods - EAGLE-RC
<p float="left">
 <img width="400" alt="EAGLE-RC_workflow" src="https://user-images.githubusercontent.com/48200405/72600685-05ec8980-390c-11ea-93a2-ff26c650b296.jpg">
 <img width="320" alt="EAGLE-RC_merged" src="https://user-images.githubusercontent.com/48200405/72601596-9a0b2080-390d-11ea-9b8c-9b057dd24b4f.jpg">
</p>

---

### Challenges vs what I have learned
- Bottelneck in pipeline (BWA, EAGLE-RC, GATK) x
- Reduced disc space on server x
- Planning and organisation :heavy_check_mark:
- Github :heavy_check_mark: 
- Application of a functional genomics workflow :heavy_check_mark:

---

### Outlook
- Finish the pipeline (from EAGLE-RC to BEAGLE)
- Start pipeline for remaining 3 groups 
- At the beginning of pipeline, state what could go wrong and name workarounds 

