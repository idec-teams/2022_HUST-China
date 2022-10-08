# Results

### Results Summary

<hr>

##### Wet Lab

The (Maximum Inhibitory Concentrations) MICs of our untransformed strains were tested for, in low AgNO<sub>3</sub> concentrations. It was observed that even at concentrations as low as, 8 mg/L TOP10 cells did not grow. Thus, they were not considered the best cell strain for developing the selection. A sharp growth fall-off in BL21(DE3) cells was observed after 16 mg/L of AgNO<sub>3</sub>. This allowed us to explore BL21(DE3) cells as our expression strain for developing the selection method. 

As described in the design section, a random mutant colony and its wild-type variant for _D. rerio, M. edulis, M. galloprovincialis,_ and _S. cerevisiae_ were put through the silver-toxicity selection method. We found that MT expressing BL21(DE3) cells had a higher MIC than the untransformed cells, suggesting that MT expression increases silver resistance in _E. coli_. There were no significant differences in the MIC of the wild-types and the mutants (growth fall-off at 20 mg/L of AgNO<sub>3</sub> was observed for all cells), suggesting that a screen for these mutants would be necessary to find any improved metallothionein mutants. 

##### Modelling and Docking

Modelling and Docking simulations generated results for the number of Ag<sup>+</sup> ions docked to each species of MT, the bind energies for each cysteine of each tested metallothionein was also generated (<a href="../../supplementary_info/">see Supplementary Information</a>). This allowed us to create a pass/fail metric based on whether the ion docking reaction would be spontaneous. Using this, total Gibbs free energy for each metallothionein was calculated along with calculating, energy of binding per ion. This gave us an in-silico analysis for which MT had the highest overall binding affinity towards Ag+ ions along with each MT’s binding “efficiency.” We found, that _P. fluorescens_ which has the fewest number of cysteines, binds the greatest number of ions, therefore having the lowest total Gibbs free energy and Gibbs free energy of binding per ion (-0.407 kcal/mol). This suggests that _P. fluorescens_ has a high binding efficiency and affinity for Ag<sup>+</sup> ions. Contrastingly, MTs like _M. edulis_ contain more cysteines but bind to fewer Ag<sup>+</sup> ions thus having a lower binding efficiency and affinity. 

### Results and Discussion section of the report:

<i><b>Determining inhibitory concentration of BL21(DE3)</b></i>

To establish the MIC of untransformed BL21(DE3) and TOP10 cells, they were plated on a range of AgNO<sub>3</sub> concentrations starting with 8 mg/L until a fall-off in growth was observed (16 mg/L for BL21(DE3) cells). Cells were observed forming lawns until 16 mg/L and 17 mg/L with a sharp decline after that. This allowed us to explore 16 mg/L as the starting baseline concentration for the MT expressing cells. Contrastingly, TOP10 cells did not grow on any selected concentration suggesting that their silver resistance was too low to setup a functional selection pressure (Figure 1).   

<figure>
<img src="https://github.com/idec-teams/2022_Edinburgh-UHAS_Ghana/blob/main/figures/results-1.png?raw=true" style="width: 50vw; left: 0; right: 0; display: block; margin: auto;">
<figcaption><b>Figure 1.</b> The cultured strains were plated in duplicate on AgNO<sub>3</sub> plates from 8-18 mg/L. The number of colonies grew on the plate was counted, with a solid colour representing a bacterial lawn and blank indicating no growth. It was observed that there is a growth fall-off at 16 mg/L for BL21(DE3) cells while the lowest concentrations of AgNO<sub>3</sub> was observed to be toxic towards TOP10 cells. </figcaption>
</figure>


<i><b>Error prone PCR mutant library generation</b></i>

Error prone (EP) PCR was used to generate a mutant library of MTs (<a href="../design/">see Design section</a>). A higher concentration of dTTPs was used which would increase the chance of mutations with Uracil in the transcript. This is favourable for UGU and UGC as outcomes, which are the codons for cysteine (Section 4.3).  

