This is GEOSCHEM 12.8.2 version
We added the Brown carbon simulation module based on Xuan Wang's work.
We modified the photo bleaching parameterization scheme of BrC based on the work of Schnitzler et al.,
The main files we changed are as follows:
aerosol.mod.F90
carbon.mod.F90
dust.mod.F90
fast_jx.mod.F90
hcox_gfed_mod.F90
CMN_FJX_MOD.F90
CMN_SIZE_mod.F90
species_database_mod.F90

references
(1) Wang, X.; et al., Exploring the observational constraints on the simulation of brown carbon. Atmos Chem Phys 2018, 18 (2), 635-653. DOI: 10.5194/acp-18-635-2018.
(2) Schnitzler, E. G.; et al.,  Rate of atmospheric brown carbon whitening governed by environmental conditions. Proc Natl Acad Sci U S A 2022, 119 (38), e2205610119. DOI: 10.1073/pnas.2205610119.
