# Learning Biology

Biology as an engineering discipline. For software engineers and deep tech founders building biotech companies.

## Roadmap

This is structured in three phases. Phase 1 gets you to founder-literate. Phase 2 gets you to technically competent. Phase 3 is where you become genuinely good. Most people stop at Phase 1 — that's fine for a business-focused founder, but not enough if you want original technical insight.

### Phase 1: Biological Literacy (6-9 months, 10-15 hrs/week)

Goal: read papers, talk to scientists, evaluate opportunities, not waste anyone's time.

1. **Foundations** (6-8 weeks) — Alberts chapters 1-8, MIT 7.01x, key papers. Everything else builds on this. Don't skip.
2. **Computational Biology** (6-8 weeks) — AlphaFold papers, DeepChem/RDKit hands-on, Rosalind problems. Your highest-leverage entry point as a software person.
3. **Biotech Business** (4-6 weeks, parallel with above) — Read The Antidote + Billion Dollar Molecule. Follow Endpoints and STAT daily. Understand FDA phases. Never really "done."
4. **Virology** (3-4 weeks) — Cann's textbook, Spillover, mRNA and phage papers. More reading than doing.
5. **Synthetic Biology** (4-6 weeks) — Alon's book, CRISPR papers, gene circuit papers. Faster if your PL intuition kicks in.

What this gets you: "I can identify a real problem, evaluate the science, recruit biologists, and not get fooled."

### Phase 2: Technical Competence (12-18 months)

Goal: contribute technically, have informed opinions that biologists take seriously, build real tools.

1. **Go deep on one subfield.** Pick one: protein engineering, mRNA therapeutics, synthetic gene circuits, computational drug discovery, phage therapy. Read every important paper in that niche. Know who's doing what.
2. **Build something real.** Contribute to open source compbio (OpenFold, ESM, DeepChem). Enter competitions (CASP, DREAM challenges). Publish a preprint.
3. **Get lab experience.** Join a community bio lab. Run basic protocols — PCR, cloning, gel electrophoresis. Feel the gap between in silico and in vivo.
4. **Learn the math you're missing.** Stochastic processes, chemical kinetics, statistical mechanics. Biology's quantitative foundations are different from CS.

What this gets you: "I can do technical work that matters and have real conversations with domain experts about tradeoffs."

### Phase 3: Genuine Depth (2-5 years, ongoing)

Goal: original technical insight. See what the best people in the field see.

1. **Embed with serious biologists.** Work in or alongside a real lab — not as a tourist but solving a real problem. Arc Institute, Broad Institute, or a university lab that values computational people.
2. **Build things that touch wet lab reality.** Models that work in silico mean nothing until they work in a cell. You need to feel that gap firsthand, repeatedly.
3. **Develop taste.** Read deeply in your niche. Understand why certain approaches failed. Know which problems are hard for fundamental reasons vs which are just waiting for better compute.
4. **Publish and get feedback.** Real publications, real peer review. This is how you calibrate whether your ideas are good.

What this gets you: "Biologists respect my opinion. I can see opportunities that pure software people can't and build things that pure biologists wouldn't."

The honest framing: you're learning a second discipline. It took years to get good at software. Biology isn't easier — it's just different.

---

## Phase 1 Resources

### Foundations

The minimum molecular biology and genetics to be literate.

