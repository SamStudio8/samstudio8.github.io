---
layout: post
title: "Playing Phylogenetic Hide and Seek with Protozoa"
---

Amanda suggested that alongside archaeal, bacterial and fungal associated hydrolases,
we should also look at [**protozoans**](http://en.wikipedia.org/wiki/Protozoa). 
No problem, I'll just get the taxonomy ID for protozoa and extract another database
from UniProtKB [as before]({% post_url 2015-04-24-trembling %}). Simple! Or so I thought...

<p class="message">
The rabbit hole is pretty deep on this one. Feel free to skip my multi-day exploration in to the history of protozoans and their taxonomy and meet me <a href="#uniprot-taxa">on the other side</a>.
</p>

Classification of protozoa appears to be less clear than I had realised. UniProtKB
[lists only three taxonomy entries](http://www.uniprot.org/taxonomy/?query=protozoa&sort=score)
for the term:

* uncultured rumen protozoa
* uncultured Canadian Arcott wether rumen protozoa
* uncultured protist

But none of these are really what I'm looking for. UniProtKB uses these psuedo-species
as a catch-all for environmental samples that don't really fit elsewhere in the database.
but I want a high level [taxonomic rank](http://en.wikipedia.org/wiki/Taxonomic_rank) like a kingdom
that encompasses all of the organisms of interest. So what are the organisms of interest?
In an early introduction to my project, I described the protozoa as:

<blockquote>[...] single celled micro-organisms that feed from their direct surroundings and have the capacity for controlled movement with a tendency to thrive in moist environments [...]</blockquote>

Yet it seems the answer to "What are protozoa?" boils down to who you ask, or rather,
whose interpretation of the taxonomic system you ask.

## A Very Brief and Biased History of Modern Taxonomy
<p class="message">This section is mostly an attempt to condense J.M. Scamardella's 1999 paper: <i>Not plants or animals: a brief history of the origin of Kingdoms Protozoa, Protista and Protoctista</i>. I won't attempt to present a full history and instead summarise the origins surrounding the protozoa. For a full, interesting review I suggest you check it out.</p>

In the 18th century, Carl Linnaeus published works on the biological classification of organisms based
on their structural appearances, establishing the three kingdoms of *Animale* (Animal), *Vegetabile* (Vegetable)
and *Lapideum* (Mineral) which lend themselves to a guessing game of the same name.
Linnaeus' work, particularly on [naming strategies for organisms](http://en.wikipedia.org/wiki/Binomial_nomenclature) served as a foundation to modern taxonomy.

However, the class system set out by Linnaeus was designed for identification rather than heritage.
Following Charles Darwin's revolutionary *On the Origin of Species* a century later in 1859, tree
representations of species sharing common descent became increasingly common
(although his tree diagrams were by no means the first[^1]) and as evolutionary theory
developed and took hold, scientists attempted to group available fossil
records by structual affinity to link ancestry of common species through the ages.
It was here we drew the comparison between contemporary bird species and the dinosaurs.

Meanwhile, micro-organisms exhibiting a variety of characteristics with affinity to both known
plants and animals were confusing the topic of taxonomy further...

### All Hail the Mighty Kingdom of Protista
Before Darwin, in 1820, the first use of **Protozoa** appeared in literature from Georg Goldfuss as
a class for "first, or early animals" inside the established kingdom of *Animalia*. Other scientists
believed that the protozoa were in fact a phylum, or even a kingdom of their own[^3].

Just a few years after Darwin's publication and heavily influenced by evolutionary theory,
in 1866 Ernst Haeckel proposed the addition of a third kingdom[^9], the kingdom of **Protista**.
Not seeing a reason for organisms to be binarily classified as plant or animal, Haeckel hypothesized that
organisms which cannot be classed as plant or animal "without manifest coercion"
must "have evolved independent of the lineages of the animal and plant kingdoms"[^8].

Thus, the kingdom of Protista was proposed to
contain "doubtful organisms of the lowest rank which display no decided affinities nearer to
one side [animals] than to the other [plants]" or organisms possessing "animal and vegetable
characters united and mixed"[^3]. Haeckel proposed this as a "kingdom of primitive forms"
and included the "Monera" (bacteria) as members of this kingdom too.

It's clear how such kingdoms are later described in 21st century literature
as "a grab-bag for all eukaryotes that are not animals, plants or fungi"[^4], these
early classifications appeared to focus on removing contradicting taxa
that were clouding "pure" definitions of what was truly plant and animal and
choosing to conviniently classify difficult organisms on what they are not, as
opposed to what they are[^5]. The term became a dumping ground for
unicellular protozoa that were not quite animals, protophytic algae that were
not quite plants and fungal organisms such as slime molds that appeared to be
somewhat both (it wouldn't be until 1969 that Fungi would get a kingdom of
their own).

After the invention of the first electron microscope in the early 20th century, confusion
was further compounded by the discovery of a distinct cellular nucleus in some
unicellular organisms.

### The Protozoan Identity Crisis
Although Haeckel later refined his model, adding the now familiar term protozoa as a "sub-kingdom"
to his Protista, to represent unicellular animals, another kingdom schema
emerged in 1938. Proposed by Herbert Copeland in *The Kingdoms of Organisms*[^3],
Copeland moved the bacteria and algae out of Haeckel's Protista kingdom to create
a new kingdom: Monera.

Copeland would later re-name his kingdom of Protista to **Protoctista**
("first established beings") -- a term originally coined by John Hogg.
As Haeckel model still persisted, with his Protista kingdom still containing bacteria
Copeland deemed it "unfit" to continue using the same name in his model.
Selecting a new name, Copeland purposefully avoided the term Protozoa due
to both its confusing prior use as a kingdom, class and phylum, but also in
agreeance with a point made in Hogg's 1860 manuscript
*On the Distinctions of a Plant and an Animal and on a Fourth Kingdom of Nature*: 
 that the term "can alone include those that are admitted by all to be animals
 or 'zoa'"[^3]. *i.e.* The term is inappropriate if it is to be applied to non-animals.

### The Rise of Superkingdoms
In the 1960s, microbiologist Roger Stanier propagated an observed "fundamental division of life"
between the "prokaryotes" and "eukaryotes", originally noted decades prior by Edouard Chatton in 1925[^3].

Robert Whittaker published his own five kingdom model in 1969
(a revision of his earlier work where he had in fact returned the bacteria to the
Protista kingdom, it would take a few more years of research before concluding
"this evolutionary divergence in cellular
structure [in bacteria] had to be accounted [for]"[^3]), but placing the kingdom Monera
beneath a new **Superkingdom of Bacteria** (placing all the other kingdoms under
the new **Eukaryotic Superkingdom**) and introducing the kingdom of Fungi; a
wholly distinct kingdom from Plantae. Whittaker maintained that unicellularity was the most
important characteristic for deciding membership of the kingdom of Protista[^3].

Around the same time biologist Lynn Margulis began working on her own schema for organising life.
After several iterations, Margulis relied more on morphologic and structural observations over
Whittaker's strict unicellular criteria and allowed her Protista (later re-named to Protoctista as per
Copeland's model) to contain eukaryotic organisms that were "either unicellular
**or multicellular** that are not plants, animals or fungi"[Emphasis mine][^3].

For those still playing along at home, Whittaker's five-kingdom re-organisation in 1969 left us with this:

| Superkingdom | Kingdom | Description | Examples[^10] |
|--------------|---------|-------------|----------|
| Prokaryota   | Monera  | "Procaryotic cells, lacking nuclear membranes, plastids, mitochondria, and advanced [...] flagella"[^10] | blue-green algae (Cyanophyta), gliding bacteria (Myxobacteriae), "true" bacteria (Eubacteriae)|
| Eukaryota    | Fungi   | Whittaker's kingdom established as a rejection of "the superficial resemblance of fungi to plants"[^3] and the observation that nutrition is derived from environmental absorption[^10] | Slime molds, species demonstrating sporing |
| "            | Protista | "Primarily unicellular or colonial-unicellular organisms [...] with eucaryotic cells"[^10] | Ciliophora, Sarcodina, Sporozoa, Euglenophyta |
| "            | Plantae | "Multicellular organisms with walled and frequently vacuolate eucaryotic cells and with photosynthetic pigments in plastids"[^10] | Algaes (including red and brown, but in different subkingdoms) |
| "            | Animalia | "Multicellular organisms with wall-less eucaryotic cells lacking plastids and photosynthetic pigments. Nutrition primarily ingestive with digestion in an internal cavity"[^10] | Everything else...|

In the early 1980s, John Corliss reviewed the work of both Margulis and Whittaker and tried to solve
the question of cellular complexity by instead counting the number of "differentiated, functional tissues"
an organism exhibits, rather than just the boolean question of whether or not they are unicellular.
Corliss describes plants and animals as having more than one type of tissue, whereas
"protists, while showing multicellularity to varying
degrees in certain groups [...] fail to demonstrate the
organization of cells into two or more clearly differentiated tissues". Though, a criticism
of this model is it "overlooks the fact that multicellular, differentiated organisms are known
in all four eukaryotic kingdoms" such as cyanobacteria[^3].

In 1989, Michael Sleigh, in his second edition of *Protozoa and other Protists* opened the introduction
with:

<blockquote>
The position [regarding the origins of eukaryotes from prokaryotes] is now clearer, and there is much support for the view that eukaryotes are best divided
into four kingdoms: Animalia or multicellular animals [...], Plantae or green land plants [...], Fungi [...]
and Protista, comprising eukaryoute groups formerly classified as algae, protozoa and flagellate fungi.
<br/>
<footer>— Michael Sleigh, <i>Protozoa and other Protists</i> (2nd ed.), 1989.</footer>
</blockquote>

It appears that the scientific community were converging on an agreement that establishment of
another kingdom was necessary. But there were different arguments as to how to organise the members
of each kingdom and what criteria should be applied for classification.

Yet there was even a difference of opinion between Corliss and Copeland with respect to
why a kingdom for protists should exist. Corliss believed that a 
Protista kingdom should exist only if "major uniqueness" can be determined, rather
than classfication based on the absence of functions common in other kingdoms.
Copeland argued that a shared lack of features or function is "not a detriment to
classification as a coherent grouping"[^3].

Confusingly, Corliss advocated usage of the term *protist* to refer to any Protista,
regards of cellularity. Yet the term protist was originally defined by C. Clifford Dobell
in 1911 to specifically refer to Protista demonstrating a "unicellular type
of organization'"[^3]. These sort of disagreements only further cloud my understanding
of what the protozoa actually are.

## A Very-Very Brief Introduction to Current Taxonomy
### Domains and the Sequencing Revolution
With the development of chain-termination DNA sequencing in 1977 by Frederick Sanger, the field
of molecular genetics was born. Taxonomy could now be based on differences expressed in the genetic
sequences of organisms (particularly in highly conserved subsequences, such as those responsible
for constructing ribosomal RNA molecules), rather than by subjective observations of morphology
and function.

Indeed in 1990, Carl Woese described "textbook" definitions of the "basic organisation of life"
reliant on classical phenotyping as "outmoded" and "misleading"[^7].
Referring to a result from Zuckerkandl and Pauling, Woese states it is clear that
"it is at the level of molecules (particularly molecular sequences) that one really becomes privy to
the workings of the evolutionary process", such molecular methods reveal relationships that just cannot be
inferred from an organism's appearance or function[^7]. Certainly there have been many analyses
of ribosomal RNA that provide clear evidence for phylogenetic separation of eubacterial,
archaebacterial, and eukaryotic organisms.

Woese argued that a phylogenetic system must "first and foremost recognize the primacy of the
three groupings, eubacteria, and archaebacteria and eukaryotes"[^7] above the
conventional five kingdoms that had developed over the past few decades that fail to
represent an accurate view of the evolutionary relationship between the kingdoms.
It was here that Woese proposed a radical change to taxonomy and added
the taxonomic rank of **Domain**, superior to Kingdom.

Whilst Whittaker had previously introduced the concept of a Superkingdom to differentiate
between the Monera and the rest of the kingdoms, this distinction merely noted a difference
between "bacteria" and "everything else" and didn't describe the relationship between the
kingdoms within. And so, in his 1990 paper: *Towards a natural system of organisms: Proposal for the domains Archaea, Bacteria, and Eucarya*, Woese introduced the three domains of life[^7]:

![]({{ site.url }}/public/posts/hide-and-seek/woese-4578-tree.png)

Woese didn't make suggestions for what kingdoms should exist beneath these domains
(other than an outline for the archaea, which I will ignore here) anticipating that
"analysis of the Eucarya will preserve the kingdoms Plantae, Animalia, and Fungi
[...] and will replace Protista with a series of kingdoms corresponding to
the various ancient protistan lineages".

### The Rise and Fall of the Nine Kingdoms of Eukaryota
> Nine Kingdoms for the eukaryotes,  
> Eighteen Phyla for the protists,  
> But we were all deceived, for a definition of the protozoa, still could not be agreed.

In 1981, a decade before the **Domain**, Thomas Cavalier-Smith published his own kingdom model.
Initially sub-dividing the eukaryotes in to nine different groups and breaking Whittaker's
Protista kingdom into three: the **Archezoa** (without mitochondria),
**Chromista** (featuring chloroplasts with particular chlorophyll in the lumen)
and the **Protozoa**, defined by their phagotrophism[^12] but
still somewhat seeming as a bin for whatever couldn't fit elsewhere.
Just two years later, Cavalier-Smith culled his eukaryotic kingdoms to
the *Animalia*, *Plantae*, *Fungi*, *Chromista* and *Protozoa* (which now contained
the relegated subkingdom *Archezoa*). Bacteria still had their own kingdom but now
also contained the archaebacteria[^13].

In the following decades, Cavalier-Smith would revise his system multiple times as more
genetic sequencing data became available for analysis.
By 1993, Kingdom Protozoa had 18 phyla[^11] and as recently as 2010, Cavalier-Smith
significantly revised the ordering of subkingdoms between the Protozoa and Chromista.
As you'll see below, Cavalier-Smith's work serves as a significant foundation of the
organisation of taxonomy today.

### Getting the Band Back Together: 21st Century Supergroups
With continuing innovation fueling rapidly moving research, especially in the fields of
molecular biology and genetics, more sequences could be analysed than ever before.
Scientists had been won over by Woese's domain model and tried to maintain an underlying
kingdom structure that maintained the intregrity of the "tree" model, ensuring branches are
monophyletic (*i.e.* branches contain only descendants of that species).

In 2004, Simpson and Roger published a review article, outlining six **Supergroups** which
I have attempted to condense in to the table below[^4]. If, like me, however, you prefer
pretty colour-coordinated diagrams, refer to the figure below the table instead.

| Domain       | Group  | Description[^4] | Examples[^4] |
|--------------|----------|-------------|--------------|
| Bacteria     | Bacteria | Prokaryotic cells lacking a membrane-bound organelles and nucleus | - |
| Archaea      | Archaea  | Like bacteria but demonstrating more complex RNA polymerases than bacteria (similar to eukaryotes), peptidoglycan does not appear in the cell wall and often appear in extreme environments (*e.g.* acidophiles, halophiles, hyperthermophiles), methanogens are classified as archaea | - |
| Eukaryota    | Opisthokonta (Cavalier-Smith, 1987) | Primarily predatory multicellular organisms | "animals and tree fungi as well as several unicellular groups, including the free-living choanoflagellates" |
| "            | Amoebozoa (Cavalier-Smith, 1998)| "Most of the cells that move and feed using broad or finger-like pseudopodia" ("false feet": temporary microtubule and filament structures), typically "heterotrophs that engulf other cells using their pseudopodia"| Classical amoebae and slime moulds | 
| "            | Excavata (Cavalier-Smith, 2002) | "unicellular eukaryotes, most of which are heterotrophic flagellates", "[m]any excavates have greatly modified mitochondria that are not used for oxidative phosphorylation" | Various groups of parasitic flagellate **protozoa** |
| "            | Rhizaria (Cavalier-Smith, 2002) | "unites a wide diversity of free-living unicellular organisms, many of which feed using fine ‘filose’ pseudopodia, together with some fungi-like plant parasites" | **Protist** groups including foraminifera (mostly marine-based shell-building amoeboid protists), radiolaria (ocean based protozoa with mineral-based skeletal structures) and includes "heterotrophic flagellates or amoebae that consume other microbes associated with surfaces" |
| "            | Chromalveolata | Organisms created by secondary endosymbiosis (a eukaryote engulfs and enslaves another eukaryote containing a primary plastid) from a red algae origin | dinoflagellates (flagellate protists, mostly marine plankton), cryptophytes (freshwater algae with plastids), haptophytes and stramenopiles (*a.k.a.* Stramenopiles: algae, giant kelp, diatoms, plankton), alveolates (major grouping of **protozoa**) and apicomplexa (specialist parasites including plasmodia (causing malaria), toxoplasma, and cryptosporidium) |
| "            | Archaeplastida (Plantae) | Organisms featuring "plastids (chloroplasts) that originated by primary endosymbiosis" (enslavement and genomic reduction of a prokaryotic cell) | Land plants, red and green algae and rare microscopic algae called glaucophytes |

![]({{ site.url }}/public/posts/hide-and-seek/simpson-rogers-cb-r964.png)

Yet, even now there is no consensus on what supergroups definitely exist,
how exactly they are related and what species belong where. As recently as 2007,
Burki et al. proposed the **SAR Supergroup** (which as of this year is now
**Subkingdom Harosa**[^18]), suggesting the Stramenopiles, Alveolata and Rhizaria
should be organised beneath one branch together.

### [Woop Woop. I'm done.](http://www.adultswim.com/videos/fishcenter/)
A later paper by Burki introduces the term **Megagroup**[^15]. At this point, I realised
I've spent the best part of a week digging for an answer to my classification conundrum
that likely does not exist. This is yet another side-quest or interesting avenue that
I must turn back on to get back to the research that I should be doing...

<a name="uniprot-taxa"></a>
## Ready or not, here I come!
### UniProtKB
That was a lovely, confusing and borderline frustrating insight to the state of taxonomy Sam,
but how does this help us get the
protozoan-associated hydrolases? Who sets the taxonomic standard for TrEMBL and SwissProt?
UniProt's help documentation quickly offloads the responsibility to the NCBI:

<blockquote>The taxonomy database that is maintained by the UniProt group is based on the <a href="http://www.ncbi.nlm.nih.gov/taxonomy">NCBI taxonomy database</a>, which is supplemented with data specific to the UniProt Knowledgebase (UniProtKB). While the NCBI taxonomy is updated daily to be in sync with GenBank/EMBL-Bank/DDBJ [...]</br><footer>— <a href="http://www.uniprot.org/help/taxonomy">UniProt Help: Taxonomy</a></footer></blockquote>

Accoding to Chapter 4 of the [*NCBI Handbook*](http://www.ncbi.nlm.nih.gov/books/NBK21100/),
**The NCBI Taxonomy Project** began in 1991 "to combine the many taxonomies that existed at the
time into a single classification
that would span all of the organisms represented in any of the GenBank sources databases". The idea
was to solve the problem of duplicated, conflicting and uncomparable taxonomies maintained by the three
big sequencing databases: GenBank, EMBL and DDBJ, who were each keeping their own modified
classification system originally derived from Los Alamos National Lab by unifying the terminology used.

Six years of curation later, both EMBL and DDBJ switched to adopt the NCBI taxonomic standard;
SwissProt followed suit in 2001.

### NCBI's 21 Structures of the Eukaryotes
So, let's take a look at NCBI's taxonomy tree. As of May 2015 the following appear as
entries beneath the Eukaryota <strike>domain</strike> <strike>superkingdom</strike>[^14] top-level group[^16]:

| Name            | Rank† ([^15]) | Unauthoritative Supergroup‡ |
|-----------------|----------------|------------|
| Alveolata (alveolates) | (Superphylum) | Chromalveolata |
| Amoebozoa | (Phylum) | =Amoebozoa |
| Apusozoa | (Subphylum) | ?[^4] |
| Breviatea | (Class) | Amoebozoa |
| Centroheliozoa (centrohelids) | (Class Centrohelea) | ?[^4] |
| Cryptophyta (cryptomonads) | CLASS (Class Cryptophyceae) | Chromalveolata |
| Euglenozoa | (Infrakingdom) | Excavata |
| Fornicata | (?) | Excavata |
| Glaucocystophyceae (glaucocystophytes) | CLASS (Class Glaucophyceae) | Archaeplastida |
| Haptophyceae (coccolithophorids) | (Phylum Haptophyta,<br/>== Class Coccolithophyceae<br/>== Class Prymnesiophyceae) | Chromalveolata |
| Heterolobosea | CLASS | Excavata |
| Jakobida | (Order) | Excavata |
| Katablepharidophyta | CLASS (Order Katablepharida) | Chromalveolata |
| Malawimonadidae | FAMILY | Excavata |
| Opisthokonta | (Supergroup) | =Opisthokonta |
| Oxymonadida (oxymonads) | ORDER | Excavata |
| Parabasalia (parabasalids) | (?) | Excavata |
| Rhizaria | (Infrakingdom) | =Rhizaria |
| Rhodophyta (red algae) | (Phylum) | Archaeplastida |
| Stramenopiles (heterokonts) | (Superphylum Heterokonta<br/>== Supergroup Stramenopiles) | Chromalveolata |
| Viridiplantae (green plants) | KINGDOM (Subkingdom) | Archaeplastida |
| environmental samples | N/A | N/A |
| unclassified eukaryotes | N/A | N/A |

**†** Parentheses indicate the entry was *unranked* by UniProtKB and a rank was interpreted from another source[^15]  
**‡** There are no references for these classifications, I've just tried to make sense of where the most likely supergroup for each taxonomic entry lies, `?` indicates Simpson and Roger were unable to fit this entry in their 2004 model.

Confusingly, most of the 21 entries are not even of the same taxonomic rank. The reasoning for so
many "unorganised" entries is lost on me and I can't seem to locate more
information on the methods used to organise taxonomy from NCBI. For most of the entries,
UniProt's corresponding metadata does not even contain a taxonomic rank. I've thus
<strike>lazily</strike> inferred missing ranks (in parentheses) from <strike>WikiSpecies</strike>[^17]
Ruggiero et al.[^18]. Regardless, the footer of every page of the NCBI taxonomy database is adorned with:

<blockquote>
<b>Disclaimer</b>: The NCBI taxonomy database is not an authoritative source for nomenclature or classification - please consult the relevant scientific literature for the most reliable information.
</blockquote>

So perhaps any suggestion that the entries provide anything beyond an agreed set of boxes in
which to place organisms in a database is invalid. Though the help pages confirm the schema
attempts to maintain a phylogenetic taxonomy, my impression is that the list purposefully
contains "lower" ranks such as *Class*, *Order* and even *Family* both to potentially avoid
having to keep up with
frequent re-shuffles and re-naming of the (Infra-, Sub-, Super-) Groups, Kingdoms and Phyla but
also are left broken as a result of some of the changes that have already happened.
For example, I can't find a mention of either the *Fornicata* or *Parabasalia* in
Ruggiero et al., but one cannot simply expunge records from a widely used taxonomy database
without trouble[^19]!

## So... What are protozoa?
I... I don't know.

I think it is safe to conclude that the **protozoa** (or **protozoans**) consist of an incredibly
diverse group of various micro-organisms. There appears to be wide ranging evidence to
support phylogenetic separation of protozoans in to distinct groups (with whatever taxonomic
rank one wishes to use), each exhibiting different evolutionary variation in their genomes. Whilst it
appears that the term is a valid and widely accepted term for unicellular eukaryotes, given the
current state of their broken-up taxonomy (and the ambiguous meaning of the terms in the past),
I would discourage use of the terms when it is possible to substitute a more specialised
term for organisms of interest.

For example **Ciliates** have their own phylum **Phylum Ciliophora**[^15]) and a
[quick search for Ciliophora-associated hydrolases](http://www.uniprot.org/uniprot/?query=taxonomy%3A%22Ciliophora+%5B5878%5D%22+AND+ec%3A3.*&sort=score) returns 1,691 records.

<a name="virii"></a>
## ...and where the hell are the virii?
Already far outside the scope of what I wanted to read up on, I'll save you and myself the history of viral
classification schemes and the varying opinions still around today. Suffice to say this is unsurprisingly
another topic that the community at large has not reached an agreement on. Virii are typically
excluded from the "tree of life" and to many are "non-cellular life" (often explained
due to their inability to replicate on their own -- they must hijack a cell's machinery to do it for
them) and thus have no place in the tree. Some argue that as evidence points to Viruses co-existing
with organisms throughout evolutionary history they deserve representation as a supergroup or domain of
their own[^2], indeed viruses are a significant
contributor to genetic diversity via their role in horizontal gene transfer (transferring genes from
one organism to another (regardless of species) without 'traditional' reproduction).

Ultimately whether a virus is truly alive or not is somebody else's problem, they still possess sequence
data and that has to be organised somewhere. The NCBI database has chosen  around this by adding a
top-level taxonomic entry for "Viruses" with a structure beneath that appears to follow or emulate the
**Baltimore Classification** system; where virii are organised in to one of seven classes based on
how they store their genome and their mode of transcription.

## Conclusion
The protozoa have had a long and muddled history and my bet is they will continue to do so
as further comparative phylogenomics studies are completed. It's worth noting that phylogenomics
is still a field of scientific endeavour in itself, evolving and adapting to new evidence as other
fields (including my own) move alongside it. For the purpose of getting on with the study of our own
fields it may have been necessary to find a compromise between having the most up-to-date database
and having a database that stays constant enough to know where things actually are.

Indeed, on the subject of compromise, Ruggiero et al. describe their work as a "**consensus classification**";
a "neither phylogenetic nor evolutionary" system that makes "practical compromises" to accomodate many
wide ranging opinions and available evidence, primarily with the goal of providing a "backbone" for
databases and collections[^15].

In the end, I guess expecting the NCBI (or anyone else) to hold a concrete consensus on the
organisation of life was naive and possibly reflects the fact that I'm still more of a Computer Scientist
than Microbiologist. Here was me thinking we'd pretty much classified all of life already!

* * *

# tl;dr
* Protozoa appears to have become a somewhat ambiguous and confusing term over the past few centuries and is applied to a vast number of different species which have now been split across the tree of life.
* I need to go back to original sample and find out what "protozoa" it might contain to try and conduct more specific searches.
* Even today, we still can't agree on what to call things and where they belong in a taxonomy, or even how best to present that taxonomy. But that's just how science works.


[^1]: Mark A. Ragan, *Trees and networks before and after Darwin*, 2009.

[^2]: Arshan Nasir, Kyung Mo Kim, and Gustavo Caetano-Anolles, *Giant viruses coexisted with the cellular ancestors and represent a distinct supergroup along with superkingdoms Archaea, Bacteria and Eukarya*, 2012.

[^3]: JM Scamardella, *Not plants or animals: a brief history of the origin of Kingdoms Protozoa, Protista and Protoctista*, 1999.

[^4]: AG Simpson and AJ Roger, *The real 'kingdoms' of eukaryotes*, 2004.

[^5]: <blockquote>"No mouth. No respiration. No entry."<br/><footer>— Kingdom <i>Animalia</i> Clubhouse Rules, 1860.</footer></blockquote>[^6]

[^6]: Based on paleontologist Richard Owen's 1858 description of plants and animals.

[^7]: Carl R. Woese, Otto Kandler and Mark L. Wheelis, *Towards a natural system of organisms: Proposal for the domains Archaea, Bacteria, and Eucarya*, 1990.

[^8]: M Ragan, *A third kingdom of eukaryotic life: history of an idea*, 1997.

[^9]: Haeckel did not recognise Linnaeus' "mineral" kingdom as a kingdom of life.

[^10]: RH Whittaker, *New concepts of kingdoms of organisms*, 1969.

[^11]: T Cavalier-Smith, *Kingdom Protozoa and Its 18 Phyla*, 1993.

[^12]: T Cavalier-Smith, *Eukaryote kingdoms: Seven or nine?*, 1981. [Abstract only].

[^13]: T Cavalier-Smith, *A revised six-kingdom system of life*, 1998.

[^14]: I'm unclear on whether the NCBI have even officially adopted either of these two terms.

[^15]: Fabien Burki et al., *Phylogenomics Reshuffles the Eukaryotic Supergroups*, 2007.

[^16]: With "supergroups" and now "megagroups" being used in modern literature, I should have tread carefully even with the word "group". But it's too late for that now.

[^17]: I'm sorry.

[^18]: Michael Ruggiero et al., *A Higher Level Classification of All Living Organisms*, 2015.

[^19]: Let's not forget the confusion that happened [last time]({% post_url 2015-04-24-trembling %}) a database removed a significant number of records without obvious warning.
