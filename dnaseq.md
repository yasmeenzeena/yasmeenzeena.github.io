## DNA Sequencing

### How do we learn about DNA

A genomic library is a collection of clones where each clone carries a different
fragment of the genome. cDNA libraries vs genomic libraries:
genomic = entire genome has been cloned <br/>
cDNA = mRNA strands have been cloned and then converted back into DNA via
revere transcriptase [complimentary DNA, contains only exons no introns as
they have been spliced out in post-transcriptoinal modification]<br/>

![library](https://www.mun.ca/biology/desmid/brian/BIOL2060/BIOL2060-20/20_28.jpg)

### How to make cDNA
1. separate mRNA from the other RNA types in the cell (rRNA/tRNA)
  + all eukaryotic mRNA have a poly A tail -> once the introns are spliced out
  in the post transcription stage the poly A tail is added to the mRNA strand

  + use "oligo dT chromatography" aka affinity chromatography-> use a
  matrix with strings of thymines attached which will hydrogen bond to the
  polyAdenine tail. In high salt the binding process is more efficient; eulte
  the mRNA off of the column by removing the salt to break the hydrogen
  bonds

![oligot](http://nptel.ac.in/courses/102103013/module4/lec3/images/2.png)

2. synthesis of double stranded cDNA
  + add a primer onto the polyA tail as reverse transcriptase needs a primer
  to work! primer = TTTTTT; hydrogen bonds up to the polyA tail
  + copy the mRNa into cDNA via reverse transcriptase
  + use ribonuclease hybrid to break the phosphodiester linkages in the
  mRNA strand (ribonuclease H: cleaves ONLY the RNA strand of an
  RNA:DNA duplex)
  + mRNA strand is broken up & can be replaced with DNA via DNA
  polymerase, which is able to transcribe in the 5'->3' direction

3. clone cDNA into vectors & transform into a host cell

### Fragmenting the human genome

Methodology was to fragment the entire genome and put it back together,
relying on "contigs" => overlapping fragments [achieved by running a partial
digest of an enzyme but shortening the time, so not all the restriction sites are
cleaved & overlapping DNA sections occur.]

Use a Bacterial Artificial Chromosome which has an insert size of ~100,000bp:
1. White blood cells are mixed with agarose and placed in a mould
  + white blood cells = human DNA source
2. Cell wall is ruptured in the gel
3. Restriction enzyme is added to the mould to digest the DNA
  + enzyme digest is done in the well so that there is no possibility of
mechanical shearing
4. Each mould is placed in a well of a agarose gel
5. Gel is run & viewed under UV light -> cut out DNA fragment bands
6. Elute DNA from agarose
7. Ligate the fragments to BAC vector with the same restriction enzyme
8. Treat with DNA ligase
9. Transform the vectors into host cells (bacteria)
10. Transformed bacteria are placed onto 384 well plates in their exact size
order (gives sequence of clones)
11. Bacterial DNA isolated for sequencing reactions

BAC have ~100,000bp so sequence the ENDS of each fragment and use a
computer to match up the overlaps. Enzymes cannot sequence 100,000bp at once so each fragment is further
digested and those ends are sequenced. Contigs are linked by sequencing the ends of large DNA fragments

### Libraries and vectors for the human genome project

Used the shotgun approach to sequence the human genome (a method used
for sequencing long DNA strands): "The first phase, called the shotgunphase,
divided human chromosomes into DNA segments of anappropriate size, which
were then further subdivided into smaller, overlappingDNA fragments that were
sequenced. The Human Genome Project relied upon thephysical map of the
human genome established earlier, which served as aplatform for generating
and analyzing the massive amounts of DNA sequence datathat emerged from
the shotgun phase."

### Dideoxysequencing – Sanger method

use ddATP/ddTTP/ddGTP/ddCTP nucleotides: they lack an OH at the C3 position
and cannot make a phosphodiester bond -> the polypeptide sequence ends if a
ddNTP is included

**Run four test tubes with:**
+ a radioactive primer to let the DNA polymerase bind (known sequence)
+ a template strand of DNA to which the primer is added
+ NTPs
+ one of the four dideoxy sugars
e.g. in the ddATP tube, each time adenine needs to be added to the chain there
is 50% chance ddATP will be added not dATP and strand termination will
happen.

Run out the four tubes on a polyacridimine gel with a VERY FINE resolution so
that you can tell between each base pair -> can read off the order of the bases
via the gel.

**Florescent Sanger markers:** Sanger sequencing but each ddNTP carries a
different coloured fluorescent tag: all four reactions occur in one capillary tube
and the fluorescent peaks that occur each time a ddNTP binds and terminates a
chain are recorded to give a sequence trace.

Can use to detect genetic mutations: homozygous at a single location will give
only the peak for that nucleotide, but heterozygous locations will have two
smaller waves on top of each other to show that both nucleotides are present.

[Sanger Sequencing](https://www.youtube.com/watch?v=vK-HlMaitnE&t=8s)
