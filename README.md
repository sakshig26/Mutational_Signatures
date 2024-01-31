# Mutational_Signatures

**Work Done so Far**
  Literature Review:
  Two major papers acting as base papers to this work is being studied and cloned.
  https://github.com/AlexandrovLab/SigProfilerExtractor
  
  https://github.com/getzlab/SignatureAnalyzer


**In this proposed work, idea is to to do tasks:**
**1. Studying the effect of local neighbors on K-Mers generation.**
Finding effect of neighbors on mutation motifs.
Finding effect of long sequences of mutation motifs.

**2.Generating Sequence data**
Idea is to create sequence for Mutational Signature identification that happens in Genome Sequence reference whenever there is somatic mutation takes place due to the factors deriving cancer growth.

Current Progress
1. MSK-Data is being used to study mutations.
Data-set granularity: Group by Patient id->group by Chromosome ->check type of mutation (sbs,deletion,insertion etc.)->check for start and end position columns->map mutations to reference genome->K-Mer Construction


2. Code is being done to identify mutations at:Single Nucleotide polymorphism,Double Nulceotide polymorphism,Tri Nucleotide polymorphism. So, subsitutions are being handled.

3. Code for Insertion and deletion is in progress. Once, mutations are being identified, K-Mers generation will take place.

**** Statistics of data-set****
MSK Data has been downloaded from cbioportal and focus is primarily on 'Breast Cancer'

No. of unique patients:9594
No of variant types:
SNP    65970
DEL     8201
INS     2910
DNP     1039
TNP       81
ONP       62






 
 




