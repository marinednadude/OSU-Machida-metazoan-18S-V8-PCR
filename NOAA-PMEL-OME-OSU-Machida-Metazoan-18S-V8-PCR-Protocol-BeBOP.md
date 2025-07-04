---
#MIOP terms
methodology_category: Omics analysis
project: NOAA Pacific Marine Environmental Laboratory Ocean Molecular Ecology Group protocols
purpose: 'PCR [OBI:0000415]'
analyses: 'PCR [OBI:0000415]'
geographic_location: 'North East Pacific Ocean [GAZ:00013765], Bering Sea [GAZ:00008990], Arctic Ocean [GAZ:00000323]'
broad_scale_environmental_context: marine biome [ENVO:00000447], marine photic zone [ENVO:00000209]
local_environmental_context: oceanic epipelagic zone biome [ENVO:01000035], marine benthic biome [ENVO:01000024]
environmental_medium: 'sea water [ENVO:00002149]'
target: '18S Ribosomal RNA [NCIT:C48172]'
creator: 'Shannon Brown, Zachary Gold'
materials_required: 'vortexer [OBI:0400118], PCR instrument [OBI:0000989]'
skills_required: 'sterile technique, pipetting skills, and standard molecular technique'
time_required: 180
personnel_required: 1
language: en
issued: '2025-06-10'
audience: 'scientists'
publisher: 'NOAA Pacific Marine Environmental Laboratory Ocean Molecular Ecology Group; University of Washington Cooperative Institute for Climate, Ocean, & Ecosystem Studies'
hasVersion: 1
license: CC0 1.0 Universal
maturity level: mature

# FAIRe terms
pcr_0_1: 1
inhibition_check_0_1: not applicable
inhibition_check: not applicable
thermocycler: Generic thermal cycler
assay_name: ssu18sv8_machida_OSUmod
assay_validation: This assay was validated by Oregon State University's Center for Quantitative Life Sciences via multi-step in-silico, in-vitro, and in-situ validations.
targetTaxonomicAssay: "18S rRNA gene sequencing targeting the V8 region using primers Machida 18S #3 F and Machida 18S #5 R"
targetTaxonomicScope: metazoan organisms
target_gene: 18S
target_subfragment: V8
ampliconSize: 380
pcr_primer_forward: GYGGTGCATGGCCGTTSKTRGTT
pcr_primer_reverse: GTGTGYACAAAGGBCAGGGAC
pcr_primer_name_forward: Machida_18S V8 F
pcr_primer_name_reverse: Machida_18S V8 R
pcr_primer_reference_forward: https://doi.org/10.1371/journal.pone.0134314
pcr_primer_reference_reverse: https://doi.org/10.1371/journal.pone.0134314
pcr_primer_vol_forward: 5.0
pcr_primer_vol_reverse: 5.0
pcr_primer_conc_forward: 1.0
pcr_primer_conc_reverse: 1.0
probeReporter: not applicable
probeQuencher: not applicable
probe_seq: not applicable
probe_ref: not applicable
probe_conc: not applicable
commercial_mm: 2x KAPA HiFi HotStart Ready Mix 
custom_mm: PCR reactions were run in 25 μL reaction volumes, with 2.5 μL of DNA, 12.5 μL 2x KAPA HiFi HotStart Ready Mix, and  5 μL of each primer (1 μM).
block_seq: not applicable
block_ref: not applicable
block_taxa: not applicable
amplificationReactionVolume: 25
pcr_dna_vol: 2.0
pcr_rep: 3.0
nucl_acid_amp: 
pcr_cond: initial denaturation:95_3;normal_cycling;denaturation:95_0.5;annealing:55_0.5;elongation:72_0.5;final elongation:72_5;25
annealingTemp: 55
pcr_cycles: 25
pcr_analysis_software: "missing: not provided"
pcr_method_additional: Quality was validated via a Qubit Fluorometer.
---

