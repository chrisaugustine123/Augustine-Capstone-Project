Author: Christopher Augustine
Date: Nov 10, 2024
Purpose: This document is a metadata file for the Capstone Data Analysis Project for Biostatistics class. It will include descriptions of the dataset and changes made to the actual data including ommitting outliers and NAs. 


Citations: 
Lee, T. 2018. Photosynthesis (A max, etc.): BioCON : Biodiversity, Elevated CO2, and N Enrichment ver 9. Environmental Data Initiative. https://doi.org/10.6073/pasta/59c3aa40af556bb42107ff9d17484c0e (Accessed 2024-10-23).

Link to Data: https://portal.edirepository.org/nis/mapbrowse?packageid=knb-lter-cdr.538.9

Data Description: 
The dataset from Biocon includes measurements of plant photosynthetic activity under dynamic  conditions. Some variable are maximum photosynthetic rate, concentrations of different items, nitrogen levels, and plant species diversity. The data mainly captures how different CO2 levels and different nitrogen concentrations effect photosynthesis among different plant species. Making itself useful for understanding how changing environmental factors influence overall plant activity. 

Key: 
Year- year
Plot- Plot
Ring- Ring
CO2_Treatment- Cedar Creek CO2 Treatment
Nitrogen_Treatment- Cedar Creek Nitrogen Treatment	
CountOfSpecies- Count Of Species
measured_species- species used in photosynthetic measurement	
measured_group- functional group of species used in photosynthetic measurement
photo_rep- Replicate of photosynthetic measurement for each plot/species in each campaign
date- Date of measurement
time- Time of measurement
measurement_taken_at_growth_CO2- "atgrowth"=CO2 concentration of measurement equivalent to the ring concentration, "other"=measurement taken at the CO2 concentration of the other
PAR- photosynthetically active radiation umol/m2/sec relating to light in the 400 to 700 nanometer wavelength
transpiration_rate- transpiration rate 
Amax_area_mol_CO2_m2_s1- assimilation rate on a leaf area basis
tleaf- leaf temperature estimate in C
gs_mmol_m2_s1- stomatal conductance to water vapor
A_gs_mmol_CO2_mol_H2O- instantaneous water use efficiency (photosynthesis rate/stomatal conductance)
SLA_cm2_g- specific leaf area	
assimilation_rate- assimilation rate on a leaf mass basis	
portable_gas_exchange_system_used- portable gas exchange system used to take measurement



Changes:
changed the name of E_mmol_H2O_m2_s1 to transpiration_rate and Amax_mass_nmol_CO2_g1_s1 to assimilation rate
ommited all NAs in transpiration_rate and assimilation_rate columns 
removed all data entires in transpiration rates above 1000 as it seemd to be caused by a entry error 

