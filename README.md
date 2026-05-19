# CRISPR_Guide_design_Project
Designing a Guide RNA for knocking out PCSK9 gene that leaves more cholesterol receptors intact, lowering LDL-"bad" cholesterol.

Gene of interest – PCSK9

# ABOUT
PCSK9 (Proprotein Convertase Subtilisin/Kexin Type 9) is an enzyme encoded by the PCSK9 gene in humans.
Location: chromosome 1p32.3

Size: 25 kilobases of genomic DNA, and comprises 12 exons that encode a 692-amino-acid protein.
Conservation across species: PCSK9 is highly conserved among mammals, including chimpanzee, monkey, camel, alpaca, rat, and mouse, with an approximate amino acid identity of 99%, 96%, 82%, 81%, 77%, and 77%, respectively.

How it works: The enzymatic activity of PCSK9 is mediated by its catalytic domain, which recognises specific structural features on the LDL receptor. Interestingly, the protein retains its receptor-degrading function even after its catalytic activity is disrupted by autocatalytic cleavage — meaning it is the physical interaction between PCSK9 and the LDL receptor, rather than ongoing proteolytic activity, that drives receptor degradation.

# Why Knock Out PCSK9 using CRISPR?

PCSK9 promotes degradation of the low-density lipoprotein receptor (LDLR) and plays a central role in regulating plasma levels of LDL cholesterol, lipoprotein(a), and triglyceride-rich lipoproteins, thereby increasing the risk of cardiovascular disease.
Elevated PCSK9 levels impair LDL clearance by decreasing the availability of LDL receptors on hepatocytes, contributing to hypercholesterolemia and cardiovascular disease risk.

Meaning: High PCSK9 → High LDL-C
↑ Atherosclerosis risk
↑ Coronary artery disease
↑ Stroke, heart attack
↑ Peripheral artery disease
↑ Aortic aneurysm risk


# Steps for Designing a Guide RNA Against PCSK9

1.	Get your gene: 
Choose your target gene i.e. PCSK9
	Search NCBI Nucleotide
	Search PCSK9 Gene
	Download FASTA Format

2.	Visualization & Inspection using SnapGene Viewer:
Convert your raw FASTA Format into visual DNA map for proper understanding.

3.	Designing Guides:
	Preferred tools – CHOPCHOP, CRISPOR , BENCHLING
	Choose your target region:
Extract the 20 nt spacer. The basic goal in sgRNA design is to select a 20 nt target sequence immediately upstream of a PAM site. The complementary 20 nt spacer RNA directs the Cas9 nuclease to the specific genomic location to be edited. The target sequence should be unique within the genome to avoid off-target effects.

	Run & Review: Download the Result table with hundred’s of possible guide sequence.

4.	Scoring & Evaluating the Guides:
•	Identify PAM Sites: 
•	EFFICIENCY: Doench / CFD Score- >50% or above 70%
•	OFF TARGETS: MMO- 0 or Total off targets under 10
•	GC CONTENT: 40% – 60%
•	SELF COMPLEMENTRITY – 0 or 1

5.	Copy the Guides from Excel and view it in SnapGene Viewer. 
	Repeat the same with all 3 Cas enzymes.

6.	OUTPUT: Compile your output of top Guides into a structural report.