# NOAA PMEL OME Machida Metazoan 18S V8 PCR Protocol
**NOTE: This is NOT THE RECOMMENDED Machida 18S V8 PCR protocol, for the standard OME protocol, see [NOAA-PMEL-OME-Machida-Metazoan-18S-V8-PCR-Protocol-BeBOP.md](https://github.com/marinednadude/NOAA-PMEL-OME-Machida-Metazoan-18S-V8-PCR-Protocol-BeBOP/blob/main/NOAA-PMEL-OME-Machida-Metazoan-18S-V8-PCR-Protocol-BeBOP.md).**

## PROTOCOL INFORMATION

### Minimum Information about an Omics Protocol (MIOP)

- MIOP terms are listed in the YAML frontmatter of this page.
- See <https://github.com/BeBOP-OBON/miop/blob/main/model/schema/terms.yaml> for list and definitions.

### Making eDNA FAIR (FAIRe)

- FAIRe terms are listed in the YAML frontmatter of this page.
- See <https://fair-edna.github.io/download.html> for the FAIRe checklist and more information.
- See <https://fair-edna.github.io/guidelines.html#missing-values> for guidelines on missing values that can be used for missing FAIRe or MIOP terms.

### Authors

- All authors known to have contributed to the preparation of this protocol, including those who filled in the template.
- Visit https://orcid.org/ to register for an ORCID.
- Date is the date the author first worked on the protocol.

| PREPARED BY | AFFILIATION | ORCID | DATE |
| ------------- | ------------- | ------------- | ------------- |
|Matt Galaska	|Ocean Molecular Ecology, NOAA PMEL|	0000-0002-4257-0170	|2024-02-01|
|Sean McAllister	|Ocean Molecular Ecology, NOAA PMEL & UW CICOES	|0000-0001-6654-3495	|2024-02-01|
|Shannon Brown | Ocean Molecular Ecology, NOAA PMEL & UW CICOES  | 0000-0001-9808-2638 |2025-05-01|
|Zachary Gold	|Ocean Molecular Ecology, NOAA PMEL	|0000-0003-0490-7630	|2025-05-01|

### Related Protocols

- This section contains protocols that should be known to users of this protocol.
- Include the link to each protocol.
- Include the version number and release date (if available).
- Internal/External: "Internal" are derivative or altered protocols, or other protocols in this workflow. "External" are protocols from manufacturers or other groups.

| PROTOCOL NAME | LINK         | VERSION      | RELEASE DATE | INTERNAL/EXTERNAL |
| ------------- | ------------ | ------------ | ------------ | ----------------- |
| NOAA-PMEL-OME-Machida-Metazoan-18S-V8-PCR-Protocol-BeBOP | https://github.com/marinednadude/NOAA-PMEL-OME-Machida-Metazoan-18S-V8-PCR-Protocol-BeBOP/blob/main/NOAA-PMEL-OME-Machida-Metazoan-18S-V8-PCR-Protocol-BeBOP.md | 1.1.0 | 2025-05-01 | Internal |
| Illumina 16S Metagenomic Sequencing Library Preparation |https://support.illumina.com/documents/documentation/chemistry_documentation/16s/16s-metagenomic-library-prep-guide-15044223-b.pdf| 15044223 B | 2013-11-27  | External |

### Protocol Revision Record

- Version numbers start at 1.0.0 when the protocol is first completed and will increase when changes that impact the outcome of the procedure are made (patches: 1.0.1; minor changes: 1.1.0; major changes: 2.0.0).
- Release date is the date when a given protocol version was finalised.
- Description of revisions includes a brief description of what was changed relative to the previous version.

| VERSION | RELEASE DATE | DESCRIPTION OF REVISIONS |
| ------------- | ------------- | ------------- |
| 1.0.0 | 2025-05-01 | Initial release |
| 1.1.0 | 2025-06-10 | Content revisions, format editing, and FAIRe updates |

### Acronyms and Abbreviations

| ACRONYM / ABBREVIATION | DEFINITION |
| ------------- | ------------- |
|18S V8 rRNA gene|18S ribosomal nucleic acid sequencing assay targeting V8 gene region |
|AMBON| Arctic Marine Biodiversity Observation Network |
|BSC	|Biosafety cabinet|
|CQLS	|Center for Quantitative Life Sciences|
|DNA	|Deoxyribonucleic acid|
|eDNA	|environmental DNA|
|EtOH| Ethanol|
|IDT| Integrated DNA Technologies
|MBON	|Marine Biodiversity Observation Network|
|NTC	|No template control
|OSU | Oregon State University |
|PCR| Polymerase chain reaction |
|PPE| Personal protective equipment |

### Glossary

| SPECIALISED TERM | DEFINITION |
| ------------- | ------------- |
| Extraction blank  | Extraction negative control. Typically nuclease-free water or an empty filter is run through the DNA extraction process to control for contamination in the DNA extraction step. |
| Field blank | Sampling negative control. Typically distilled or reverse osmosis water is run through a filter like a seawater eDNA sample to control for contamination in the field sampling step.  |
| No template control | PCR negative control. Typically nuclease-free water is loaded in place of a sample on a PCR to control for contamination in the PCR step. |
| Positive control  | PCR positive control. Typically a synthetic DNA strand, non-indigenous DNA extract, or intentionally designed mock community is loaded in place of a sample on a PCR to control for contamination and index hopping in the PCR step. |

## BACKGROUND
**NOTE: This is NOT THE RECOMMENDED Machida 18S V8 PCR protocol, for the standard OME protocol, see [NOAA-PMEL-OME-Machida-Metazoan-18S-V8-PCR-Protocol-BeBOP.md](https://github.com/marinednadude/NOAA-PMEL-OME-Machida-Metazoan-18S-V8-PCR-Protocol-BeBOP/blob/main/NOAA-PMEL-OME-Machida-Metazoan-18S-V8-PCR-Protocol-BeBOP.md).**

### Summary

This protocol is for amplifying the small subunit ribosomal ribonucleic acid (SSU rRNA) 18S v8 gene in eukaryotes. The primers (forward: Machida 18S #3 F, reverse: Machida 18S #5 R) were first presented in [Machida & Nowlton 2012](https://doi.org/10.1371/journal.pone.0046180). The target amplicon size is ~380 base pairs.

This primer set targets metazoan organisms (e.g., molluscs, arthropods, and vertebrates). Important note: this primer also amplifies non-target organisms, including single-celled phytoplankton (e.g., dinoflagellates, diatoms, and haptophytes).

The protocol presented here is intended as the first PCR of a two-step PCR next-generation sequencing library preparation using Illumina Nextera Unique Dual Indices. Our written protocol does not include the second PCR step in which unique library-specific barcodes are attached to each round 1 PCR product. 

### Method Description and Rationale

These primers were chosen because they are used by the Arctic Marine Biodiversity Observation Network (AMBON) as well as MBON, a leader in the field of eDNA research and an important partner in the Arctic/Alaska region, to generate marine eDNA time series. Work was completed at the Center for Quantitative Life Sciences (CQLS) at OSU, as they were able to continue labwork during the pandemic.

This amplification protocol is accessible to most molecular biology labs.

### Spatial Coverage and Environment(s) of Relevance

This protocol has been standardized by CQLS OSU and has been used on hundreds of DNA samples taken from coastal stations off the western coast of North America in the Northeastern Pacific Ocean, Bering Sea and Arctic Ocean (primarily off California, Oregon, Washington, and Alaska). Samples collected range in depth from surface ocean (epipelagic biome) to just off bottom (benthic biome) at varying distances from shore (coastal to off-shelf).

### Personnel Required

One person with molecular biology experience.

### Safety

This protocol does not involve any hazardous chemicals, although standard precautions, including wearing PPE, should be taken to avoid skin and eye exposure to chemical reagents.

### Training Requirements

Molecular biology training (including, at a minimum, sterile technique, pipetting small volumes, and programming and running PCR thermocyclers) is required to conduct this protocol.

### Time Needed to Execute the Procedure

PCR preparation, running the PCR protocol, and PCR clean-up for a single 96-well plate takes 3 hours (180 minutes), 45 mins of which is the thermocycler run time. Additional plates can be run simultaneously without greatly increasing the time required. 

## EQUIPMENT

- Description: E.g., "filter".
- Product Name and Model: Provide the official name of the product.
- Manufacturer: Provide the name of the manufacturer of the product.
- Quantity: Provide quantities necessary for one application of the standard operating procedure (e.g., number of filters).
- Remark: For example, some of the consumables may need to be sterilized, some commercial solutions may need to be diluted or shielded from light during the operating procedure.

For a 96-well Plate:

| DESCRIPTION | PRODUCT NAME AND MODEL | MANUFACTURER | QUANTITY | REMARK |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| **Durable equipment**|
|Pipetter: 1-10 μl|P10|Generic Brand|1||
|Pipetter: 2 - 20 μL| P20|Generic Brand|	1||
|Pipetter: 20 - 200 μL| P200|Generic Brand|	1||
|Pipetter: 100-1000 μL| P1000	|Generic Brand	|1||
|Thermocycler| |Generic Brand| 1|	|
| Mini-centrifuge | Personal mini centrifuge  | Generic Brand | 1 | Needs to fit 1.5-2.0 mL tubes |
| Vortex | Benchtop vortex mixer | Generic Brand | 1 | |
| PCR cooler rack | PCR cooler 0.2-0.5 mL | Generic Brand | 1 ||
| 1.5 mL tube cooler rack | Benchtop cooler | Generic Brand   | 1 |  |
| 2 mL tube rack | Microcentrifuge tube rack | Generic Brand | 1 |  |
| 0.2 mL PCR plate rack | PCR tube rack for 0.2 mL micro-tubes | Generic Brand | 1 |  |
|Wash bottle|Safety Wash Bottle for Ethanol and Bleach|Generic Brand|2||
|Freezer|Freezer capable of reaching and maintaining -20°C|Generic Brand|1| Used to store DNA and PCR reagents |
|Fridge| Refrigerator capable of reaching and maintaining 4°C|Generic Brand|1|Used to store some PCR reagents |
|Cryoboxes||Generic Brand|2| |
| Qubit | Qubit™ 3 Flurometer| Thermo Scientific | 1|Can be substituted with any version |
| Large desktop centrifuge || Generic Brand | 1|Needs to fit PCR plates |
| Magnetic Stand-96 | | Generic Brand | 1||
| **Consumable equipment** |
| 1000 μL pipette tips | | Generic Brand | 4 | Recommend sterile and filtered |
| 200 μL pipette tips  | | Generic Brand | 350| Recommend sterile and filtered |
| 20 μL pipette tips  | | Generic Brand | 105| Recommend sterile and filtered |
| 10 μL pipette tips  | | Generic Brand | 194 | Recommend sterile and filtered |
| PCR plates | LoBind PCR plates, semi-skirted (96-wells)| Eppendorf | 2 | |
| PCR aluminum foil | Adhesive sterile PCR foil seals | Generic Brand | 5 | Must be sterile |
| 2 mL tubes | DNA LoBind 2.0 mL tubes, PCR-clean| Generic Brand |5 | Must be sterile |
| 1.5 mL tubes | DNA LoBind 1.5 mL tubes, PCR-clean| Generic Brand |2 | Must be sterile |
| 15 mL falcon tube | | Generic Brand |1 |  |
| Qubit assay tubes | | Thermo Scientific | 98 | |
| Kimwipes | Delicate task wipes | Generic Brand | 5 | |
| Nitrile gloves | | Generic Brand | 4 | Does not come sterile, must be sterilized before use (10% bleach followed by 70% EtOH) |
| Lab notebook | Durable, hardcover lab notebook | Generic Brand | 1 | Dedicated to the lab space|
| Writing utensils | Sharpies and pens | Generic | 2 | Dedicated to the lab extraction space. Not made of wood - must be able to be wiped down with bleach/EtOH  |
|**Optional Equipment**|||			
|8-channel multichannel pipetter: 1-10 μL| Multichannel P8X10| Generic Brand|	1||
|8-channel multichannel pipetter: 2-20 μL| Multichannel P8X20| Generic Brand|	1||
|BluePippin|BluePippin System BLU0001|Sage Science|1|Can be substituted with AMPure XP beads for PCR clean-up - additional materials required but not listed |
| **Chemicals** |
| PCR master mix | 2x KAPA HiFi HotStart ReadyMix | Roche Diagnostics | 1300 μl per plate | Store at -20°C |
| Forward primer | Custom oligo | IDT |520 μl per plate| Store at -20°C|
| Reverse primer| Custom oligo | IDT | 520 μl per plate | Store at -20°C|
| Camel Positive control| Zyagen Labs CAMEL control genomic DNA, in TE buffer | IDT | 2 μl per plate | Store at -20°C |
| Ferret Positive control| Zyagen Labs FERRET control genomic DNA, in TE buffer | IDT | 2 μl per plate | Store at -20°C |
| Qubit HS Buffer | Qubit dsDNA HS Reagent | Thermo Scientific | 100 μl per plate | |
| Qubit HS Reagent | Qubit dsDNA HS Buffer| Thermo Scientific | 20 mL per plate||
| Qubit HS S1 | Qubit™ dsDNA HS Standard #1 | Thermo Scientific | 10 μl per plate| |
| Qubit HS S2 | Qubit™ dsDNA HS Standard #2 | Thermo Scientific | 10 μl per plate| |
| 10 mM Tris | 10 mM Tris pH 8.5 | Fisher Scientific | 5040 μl per plate (for clean-up) | Store at -20°C|
| AMPure beads | AMPure XP beads | Fisher Scientific | 1920 μl per plate (for clean-up) | Store at fridge|
| 70% EtOH | Molecular grade ethanol| Generic Brand | 40 mL |
| 10% bleach| Hypochlorite bleach |Clorox| 40 mL | Remake every ~5 days as bleach decomposes quickly at 10% concentration |

## STANDARD OPERATING PROCEDURE
**NOTE: This is NOT THE RECOMMENDED Machida 18S V8 PCR protocol, for the standard OME protocol, see [NOAA-PMEL-OME-Machida-Metazoan-18S-V8-PCR-Protocol-BeBOP.md](https://github.com/marinednadude/NOAA-PMEL-OME-Machida-Metazoan-18S-V8-PCR-Protocol-BeBOP/blob/main/NOAA-PMEL-OME-Machida-Metazoan-18S-V8-PCR-Protocol-BeBOP.md).**

### Preparation

1. Sterilize workspaces and durable equipment, including pipettes, with 10% bleach. Then wipe down all surfaces and equipment with 70% EtOH.
2. Label all PCR plates both on the side of the plate and on the top of the foil (in the plate margins).

### PCR

**Primer Sequences without Adapters**: PCR primer sequences (**target sequence bolded**)

| PCR Primer Name | Direction | Sequence (5’ -> 3’)|
| ----- | ----- | ----- |
|Machida_18S V8 F | Forward |**GYGGTGCATGGCCGTTSKTRGTT** |
| Machida_18S V8 R | Reverse | **GTGTGYACAAAGGBCAGGGAC** |

[Machida & Nowlton 2012](https://doi.org/10.1371/journal.pone.0046180) published an erratum fixing primer orientation, but we have confirmed that these sequences are correct.

**Reaction Mixture**: PCR reagents, volumes, initial, and final concentrations

| Reagent |Volume (μL) per plate| Volume (μL) per reaction | Intial concentration| Final concentration|
| ----- | ----- | ----- |----- |-----|
|2x KAPA HiFi HotStart Ready Mix  |1300|  12.5|200% | 100%|
| Forward Primer| 520| 5|1 μM | 0.2 μM |
| Reverse Primer |520| 5|1 μM |0.2 μM |
| Template DNA|N/A| 2.5 | 100%|10% |
| **Total**|**2340**| **25** | **N/A** |**N/A**|

This table breaks down the mixture per plate and per reaction. When running full plates (96-wells), each reagent volume was multiplied by 104 (96+8 extra sample volumes to account for pipetting error) when preparing the final master mix.

**PCR Cycling Program**:

| PCR step | Temperature | Duration | Repetition |
| ----- | ----- | ----- | ----- |
|Initial denaturation|	95°C	|3 min|	1X
|**Normal Cycling**||||
|Denaturation|	95°C|	30s|	25X |
|Annealing|	55°C|	30s	| 25X |
|Extension 	|72°C	|30s	|25X|
|Final extension	|72°C	| 5min	|1X|
|Hold	|4°C	|∞	|1X|

**Step-by-Step Instructions:**

*Note: When possible, PCR set-up should be carried out in a separate pre-PCR space that is distinct from where the post-PCR space where thermocyclers are located and all post-PCR processing is performed. No equipment, consumables, or reagents should be shared between pre- and post-PCR spaces with a unidirectional flow of sample processing.*

1. Set out primers and positive control to thaw.
2. Vortex and spin down thawed positive control, primers, and nuclease-free water. Then tap/flick the PCR master mix rather than vortexing before spinning down. Thawed reagents should be stored in a cooling block or fridge when not in use.
3. Pool reagents to make final master mix, as denoted in the reagent mixture table.
4. Set out the template DNA to thaw if frozen.
5. Aliquot 22.5 μL of final master mix into each well of the PCR plate. The plate should sit in a cold block to ensure the reagents remain at a low temperature.
6. Add 2.5 μL DNA template to each well. If input DNA was > 10ng/µL, dilute 1:3. Reserve two wells for the positive control and a no template control (NTC). 
7. To one well each, add 2.5 μL of the positive control and 2.5 μL of nuclease-free water for the NTC.
8. Seal the PCR plate with foil.
9. Spin down the plate and then transport in cooler blocks before placing in the thermocycler.
10. Run thermocycler protocol.
11. PCRs were run in triplicate for each sample and then pooled evenly by volume.

### Quality control

Qubit quantification was used to test the success of the amplicon amplification. CQLS OSU followed the standard [Qubit dsDNA HS Assay Kit protocol](https://assets.thermofisher.com/TFS-Assets/LSG/manuals/Qubit_dsDNA_HS_Assay_UG.pdf) by ThermoFisher.

#### Positive Control
A positive control is used in every PCR run to verify the success of the PCR reaction. 2μL of both Camel and Ferret positive controls at 0.5mg/ml were used in place of template DNA. One well per plate per positive control is allotted. 

[Zyagen Camel Genomic DNA (Cat_No:GC-270)](https://www.zyagen.com/product/camel-genomic-dna/)

[Zyagen Ferret Genomic DNA (Cat_No:GF-180)](https://www.zyagen.com/product/ferret-genomic-dna/)

#### Negative Control

Nuclease-free water is used as an NTC when setting up each PCR plate. One well per plate is allotted to an NTC. NTCs should be run in addition to both field blanks and extraction blanks.

### PCR Clean-up

Due to primer dimer (shorter 170 bp peak) with the main target ~500 bp, size selection using Option A (BluePippin) or Option B (MagBead Cleanup) was used to purify the amplicon. The protocol below details the protocol for Option B.

1. Centrifuge the amplicon PCR plate at 1,000 × g at 20°C for 1 minute to collect condensation, carefully remove the seal.
2. Vortex the AMPure XP beads for 30 seconds to make sure that the beads are evenly dispersed. Add an appropriate volume of beads to a trough depending on the number of samples being processed.
3. Using a multichannel pipette, add 20 µl of AMPure XP beads to each well of the Amplicon PCR plate. Change tips between columns.
4. Gently pipette the entire volume up and down 10 times if using a 96‐well PCR plate or seal plate.
5. Incubate at room temperature without shaking for 5 minutes.
6. Place the plate on a magnetic stand for 2 minutes or until the supernatant has cleared.
7. With the amplicon PCR plate on the magnetic stand, use a multichannel pipette to remove and discard the supernatant. Change tips between samples.
8. With the amplicon PCR plate on the magnetic stand, wash the beads with freshly prepared 80% ethanol as follows: (a) Using a multichannel pipette, add 200 µl of freshly prepared 80% ethanol to each sample well. (b) Incubate the plate on the magnetic stand for 30 seconds. (c) Carefully remove and discard the supernatant.
9. With the amplicon PCR plate on the magnetic stand, perform a second ethanol wash as follows:(a) Using a multichannel pipette, add 200 µl of freshly prepared 80% ethanol to each sample well. (b) Incubate the plate on the magnetic stand for 30 seconds. (c) Carefully remove and discard the supernatant. (d) Use a P20 multichannel pipette with fine pipette tips to remove excess ethanol.
10. With the amplicon PCR plate still on the magnetic stand, allow the beads to air‐dry for 10 minutes.
11. Remove the amplicon PCR plate from the magnetic stand. Using a multichannel pipette, add 52.5 µl of 10 mM Tris pH 8.5 to each well of the amplicon PCR plate.
12. Gently pipette mix up and down 10 times, changing tips after each column. Make sure that beads are fully resuspended. Incubate at room temperature for 2 minutes.
13. Place the plate on the magnetic stand for 2 minutes or until the supernatant has cleared.
14. Using a multichannel pipette, carefully transfer 50 µl of the supernatant from the amplicon PCR plate to a new 96‐well PCR plate. Change tips between samples to avoid cross‐contamination.

### Basic Troubleshooting Guide

**Issue 1**: Streaking is observed for sample wells in the gel, but the positive control band appears normal. 

**Solution**: Dilute the sample DNA to a 1:10 dilution with nuclease-free water. If smearing is still observed using a 1:10 dilution, dilute the DNA samples further to a 1:100 dilution. If the samples do not amplify under these conditions, the sample is likely inhibited or has too little target DNA and thus is unlikely to yield valuable results. Alternative solutions include cleaning DNA extractions with a commercial cleanup kit.

**Issue 2**: No bands were observed in the PCR, including the positive control.

**Solution**: The PCR likely failed. Check reagents to confirm they were not mishandled or expired and rerun the PCR. If positive control fails again, the reagents or positive control are likely compromised. 

**Issue 3**: Band observed in no template control.

**Solution**: The PCR was likely contaminated. Sterilize lab space thoroughly and rerun with new aliquots of reagents.

## REFERENCES

1. Machida, R. J., & Knowlton, N. (2012). PCR Primers for Metazoan Nuclear 18S and 28S Ribosomal DNA Sequences. PloS One, 7(9), e46180–e46180. https://doi.org/10.1371/journal.pone.0046180

## APPENDIX A: DATASHEETS
