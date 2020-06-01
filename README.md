[![DOI](https://zenodo.org/badge/268489142.svg)](https://zenodo.org/badge/latestdoi/268489142)

# Materials-Datasets
Curated ExtXYZ Formatted NOMAD Archive Datasets

### How to access unique IDs and URIs of NOMAD data

#### NOMAD Encyclopedia data:

NOMAD Encyclopedia data can be accessed through [https://encyclopedia.nomad-coe.eu/](https://encyclopedia.nomad-coe.eu/)

Below we provie an example from a structure entry in AlNiCu dataset.
NOMAD Encyclopedia entries are given with `metadata` keywords of `nomad_enc_material_id`, `nomad_enc_calc_id` and `nomad_uri`.
 
These keywords correspond to the Encyclopedia Material Id, Calculation Id and unique URI of data in NOMAD Encyclopedia as follows:
Material Id :  23882
Calculation Id : 3928477
Materials URI : materials/23882

Structure entry in ExtXYZ file:
```
4
Lattice="4.521518737811202 0.0 0.0 -2.2607593689056014 3.9157500906318514 0.0 0.0 0.0 5.21030901" Properties=species:S:1:pos:R:3 nomad_metadata_type=https://encyclopedia.nomad-coe.eu/api/v1.0/ nomad_enc_material_id=23882 nomad_uri=materials/23882 nomad_enc_calc_id=3928477 nomad_program_name=VASP nomad_potential_energy=0.0 nomad_total_energy=-3.2437785461656428 nomad_free_energy=-3.2437785461656428 pbc="T T T"
Al       0.00000000       0.00000000       1.30257725 
Al      -0.00000000       2.61050006       1.30257725 
Al       0.00000000       0.00000000       3.90773176 
Al       2.26075937       1.30525003       3.90773176
```


#### NOMAD Archive data:

Similar to NOMAD Encyclopedia data, NOMAD Archive data is also accessible through the uniques NOMAD URIs of the structure and corresponding calculations. For NOMAD Archive, the following metadata is available in the ExtXYZ datasets here: `nmd`, the unique data entry URI link of NOMAD Archive and the direct access structure ID for the atomic positions entry in the selected calculation step.

Accessing NOMAD data using the provided NMD as given in the structure entry of ExtXYZ files below:

NMD URI: nmd://NmuEwYLmuGsGOP1JBPf4Ka7P_qU7I/C-0nF6O_Ks-pQhaB0azHKWreMFBzA

Web access link: 
[https://metainfo.nomad-coe.eu/nomadmetainfo_public/archive.html](https://metainfo.nomad-coe.eu/nomadmetainfo_public/archive.html)

```
8
Properties=species:S:1:pos:R:3 nomad_metadata_type=nomad_section_2_0 nomad_run_gIndex=0 nomad_uri=nmd://NmuEwYLmuGsGOP1JBPf4Ka7P_qU7I/C-0nF6O_Ks-pQhaB0azHKWreMFBzA/section_run/0c/section_system/0c nomad_system_gIndex=0 nomad_calculation_uri=nmd://NmuEwYLmuGsGOP1JBPf4Ka7P_qU7I/C-0nF6O_Ks-pQhaB0azHKWreMFBzA nomad_program_name=Octopus nomad_total_energy=-1732.9433404043968 nomad_free_energy=-1732.9433404043968 nomad_XC_functionals=GGA_X_PBE,GGA_C_PBE nomad_electronic_structure_method=DFT pbc="F F F"
N       0.03490665      -1.12822698      -0.00385045 
C       0.00251673       0.02635101       0.00282495 
C      -0.02389748       1.45255440       0.01088740 
N      -1.15569657       2.11906368       0.02951772 
O      -0.73648238       3.43907507       0.03111229 
C       0.60072197       3.41911979       0.01323012 
N       1.11302901       2.23127042      -0.00000110 
H       1.10985395       4.37135302       0.01162269
```