The mutated PCR products were double-stranded linear fragments of DNA which were assembled into the ORF of pJUMP29-1A(lacZ) level 1 plasmids containing a constitutive promoter (J23100), using level 0 parts (<a href="../../supplementary_info/">see Supplementary Information S.1</a>) following the JUMP assembly protocol (Valenzuela-Ortega and French, 2021). The same assembly method was used to generate WT MT expression plasmids.  

All Level 1 plasmids were transformed into TOP10 cells and subjected to blue-white colony screening where blue colonies represent lacZ positive control. White colonies were checked for containing the insert using colony PCR (Section 4.2.2). A single WT MT expressing colony was picked and cultured to be transformed into BL21(DE3) cells for protein expression and negative selection. Similarly, a random mutant colony was picked, verified for containing the insert and cultured for BL21(DE3) transformation and subsequent selection. The mutants and wild type MT expressing cells were plated on AgNO<sub>3</sub> plates of increasing concentration (16-30 mg/L).  

<h4 style="text-align: center;">Negative selection for enhanced metal binding capacity </h4>

The assembled plasmids were transformed into TOP10 cells. This meant the mutant libraries were plated on blue/white colony screening plates in TOP10 cells. To transfer the DNA of each white colony on a plate to BL21(DE3) cells would not be feasible, since the MIC of TOP10 cells was not determined (Figure 1) we could not screen for the best mutant. Hence, one mutant was selected at random and transformed to our expression strain.   

<figure>
<img src="https://github.com/idec-teams/2022_Edinburgh-UHAS_Ghana/blob/main/figures/results-2.png?raw=true" style="width: 30vw; left: 0; right: 0; display: block; margin: auto;">
<figcaption><b>Figure 2. a)</b> Illustrates, colony counts of BL21(DE3) recombinantly expressing MTs. In the figure, BL21 (DE3) cells expressing MTs of Danio rerio (DR), Saccharomyces cerevisiae (SC), Mytilus galloprovincialis (MG), and Mytilus edulis (ME) were plated, the wild type is shown in grey and the randomly picked mutant (EP) in red. The figure shows a significant difference in MIC between all the MTs expressing cells and the control. The figure doesn’t indicate if the mutants were better than WTs or vice versa. However, some MTs grew at higher concentration but did not grow at lower concentrations. <b>b)</b> Shows an example of the raw data using WT MT DR plates. The colonies were counted and photographed for each species (<a href="../../supplementary_info/">see Supplementary Information S.3</a>). </figcaption>
</figure>


MTs originating from almost all species, except for S. cerevisiae and M. galloprovincialis grew as lawns at 16 and 17 mg/L of AgNO<sub>3</sub>. The results indicated that there is a sharp decrease in BL21(DE3) growth at 20 mg/L beyond which no lawns were observed for the four species of MTs shown in Figure 3a. Interestingly, in several plated samples (EP MT (DR), WT MT (DR) and WT MT (MG)) no growth was observed in lower concentrations while some colonies grew at higher concentrations. These colonies are good candidates for sequencing analysis and re-plating at higher concentrations. Additionally, the results also indicate that a randomly selected mutant from an EP PCR library did not outperform the wildtype variant of the same species indicating that a screen of the entire mutant library is pertinent.  

<h4 style="text-align: center;">2. Docking simulations </h4>

FASTA sequences of the six MTs were taken from the NCBI database. These sequences were folded, and the Alphafold structures shown in Figure 3 were predicted. These structures were docked to Ag<sup>+</sup> using AutoDock 4.2 such that the structures were hydrated and energy minimised while allowing gamma sulphurs on the sidechains of cysteines to form coordinate covalent bonds with the metal ligand (Figure 3g). The energy minimisation was done after each ligand was docked. MTs contain many cysteines however each cysteine does not carry the same binding affinity for the ligand. This was accounted for using a pass/fail metric (<a href="../../supplementary_info/">see Supplementary Information S.12</a>) where the passed cysteine had negative Gibbs free energy thus making the binding spontaneous.  

