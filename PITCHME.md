## Finger Millet Genomic Analysis
Céline Bitter and Masaomi Hatekayama

---

### Introduction


<img width="700" alt="fingermillet" src="https://user-images.githubusercontent.com/48200405/72526126-991ab600-385d-11ea-897d-a620bfdf276b.jpg">

---

#### Objective
@size[5em]
(
- Allopolyploidie poses many challenges in finding true variants, due to the high number of homeologs between the subgenomes
- Finger millet is a tetrapolyploid crop species, with subgenome A and subgenome B
- EAGLE-RC is able to map reads to the subgenomes seperately and evaluates the likelihood of the data under a given hypothesis
)
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
 <img width="300" alt="number_of_reads_on_A" src="https://user-images.githubusercontent.com/48200405/72680170-e346a600-3aae-11ea-9af9-de11a0f7b349.png">
 <img width="300" alt="number_of_reads_on_B" src="https://user-images.githubusercontent.com/48200405/72680174-e6419680-3aae-11ea-9e1f-bfb64b4fb616.png">
</p>

<p float="left">
 <img width="300" alt="number_of_mapped_reads_on_A" src="https://user-images.githubusercontent.com/48200405/72680177-ed68a480-3aae-11ea-9b46-59d37a521c97.png">
 <img width="300" alt="number_of_mapped_reads_on_B" src="https://user-images.githubusercontent.com/48200405/72680178-efcafe80-3aae-11ea-84f7-ddc613af865d.png">
</p>
---


#### Challenges vs what I have learned
- Bottelneck in pipeline (BWA, EAGLE-RC, GATK) :x:
- Reduced disc space on server :x:
- Planning and organisation :heavy_check_mark:
- Github :heavy_check_mark: 
- Application of a functional genomics workflow :heavy_check_mark:

---

#### Outlook

- Finish the pipeline (from EAGLE-RC to BEAGLE)
- Start pipeline for remaining 3 groups 
- At the beginning of pipeline, state what could go wrong and name workarounds 

---
#### Acknowledgement

