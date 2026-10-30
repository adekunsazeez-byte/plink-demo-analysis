# plink-demo-analysis
make bed from ped and map files
PS C:\Users\USER\Downloads\plink demo> ren map.txt demo.map
PS C:\Users\USER\Downloads\plink demo> ren ped.txt demo.ped
PS C:\Users\USER\Downloads\plink demo> .\plink --file demo --make-bed --out demo
PLINK v1.90b7.4 64-bit (18 Aug 2024)           www.cog-genomics.org/plink/1.9/
(C) 2005-2024 Shaun Purcell, Christopher Chang   GNU General Public License v3
Logging to demo.log.
Options in effect:
  --file demo
  --make-bed
  --out demo

8067 MB RAM detected; reserving 4033 MB for main workspace.
.ped scan complete (for binary autoconversion).
Performing single-pass .bed write (5 variants, 500 people).
--file: demo-temporary.bed + demo-temporary.bim + demo-temporary.fam written.
5 variants loaded from .bim file.
500 people (251 males, 249 females) loaded from .fam.
500 phenotype values loaded from .fam.
Using 1 thread (no multithreaded calculations invoked).
Before main variant filters, 500 founders and 0 nonfounders present.
Calculating allele frequencies... done.
Total genotyping rate is 0.9908.
5 variants and 500 people pass filters and QC.
Among remaining phenotypes, 318 are cases and 182 are controls.
--make-bed to demo.bed + demo.bim + demo.fam ... done.
PS C:\Users\USER\Downloads\plink demo>