<figure>
<img src="https://github.com/idec-teams/2022_Edinburgh-UHAS_Ghana/blob/main/figures/results-3.png?raw=true" style="width: 50vw; left: 0; right: 0; display: block; margin: auto;">
<figcaption><b>Figure 3 a-f) </b>The structures on the left side are generated by AlphaFold using FASTA sequences, and on the right side are the Autodock-generated docking simulations of Ag+ ligands forming coordinate covalent bonds to the WT MT structures. <b>(a)</b> Danio rerio. <b>(b)</b> S. cerevisiae. <b>(c)</b> Mytilus galloprovincialis. <b>(d)</b> Mytilus edulis. <b>(e)</b> Pseudomonas fluorescens. <b>(f)</b> Callinectes sapidus. <b>g)</b> on the left is the undocked structure of D. rerio with all cysteine sidechains visible, the structure on the right is the docked D. rerio structure, which illustrates the conformational change in the gamma sulphurs upon forming coordinate covalent bonds.</figcaption>
</figure>

Furthermore, based on the number of ligands bound per MT a score for the Gibbs free energy of binding per ion was generated for all WT MT sequences (Table 1). The data indicates that _P. fluorescens_ which has the fewest number of cysteines, binds the greatest number of ions, therefore having the lowest total Gibbs free energy and Gibbs free energy of binding per ion (-0.407 kcal/mol). This suggests that _P. fluorescens_ has a high binding efficiency and affinity for Ag<sup>+</sup> ions. Contrastingly, MTs like M. edulis contain more cysteines but bind to fewer Ag<sup>+</sup> ions thus having a lower binding efficiency and affinity.  

<h4 style="text-align:center;">Table 1. In-silico modelled Gibbs free energy</h4>

<table>
    <tr>
        <th>Metallothionein</th>
        <th>Total cysteines</th>
        <th>Number of Ag<sup>+</sup> ions docked</th>
        <th>Total free energy of binding (kcal/mol)</th>
        <th>Gibbs free energy of binding per ion (kcal/mol)</th>
    </tr>
    <tr>
        <td><i>M. edulis </i></td>
        <td>20</td>
        <td>4</td>
        <td>-0.83</td>
        <td>-0.208</td>        
    </tr>
    <tr>
        <td><i>M. galloprovincialis </i></td>
        <td>21</td>
        <td>5</td>
        <td>-0.85</td>
        <td>-1.70</td>        
    </tr>
    <tr>
        <td><i>D. rerio </i></td>
        <td>20</td>
        <td>4</td>
        <td>-0.58</td>
        <td>-0.145</td>        
    </tr>
    <tr>
        <td><i>C. sapidus </i></td>
        <td>18</td>
        <td>5</td>
        <td>-0.65</td>
        <td>-0.130</td>        
    </tr>
    <tr>
        <td><i>P. fluorescens </i></td>
        <td>9</td>
        <td>6</td>
        <td>-2.44</td>
        <td>-0.407</td>        
    </tr>
    <tr>
        <td><i>S. cerevisiae</i></td>
        <td>12</td>
        <td>5</td>
        <td>-1.87</td>
        <td>-0.374</td>        
    </tr>
        
</table>


<figure>
<img src="https://github.com/idec-teams/2022_Edinburgh-UHAS_Ghana/blob/main/figures/results-4.png?raw=true" style="width: 50vw; left: 0; right: 0; display: block; margin: auto;">
<figcaption><b>Figure 4. a)</b> Multiple sequence alignments of the MTs were followed by conservation analysis against phylogenetically relevant MTs. <b>b)</b> Shows the sequence of <i>Danio rerio</i> metallothionein, with amino acids targeted for potential mutagenesis highlighted in red. </figcaption>
</figure>

MTs contain metal-binding motifs which typically present as: 
<p style="text-align: center;">cys-x-cys, cys-x-x-cys, x-cys-cys-x and x-cys-cys-cys-x</p>

Here, x denotes any amino acid other than cysteine (Ziller and Fraissinet-Tachet, 2018). We hypothesised that increasing the number of these motifs in a MT molecule would increase its number of metal-binding sites as long and the protein was functionally folded. 

