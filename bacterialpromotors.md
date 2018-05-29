## L8: Bacterial gene control

Aims of this lecture:
+ The bacterial operon:
    1. Positive and negative regulation of the lactose operon
    2. Regulation of the tryptophan operon by a repressor protein and by
the process of attenuation.
    3. Two-component regulatory systems – phosphate concentration
and gene regulation.
    4. Quorum sensing and the lux operon – you will PROBABLY not find
this information in most textbooks. The notes given should suffice.
    5. The ribosomal and transfer RNA operons of E. coli

## Positive and negative regulation of the lactose operon

Housekeeping proteins are always present in the cell in a constant concentration, but
other proteins are linked to nutrient amounts in the environment.

Genes coding for proteins involved in same metabolic pathway are clustered into an
OPERON! Therefore a cluster of genes can make one long mRNA which is later split up
into the individual proteins its codes for "polycistronic mRNA."

![polycistronic](http://bio1510.biology.gatech.edu/wp-content/uploads/2012/11/coupled-transcription-translation.jpg)

The polycistronic mRNA will have a number of AUGs (methoinine = start codon) and
UGAs (stop codon) to indicate where each polypeptide begins and ends in the RNA.
When the mRNA is being translated the ribosome will bind to AUG, translate til UGA and
unbind. This will occur for each polypeptide in the RNA sequence.

Genes are only transcribed when needed!
>inducible operons = must be turned on <br/>
>repressible operons = must be turned off

# Lac Operon
Inducible operon = usually occur in a catabolic pathway (i.e. breakdown) e.g. sugar
breakdown, lac operon. Activated by a sugar molecule!

+ glucose (breaks the β- galactoside linkage)
+ Lactose: inducer, sugar that binds preferentially to the promoter so that the LacI
+ repressor cannot bind. Its actually allolactose that binds, an isomer of lactose
(made by the low levels of β- galactosidase that are always in the cell!)
+ Glucose: sugar that is metabolised preferentially to lactose via *catabolite repression*: glucose is phosphorylised over adenylyl cyclase, enzyme
inactive so cAMP cannot be made to activate CAP, no CAp = down
transcription of genes as RNA poly binding is weak
+ RNA polymerase: transcribes the Z, Y & A genes, cannot bind if the LacI repressor
protein is bound to the promoter/operator region first. Needs the help of the
catabolite activator protein (CAP) to bind.
+ LacI: makes the repressor protein, as its own promoter so is continuously
expressed.
+ LacZ: β- galactosidase
+ LacY: lactose permease (moves lactose into the cell)
+ LacA: thiogalactoside transacetylase (helps remove toxic metabolites e.g.
thiogalactosides, which are transported out of cell by lac Y protein)

If the operon is repressed, the LacI gene produces its repressor protein which binds to the
operator (which overlaps with the promoter) and stops the RNA polymerase enzyme
transcribing the LacZ, Y and A genes. The operator region is a negative regulatory site
as it stops transcription. The RNA polymerase has a weak affinity to the DNA because the
lac promoter is weak, and so needs the help of the catabolite activator protein (CAP) to
bind.

![lacoperon](data:image/png;base64,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)

The lac operator sequence of
the O1 (primary operator) is a
near perfect inverted repeat,
i.e. there are two half sites on
either side with the repeat. One
molecule of repressor protein
can bind to each half site = 2
repressor molecules bound at
O1. There is also an auxiliary
operator upstream of the O1
before the promotor which can
also bind two repressor
proteins. The four repressor
proteins are arranged in a
tetramer, which forces the DNA strands to curve around the tetramer to allow binding to
O1 and O3. There is another operator sequence much further downstream that has also
been shown to form a loop with the primary O1.

![o123](http://jb.asm.org/content/191/16/5301/F1.large.jpg)

__If lactose is present the operon is
activated!__ An isomer of lactose,
allolactose, binds to the
repressor protein and causes a
conformational shift which
results in the repressor
dissociating from the
operator region.

**The lac operon is usually turned OFF** i.e. negative control as the bacteria prefer to use
glucose over lactose: if glucose is present the lac operon transcription is inhibited
[glucose metabolism doesn't need new proteins whilst lactose metabolism requires Z and
Y and A so transcription and translation needed: energy conserved.]

**Glucose inhibits the lac operon**, so that if lactose and glucose are both present there is
no transcription of the genes! This is achieved through catabolite repression i.e. a glucose
metabolite inhibits transcription (which proves the glucose metabolism is occurring and
the cell doesn't need lactose.)

When glucose enters the cell the first stage of glycolysis is it converted into glucose-6-
phosphate. Since the glucose is phosphorylated the enzyme adenylyl cyclase is not, so it
remains inactive. This enzyme can also make cAMP by adding a P to ATP, but this
reaction only occurs when glucose is not present. Thus, increase in [glucose] = decrease
in [cAMP].

![adenylylcylase](http://cubocube.com/files/images/opengenetics/chapter12/image5.png)

These cAMP molecules are able to bind to the catabolite activator protein and activate it,
which allows it to bind to DNA. When cAMP is low, less CAP is activated and the RNA
polymerase cannot bind. Thus, high glucose is able to inhibit the lac operon being
transcribed.

The CAP protein increase the affinity of RNA polymerase for the weak lac operon. The
CAP binding to the CAP site on the DNA causes the DNA to bend 90 degrees, which
increases the affinity for RNA polymerase. The CTD (carboxyl terminal domain) of the RNA
polymerase binds to the CAP protein now that the DNA is bent.

> Lactose paradox: how can lactose induce the operon if the lacY gene is needed
to transport lactose into the cell initially? A: The lac repressor is a highly
specific DNA binding protein that binds very tightly to O1 and O2. But no
protein can bind forever. When it dissociates, an mRNA is made and some
permease and some β-galactosidase is synthesized. The repressor quickly rebinds
and transcription is blocked.

>The effect of this "escape" synthesis is that there will always be a few
molecules of permease and a few molecules of β-galactosidase inside the cell.
When the cell encounters lactose in the medium enough can be taken up and
converted to allolactose to induce the operon.
http://sandwalk.blogspot.co.uk/2008/10/lactose-paradox.html

SUMMARY:
1. Lactose present, no glucose:
cAMP binds to CAP, making CAP able to bind DNA
Bound CAP helps RNA polymerase attach to the lac operon promoter
Lactose in cell via lactose permease
Lactose --> allolactose via β-galactosidase
Allolcatose binds to repressor preferentially
RNA polymerase can now transcribe!

2. Only glucose:
High glucose means low cAMP as adenylyl cyclase is involved in the first
stage of glycolysis not cAMP production
Lack of cAMP = no activation of catabolite activator protein, CAP
RNA polymerase cannot bind to the weak promoter
No transcription of Z Y A genes

3. No sugars:
lac operon is not activated
cAMP is high so CAP is activated but
repressor from LacI is bound to the operator site


# Regulation of the tryptophan operon by a repressor protein and by the process of attenuation (repressible operators)
Transcription is turned off when enough of the product is made in a cell. e.e. trp operon,
involved in tryptophan. Transcription of trp is high when [trp] is low, but drops off once
enough is made. The trp operon is expressed (turned "on") when tryptophan levels are
low and repressed (turned "off") when they are high.
https://www.khanacademy.org/science/biology/gene-regulation/gene-regulation-inbacteria/
a/the-trp-operon

![trpnormal](https://ka-perseus-images.s3.amazonaws.com/af4a7fca79841d5578f4fc1352c1ed3afd6252cc.png)

The operon here involves five genes (E to A are structural) with a single promoter and
operator. Between the operator and the first gene is the leader sequence. The leader
encodes a short polypeptide and also contains an attenuator sequence. Overall
regulation happens in two ways: through the attenuator sequence (which is transcribed
into mRNA) or through a repressor binding.

When try is present in high enough quantities the trp repressor binds to the operon and
stops RNA polymerase from transcribing the genes, thus switching off the cell's ability to
make more trp. Here trp is considered a corepressor because it binds to the trp
repressor and activates it, allowing it to bind to the operon.

![trp](https://cdn.kastatic.org/googleusercontent/2yG6GdBT6ER5UaZnURjoV9XjJJtP-wG6zrleIbU1o84-2uARriq931HT8rpYwtltVA1hQLKoJDptZqJ0kTFoC2o)

The trp repressor is encoded by a trp R gene, which is not located in the trp operon & has
it's own promoter. The protein it makes is called a "apo-repressor" aka needs a
corepressor to function.

In low trp concentration, the trp repressor is not activated and will not bind. In this
system, the trp repressor acts as both a sensor and a switch. It senses whether
tryptophan is already present at high levels, and if so, it switches the operon to the "off"
position.

**Attenutation** is another mechanism to stop trp production - it stops the completion of the
mRNA and halts transcription. Once the leader strand is transcribed into mRNA it can be
translated immediately (prokaryote host!) and it makes 2 try residues and the attenuator
sequence.

If trp conc is high the ribosome translates all of leader mRNA region one quickly and
stops at the stop codon in region two. As region two is covered by the ribosome regions
3&4 hydrogen bond together, creating a hairpin loop structure. This is a Ro independant
terminator which results in the dissociation of RNA polymerase. The structural genes
cannot be transcribed now!

![hightrp](https://ka-perseus-images.s3.amazonaws.com/8ca61b144a579573b680ece8b0a2308309097ec1.png)

When trp is low the ribosome binds at methionine but is stopped at the trp
codons and waits for tRNA. This allows region 2 to hydrogen bond to region 3
--> stops 3&4 bonding (4 hasn't been transcribed yet) so no hairpin loop
structure forms. The RNA polymerase is not dissociated and the ribosome
continues along.

![trplow](https://ka-perseus-images.s3.amazonaws.com/8a8dc622739e582c1c1fc32ddfbe2dd1c99d237c.png)

If the leader mRNA sequence is translated quickly, because the tRNA can bring the trp
resides over immediately due to their high intracellular concentration, the ribosome will
not pause at all. . aka Rho independent termination.

+ RNA poly has just made mRNA out of the leader and attenuator strand, is at the
structural genes
+ Ribosome attaches right after and beings to translate the mRNA
+ It reaches the trp codons in the leader mRNA first
+ Low trp levels:
1. tRNA takes a while to bring the trp, ribosome pauses in the middle of region
one
2. this allows regions 2&3 to hydrogen bond together
3. no hairpin loop structure is made
4. once the trp residues are added ribosome continues normally
+ High trp levels:
1. the tRNA brings the trp quickly
2. ribosome only pauses at the stop codon in region 2 of the leader mRNA
3. region two is blocked so region 3 hydrogen bonds to region 4, causing a
hairpin loop structure to form
4. release of RNA polymerase
5. structural genes cannot be transcribed

## Two component regulatory systems - phosphate concentration and gene regulation

Phosphate operon: has a sensor protein (PhoR) and a regulatory protein (PhoB.)

**PhoR** has three domains: periplasmic (binds to the phosphate), transmembrane &
cytoplasmic. When the [phosphate] decreases, the periplasmic domain releases its
phosphate -> conformational change, the histidine on the cytoplasmid domain is
exposed. The histidine is phosphorylated by ATP and the protein is now in its active
sensor form.

Once PhoR has been activated it transfers its phosphate onto the aspartate of **PhoB**, the
regulator protein. Active PhoB can now bind to DNA, increasing the affinity of the RNA
polymerase for various promoters: genes phoA (alkaline phosphatase) phoS (phosphate
binding protein) phoE (porin) & gpB (phosphate transporter.) PhoB binds near the
promoter of each gene involved (~30 overall.) PhoB = transcription factor!

## Quorum sensing and the lux operon

Vibrio fischeri are a bacterium that are able to bioluminesce when in a quorum (i.e. large
numbers.) They often colonise in squid organs and other sea creatures. Each bacterium
makes one molecule of **VAI** (Vibrio fischeri autoinducer) so a quorum will contain many of
these molecules! Molecules are secreted through the cell membrane into the extracellular
environment. VAI eventually diffuses back into cells once a threshold concentration (~10
μg/ml) has been reached. VAI is a transcription factor that increases the RNA polymerase
affinity for the lux promoter. Once RNA polymerase has bound the lux genes are
transcribed. lux I = VAI synthetase, makes more VAI. lux R = produces Lux R protein
which binds to VAI. The luxR-VAI complex can bind to the operator and increase the
RNA polymerase affinity again.

The first few VAI molecules help the RNA polymerase bind and start the lux operon, after
which the main regulatory protein is the luxR-VAI complex = "autoinduction." luxR has its
own promoter and is not part of the lux operon.

Operon:
+ luxI = VAI synthetase
+ luxA&B = code for subunits of enzyme luciferase (this is the one that makes light!)
+ luxC&D&E = code for luciferin (substrate for luciferase)
+ Luciferin is oxidised by luciferase which causes flashes of blue and green light.

![lux](http://2010.igem.org/wiki/images/2/25/Luxoperondiagram.jpg)

## The ribosomal and transfer RNA operons of E. coli
Genes encoding tRNA and rRNA are transcribed by RNA polymerase (note that
in human cells we have a specific subset of RNA polymerase for this task.)
rRNA + tRNA = 98% of cell’s total RNA BUT they are encoded by only 1% of
genome! Whilst mRNA is very unstable and only exists for a few minutes at a
time in the cell tRNA and rRNA are stable throughout generations of cells ->
carried over (very energetically costly to make ribosomes so must stay intact
for a long time.) tRNA and rRNAs are made from short lived precursor
molecules.

tRNA: mature tRNAs (clover leaf structure) have their 5' and 3' flanking regions
removed before they are involved in translation. In bacteria all 3 genes
associated with tRNA production are clustered together into an operon. The
primary transcript of the operon undergoes secondary folding to form a long
primary tRNA molecule, which is cut in three places by ribonucleases: RNase P
specifically. RNaseP digests the phosphodiester bonds, gives three tRNA
molecules which still need their flanking regions removed.

The 5' phosphate flanking region is removed by RNaseP again, an
endonuclease (i.e. cleaves internally, in the middle of the strand.) Precursor
tRNA strand is thus removed. RNaseD removes the 3' OH flanking region and is
an exonuclease: cleaves phopshodiester bonds one at a time until it reaches
the CCA codon (this is the stop codon, all tRNA molecules have this at the
end.)

3 gene operon ---> transcribed into the primary transcript ---> cleaved at three
points by RNaseP ---> must remove flanking regions via RNaseP [5' region]
and RNaseD [3' region, leaves CCA]

rRNA: in bacteria, an "rrn" is a ribosomal RNA operon -> E coli has seven! tRNA
genes may also be included in these rrns. Each operon gives an output of a
"30S RNA primary transcript", which is cut enzymatically to give:
+ 2 tRNA molecules (use RNase D and RNase P to become mature)
+ 16S RNA [small subunit of ribosome]
+ 23S RNA [large subunit of ribosome]
+ 5S RNA [large subunit of ribosome]

All RNA subunits are made in equimolar amounts as they are all transcribed
onto a polycistronic mRNA = rrn efficient way of packaging RNA genes to
ensure that they are all in the right location (together) in the right
concentration (1:1 ratio.) [S= svedborg units (if centrifuged all have specific
sedimentation coefficient.)]

This 30S transcript of rRNA makes a huge stem loop structure with
complimentary on both sides. This structure is cleaved at points by RNase III to
make a functional, mature rRNA.
