---
layout: page
title: Software
---

See my [github](http://github.com/kbroman) page.  The R packages below are available through [CRAN](http://cran.r-project.org) or [github](http://github.com/kbroman).

---

### <a name="qtl"></a>[R/qtl](http://www.rqtl.org)

A package, composed of tools for analyzing QTL experiments, for
use with [R](http://www.r-project.org/)
(aka Gnu S), an open-source implementation of the S language.

To receive announcements about updates to R/qtl, join the
Google group, [R/qtl announcements](http://groups.google.com/group/Rqtl-announce).

To participate in discussion about the use of R/qtl, join the
Google group, [R/qtl discussion](http://groups.google.com/group/Rqtl-disc)

---

### <a name="qtlcharts"></a>[R/qtlcharts](http://github.com/kbroman/qtlcharts)

An [R](http://www.r-project.org) package for [D3](http://d3js.org)-based interactive QTL graphics.


---

### <a name="D3"></a>[D3 examples](https://www.biostat.wisc.edu/~kbroman/D3/)
    
Various examples of [D3](http://d3js.org)-based interactive graphs.

---

### <a name="broman"></a>[R/broman](http://github.com/kbroman/broman)

Various R functions that I find useful.

---

### <a name="xoi"></a>[R/xoi](http://github.com/kbroman/xoi)

Software for the analysis of crossover interference in
experimental crosses, particularly regarding the gamma model.

---

### <a name="lineup"></a>[R/lineup](http://github.com/kbroman/lineup)

Software for detecting and correcting sample mix-ups between two sets of measurements, such as between gene expression data on two tissues.

---

### <a name="ricalc"></a>[R/ricalc](http://github.com/kbroman/ricalc)

Software for calculation of two- and three-locus probabilities in
multiple-strain recombinant inbred lines, and the simulation of such lines.
See the related paper: Broman KW (2005) The genomes of
recombinant inbred lines.  [Genetics](http://www.genetics.org/) 169:1133-1146
\[[PubMed](http://www.ncbi.nlm.nih.gov/pubmed/15545647) | [pdf (525k)](http://www.biostat.wisc.edu/kbroman/~publications/rigenome.pdf)\]


---

### <a name="negenes"></a>[R/negenes](http://github.com/kbroman/negenes)

Software for estimating the number of essential genes in a genome
on the basis of data from a random transposon mutagenesis experiment.
See the related [technical report](https://www.biostat.wisc.edu/~kbroman/publications/ms0220.pdf).


---

### <a name="npem"></a>[R/npem](http://github.com/kbroman/npem)

Software for analyzing cell proliferation assays using the
normal-Poisson mixture model described by Broman et al.
([J Immunol Meth 198:119-132, 1996](http://www.ncbi.nlm.nih.gov/pubmed/8946008)).

---

### <a name="fingers"></a>[R/fingers](http://github.com/kbroman/fingers)

Software for the inference of full sibling families with data on
dominant genetic markers (such as RAPDs), following the hierarchicical
clustering approach of Apostol et al. (1993) Theor Appl Genet
86:991-1000.  The title follows from Fortran software written by WC
Black IV.

---

### <a name="geesibsor"></a>[R/geesibsor](http://github.com/kbroman/geesibsor)

Software for estimating the odds ratio for siblings for a binary
phenotype, adjusting for covariates, using generalized estimating equations.

---

### <a name="qtlsim"></a>[R/qtlsim](http://github.com/kbroman/qtlsim)

Software for testing, by computer simulation, various approaches
to mapping QTLs in a backcross experiment.  This was written for the
manuscript Broman and Speed (2002) [A model
selection approach for the identication of quantitative trait loci in
experimental crosses](http://www.biostat.wisc.edu/~kbroman/publications/index.html#rss). J Roy Stat Soc B
64:641-656.  Also see the [R/qtl
package](http://www.rqtl.org).

---

### <a name="relcheck"></a>RelCheck
Version 0.67 (24 August 2000)
Software for verifying relationships between all pairs of
individuals in a linkage study, using the approach of Boehnke and Cox
([Am
J Hum Genet, 61:423-429, 1997](http://www.ncbi.nlm.nih.gov/pubmed/9311748)), with the modification described by
Broman and Weber ([Am
J Hum Genet 63:1563-1564, 1998](http://www.ncbi.nlm.nih.gov/pubmed/9792888)), to allow for the presence of
genotyping errors.  We look only at the relationships MZ twins,
parent/offspring, fullsibs, halfsibs and unrelated.

**Note**: I am no longer actively developing this software. You may wish to check out Mary Sara McPeek and Lei
Sun's program [PREST](http://galton.uchicago.edu/~mcpeek/software/prest/).  It has a similar aim, and calculates a
more extensive set of statistics, includes measures of statistical
significance, and also looks at avuncular and first cousin
relationships.  Other alternatives include the programs Borel,
Relpair, Relative, Reltype and Siberror.  Go to the 
[Rockefeller software list](http://www.jurgott.org/linkage/ListSoftware.html)
to find these programs.

The input/output for my program is rather crude.  If you use the
software, please reference the above papers in any publications.

A perl script for converting data from linkage format to that used by
RelCheck is included with the software.

Download:
[source](http://www.biostat.wisc.edu/software/relcheck/relcheck_0.67.tar.gz) | [windows](http://www.biostat.wisc.edu/software/relcheck/relcheck_0.67.zip)

Sample data \[[tar.gz](http://www.biostat.wisc.edu/software/relcheck/sampledata.tar.gz) |
[zip](http://www.biostat.wisc.edu/software/relcheck/sampledata.zip)\]
README file: \[[README.txt](http://www.biostat.wisc.edu/software/relcheck/README.txt)\]
List of updates to the software: \[[CHANGES.txt](http://www.biostat.wisc.edu/software/relcheck/CHANGES.txt)\]

---

### <a name="f2"></a>f2

Version 0.50 (7 Feb 2000)

Software for QTL analysis of an F2 intercross experiment,
including forward selection for multiple QTLs, all pairs of loci, and
pairwise interactions.

**Note**: This is very preliminary, the input and output
are not well documented, and I'm no longer actively developing this software.  Look at [R/qtl](http://www.rqtl.org), instead.

Download: [source](http://www.biostat.wisc.edu/software/f2/f2_0.50.tar.gz) | [windows](http://www.biostat.wisc.edu/software/f2/f2_0.50.zip)

Sample data \[[tar.gz](http://www.biostat.wisc.edu/software/f2/example.tar.gz) | [zip](http://www.biostat.wisc.edu/software/f2/example.zip)\]