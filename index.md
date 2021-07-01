## Minimal Information about MHC Multimers (MIAMM)

These guidelines were established with the expertise of the members of the NIH Tetramer Facility, laboratory users of such reagents, and database curators tasked with describing such reagents in machine-readable and interoperable digital resources. These minimal nomenclature guidelines for MHC Multimers will ensure that multimer data is presented according to the FAIR principles and is more Findable, Accessible, Interoperable and Reusable. Please see this publication explaining the standard [PMID].


### Minimal Information about MHC Multimers (MIAMM) components and how they are standardized.

**Table 5. Minimal Information about MHC Multimer (MIAM) components and how they are standardized.**

| Component      | Standardization method    | Example | Standardized name |
| :------------- | :----------------------:  | ---- -: | ----------------: |
| MHC molecule | MHC Restriction Ontology (MRO)  | A0201 | HLA-A*02:01 |
| Peptidic ligand | Nomenclature Committee of the International Union of Biochemistry (IUPAC-IUB)  | SLYNTVATL | SLYNTVATL |
| Non-peptidic ligand | Chemical Entities of Biological Interest (ChEBI) | α-GalCer | 1-O-(α-D-galactosyl)-N-hexacosanoylphytosphingosine |
| Post translational modification | Protein Modification Ontology (PSI-MOD) | Acetylation | acetylated residue |
| Modification position | Letter followed by position in ligand | the first leucine in SLYNTVATL | L2 |

![MIAMM Table](https://user-images.githubusercontent.com/86632873/123714022-6d5d7700-d82a-11eb-8a59-6cf577908177.PNG)


MHC molecules are described using the MHC Restriction ontology (MRO)<sup>1</sup>. <http://www.obofoundry.org/ontology/mro.html>

Peptidic ligands are described using standard single letter abbreviations.

Non-peptidic ligands are described using Chemical Entities of Biological Interest (ChEBI)<sup>2</sup>.
<https://www.ebi.ac.uk/chebi/>

Post translational modifications of peptide ligands are described using Protein Modification Ontology (PSI-MOD)<sup>3</sup>.
<https://psidev.info/groups/protein-modifications>

Modification position within a peptide ligand is to be described by the single letter abbreviation of the amino acid that is modified, followed by the position of that amino acid within the peptide (L2).

For assistance following this standard, see the Multimer Validator, a web tool which allows users to either a) parse the full name they generated, and validate that it fulfills the specifications, or b) compose the full name, based on the information added by the user. The tool ensures that the valid ontology terms and nomenclatures are enforced. It can be used by entering multimers into a web form or by uploading a spreadsheet.

For questions or feedback, contact us: <miammhelp@lji.org> [TBC]



1. Vita R, Overton JA, Seymour E, Sidney J, Kaufman J, Tallmadge RL, Ellis S, Hammond J, Butcher GW, Sette A, Peters B. An ontology for major histocompatibility restriction. for major histocompatibility restriction. J Biomed Semantics. 2016 Jan 11;7:1. doi: 10.1186/s13326-016-0045-5. eCollection 2016.

2. Hastings J, Owen G, Dekker A, Ennis M, Kale N, Muthukrishnan V, Turner S, Swainston N, Mendes P, Steinbeck C. (2016). ChEBI in 2016: Improved services and an expanding collection of metabolites. Nucleic Acids Res. 2016 Jan 4;44(D1):D1214-9.

3. Montecchi-Palazzi L, Beavis R, Binz PA, Chalkley RJ, Cottrell J, Creasy D, Shofstahl J, Seymour SL, Garavelli JS. The PSI-MOD community standard for representation of protein modification data. Nat Biotechnol. 2008 Aug;26(8):864-6. doi: 10.1038/nbt0808-864.