Using Consurf, we analysed our MSA, it generated conservation scores based on phylogenetic analysis. We identified the less conserved regions between two cysteines at least 3 residues apart (Figure 4a). These less conserved sites (Figure 4b) are proposed as possible sites to explore for site-specific mutagenesis using random mutagenic methods like GeneOrator or targeted mutagenesis. We created mutagenic primers for the same (<a href="../../supplementary_info/">see Supplementary Information S.7, S.8</a>). 

<u><b>1. Discussion</b></u>

As our results indicate, we did not screen the entire mutant library (Figure 2a). This was a consequence of several failed DNA assemblies and transformation into BL21 (DE3) cells directly from the JUMP assembly reaction. We observed no colony growth post-transformation, and several colony PCRs showed that the chemically competent BL21 (DE3) cells did not contain the expression plasmid for our MTs. We tried various troubleshooting measures like increasing DNA concentrations in the plasmid assembly reaction, trying different protocols to make a new batch of chemically competent BL21 (DE3) cells. Each assembly was tested via Eco R1 digestion and colony PCR. Given the unsuccessful results, we tried transforming our assemblies onto TOP10 cells (_E. coli_ strain) which was successful, this made it relevant to test the AgNO<sub>3</sub> MIC of TOP10 cells, replacing BL21(DE3) in the screen. It was observed that AgNO<sub>3</sub> was significantly more toxic for TOP10 cells than BL21 (DE3) cells. No growth was observed in TOP10 cells at concentrations as low as 8 mg/L. Consequently, we were not able to establish the MIC of TOP10 cells towards AgNO<sub>3</sub> which meant that we couldn’t successfully establish a starting concentration for a TOP10 cell based mutant screen. We re-designed our experimental pipeline to focus on inferring whether AgNO<sub>3</sub> toxicity was a valid method for a possible BL21(DE3) mutant screen.   

For this, one random mutant MT expressing colony was taken and transformed to BL21(DE3) cells and plated on the AgNO<sub>3</sub> plates, alongside a WT variant of the same species. This result doesn’t indicate if random mutagenesis is the best approach for directed evolution of MTs and other techniques involving site-specific and targeted mutagenesis should be explored. 

The results (Figure 2a) show that MT expression does have an impact on the overall MIC of the cell. However, it is difficult to conclude whether the rise in MIC was due to outliers, or metal bioaccumulation. Additionally, this change could be due to cells down-regulating metal transporter proteins, faulty plates with precipitation, or expression of other proteins. To ensure that the original screening hypothesis holds true, the selection needs to be done using controls for all the above stated factors along with the necessary repetition for more accurate data. Protein expression was also not factored into the results, survival at higher concentration for each MT could be because the MTs are chelating more metals per molecule or because the protein expression of 1 MT species is significantly higher than others. 

The selection results indicate that the mutants selected did not outcompete WTs for survival, to validate the scope of this screen as a tool to study MTs for bioaccumulation, it would be necessary to do a complete mutant library screen in BL21(DE3) cells. The relevant mutants should be characterised by mass-spec, sequenced, and rescreened along with comparative docking simulations (Figure 1a).  

The docking simulations (Figure 3) and Table 1 was generated using assumptions. The maximum Gibbs free energy (Torsional free energy) was kept constant at 0.60 kcal/mol (<a href="../../supplementary_info/">see Supplementary Information S.13</a>) for all MT species because new atom types cannot be used to calculate the Root Mean Square Deviation (RMSD) of the ligand. This impacts the overall accuracy of the docking.   

The overall experimental output showcased the shift in survival between untransformed BL21 (DE3) cells the MT expressing cells, _P fluorescens_, showed more “efficient” binding based on the data from Table 1, however, it was never tested experimentally due to flaws in the DNA construct along with _C. sapidus_ which wasn’t tested due to a shortage of resources. 

This study shows that there is potential in exploring MTs as an option when considering biotechnological solutions towards problems as scary as the water pollution crisis in Ghana. The novel screening method explored here has not been characterised fully but leaves room for further directed evolution experiments and a platform for doing so has also been provided with the proposal for alternate methods of random site-specific mutagenesis. 

