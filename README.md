# Learning Biology

Biology as an engineering discipline. For software engineers and deep tech founders building biotech companies.

## Foundations

The minimum molecular biology and genetics you need to be literate.

### Books
- [Molecular Biology of the Cell](https://www.amazon.com/Molecular-Biology-Cell-Bruce-Alberts/dp/0393884821) - Alberts et al. The standard reference. You don't need to read all of it — focus on chapters 1-8 (cells, DNA, proteins) and 24 (immune system).
- [Physical Biology of the Cell](https://www.amazon.com/Physical-Biology-Cell-Rob-Phillips/dp/0815344503) - Phillips et al. Physics meets biology. Quantitative reasoning about biological systems.
- [The Vital Question](https://www.amazon.com/Vital-Question-Evolution-Origins-Complex/dp/0393352978) - Nick Lane. Energy and the origin of complex life. Changes how you think about biology.
- [What Is Life?](https://www.amazon.com/What-Life-Physical-Aspect-Living/dp/1107604664) - Erwin Schrödinger. A physicist's view of biology. Short and foundational.
- [Random Walks in Biology](https://www.amazon.com/Random-Walks-Biology-Howard-Berg/dp/0691000646) - Howard Berg. Stochastic processes in biology. Elegant and short.

### Papers
- [Molecular Structure of Nucleic Acids](https://www.nature.com/articles/171737a0) - Watson & Crick (1953). The DNA structure paper. One page.
- [On Protein Synthesis](https://profiles.nlm.nih.gov/spotlight/sc/catalog/nlm:nlmuid-101584582X366-doc) - Crick (1958). The central dogma.
- [The Hallmarks of Cancer](https://www.cell.com/fulltext/S0092-8674(00)81683-9) - Hanahan & Weinberg (2000). Framework for understanding cancer biology.

### Courses
- [MIT 7.01x: Introduction to Biology](https://www.edx.org/course/introduction-to-biology-the-secret-of-life) - Eric Lander on edX. Best single course for foundations.
- [iBiology](https://www.ibiology.org/) - Free talks by leading biologists. Watch selectively based on interest.

## Synthetic Biology & Genetic Engineering

Designing biological systems from parts. This is where PL/compiler thinking maps to biology.

### Books
- [Synthetic Biology: A Primer](https://www.amazon.com/Synthetic-Biology-Primer-Revised/dp/1783268794) - Baldwin et al. Concise overview of the field.
- [An Introduction to Systems Biology](https://www.amazon.com/Introduction-Systems-Biology-Mathematical-Computational/dp/1439837172) - Uri Alon. Design principles of biological circuits. Elegant — treats biology like engineering.
- [Regenesis](https://www.amazon.com/Regenesis-Synthetic-Biology-Reinvent-Ourselves/dp/0465075703) - George Church & Ed Regis. Vision of synthetic biology's future from one of its founders.
- [The Biobuilder](https://www.amazon.com/BioBuilder-Synthetic-Biology-Lab-Class/dp/1491904291) - Natalie Kuldell et al. Hands-on synthetic biology.
- [A Crack in Creation](https://www.amazon.com/Crack-Creation-Editing-Unthinkable-Evolution/dp/1328915360) - Jennifer Doudna & Samuel Sternberg. CRISPR from one of its inventors.

### Papers
- [Programmable CRISPR-Cas9 Genome Editing](https://www.science.org/doi/10.1126/science.1231143) - Cong et al. (2013). CRISPR-Cas9 for genome editing.
- [A Synthetic Oscillatory Network of Transcriptional Regulators](https://www.nature.com/articles/35002125) - Elowitz & Leibler (2000). The repressilator — a genetic circuit.
- [Construction of a Genetic Toggle Switch in E. coli](https://www.nature.com/articles/35002131) - Gardner et al. (2000). Bistable gene circuit.
- [Creation of a Bacterial Cell Controlled by a Chemically Synthesized Genome](https://www.science.org/doi/10.1126/science.1190719) - Gibson et al. (2010). Venter's synthetic cell.
- [Gene Drives on the Horizon](https://nap.nationalacademies.org/catalog/23405/gene-drives-on-the-horizon-advancing-science-navigating-uncertainty-and) - NAS (2016). Gene drives and their implications.
- [Cell-Free Synthetic Biology](https://www.nature.com/articles/s41570-021-00330-w) - Laohakunakorn et al. (2021). Building biology without cells.

### Resources
- [iGEM](https://igem.org/) - International Genetically Engineered Machine competition. See past projects for what's possible.
- [BioBricks Foundation](https://biobricks.org/) - Standard biological parts registry.
- [Addgene](https://www.addgene.org/) - Nonprofit plasmid repository. Browse to understand available tools.
- [OpenWetWare](https://openwetware.org/) - Protocols and resources for biological engineering.

## Computational Biology & Drug Discovery

Where software engineers have the most leverage right now.

### Books
- [Deep Learning for the Life Sciences](https://www.amazon.com/Deep-Learning-Life-Sciences-Microscopy/dp/1492039837) - Bharath Ramsundar et al. ML applied to biology with DeepChem.
- [Biological Sequence Analysis](https://www.amazon.com/Biological-Sequence-Analysis-Probabilistic-Proteins/dp/0521629713) - Durbin et al. HMMs, sequence alignment, phylogenetics. The algorithms foundation.
- [An Introduction to Bioinformatics Algorithms](https://www.amazon.com/Introduction-Bioinformatics-Algorithms-Computational-Molecular/dp/0262101068) - Jones & Pevzner. Algorithms-first approach to bioinformatics.
- [Drug-like Properties](https://www.amazon.com/Drug-like-Properties-Concepts-Structure-Optimization/dp/0128010762) - Di & Kerns. Understanding what makes a molecule a drug.

### Papers
- [Highly Accurate Protein Structure Prediction with AlphaFold](https://www.nature.com/articles/s41586-021-03819-2) - Jumper et al. (2021). AlphaFold 2. Changed structural biology overnight.
- [De novo design of protein structure and function with RFdiffusion](https://www.nature.com/articles/s41586-023-06415-8) - Watson et al. (2023). Protein design with diffusion models.
- [Large Language Models Generate Functional Protein Sequences](https://www.nature.com/articles/s41587-022-01618-2) - Madani et al. (2023). ProGen — LLMs for protein engineering.
- [A Complete Reference Genome Improves Analysis of Human Genetic Variation](https://www.science.org/doi/10.1126/science.abl3533) - Nurk et al. (2022). T2T complete human genome.
- [Evolutionary-Scale Prediction of Atomic-Level Protein Structure with a Language Model](https://www.science.org/doi/10.1126/science.ade2574) - Lin et al. (2023). ESMFold — protein structure from language models.
- [A Foundation Model for Drug Candidate Molecule Generation](https://arxiv.org/abs/2301.01678) - Molecular generation for drug discovery.
- [Recursive Neural Networks for Molecular Property Prediction](https://arxiv.org/abs/1702.00181) - Gilmer et al. (2017). Message passing neural networks for molecules.

### Tools & Databases
- [AlphaFold Protein Structure Database](https://alphafold.ebi.ac.uk/) - Predicted structures for 200M+ proteins.
- [UniProt](https://www.uniprot.org/) - Protein sequence and function database.
- [PDB](https://www.rcsb.org/) - Protein Data Bank. 3D structures.
- [NCBI](https://www.ncbi.nlm.nih.gov/) - National Center for Biotechnology Information.
- [DeepChem](https://deepchem.io/) - Python library for drug discovery and molecular ML.
- [RDKit](https://www.rdkit.org/) - Cheminformatics toolkit. Essential for small molecule work.
- [Biopython](https://biopython.org/) - Python tools for computational biology.
- [Rosalind](https://rosalind.info/) - Bioinformatics coding challenges.

### Courses
- [Coursera: Biology Meets Programming](https://www.coursera.org/learn/bioinformatics) - Pevzner. Bioinformatics algorithms.
- [MIT 6.047: Machine Learning for Genomics](https://ocw.mit.edu/courses/6-047-computational-biology-fall-2015/) - Manolis Kellis.

## Virology & Infectious Disease

Viruses as adversarial systems exploiting host protocols. Fast-moving market with huge unmet needs.

### Books
- [Principles of Molecular Virology](https://www.amazon.com/Principles-Molecular-Virology-Alan-Cann/dp/0128019468) - Alan Cann. The standard virology textbook. Clear and well-structured.
- [Spillover](https://www.amazon.com/Spillover-Animal-Infections-Human-Pandemic/dp/0393346617) - David Quammen. Zoonotic diseases and how pandemics emerge. Compelling narrative.
- [Viruses, Plagues, and History](https://www.amazon.com/Viruses-Plagues-History-Past-Present/dp/0195327314) - Michael Oldstone. Historical impact of viral diseases.
- [A Planet of Viruses](https://www.amazon.com/Planet-Viruses-Third-Carl-Zimmer/dp/022644184X) - Carl Zimmer. Short, accessible introduction to the viral world.
- [The Great Influenza](https://www.amazon.com/Great-Influenza-Deadliest-Pandemic-History/dp/0143036491) - John Barry. The 1918 pandemic. Relevant to pandemic preparedness.

### Papers
- [Quasispecies Theory and RNA Virus Evolution](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7120325/) - Domingo & Perales. Viral evolution as error-prone replication — information theory meets virology.
- [mRNA Vaccines — A New Era in Vaccinology](https://www.nature.com/articles/nrd.2017.243) - Pardi et al. (2018). The science behind mRNA platforms.
- [The Proximal Origin of SARS-CoV-2](https://www.nature.com/articles/s41591-020-0820-9) - Andersen et al. (2020). Genomic analysis of SARS-CoV-2 origins.
- [Phage Therapy in the Era of Synthetic Biology](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6950386/) - Adaptive phage therapy as an alternative to antibiotics.
- [Broadly Neutralizing Antibodies Against HIV](https://www.nature.com/articles/s41577-019-0244-2) - Burton & Hangartner. Engineering antibodies against viral targets.
- [Pandemic Preparedness and Response](https://www.who.int/publications/m/item/pandemic-preparedness-and-response) - WHO frameworks. The policy side.

### Biodefense & Pandemic Preparedness
- [Biosecurity Dilemmas](https://www.amazon.com/Biosecurity-Dilemmas-Dreaded-Diseases-Defense/dp/1626164045) - Koblentz. Dual-use research and governance.
- [The Apollo Program for Biodefense](https://biodefensecommission.org/reports/the-apollo-program-for-biodefense-winning-the-race-against-biological-threats/) - Bipartisan Commission. 100-day vaccine development vision.
- [Center for Health Security](https://www.centerforhealthsecurity.org/) - Johns Hopkins. Policy research on health security.

## Biotech Business & Industry

How biotech companies actually work. This is what most technical founders underestimate.

### Books
- [The Antidote](https://www.amazon.com/Antidote-Inside-World-New-Pharma/dp/1451655673) - Barry Werth. Inside Vertex Pharmaceuticals. How a biotech company really operates.
- [Science Lessons](https://www.amazon.com/Science-Lessons-Companies-Biotech-Breakthroughs/dp/1422114805) - Gordon Binder. Amgen's founding CEO on building a biotech company.
- [For Blood and Money](https://www.amazon.com/Blood-Money-Nathan-Vardi/dp/1324074574) - Nathan Vardi. The story of BTK inhibitors and biotech dealmaking.
- [The Billion Dollar Molecule](https://www.amazon.com/Billion-Dollar-Molecule-Companys-Perfect/dp/0671510576) - Barry Werth. The founding of Vertex. Classic biotech narrative.
- [Natural Born Cloners](https://federicocarrone.com) - On platform vs pipeline biotech strategies.

### Understanding the Industry
- [FDA Drug Approval Process](https://www.fda.gov/patients/learn-about-drug-and-device-approvals) - Understand Phase I/II/III trials, IND, NDA.
- [Biotech Primer](https://www.biotechprimer.com/) - Industry education.
- [Drug Development Timeline](https://www.bio.org/sites/default/files/legacy/bioorg/docs/Clinical%20Development%20Success%20Rates%20and%20Contributing%20Factors%202011-2020.pdf) - BIO. Success rates by phase.
- [Endpoints News](https://endpts.com/) - Biotech industry news. Essential reading.
- [STAT News](https://www.statnews.com/) - Health and life sciences journalism.
- [BioCentury](https://www.biocentury.com/) - Industry analysis.
- [Derek Lowe's In The Pipeline](https://www.science.org/blogs/pipeline) - Medicinal chemist's blog. Decades of industry wisdom.

### Funding & Business Models
- [a16z Bio Fund](https://a16z.com/bio-health/) - Thesis and portfolio.
- [Flagship Pioneering](https://www.flagshippioneering.com/) - Created Moderna. Their venture creation model is worth studying.
- [Arch Venture Partners](https://www.archventure.com/) - Major biotech VC.
- Platform companies (Recursion, Ginkgo, Insitro) vs pipeline companies (traditional pharma model). Understand the tradeoffs.

## Lab Skills & Wetlab for Engineers

Getting your hands dirty. You don't need a PhD, but you need to understand the physical constraints.

- [Genspace](https://www.genspace.org/) (NYC), [BioCurious](https://biocurious.org/) (Bay Area), [Counter Culture Labs](https://www.counterculturelabs.org/) (Oakland) - Community bio labs where you can learn wetlab skills.
- [MIT OpenCourseWare: Experimental Biology](https://ocw.mit.edu/courses/7-02ci-experimental-biology-communications-intensive-spring-2005/) - Lab techniques.
- [Benchling](https://www.benchling.com/) - Cloud-based lab informatics platform. Free for academics. Learn how modern labs manage data.
- [Protocols.io](https://www.protocols.io/) - Open access repository of scientific methods.
- [The Minipcr Learning Lab](https://www.minipcr.com/) - Affordable PCR and lab equipment for learning.
- [Cold Spring Harbor Protocols](http://cshprotocols.cshlp.org/) - Gold standard protocols.

## Key Companies & People

### Companies to Study
- **[Moderna](https://www.modernatx.com/)** - mRNA platform. From concept to COVID vaccine in 11 months.
- **[Ginkgo Bioworks](https://www.ginkgobioworks.com/)** - Cell programming platform. The "AWS of biology" thesis.
- **[Recursion Pharmaceuticals](https://www.recursion.com/)** - ML-driven drug discovery at scale. Heavy compute approach.
- **[Isomorphic Labs](https://www.isomorphiclabs.com/)** - DeepMind's drug discovery spinoff.
- **[Dyno Therapeutics](https://www.dynotx.com/)** - AI-designed AAV vectors for gene therapy. Church lab spinoff.
- **[Insitro](https://insitro.com/)** - ML + biology for drug discovery. Daphne Koller.
- **[Arc Institute](https://arcinstitute.org/)** - Patrick Collison, Silvana Konermann, Patrick Hsu. New research model.
- **[Mammoth Biosciences](https://mammoth.bio/)** - CRISPR diagnostics. Doudna co-founded.
- **[Resilience](https://resilience.com/)** - Biomanufacturing infrastructure.
- **[Benchling](https://www.benchling.com/)** - R&D cloud for biotech. Software company in biotech.

### People to Follow
- **George Church** - Synthetic biology pioneer, Harvard. Prolific company creator.
- **Jennifer Doudna** - CRISPR co-inventor, Nobel laureate.
- **Feng Zhang** - CRISPR applications, Broad Institute.
- **Daphne Koller** - CEO of Insitro. Stanford CS → biology.
- **Vijay Pande** - a16z Bio GP. Stanford CS/Bio → VC. The archetype of the engineer-turned-bio-investor.
- **Patrick Collison** - Stripe CEO, Arc Institute co-founder. Tech founder investing in bio research infrastructure.
- **Drew Endy** - Stanford. Synthetic biology, BioBricks, open-source biology advocacy.
- **David Baker** - UW. Protein design pioneer. Rosetta, RFdiffusion.
- **Noubar Afeyan** - Flagship Pioneering founder. Created Moderna.
- **Laura Deming** - Longevity Fund. Started in anti-aging research at 12, VC by 17.

## Podcasts & Newsletters

- [The a16z Bio Podcast](https://a16z.com/podcasts/) - Bio/health episodes.
- [Talking Biotech](https://www.talkingbiotechpodcast.com/) - Kevin Folta. Accessible biotech conversations.
- [This Week in Virology](https://www.microbe.tv/twiv/) - Vincent Racaniello. Deep virology discussions.
- [Bits in Bio](https://bitsinbio.substack.com/) - Newsletter for people at the intersection of software and biology.
- [Codon](https://www.codonmag.com/) - Niko McCarty. Synthetic biology newsletter.
- [Luca Naef's Newsletter](https://lucanaefsynthbio.substack.com/) - Synthetic biology business.