#### Books
- [Molecular Biology of the Cell](https://www.amazon.com/Molecular-Biology-Cell-Bruce-Alberts/dp/0393884821) - Alberts et al. Focus on chapters 1-8 (cells, DNA, proteins) and 24 (immune system).
- [Physical Biology of the Cell](https://www.amazon.com/Physical-Biology-Cell-Rob-Phillips/dp/0815344503) - Phillips et al. Physics meets biology. Quantitative reasoning about biological systems.
- [The Vital Question](https://www.amazon.com/Vital-Question-Evolution-Origins-Complex/dp/0393352978) - Nick Lane. Energy and the origin of complex life.
- [What Is Life?](https://www.amazon.com/What-Life-Physical-Aspect-Living/dp/1107604664) - Erwin Schrödinger. A physicist's view of biology. Short and foundational.
- [Random Walks in Biology](https://www.amazon.com/Random-Walks-Biology-Howard-Berg/dp/0691000646) - Howard Berg. Stochastic processes in biology. Elegant and short.

#### Papers
- [Molecular Structure of Nucleic Acids](https://www.nature.com/articles/171737a0) - Watson & Crick (1953). The DNA structure paper. One page.
- [On Protein Synthesis](https://profiles.nlm.nih.gov/spotlight/sc/catalog/nlm:nlmuid-101584582X366-doc) - Crick (1958). The central dogma.
- [The Hallmarks of Cancer](https://www.cell.com/fulltext/S0092-8674(00)81683-9) - Hanahan & Weinberg (2000). Framework for understanding cancer biology.

#### Courses
- [MIT 7.01x: Introduction to Biology](https://www.edx.org/course/introduction-to-biology-the-secret-of-life) - Eric Lander on edX. Best single course for foundations.
- [iBiology](https://www.ibiology.org/) - Free talks by leading biologists. Watch selectively based on interest.

### Computational Biology & Drug Discovery

Where software engineers have the most leverage right now.

#### Books
- [Deep Learning for the Life Sciences](https://www.amazon.com/Deep-Learning-Life-Sciences-Microscopy/dp/1492039837) - Bharath Ramsundar et al. ML applied to biology with DeepChem.
- [Biological Sequence Analysis](https://www.amazon.com/Biological-Sequence-Analysis-Probabilistic-Proteins/dp/0521629713) - Durbin et al. HMMs, sequence alignment, phylogenetics.
- [An Introduction to Bioinformatics Algorithms](https://www.amazon.com/Introduction-Bioinformatics-Algorithms-Computational-Molecular/dp/0262101068) - Jones & Pevzner. Algorithms-first approach.
- [Drug-like Properties](https://www.amazon.com/Drug-like-Properties-Concepts-Structure-Optimization/dp/0128010762) - Di & Kerns. What makes a molecule a drug.

#### Papers
- [Highly Accurate Protein Structure Prediction with AlphaFold](https://www.nature.com/articles/s41586-021-03819-2) - Jumper et al. (2021). Changed structural biology overnight.
- [De novo design of protein structure and function with RFdiffusion](https://www.nature.com/articles/s41586-023-06415-8) - Watson et al. (2023). Protein design with diffusion models.
- [Large Language Models Generate Functional Protein Sequences](https://www.nature.com/articles/s41587-022-01618-2) - Madani et al. (2023). ProGen — LLMs for protein engineering.
- [Evolutionary-Scale Prediction of Atomic-Level Protein Structure with a Language Model](https://www.science.org/doi/10.1126/science.ade2574) - Lin et al. (2023). ESMFold.
- [A Complete Reference Genome Improves Analysis of Human Genetic Variation](https://www.science.org/doi/10.1126/science.abl3533) - Nurk et al. (2022). T2T complete human genome.

#### Tools & Databases
- [AlphaFold Protein Structure Database](https://alphafold.ebi.ac.uk/) - Predicted structures for 200M+ proteins.
- [UniProt](https://www.uniprot.org/) - Protein sequence and function database.
- [PDB](https://www.rcsb.org/) - Protein Data Bank. 3D structures.
- [NCBI](https://www.ncbi.nlm.nih.gov/) - National Center for Biotechnology Information.
- [DeepChem](https://deepchem.io/) - Python library for drug discovery and molecular ML.
- [RDKit](https://www.rdkit.org/) - Cheminformatics toolkit. Essential for small molecule work.
- [Biopython](https://biopython.org/) - Python tools for computational biology.
- [Rosalind](https://rosalind.info/) - Bioinformatics coding challenges.

#### Courses
- [Coursera: Biology Meets Programming](https://www.coursera.org/learn/bioinformatics) - Pevzner. Bioinformatics algorithms.
- [MIT 6.047: Machine Learning for Genomics](https://ocw.mit.edu/courses/6-047-computational-biology-fall-2015/) - Manolis Kellis.

### Virology & Infectious Disease

Viruses as adversarial systems exploiting host protocols. Fast-moving market with huge unmet needs.

#### Books
- [Principles of Molecular Virology](https://www.amazon.com/Principles-Molecular-Virology-Alan-Cann/dp/0128019468) - Alan Cann. The standard virology textbook.
- [Spillover](https://www.amazon.com/Spillover-Animal-Infections-Human-Pandemic/dp/0393346617) - David Quammen. How pandemics emerge.
- [Viruses, Plagues, and History](https://www.amazon.com/Viruses-Plagues-History-Past-Present/dp/0195327314) - Michael Oldstone.
- [A Planet of Viruses](https://www.amazon.com/Planet-Viruses-Third-Carl-Zimmer/dp/022644184X) - Carl Zimmer. Short, accessible.
- [The Great Influenza](https://www.amazon.com/Great-Influenza-Deadliest-Pandemic-History/dp/0143036491) - John Barry. The 1918 pandemic.

#### Papers
- [Quasispecies Theory and RNA Virus Evolution](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7120325/) - Domingo & Perales. Information theory meets virology.
- [mRNA Vaccines — A New Era in Vaccinology](https://www.nature.com/articles/nrd.2017.243) - Pardi et al. (2018). The science behind mRNA platforms.
- [The Proximal Origin of SARS-CoV-2](https://www.nature.com/articles/s41591-020-0820-9) - Andersen et al. (2020).
- [Phage Therapy in the Era of Synthetic Biology](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6950386/) - Phage therapy as an alternative to antibiotics.
- [Broadly Neutralizing Antibodies Against HIV](https://www.nature.com/articles/s41577-019-0244-2) - Burton & Hangartner.

#### Biodefense & Pandemic Preparedness
- [Biosecurity Dilemmas](https://www.amazon.com/Biosecurity-Dilemmas-Dreaded-Diseases-Defense/dp/1626164045) - Koblentz.
- [The Apollo Program for Biodefense](https://biodefensecommission.org/reports/the-apollo-program-for-biodefense-winning-the-race-against-biological-threats/) - 100-day vaccine vision.
- [Center for Health Security](https://www.centerforhealthsecurity.org/) - Johns Hopkins.

### Synthetic Biology & Genetic Engineering

Designing biological systems from parts. Where PL/compiler thinking maps to biology.

#### Books
- [Synthetic Biology: A Primer](https://www.amazon.com/Synthetic-Biology-Primer-Revised/dp/1783268794) - Baldwin et al.
- [An Introduction to Systems Biology](https://www.amazon.com/Introduction-Systems-Biology-Mathematical-Computational/dp/1439837172) - Uri Alon. Design principles of biological circuits. Elegant.
- [Regenesis](https://www.amazon.com/Regenesis-Synthetic-Biology-Reinvent-Ourselves/dp/0465075703) - George Church & Ed Regis.
- [The Biobuilder](https://www.amazon.com/BioBuilder-Synthetic-Biology-Lab-Class/dp/1491904291) - Natalie Kuldell et al. Hands-on.
- [A Crack in Creation](https://www.amazon.com/Crack-Creation-Editing-Unthinkable-Evolution/dp/1328915360) - Jennifer Doudna & Samuel Sternberg. CRISPR from its inventor.

#### Papers
- [Programmable CRISPR-Cas9 Genome Editing](https://www.science.org/doi/10.1126/science.1231143) - Cong et al. (2013).
- [A Synthetic Oscillatory Network of Transcriptional Regulators](https://www.nature.com/articles/35002125) - Elowitz & Leibler (2000). The repressilator.
- [Construction of a Genetic Toggle Switch in E. coli](https://www.nature.com/articles/35002131) - Gardner et al. (2000).
- [Creation of a Bacterial Cell Controlled by a Chemically Synthesized Genome](https://www.science.org/doi/10.1126/science.1190719) - Gibson et al. (2010). Venter's synthetic cell.
- [Gene Drives on the Horizon](https://nap.nationalacademies.org/catalog/23405/gene-drives-on-the-horizon-advancing-science-navigating-uncertainty-and) - NAS (2016).
- [Cell-Free Synthetic Biology](https://www.nature.com/articles/s41570-021-00330-w) - Laohakunakorn et al. (2021).

#### Resources
- [iGEM](https://igem.org/) - See past projects for what's possible.
- [BioBricks Foundation](https://biobricks.org/) - Standard biological parts registry.
- [Addgene](https://www.addgene.org/) - Nonprofit plasmid repository.
- [OpenWetWare](https://openwetware.org/) - Protocols and resources.

### Biotech Business & Industry

How biotech companies actually work. What most technical founders underestimate.

#### Books
- [The Antidote](https://www.amazon.com/Antidote-Inside-World-New-Pharma/dp/1451655673) - Barry Werth. Inside Vertex Pharmaceuticals.
- [Science Lessons](https://www.amazon.com/Science-Lessons-Companies-Biotech-Breakthroughs/dp/1422114805) - Gordon Binder. Amgen's founding CEO.
- [For Blood and Money](https://www.amazon.com/Blood-Money-Nathan-Vardi/dp/1324074574) - Nathan Vardi. BTK inhibitors and biotech dealmaking.
- [The Billion Dollar Molecule](https://www.amazon.com/Billion-Dollar-Molecule-Companys-Perfect/dp/0671510576) - Barry Werth. The founding of Vertex.

#### Understanding the Industry
- [FDA Drug Approval Process](https://www.fda.gov/patients/learn-about-drug-and-device-approvals) - Phase I/II/III trials, IND, NDA.
- [Drug Development Success Rates](https://www.bio.org/sites/default/files/legacy/bioorg/docs/Clinical%20Development%20Success%20Rates%20and%20Contributing%20Factors%202011-2020.pdf) - BIO. Success rates by phase.
- [Endpoints News](https://endpts.com/) - Biotech industry news. Essential.
- [STAT News](https://www.statnews.com/) - Health and life sciences journalism.
- [BioCentury](https://www.biocentury.com/) - Industry analysis.
- [Derek Lowe's In The Pipeline](https://www.science.org/blogs/pipeline) - Decades of industry wisdom.

#### Funding & Business Models
- [a16z Bio Fund](https://a16z.com/bio-health/) - Thesis and portfolio.
- [Flagship Pioneering](https://www.flagshippioneering.com/) - Created Moderna. Study their venture creation model.
- [Arch Venture Partners](https://www.archventure.com/) - Major biotech VC.
- [Platform vs Pipeline companies](https://a16z.com/bio-and-health-newsletter/) - Platform (Recursion, Ginkgo, Insitro) vs pipeline (traditional pharma). Understand the tradeoffs.

---

## Phase 2 Resources

### Lab Skills & Wetlab for Engineers

You need to understand the physical constraints. Models are not biology.

- [Genspace](https://www.genspace.org/) (NYC), [BioCurious](https://biocurious.org/) (Bay Area), [Counter Culture Labs](https://www.counterculturelabs.org/) (Oakland) - Community bio labs.
- [MIT OpenCourseWare: Experimental Biology](https://ocw.mit.edu/courses/7-02ci-experimental-biology-communications-intensive-spring-2005/) - Lab techniques.
- [Benchling](https://www.benchling.com/) - Cloud-based lab informatics. Learn how modern labs manage data.
- [Protocols.io](https://www.protocols.io/) - Open access scientific methods.
- [The Minipcr Learning Lab](https://www.minipcr.com/) - Affordable PCR and lab equipment.
- [Cold Spring Harbor Protocols](http://cshprotocols.cshlp.org/) - Gold standard protocols.

### Competitions & Open Source

How you build a real track record.

- [CASP](https://predictioncenter.org/) - Critical Assessment of protein Structure Prediction. The benchmark.
- [DREAM Challenges](https://dreamchallenges.org/) - Crowd-sourced computational biology challenges.
- [OpenFold](https://github.com/aqlaboratory/openfold) - Open source protein structure prediction.
- [ESM](https://github.com/facebookresearch/esm) - Meta's evolutionary scale modeling. Contribute or build on top.
- [DeepChem](https://github.com/deepchem/deepchem) - Drug discovery ML. Active community.
- [Open Problems in Single-Cell Analysis](https://openproblems.bio/) - Benchmarking for single-cell methods.

### Quantitative Foundations

The math biology uses that CS doesn't teach you.

- [Chemical Kinetics](https://www.amazon.com/Chemical-Kinetics-Reaction-Dynamics-Paul/dp/0486453340) - Houston. How reactions work.
- [Stochastic Processes in Physics and Chemistry](https://www.amazon.com/Stochastic-Processes-Physics-Chemistry-Third/dp/0444529659) - Van Kampen. The reference.
- [Physical Biology of the Cell](https://www.amazon.com/Physical-Biology-Cell-Rob-Phillips/dp/0815344503) - Phillips. Double-dip from Phase 1, but go deeper on the math.
- [Biological Physics](https://www.amazon.com/Biological-Physics-Energy-Information-Life/dp/0716798972) - Philip Nelson. Energy, information, life.
- [An Introduction to Systems Biology](https://www.amazon.com/Introduction-Systems-Biology-Mathematical-Computational/dp/1439837172) - Uri Alon. Second pass, focusing on the math of network motifs.

---

## Phase 3 Resources

### Going Deep

At this stage, resources matter less than environment and practice. But these help.

#### History & Context
- [The Eighth Day of Creation](https://www.amazon.com/Eighth-Day-Creation-Revolution-Commemorative/dp/0879694785) - Horace Freeland Judson. The history of molecular biology. Masterful.
- [The Double Helix](https://www.amazon.com/Double-Helix-Personal-Discovery-Structure/dp/074321630X) - James Watson. How discovery actually happens.
- [The Gene: An Intimate History](https://www.amazon.com/Gene-Intimate-History-Siddhartha-Mukherjee/dp/1432837818) - Siddhartha Mukherjee. The full arc of genetics.
- [I Contain Multitudes](https://www.amazon.com/Contain-Multitudes-Microbes-Within-Grander/dp/0062368591) - Ed Yong. The microbiome.

#### Advanced Technical
- [Lehninger Principles of Biochemistry](https://www.amazon.com/Lehninger-Principles-Biochemistry-David-Nelson/dp/1319228003) - Nelson & Cox. Full biochemistry when you need it.
- [Principles of Neural Science](https://www.amazon.com/Principles-Neural-Science-Sixth-Kandel/dp/1259642232) - Kandel et al. If you go into neurotech.
- [Molecular Biology of the Cell](https://www.amazon.com/Molecular-Biology-Cell-Bruce-Alberts/dp/0393884821) - Alberts. Now read the whole thing.

#### Where to Embed
- [Arc Institute](https://arcinstitute.org/) - New research model. Patrick Collison, Silvana Konermann, Patrick Hsu.
- [Broad Institute](https://www.broadinstitute.org/) - MIT/Harvard. Computational biology hub.
- [EMBL-EBI](https://www.ebi.ac.uk/) - European bioinformatics. Strong computational culture.
- [Wyss Institute](https://wyss.harvard.edu/) - Harvard. Biologically inspired engineering.
- Your local university's biology department — offer to build tools for a lab in exchange for learning.

---

## Key Companies & People

### Companies to Study
- **[Moderna](https://www.modernatx.com/)** - mRNA platform. Concept to COVID vaccine in 11 months.
- **[Ginkgo Bioworks](https://www.ginkgobioworks.com/)** - Cell programming platform. The "AWS of biology" thesis.
- **[Recursion Pharmaceuticals](https://www.recursion.com/)** - ML-driven drug discovery at scale.
- **[Isomorphic Labs](https://www.isomorphiclabs.com/)** - DeepMind's drug discovery spinoff.
- **[Dyno Therapeutics](https://www.dynotx.com/)** - AI-designed AAV vectors for gene therapy.
- **[Insitro](https://insitro.com/)** - ML + biology. Daphne Koller.
- **[Arc Institute](https://arcinstitute.org/)** - New research model for fundamental science.
- **[Mammoth Biosciences](https://mammoth.bio/)** - CRISPR diagnostics. Doudna co-founded.
- **[Resilience](https://resilience.com/)** - Biomanufacturing infrastructure.
- **[Benchling](https://www.benchling.com/)** - R&D cloud for biotech. Software company in biotech.

### People to Follow
- **[George Church](https://arep.med.harvard.edu/gmc/)** - Synthetic biology pioneer, Harvard. Prolific company creator.
- **[Jennifer Doudna](https://en.wikipedia.org/wiki/Jennifer_Doudna)** - CRISPR co-inventor, Nobel laureate.
- **[Feng Zhang](https://zlab.bio/)** - CRISPR applications, Broad Institute.
- **[Daphne Koller](https://en.wikipedia.org/wiki/Daphne_Koller)** - CEO of Insitro. Stanford CS → biology.
- **[Vijay Pande](https://en.wikipedia.org/wiki/Vijay_Pande)** - a16z Bio GP. The archetype of engineer-turned-bio-investor.
- **[Patrick Collison](https://patrickcollison.com/)** - Stripe CEO, Arc Institute co-founder.
- **[Drew Endy](https://en.wikipedia.org/wiki/Drew_Endy)** - Stanford. Synthetic biology, BioBricks, open-source biology.
- **[David Baker](https://en.wikipedia.org/wiki/David_Baker_(biochemist))** - UW. Protein design pioneer. Rosetta, RFdiffusion. Nobel laureate 2024.
- **[Noubar Afeyan](https://en.wikipedia.org/wiki/Noubar_Afeyan)** - Flagship Pioneering founder. Created Moderna.
- **[Laura Deming](https://www.ldeming.com/)** - Longevity Fund. Anti-aging research → VC.

## Podcasts & Newsletters

- [Bits in Bio](https://bitsinbio.substack.com/) - For people at the intersection of software and biology.
- [Codon](https://www.codonmag.com/) - Niko McCarty. Synthetic biology newsletter.
- [This Week in Virology](https://www.microbe.tv/twiv/) - Vincent Racaniello. Deep virology.
- [The a16z Bio Podcast](https://a16z.com/podcasts/) - Bio/health episodes.
- [Talking Biotech](https://www.talkingbiotechpodcast.com/) - Kevin Folta.
- [Endpoints News](https://endpts.com/) - Daily biotech industry news.
- [STAT News](https://www.statnews.com/) - Health and life sciences journalism.
- [Derek Lowe's In The Pipeline](https://www.science.org/blogs/pipeline) - Medicinal chemistry blog with decades of wisdom.
