# Antibody-Drug Conjugates: Mechanism of Action and Design Principles
*Author: Yuying Fan | April 2026*  

## 1. Antibody-Drug Conjugate (ADC) Biology
*Sources: [[1](https://www.sciencedirect.com/science/article/abs/pii/S2666634025002764)], [[2](https://pmc.ncbi.nlm.nih.gov/articles/PMC10544916/)]*

### <u>Core Design</u>
Antibody-Drug Conjugates (ADCs) are a new class of biopharmaceurtical therapies that combines the specificity of monoclonal antibodies with potent cytotoxicity of small molecule drugs. 

**ADCs are composed of three components:**
1) <span style="color: blue;">Antibody</span> - selectively binds to target antigens specifically located on the targeted cancer cells and drives internalization
2) <span style="color: blue;">Payload</span> - cytotoxic drug that is used for destroying cancer cells (though less common, can also be [non-cytotoxic](https://sigutlabs.com/beyond-cytotoxicity-the-rise-of-non-cytotoxic-payloads-in-adc-development/))
3) <span style="color: blue;">Linker</span> - for controlled drug release inside cancer cells; acts as the bridge between antibody and the payload

### <u>Basic Mechanism</u>
- The ADC will bind to its specific tumor-associated antigen on the cancer cell surface
- The resulting ADC-antigen complex is internalized into endosomes after receptor-mediated endocytosis
- The complex reaches lysosomes where the linker is cleaved by proteases or the acidic environment and the payload is released into the cytoplasm

The main advantage over chemotherapy is _precision delivery_: a potent payload is concentrated within the tumor. This allows for use of highly potent cytotoxins while minimizing systemic exposure, widening the therapeutic window. 

However, although theoretically, ADCs should expand the therapeutic window, clinical data contradicts this  
- ADCs rarely result in an increased maximum tolerated dose (MTD) compared to chemotherapies
- One main challenge is that each component introduces its own issues: antigen heterogeneity (antibody), drug resistance (payload), and premature release or immunogenicity (linker)
- The individual components also need to be optimized against each other; highly stable linkers would reduce premature release but this reduction in bystander effect also makes it less effective in heterogenous tumors, where only a fraction of cells express the antigen.

### <u>Design Tradeoffs That Drive Indication Selection</u>

Understanding these tradeoffs explains why indication selection is not merely a question on target expression and presence:

**Antigen selection**  
The ideal ADC target is highly expressed on tumor cells, minimally expressed on normal tissues, and efficiently internalized upon antibody binding. A high antigen density increases payload delivery, while low antigen expression in normal cells would enhance ADC selectivity and reduces systemic toxicity. Although ADC efficacy is also dependent on the type of cancer and spatial distribution; where different tumors have varied antigen expression thresholds for ADC activation.

**Linker chemistry**  
The linker connects the antibody to the payload, and is a key component in ADC pharmacookinetics. Current linkers can be classified into cleavvable and uncleavable linkers. Cleavable linkers (protease-cleavable, pH-sensitive) releases the payload inside lysosomes after internalization. Uncleavable linkers have high bond stability and release their payload only after complete lysosomal digestion of the antibody. While high stability prevents premature payload release, it can also lead to increase localized on-target, off-tumor toxicities (e.g. ocular toxicity, hepatotoxicity). Furthermore, premature release actually enables _bystander killing_, where the released drug diffuses to antigen-negative neighboring cancer cells in heterogeneous tumors.

**Payload class**  
This component is the cytotoxic component that's designed to kill the cancer cells. The most common paylods include tubulin inhibitors, TOP1 inhibitors, or DNA-alkylating agents that induce apoptosis by disrupting cell division, blocking DNA repair mechanism or damaging DNA.The payload choice will determine both the mechanism of action as well as the cancer types most likely to respond. For example, tubulin inhibitors disrupt cell division and thus favor actively diving cells. Payload potency and membrane permeability all influence which indications would be preferred. A membrane-permeable payload (enable high bystander killing potential) is advantageous in heterogeneously-expressing tumors, while a highly potent but non-permeable payload may be better suited to uniformly expressing targets.

<br>
<hr style="border: 2px solid black;">

## 2. Development of Bispecific ADC 
*Sources: [[1](https://link.springer.com/article/10.1186/s13045-025-01704-3/)], [[2](https://www.dcatvci.org/features/bispecific-adcs-the-next-targeted-therapy/)]*

Standard ADCs target a single antigen; but to increase toxicity and specificity, <span style="color: blue;">bispecific antibodies (BsAbs)</span> have been developed. BsAbs simultaneously binds to two different antigens or to two distinct epitopes on a single antigen. _Dual-epitope ADCs_, which bind to two different sites on the same antigen, have enhanced binding stability and receptor clustering. _Dual-target ADCs_, which bind to two different antigens, have improved targeting specificity to the tumor as well as wider coverage in heterogeneous tumors.

In terms of dual-target ADCs, the benefits include:
- **Enhanced internalization**: Capability of binding to two different surface receptors can increase internalization rates vs. monospecific antibodies, potentially improving payload delivery efficiency.
- **Reduced Toxicity** due to enhanced specificity and improved targeting
- **Antigen escape mitigation**: A tumor cell that downregulates one target can still be engaged via the second target. This is directly relevant in contexts where single-target ADCs have shown acquired resistance via antigen loss (e.g., HER2 loss on Enhertu progression).
- **Address tumor heterogeneity**
- **Wider patient eligibility**: Dual-positive patients are the ideal population, but single-positive patients for either target also remain eligible. This effectively broadens the addressable population.

### <u>Current Landscape in 2026</u>
The bispecific space is an emerging next generation ADC platform that is not yet crowded. Based on a recent analysis by GlobalData, bispecific ADCs remain a small (~211 bsADCs) but growing segment of the active ADC development pipeline - representing 14% of active ADC candidates, with around 84% still in preclinical or discovery stage.  

Currently (of April 15, 2026), there are no FDA approved BsADCs and only 4 have advanced to Phase III clinical trials
- Three are in oncology: izalontamab brengitecan (EGFRxHER3) by SystImmune/BMS; JSKN003 (two distinct HER2 epitopes) by Shanghai JMT-Bio; and TQB-2102 (two distinct HER2 epitopes) by Chia Tai Tianqing
- The remaining one is in metabolic disease: MariTide by Amgen, for obesity and Type 2 diabetes.

<br>
<hr style="border: 2px solid black;">
