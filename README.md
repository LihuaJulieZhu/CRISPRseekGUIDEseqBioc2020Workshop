# CRISPRseekGUIDEseqBioc2020Workshop

<b>CRISPRseek for design target-specific gRNAs for the CRISPR genome editing system including base editor and prime editor </b>

Lihua Julie Zhu

Department of Molecular, Cell and Cancer Biology, Program in Molecular Medicine, Program in Bioinformatics and Integrative Biology, Worcester, MA, 01655, USA.

Julie.Zhu@umassmed.edu

<b>Workshop Description</b>

In this workshop, participants will not only gain the theoretical understanding of the principles of CRISPR genome editing system and gRNA design, but they will also obtain hands-on experience on designing gRNAs with high specificity and efficacy using CRISPRseek package. I will provide a brief introduction to CRISPR genome editing system and guiding principles of gRNA design. Then, I will give a demo to perform gRNA design for various scenarios using the CRISPRseek package. Participants will have the opportunity to design gRNAs for the sequences of their interests. Detailed notes and R code are provided for reproducibility and follow-up exploration. 

<b>Expectation</b>

After this workshop, participants should be able to apply the learned skills to design gRNAs for various variants of CRISPR Cas system such as spCas9 and cpf1 in paired or unpaired configuration. In addition, they will learn how to apply different efficacy and offtarget scoring methods to meet their needs. Furthermore, they will learn how to design gRNAs for the base editor and prime editor systems.

<b>Prerequisites</b>

<p>Participants are expected to have basic knowledge as follows:</p>
<p>•	Basic knowledge of R syntax</p>
<p>•	Some familiarity with the OrgDb, BSgenome, TxDb classes</p>

Basic understanding on how CRISPR genome editing works is helpful but not required.

<p>Please refer to the following resource for gRNA design using CRISPRseek.</p>
Zhu LJ, Holmes BR, Aronin N, Brodsky MH (2014). “CRISPRseek: A Bioconductor Package to Identify Target-Specific Guide RNAs for CRISPR-Cas9 Genome-Editing Systems.” PLoS one, 9(9).http://www.ncbi.nlm.nih.gov/pmc/articles/PMC4172692/. 

Zhu LJ (2015). “Overview of guide RNA design tools for CRISPR-Cas9 genome editing technology.”Front. Biol., 10(4).

<b>Workshop Participation</b>

<p>Participants are expected to have basic knowledge about R and several R packages as described above in advance. To follow along the hands-on session, we recommend participants bring your own laptop with the following computing tools installed.
<p>•R (version > 4.0; https://cran.r-project.org/)</p>
<p>•	the CRISPRseek package along its dependencies</p>
<p>	if (!requireNamespace("BiocManager", quietly = TRUE))</p>
<p>	    install.packages("BiocManager")</p>
<p>BiocManager::install("CRISPRseek")</p>

<b>R/Bioconductor packages used</b>

<p>The following R/Bioconductor packages will be explicitly used:<p>
<p>• library(CRISPRseek)</p>
<p>• library(org.Hs.eg.db)</p>
<p>• library(BSgenome.Hsapiens.UCSC.hg19)</p>
<p>• library(TxDb.Hsapiens.UCSC.hg19.knownGene)</p>

<b>Time outline</b>
<p>Activity	Time</p>
Introduction to CRISPR genome editing system and gRNA design	10 m
gRNA design using CRISPRseek	10 m
Hands on experience with CRISPRseek	10m

<b>Workshop goals and objectives</b>

<b>Learning goals</b>
<ul>
  <li>•	Understand how CRISPR genome editing works </li>
•	Understand the guiding principle of gRNA design
•	Learn how to perform gRNA design using CRISPRseek
•	Learn how to select the best gRNAs for given input sequences
</ul>
<b>Learning objectives</b>
•	By the end of the workshop, participants will be able to design gRNAs for given input sequences with high efficacy and low offtarget effects for various variants of CRISPR genome editing systems such as the recently developed prime editor and base editor systems.
