# CRISPRseekGUIDEseqBioc2020Workshop

<b>CRISPRseek for design target-specific gRNAs for the CRISPR genome editing system including base editor and prime editor </b>

Lihua Julie Zhu

Department of Molecular, Cell and Cancer Biology, Program in Molecular Medicine, Program in Bioinformatics and Integrative Biology, Worcester, MA, 01655, USA.

Julie.Zhu@umassmed.edu

<br>Note: this workshop will be followed with [motif analysis with motifStack and dagLogo workshop](https://github.com/jianhong/Bioc2020workshop).

<b>Workshop Description</b>

In this workshop, participants will not only gain the theoretical understanding of the principles of CRISPR genome editing system and gRNA design, but they will also obtain hands-on experience on designing gRNAs with high specificity and efficacy using CRISPRseek package, and identifying genome-wide offtargets with GUIDE-seq data using GUIDE-seq package. I will provide a brief introduction to CRISPR genome editing system and guiding principles of gRNA design. Then, I will give a demo to perform gRNA design for various scenarios using the CRISPRseek package and GUIDE-seq data analysis using GUIDE-seq package. Participants will have the opportunity to design gRNAs for the sequences of their interests and analyze their own GUIDE-seq data. Detailed notes and R code are provided for reproducibility and follow-up exploration. 

<b>Expectation</b>

After this workshop, participants should be able to apply the learned skills to design gRNAs and analyze GUIDE-seq data for various variants of CRISPR Cas system such as spCas9 and cpf1. In addition, they will learn how to apply different efficacy and offtarget scoring methods to meet their needs. Furthermore, they will learn how to design gRNAs for the base editor and prime editor systems.

<b>Prerequisites</b>

<p>Participants are expected to have basic knowledge as follows:</p>
<p>•	Basic knowledge of R syntax</p>
<p>•	Some familiarity with the OrgDb, BSgenome, and TxDb classes</p>

Basic understanding on how CRISPR genome editing works is helpful but not required.

<p>Please refer to the following resource for gRNA design using CRISPRseek.</p>

<ul><li>Zhu LJ, Holmes BR, Aronin N, Brodsky MH (2014). “CRISPRseek: A Bioconductor Package to Identify Target-Specific Guide RNAs for CRISPR-Cas9 Genome-Editing Systems.” PLoS one, 9(9).http://www.ncbi.nlm.nih.gov/pmc/articles/PMC4172692/. </li>

<li>Zhu LJ (2015). “Overview of guide RNA design tools for CRISPR-Cas9 genome editing technology.”Front. Biol., 10(4).</li></ul>

<b>Workshop Participation</b>

<p>Participants are expected to have basic knowledge about R and several R packages as described above in advance. To follow along the hands-on session, I recommend participants bring your own laptop with the following computing tools installed.
<ul><li>R (version > 4.0; https://cran.r-project.org/)</li>
<li>the CRISPRseek package along its dependencies</li>
<li>if (!requireNamespace("BiocManager", quietly = TRUE))</li>
<li>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;	    install.packages("BiocManager")</li>
<li>BiocManager::install("CRISPRseek")</li></ul>

<b>R/Bioconductor packages used</b>

<p>The following R/Bioconductor packages will be explicitly used:<p>
<p>• library(CRISPRseek)</p>
<p>• library(org.Hs.eg.db)</p>
<p>• library(BSgenome.Hsapiens.UCSC.hg19)</p>
<p>• library(TxDb.Hsapiens.UCSC.hg19.knownGene)</p>

<b>Time outline</b>
<table><th>Activity</th><th>Time</th>
  <tr><td>Introduction to CRISPR genome editing system and gRNA design</td><td>5 m</td></tr>
<tr><td>gRNA design using CRISPRseek</td><td> 15 m</td></tr>
  <tr><td>Introduction to GUIDE-seq technology and GUIDEseq pacakge </td><td>5m</td></tr>
  <tr><td>Hands on experience with GUIDEseq</td><td>5m</td></tr>
</table>
<b>Workshop goals and objectives</b>

<b>Learning goals</b>
<ul>
  <li>	Understand how CRISPR genome editing works </li>
<li>	Understand the guiding principle of gRNA design</li>
<li>	Learn how to perform gRNA design using CRISPRseek</li>
<li>	Learn how to select the best gRNAs for given input sequences</li>
  <li>	Learn how to analyze GUIDE-seq data</li>
</ul>
<b>Learning objectives</b>
•	By the end of the workshop, participants will be able to design gRNAs for given input sequences with high efficacy and low offtarget effects for various variants of CRISPR genome editing systems such as the recently developed prime editor and base editor systems. In addition, the participants will be able to analyze their own GUIDE-seq data.
