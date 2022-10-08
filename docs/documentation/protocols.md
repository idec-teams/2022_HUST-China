# Protocols

### Error-prone PCR

<ol>

<li> Dilute primers down to 10 uM </li>
<li> Dilute DNA down to 1 ng/uL </li>
<li> Set up the reaction using the table below 
<br>
<table>
    <tr>
        <td>PCR standard buffer&nbsp;</td>
        <td>dNTP mix&nbsp;</td>
        <td>55 mM MgCl2&nbsp;</td>
        <td>0.01 mM MnCl2&nbsp;</td>
        <td>FWD Primer&nbsp;</td>
        <td>REV Primer&nbsp;</td>
        <td>Taq Polymerase&nbsp;</td>
        <td>Plasmid DNA&nbsp;</td>
        <td>H2O&nbsp;</td>
        <td>Total&nbsp;</td>
    </tr>
    <tr>
        <td>5 uL&nbsp;</td>
        <td>5 uL&nbsp;</td>
        <td>5 uL&nbsp;</td>
        <td>0.5 uL&nbsp;</td>
        <td>1.5 uL&nbsp;</td>
        <td>1.5 uL&nbsp;</td>
        <td>0.5 uL&nbsp;</td>
        <td>~ 5 ng&nbsp;&nbsp;</td>
        <td>to 50 uL&nbsp;</td>
        <td>50 uL&nbsp;</td>
    </tr>
</table>
  <br>
dNTP concentrations were varied for each base (3.5 mM dATP, 4 mM dCTP, 6mM dGTP, 13.5 mM dTTP) to promote mutations 

<li> Then run PCR using the cycling information as follows: 
<br>
1 cycle at 95°C for 60s,
<br>
25 cycles at 95°C for 30s, 
<br>
1 cycle at 72°C for 45s, 
<br>
1 cycle at 68°C for 90s,  
<br>
elongation at 68°C for 5 mins then held at 4°C.  
</li>
<li> Mutant MT plasmids were then purified and kept at -18°C. </li>
</ol>

### Colony PCR

<ol>
<li> Prepare 50 uL of sterile water in a PCR tubes </li>
<li> Pick a single colony and resuspend in 50 uL water, then draw 5 uL out into a new tube </li>
<li> Freeze 5 uL cell suspension at -20°C for at least 10 minutes </li>
<li> Prepare the master mix following the table below 
<br>
<table>
    <tr>
        <td>Component&nbsp;&nbsp;</td>
        <td>Final Concentration&nbsp;&nbsp;</td>
        <td>µL in final reaction&nbsp;&nbsp;</td>
    </tr>
    <tr>
        <td>5x GoTaq buffer&nbsp;&nbsp;</td>
        <td>1x&nbsp;</td>
        <td>4&nbsp;</td>
    </tr>
    <tr>
        <td>10mM dNTP mix&nbsp;</td>
        <td>0.2mM&nbsp;</td>
        <td>0.5&nbsp;</td>
    </tr>
    <tr>
        <td>Forward Primer PS1 10µM&nbsp;</td>
        <td>0.1 - 1µM&nbsp;</td>
        <td>2&nbsp;</td>
    </tr>
    <tr>
        <td>Reverse Primer PS2 10µM&nbsp;</td>
        <td>0.1 - 1µM&nbsp;</td>
        <td>2&nbsp;</td>
    </tr>
    <tr>
        <td>Cell Suspension&nbsp;&nbsp;</td>
        <td>5µL&nbsp;</td>
        <td>5&nbsp;</td>
    </tr>
    <tr>
        <td>GoTaq polymerase&nbsp;&nbsp;</td>
        <td>1.25 units&nbsp;</td>
        <td>0.1&nbsp;</td>
    </tr>
    <tr>
        <td>Deionised water&nbsp;&nbsp;</td>
        <td>Total 20µL&nbsp;</td>
        <td>6.5</td>
    </tr>
</table>
  </li>
