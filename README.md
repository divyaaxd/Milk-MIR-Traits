# Milk-MIR-Traits
Analysis of the mid-infrared (MIR) spectral data extracted from milk samples, and their associated protein and technological traits using R.

## Data set

The initial columns in the dataset contain details (i.e. covariates) of the cows which produced the milk
samples and the protein and technological traits of the milk samples measured in the laboratory. The
data in the final 531 columns are the MIR spectra, with the first row of these columns detailing the
wavenumber (measured in cm-1). The spectral values in the dataset are the absorbance values (the
log10 of the reciprocal of the transmittance value). The water region has been removed.

1. Proteins
   
» 2 types of milk proteins: Casein and Whey 
» Casein: used for cheese production 
- αs1 casein
- αs2 casein 
- β casein
- k casein

» Whey: used for protein drinks
- α Lactalbumin, 
- β Lactoglobulin A, 
- β Lactoglobulin B

2. Technological Traits
   
» Heat stability
- What happens when heat treatment applied to milk

» pH
- Spoilage of milk
  
» Milk coagulation properties; 
- Cheese yield & sensory characteristics
- Rennet coagulation time, k20, a30, a60
- Curd firming time
- Curd firmness after 30 & 60 minutes
- 
» Casein micelle size

## Acknowledgement:
Teagasc: Agriculture and Food Development Authority is the national body providing integrated research, advisory and training 
services to the agriculture and food industry and rural communities.

## Reference:

This material is provided by Adjunct Associate Professor Sinead McParland,
Animal and Grassland Research & Innovation, Teagasc during a guest lecture at University College Dublin.


