# Welcome to the OHSU NLP/Grammar Rules Hackathon

Feel free to update this README as you make changes so that others can follow along.

## Intro slides to linguistics
See files linguistics_intro-1.pptx and linguistics_intro-2.pptx for the slides presented by Dane on Thursday morning.

## Odin

Dane has recommended that we clone his odin-examples repository: https://github.com/clulab/odin-examples

This can be accomplished in the command line as follows:

`git clone https://github.com/clulab/odin-examples.git`

Please also check to be sure that you have sbt and Java 8 installed.

Gus has provided an Odin tutorial here: https://github.com/myedibleenso/odin-tutorial

To use the ipython notebook in this tutorial, be sure that you have jupyter installed and then install Gus' py-processors:

`pip install git+https://github.com/myedibleenso/py-processors.git`

Then clone the tutorial:
`git clone https://github.com/myedibleenso/odin-tutorial`

And type this in the command line: `jupyter notebook odin-tutorial.ipynb` to open the notebook in your browser.



## Files in sentences_and_abstracts
| Filename        | Description   |
|:--------------- |:------------- |
| BCC_PTTB_Sentences.txt | 1st line of each block was written by a researcher in preparation for a discussion with clinicians (starts with '@'). 2nd is citation (starts with '>'). 3rd is (possible) original source (starts with '$'). |
| CIViC_abstracts.zip | Contains >1000 abstracts scraped from CIViC. Each saved under its PubMed ID number. |
| CIViC_summaries.txt | "Nightly summary" of evidence used by CIViC. |
| g2p-SNAPSHOT-O5-17-2017.tsv | A collection of evidence used by the Genotype to Phenotype Knowledgebase tool developed by OHSU's Brian Walsh. The knowledgebase connects genomic markers to phenotypes (i.e. drug sensitivity) by querying reputable databases including OncoKB, CIViC, PMKB, JAX, and MolecularMatch. |
| G2P_interesting_sentences.txt | 51 sentences taken from g2p-SNAPSHOT file listed above. 1 sentence per line. All in this file are from CIViC (the other databases exhibited strict homogeneity of format--not ideal for our purposes) |
| modification-to-activity.txt | Ozgun's sentences for protein modification to function inference. |