<li> Mix the master mix with 5 uL cell suspension (DNA template) and PCR according to the condition in the table below 
<br>
<table>
    <tr>
        <td>Temperature&nbsp;</td>
        <td>Time&nbsp;</td>
        <td>Cycle&nbsp;</td>
        <td></td>
    </tr>
    <tr>
        <td>Initial denaturation&nbsp;</td>
        <td>95°C&nbsp;</td>
        <td>2 min&nbsp;</td>
        <td>1&nbsp;</td>
    </tr>
    <tr>
        <td>Denaturation&nbsp;</td>
        <td>95°C&nbsp;</td>
        <td>1 min&nbsp;</td>
        <td rowspan="3">25&nbsp;</td>
    </tr>
    <tr>
        <td>Annealing&nbsp;</td>
        <td>58°C&nbsp;</td>
        <td>1 min&nbsp;</td>
    </tr>
    <tr>
        <td>Extension&nbsp;</td>
        <td>72°C&nbsp;</td>
        <td>1 min&nbsp;&nbsp;</td>
    </tr>
    <tr>
        <td>Final extension&nbsp;</td>
        <td>72°C&nbsp;</td>
        <td>5 min&nbsp;</td>
        <td rowspan="2">1&nbsp;</td>
    </tr>
    <tr>
        <td>Hold&nbsp;</td>
        <td>4°C&nbsp;</td>
        <td>∞</td>
    </tr>
</table>
  </li>
<li>Run the PCR product on 1% agarose gel at 100 V for 40 minutes and visualise the result under UV exposition</li>
</ol>

### JUMP Assembly
<ol>
<li>Determine the concentration of the assembly parts with Nanodrop</li>
<li>Use DNA calculator (from Promega) to calculate fmol of each part</li>
<li>Prepare the assembly parts in the concentration of 20 fmol/uL </li>
<li>Set up 20 uL JUMP assembly reaction using 1 uL of all parts (or 20 fmol)</li>
<li>Add 2 uL of 10X T4 ligase reaction buffer, 1 uL of either BsmBI (for Level0 assembly) or BsaI-HF (for Level 1 assembly), and 0.25 uL of T4 ligase </li>
<li>Add sterile water to adjust the volume up to 20 uL </li>
<li>Incubate the reaction following the tables below <br><br>

<u>Level 0 assembly: BsmBI</u><br>
<table>
    <tr>
        <td>Temperature&nbsp;</td>
        <td>Time&nbsp;</td>
        <td>Cycle&nbsp;</td>
    </tr>
    <tr>
        <td>42°C&nbsp;</td>
        <td>15 min&nbsp;</td>
        <td>1&nbsp;</td>
    </tr>
    <tr>
        <td>42°C&nbsp;</td>
        <td>3 min&nbsp;</td>
        <td rowspan="2">30&nbsp;</td>
    </tr>
    <tr>
        <td>16°C&nbsp;</td>
        <td>3 min&nbsp;</td>
    </tr>
    <tr>
        <td>55°C&nbsp;</td>
        <td>15 min&nbsp;</td>
        <td>1&nbsp;</td>
    </tr>
    <tr>
        <td>80°C&nbsp;</td>
        <td>5 min&nbsp;</td>
        <td rowspan="2">1&nbsp;</td>
    </tr>
    <tr>
        <td>10°C&nbsp;</td>
        <td>∞</td>
    </tr>
</table><br><br>
<u>Level 1 assembly: BsaI-HF</u><br>
<table>
    <tr>
        <td>Temperature&nbsp;</td>
        <td>Time&nbsp;</td>
        <td>Cycle&nbsp;</td>
    </tr>
    <tr>
        <td>37°C&nbsp;</td>
        <td>15 min&nbsp;</td>
        <td>1&nbsp;</td>
    </tr>
    <tr>
        <td>37°C&nbsp;</td>
        <td>5 min&nbsp;</td>
        <td rowspan="2">60&nbsp;</td>
    </tr>
    <tr>
        <td>16°C&nbsp;</td>
        <td>5 min&nbsp;</td>
    </tr>
    <tr>
        <td>37°C&nbsp;</td>
        <td>60 min&nbsp;</td>
        <td>1&nbsp;</td>
    </tr>
    <tr>
        <td>80°C&nbsp;</td>
        <td>5 min&nbsp;</td>
        <td rowspan="2">1&nbsp;</td>
    </tr>
    <tr>
        <td>10°C&nbsp;</td>
        <td>∞</td>
    </tr>
</table><br>

</li>
<li>Transform the reaction directly to the competent cells </li>
</ol>

### Heat Shock Transformation

1. Defrost chemically competent cells on ice. 
2. Add 2ul of plasmid DNA or 10 uL of assembly reaction to 100 uL competent cells 
3. Flick the tube to mix and incubate on ice for 30 minutes 
4. Heat shock at 42°C for 30 seconds 
5. Incubate on ice for 2 minutes 
6. Add 1 mL SOC media and recover cells at 37°C, 200 rpm for 1 hour 
8. Spread 100 uL on an appropriate antibiotic LB/agar plate 
7. Spin the rest of the cells at 4000 rpm, remove 900 uL of the media, resuspend and spread onto another LB/agar plate 
9. Incubate plates at 37°C overnight 

### Competent Cells preparation

