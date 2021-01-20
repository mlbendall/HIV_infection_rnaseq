# HIV_infection_rnaseq
List of HIV infection RNA-seq datasets analyzed

### Peng dataset

Peng X, Sova P, Green RR, Thomas MJ et al., 2014. **Deep sequencing of HIV-infected cells: insights into nascent transcription and host-directed therapy.** _J Virol_, 88(16):8768-82. PMID: [24850744](https://pubmed.ncbi.nlm.nih.gov/24850744/)

GEO: GSE53993

SRA: SRP035316

Description:

Total RNA-seq of SUP-T1 infected with HIV-1 (LAI). 6 samples in total from two time points after infection 12 and 24 hpi; Samples were either Mock infected (12: 3 rep; 24: 2 reps), HIV-1 infected (12: 3 reps; 24: 3 reps), or UV-inactivated viron (12: 3 reps; 24: 2 reps).

Comments:

________________________________________

### Chang dataset
Chang ST, Sova P, Peng X, Weiss J et al., 2011. **Next-generation sequencing reveals HIV-1-mediated suppression of T cell activation and RNA processing and regulation of noncoding RNA expression in a CD4+ T cell line.** _mBio_, 2(5). PMID: [21933919](https://pubmed.ncbi.nlm.nih.gov/21933919/)

GEO: GSE38006

SRA: SRP013224

Description:

Poly-A RNA-seq of SUP-T1 infected with HIV-1 (LAI). 4 samples in total from two time points after infection 12 and 24 hpi; Samples were either Mock infected (12: 3 rep; 24: 2 reps) or HIV-1 infected (12: 3 reps; 24: 3 reps).

Comments:

________________________________________

### Sherrill-Mix dataset
Sherrill-Mix, S., Ocwieja, K.E. & Bushman, F.D., 2015. **Gene activity in primary T cells infected with HIV89.6: intron retention and induction of genomic repeats.** _Retrovirology_, 12(1), p.79. PMID: [26377088](https://pubmed.ncbi.nlm.nih.gov/26377088/)

SRA: SRP055981

SRA: SRP057555 (integration site data)

Description:

Primary human T cells from a **single human donor** were infected with the low passage HIV isolate HIV89.6 ( 3 reps HIV infected and 2 mock infected)

Comments:

HIV integration site is available

________________________________________

### Langer dataset
Langer S, Hammer C, Hopfensperger K, Klein L et al., 2019. **HIV-1 Vpu is a potent transcriptional suppressor of NF-κB-elicited antiviral immune responses.** _Elife_, 8. PMID: [30717826](https://pubmed.ncbi.nlm.nih.gov/30717826/)

Srinivasachar Badarinarayan S, Shcherbakova I, Langer S, Koepke L et al., 2020. **HIV-1 infection activates endogenous retroviral promoters regulating antiviral gene expression.** _Nucleic Acids Res_, 48(19):10890-10908. PMID: [33021676](https://pubmed.ncbi.nlm.nih.gov/33021676/)

GEO: GSE117655

SRA: SRP155217

Description:

3 different viral isolets (CH293 [clade C], CH077 [clade B] and STCO1 [clade B]), and each viral isolet with three VPU mutation + WT (VPU-; NFKB def.; Tehterin def.)

CD4+ T cells from 4 donors (2 male and 2 female) were infected with each viral isolet WT and VPU mutation + Mock (52 samples in total)

Comments:

Despite the samples look great with an interesting experimental design, not many results from HERVs can be pulled out. I might have missed to ask important questions to the data.

________________________________________

### Jones dataset

Description:

This samples are "superinfections" (reinfections of HIV+ donors). All samples were polyA enriched. Infected samples were sorted for GAG (???), therefore HIV is being translated in all cells from HIV+ samples.

|  | Donor | HIV_STRAIN | STARTING_CD4_T_CELL |
|---------|--------------|---------------------|---------------------|
| Sample2 | OM5267 (II) | JRCSF | memory CD4+ |
| Sample3 | OM5267 (II) | JRCSF | naive CD4+ |
| Sample4 | OM5011 (III) | OM5011   autologous | naive CD4+ |
| Sample5 | OM5267 (II) | JRCSF | total CD4+ |

Each sample has two replicates plus two Mock infection. (16 RNA-seq libraries)

Comments:

Luis has presented the data in a BELIVE meeting.

________________________________________

### Miguel dataset

Description:

This data was generated for detection and quantification of circRNAs, therefore total RNA-seq. CD4+ (???) cells from 4 different healthy donors were infected with HIV and Mock, samples were collected at two time points 12 and 24 hpi. (16 RNA-seq libraries)

Comments:

The samples were run in two batches, the quality of the first one is not as good as the second one. One sample of the first batch has DNA contamination. Additionally the first run used a high-output kit and the second one a mid-output one.


________________________________________

### Shytaj dataset (EMBO paper)
Shytaj, Iart Luca et al., 2020. **Alterations of redox and iron metabolism accompany the development of HIV latency.** _The EMBO journal_, vol. 39,9  PMID: [32157726](https://pubmed.ncbi.nlm.nih.gov/32157726/)

GEO: GSE127468

SRA: SRP187079

Description:

CD4+ T cells from 3 different donors were infected with HIV‐1NL4‐3 or Mock and samples were collected at 4 different timepoints (3,7,9,14 days post infection) (24 samples in total). It is important to mention that on day 5 after infectio ART (three‐drug) was initiated to achieve a latent state at day 14.

Comments:

________________________________________

### White dataset (Bosque)
White, Cory H et al. 2016. **Transcriptomic Analysis Implicates the p53 Signaling Pathway in the Establishment of HIV-1 Latency in Central Memory CD4 T Cells in an In Vitro Model.** _PLoS pathogens_ PMID: [27898737](https://pubmed.ncbi.nlm.nih.gov/27898737/)

GEO: GSE81810

SRA: SRP075608

Description:

The dataset consisted of four conditions (LI: latently; UI: uninfected; LIA: latently reactivated; UIA: uninfected reactivated) from four healthy donors.

Comments:

Analyzing the samples I found that the donors were 3 woman and 1 men. Transposable Element analysis was already submitted in Miguel's latency paper.

________________________________________

### Miguel and Talia

Description:

CD4+ T cells from HIV+ donors (4) were reactivated with anti-CD3 and anti-CD28 in the presence of ART (total 8 samples)

Comments:

The analysis of these samples is already submitted in Miguel's latency paper

________________________________________

### Dobrowolski dataset (QUECEL)
Dobrowolski, Curtis et al. 2019. **Entry of Polarized Effector Cells into Quiescence Forces HIV Latency.** _mBio_ vol. 10,2 e00337-19. PMID: [30914509](https://pubmed.ncbi.nlm.nih.gov/30914509/)

SRA: SRP145508

Description:

Samples come from an ex vivo method, called QUECEL (quiescent effector cell latency), that mimics this process efficiently and allows production of large numbers of latently infected CD4+ T cells. Naïve CD4+ T cells were polarized into the four major T cell subsets (Th1, Th2, Th17, and Treg) and subsequently infected with a single-round reporter virus which expressed GFP/CD8a.  The infected cells were purified and coerced into quiescence producing a homogeneous population of latently infected cells. This method is a refinement of the model of Bosque and Planelles. After achieving latency state cells were reactivated with TCR. 4 different conditions were sequenced; uninfected, expanding, quiescent and reactivated for each T cell subset.

| Polarized Cells | State | Reps |
|:-:|:-:|:-:|
| Th17 | Mock | 1 |
| Th17 | Expanding | 2 |
| Th17 | Quiescent | 2 |
| Th17 | Reactivated | 2 |
| Th1 | Mock | 1 |
| Th1 | Expanding | 1 |
| Th1 | Quiescent | 1 |
| Th1 | Reactivated | 1 |
| Th2 | Mock | 1 |
| Th2 | Expanding | 1 |
| Th2 | Quiescent | 1 |
| Th2 | Reactivated | 1 |
| Treg | Mock | 1 |
| Treg | Expanding | 1 |
| Treg | Quiescent | 5 |
| Treg | Reactivated | 1 |

Comments:

________________________________________

### Jiang dataset (Nature Controllers)
Jiang, Chenyang et al. 2020. **Distinct viral reservoirs in individuals with spontaneous control of HIV-1.** _Nature_ vol. 585,7824: 261-267. PMID: [32848246](https://pubmed.ncbi.nlm.nih.gov/32848246/)

GEO: GSE144334

SRA: SRP245436

Description:

Different CD4+ T cells subsets from ART donors(3) and elite controllers (12). The subset collection comprise central memory (CM), effector memory (EM), naive (N),  effector memory T cells re-expresses CD45RA (TEMRA) and total CD4+ cells. (75 samples in total)

Comments:

________________________________________

### Boritz dataset (Douek Controllers)
Boritz, Eli A et al. 2016. **Multiple Origins of Virus Persistence during Natural Control of HIV Infection.** _Cell_ vol. 166,4: 1004-1015. PMID: [27453467](https://pubmed.ncbi.nlm.nih.gov/27453467/)

GEO: GSE83482

SRA: SRP076719

Description:

83 samples, all from elite controllers, from 14 donors (1 has two timepints 2010 and 2015) from either PBMC (60) or LympNode (22) divided in CD4+ T cells subtypes. Naive, central memory, effector memory,transitional memory subset were selected and sequenced from PBMC from the 14 donors and naive, Tfh, from germinal center and from non germinal center, effector memory and with different levels of CMPD1

Comments:

________________________________________
