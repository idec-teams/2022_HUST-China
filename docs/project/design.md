# Design

<figure>
<img src="https://github.com/idec-teams/2022_Edinburgh-UHAS_Ghana/blob/main/figures/design-1.png?raw=true" style="width: 50vw; left: 0; right: 0; display: block; margin: auto;">
</figure> 

### Dry Lab

AlphaFold, a protein structure determination software was used to predict the structures of the various metallothioneins (MTs). Once obtaining the structures, AutoDock 4.2 was used for docking simulations, to visualise Ag<sup>+</sup> forming coordinate covalent bonds to the thiol groups in the cysteine side chains of MTs. Structures of MTs from _D. rerio, M. edulis, M. galloprovincialis, S. cerevisiae, C. sapidus_, and _P. fluorescens_ were compared in terms of the number of cysteines present, the number of Ag<sup>+</sup> ions bound, and the total energy of binding per ion. This gave us an idea of the efficiency and affinity with which the cysteines would bind Ag<sup>+</sup>. We proposed a mutant screen and selection technique, this allows future research to model and simulate results of a directed evolution screen and compare it to data we generated for the wild type variants of the above-mentioned species.  

Additionally, to help with research in the domain of metallothionein directed evolution, phylogenetic analysis followed by multiple sequence alignments for all peptide sequences for the above-mentioned MT species was conducted. Based on previous research on functional MT metal binding motifs (Ziller and Fraissinet-Tachet, 2018), possible functional mutation sites were identified. These sites could be utilised for studies exploring site-specific targeted or random mutagenesis. To aid in this exploration, mutagenic primers were designed and described (see <a href="../../supplementary_info/">Supplementary Information</a>).   

### Wet Lab

##### Random Mutagenesis Technique

Error prone PCR can be used for generating mutant libraries by using a low-fidelity DNA polymerase (Taq M0267) which lacks 3’ to 5’ exonuclease proof-reading abilities (Wilson and Keefe, 2001). Increasing MgCl2 concentrations is another way to increase mutation rates by reducing DNA polymerase fidelity. To manipulate the kinds of mutations being incorporated, the concentrations of dNTPs can be varied to increase the likelihood that dNTPs present at higher concentrations are incorporated into the newly replicated strand.  

<figure>
<img src="https://github.com/idec-teams/2022_Edinburgh-UHAS_Ghana/blob/main/figures/design-2.png?raw=true" style="width: 50vw; left: 0; right: 0; display: block; margin: auto;">
</figure>

We generated our MT mutant libraries using error-prone PCR under the abovementioned conditions. Based on the assumption that metal-binding capacity is a function of cysteine content, we increased the concentration of dTTPs to increase the incorporation of uracil point mutations in the transcript which would correspond to more UGU and UGC codons encoding more cysteines (Coyle et al. 2002).  

##### Toxic Metal Selection

 Silver is toxic to gram-negative bacteria like _E. coli_ while also functioning as a ligand for MTs (Scheuhammer and George, 1986). Other MT ligands like zinc and copper have previously been used to understand MT ligand binding and binding affinity (Xu et al. 2018), however, we found that these metals did not exhibit usable toxicity towards _E. coli_ strains to design a selection pressure. Silver is not a heavy metal nor is it a common water pollutant, however, it is a safer alternative to using lead, mercury, cadmium, or arsenic which are good ligands and common toxic pollutants. Thus, silver nitrate (AgNO<sub>3</sub>) was used, it was handled carefully in light depraved conditions to ensure nothing was precipitated.  

 DNA sequences of wild type MTs from _D. rerio, M. edulis, M. galloprovincialis_, and _S. cerevisiae_ were subjected to random mutagenesis using Error-prone PCR, the mutated products were assembled into expression plasmids. This created our mutant libraries; the wild type sequences were also similarly assembled. The DNA assembly method we used was JUMP which is a type of Type II restriction enzyme assembly method (Valenzuela-Ortega and French, 2021).  

 All expression plasmids were transformed into TOP10 _E. coli_ cells and the presence of the relevant construct was checked via colony PCR.  A single colony from each plated wildtype and its mutant counterpart were cultured and transformed into BL21(DE3) _E. coli_ cells.  

 The MT expressing cells were plated on AgNO<sub>3</sub> containing plates of increasing concentration. The concentrations were decided based on previous experiments which checked for the Maximum Inhibitory Concentration (MIC) of untransformed BL21(DE3) cells. The selection gradient was between 16 to 30 mg/L of AgNO<sub>3</sub>. Colony growth was used a metric to test the validity of our proposed selection and mutant screening technique. We hypothesised that if we grow MT expressing bacteria in toxic AgNO<sub>3</sub> concentrations, the bacteria will have to utilise MTs for metal chelation, critical for its survival. 

