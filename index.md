## About MIAMM

These guidelines were established with the expertise of the members of the NIH Tetramer Facility, laboratory users of such reagents, and database curators tasked with describing such reagents in machine-readable and interoperable digital resources. These minimal nomenclature guidelines for MHC Multimers will ensure that multimer data is presented according to the FAIR principles and is more Findable, Accessible, Interoperable and Reusable. Please see this publication explaining the standard [weblink to preprint].


See our **Multimer Validator** webtool to validate your multimers
<https://multimer.lji.org>



**Minimal Information about MHC Multimer (MIAMM) components and how they are standardized.**

| Component | Standardization method | Example | Standardized name |
| --------- | ---------------------- | ------- | ----------------- |
| MHC molecule | MHC Restriction Ontology (MRO)  | A0201 | HLA-A*02:01 |
| Peptidic ligand | Nomenclature Committee of the International Union of Biochemistry (IUPAC-IUB)  | SLYNTVATL | SLYNTVATL |
| Non-peptidic ligand | Chemical Entities of Biological Interest (ChEBI) | α-GalCer | 1-O-(α-D-galactosyl)-N-hexacosanoylphytosphingosine |
| Post translational modification | Protein Modification Ontology (PSI-MOD) | Acetylation | acetylated residue |
| Modification position | Letter followed by position in ligand | the first leucine in SLYNTVATL | L2 |


MHC molecules are described using the MHC Restriction ontology (MRO)[1]. <http://www.obofoundry.org/ontology/mro.html>

Peptidic ligands are described using standard single letter abbreviations.

Non-peptidic ligands are described using Chemical Entities of Biological Interest (ChEBI)[2].
<https://www.ebi.ac.uk/chebi/>

Post translational modifications of peptide ligands are described using Protein Modification Ontology (PSI-MOD)[3]. A table provided below provides the most commonly used modifications in multimer ligands.
<https://psidev.info/groups/protein-modifications>

Modification position within a peptide ligand is to be described by the single letter abbreviation of the amino acid that is modified, followed by the position of that amino acid within the peptide (L2).

For assistance following this standard, see the Multimer Validator, a web tool which allows users to either a) parse the full name they generated, and validate that it fulfills the specifications, or b) compose the full name, based on the information added by the user. The tool ensures that the valid ontology terms and nomenclatures are enforced. It can be used by entering multimers into a web form or by uploading a spreadsheet.





**Common Modifications. Modifications commonly found in multimer ligands standardized using PSI-MOD terminology.**

| PSI-MOD label | Synonym | PSI-MOD ID |
| ------------- | ------- | ---------- |
| amidated residue | Amidation, AMID | MOD:00674 |
| 2-pyrrolidone-5-carboxylic acid (Glu) | Pyrrolidone carboxylic acid, PYRE, PCA, pyroglutamic acid | MOD:00420 |
| 9-fluorenylmethyloxycarbonyl (Fmoc) | Fluorenylmethyloxycarbonyl, FMOC | MOD:01109 |
| acetylated residue | Acetylation, ACET, AcRes, Acetyl | MOD:02078 |
| biotinylated residue | Biotin, BIOT, BtnRes, Biotinylation | MOD:01885 |
| cysteinylation (disulfide with free L-cysteine) | Cysteinylation, CYSTL, SCysCys | MOD:00765 |
| deamidated and methyl esterified residue | Deamidation followed by a methylation, DEAME |	MOD:01369 |
| deamidated residue | Deamidation, DEAM, dNRes, Deamidated	| MOD:00400 |
| dehydrated residue | Dehydration, DEHY, Dehydrated | MOD:00704 |
| formylated residue |	Formylation, FORM, FoRes, Formyl	| MOD:00493 |
| galactosylated residue |	Galactosylation, GAL, GalRes |	MOD:00728 |
| glucosylated residue |	Glucosylation, GLUC, GlcRes, Glycation |	MOD:00726 |
| glycosylated residue |	Glycosylation, GLYC, GlycoRes |	MOD:00693 |
| hydroxylated residue |	Hydroxylation, HYL, HyRes |	MOD:00677 |
| L-2-aminobutanoic acid (Glu) |	L-Î±-Aminobutyric acid, Abu |	MOD:00819 |
| L-citrulline |	Citrullination, CITR, Cit, Deamidated |	MOD:00219 |
| methylated residue |	Methylation, METH, METH, MeRes |	MOD:00427 |
| myristoylated residue |	Myristoylation, MYRI, MYRI, MyrRes |	MOD:00438 |
| mono N-acetylated residue |	N-acetylation, NAc, NAcRes, N-Acetyl |	MOD:00408 |
| oxidized residue |	Oxidation, OX, OxRes |	MOD:00675 |
| palmitoylated residue |	Palmitoylation PALM, PALM, PamRes, Palmitoyl |	MOD:00440 |
| phosphorylated residue |	Phosphorylation, PHOS, PhosRes, Phospho |	MOD:00696 |
| reduced residue |	Reduction, RED, RedRes |	MOD:01472 |
| sulfated residue |	Sulfation, SULF, SulfRes, Sulfo |	MOD:00695 |
| other |	OTH	|


**Edge Cases**

Tethered peptides


Chimeric MHC molecules


**References**
1. Vita R, Overton JA, Seymour E, Sidney J, Kaufman J, Tallmadge RL, Ellis S, Hammond J, Butcher GW, Sette A, Peters B. An ontology for major histocompatibility restriction. for major histocompatibility restriction. J Biomed Semantics. 2016 Jan 11;7:1. doi: 10.1186/s13326-016-0045-5. eCollection 2016.

2. Hastings J, Owen G, Dekker A, Ennis M, Kale N, Muthukrishnan V, Turner S, Swainston N, Mendes P, Steinbeck C. (2016). ChEBI in 2016: Improved services and an expanding collection of metabolites. Nucleic Acids Res. 2016 Jan 4;44(D1):D1214-9.

3. Montecchi-Palazzi L, Beavis R, Binz PA, Chalkley RJ, Cottrell J, Creasy D, Shofstahl J, Seymour SL, Garavelli JS. The PSI-MOD community standard for representation of protein modification data. Nat Biotechnol. 2008 Aug;26(8):864-6. doi: 10.1038/nbt0808-864.


For questions or feedback, contact us: <miamm@lji.org>