1. Inoculate a single colony of appropriate cells into 10ml LB media and culture overnight at 37°C, 200rpm 
2. Inoculate 1% of the overnight culture into a fresh LB media (100 mL) 
3. Incubate at 37 °C, 200rpm until OD600 = 0.3-0.6 (approx. 2 hours) 
4. Transfer to 2 x 50 ml tubes and leave on ice for 30 minutes
5. Centrifuge at 4000 x g for 5 minutes at 4 °C 
6. Gently resuspend pellet in 25 mL ice-cold 0.1 M MgCl2 and keep on ice for 30 minutes
7. Centrifuge at 4000 xg, 5 min for 5 minutes at 4 °C 
8. Gently resuspend pellet in 25 mL ice-cold 0.1 M CaCl2 and incubate on ice for 30 minutes 
9. Centrifuge at 4000 xg, 5 min for 5 minutes at 4 °C 
1. Gently resuspend pellet in 1.25 mL ice-cold CaCl2 with 15% Glycerol solution 
1. Aliquot 100 uL and flash freeze with liquid nitrogen. Store at – 80 °C until required 

### AgNO<sub>3</sub> plates preparation

<ol>
<li>Prepare the AgNO<sub>3</sub> stock solution (0.256 mg/mL) in a dark room </li>
<li>Using molten LB agar at 50°C to pour the plates add the stock solution using the table below to make the correct plates: <br><br> <table>
    <tr>
        <td>AgNO3 concentration (mg/L)&nbsp;</td>
        <td>AgNO3 stock solution volume (μL)&nbsp;&nbsp;</td>
    </tr>
    <tr>
        <td>8&nbsp;</td>
        <td>1.563&nbsp;</td>
    </tr>
    <tr>
        <td>10&nbsp;</td>
        <td>1.953&nbsp;</td>
    </tr>
    <tr>
        <td>12&nbsp;</td>
        <td>2.344&nbsp;</td>
    </tr>
    <tr>
        <td>14&nbsp;</td>
        <td>2.734&nbsp;&nbsp;</td>
    </tr>
    <tr>
        <td>&nbsp;16&nbsp;&nbsp;</td>
        <td>3.130&nbsp;&nbsp;</td>
    </tr>
    <tr>
        <td>17&nbsp;&nbsp;</td>
        <td>3.330&nbsp;&nbsp;</td>
    </tr>
    <tr>
        <td>18&nbsp;&nbsp;</td>
        <td>3.520&nbsp;&nbsp;</td>
    </tr>
    <tr>
        <td>19&nbsp;&nbsp;</td>
        <td>3.720&nbsp;&nbsp;</td>
    </tr>
    <tr>
        <td>20&nbsp;&nbsp;</td>
        <td>3.910&nbsp;&nbsp;</td>
    </tr>
    <tr>
        <td>22&nbsp;&nbsp;</td>
        <td>4.300&nbsp;&nbsp;</td>
    </tr>
    <tr>
        <td>24&nbsp;&nbsp;</td>
        <td>4.690&nbsp;&nbsp;</td>
    </tr>
    <tr>
        <td>26&nbsp;&nbsp;</td>
        <td>5.080&nbsp;&nbsp;</td>
    </tr>
    <tr>
        <td>28&nbsp;&nbsp;</td>
        <td>5.470&nbsp;&nbsp;</td>
    </tr>
    <tr>
        <td>30&nbsp;&nbsp;</td>
        <td>5.860</td>
    </tr>
</table></li>
<li>Adding the above-stated volumes of AgNO<sub>3</sub> to 50 mL LB agar produces 2 silver plates of 25mL each.  
</ol>

### Plasmid Digestion

<ol>
<li>The DNA concentration of the purified plasmid is to be determined via Nanodrop </li>
<li>A reaction mixture is made up as follows: <br><br> <table>
    <tr>
        <td>Reagent&nbsp;</td>
        <td>Final concentration&nbsp;</td>
    </tr>
    <tr>
        <td>Plasmid DNA&nbsp;</td>
        <td>50 ng/µL&nbsp;</td>
    </tr>
    <tr>
        <td>EcoRI&nbsp;</td>
        <td>1.25 U/µL&nbsp;</td>
    </tr>
    <tr>
        <td>10X CutSmart buffer&nbsp;</td>
        <td>1X&nbsp;</td>
    </tr>
    <tr>
        <td>H20&nbsp;</td>
        <td>To 20 µL</td>
    </tr>
</table>
<li>The reaction mixture is incubated at 37 °C for an hour </li>
<li>Digested DNA is run on a 1% agarose gel at 100 V for 40 minutes, then imaged under UV light </li>
