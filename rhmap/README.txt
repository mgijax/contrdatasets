RH Mapping Panel README
April 2004


The RH Mapping Panel data spreadsheet (or tab-delimited text file) summarizes how the information on RH panel are represented in MGI. It provides the information on a mapped locus as well as the gene with which a sequence used to map the RH locus is biologically associated (i.e., which gene the sequence is a transcriptional product of). Sequences used to design probes for RH mapping were sometimes mapped to a locus in the mouse genome that did not correspond to the structural gene that the sequence represented. In MGI sequences are associated directly with a gene only if they are the transcriptional or translational product of that gene.

The T31 RH Mapping Panel for the Laboratory Mouse can be found at:
http://www.jax.org/resources/documents/cmdata/rhmap/

The representation of the RH Mapping Panel in MGI (http://www.informatics.jax.org) can be found by an Accession ID Query for J:68900.


RH Panel Data:

1. RH Panel Chr - the chromosome of the RH mapped locus
2. RH Panel Locus - the name of the locus on the RH map; the same name with different suffixes can appear multiple times if multiple groups mapped the same locus
3. RH Panel Locus Alias - alternate locus name, sometime the name of the gene if the RH mapped locus can be associated with a specific gene
4. mRNA Seq Acc ID - the accession id of the sequence used to design the probes in the RH mapping experiment. The accession ids were retrieved from either locus or alias by removing any suffix, such as *, -1, -2, a, b. 

RH Locus Representation in MGI:

5. MapMGIAcc - the accession id of the locus that represents the RH mapped locus in MGI
6. MapMGISymbol - the current, official symbol of the RH mapped locus
7. MapMGIChr - the chromosome of the RH mapped locus

Association of mRNA Sequence Accession ID to Genes in MGI:

8. SeqMGIAcc - the accession id of the locus with which the sequence in column 4 is associated as a transcription product
9. SeqMGISymbol - the current, official symbol of the gene in MGI with which the sequence is associated
10. SeqMGIChr - the chromosome location of the gene with which the sequence in column 4 is associated
