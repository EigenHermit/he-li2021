# Download instructions
Provide download instructions for He&amp;Li, 2022 (submitted to RAA).         
ALL catalogues could be download from China-VO: https://nadc.china-vo.org/res/r101137/                        

# Description of columns
         
## Grade-A/Grade-B/DECaLS/BASS+MzLS catalogue
         
ra:     right ascension (J2000)         
dec:    declination (J2000)         
g:      g-band magnitude (AB)         
r:      r-band magnitude (AB)         
z:      z-band magnitude (AB)         
w1:     w1-band magnitude (AB)         
w2:     w2-band magnitude (AB)         
score:  the probablity of being a QSO that given by RF model         
         
## Testing sample        
         
ra:     right ascension (J2000)         
dec:    declination (J2000)         
g:      g-band magnitude (AB)         
r:      r-band magnitude (AB)         
z:      z-band magnitude (AB)         
w1:     w1-band magnitude (AB)         
w2:     w2-band magnitude (AB)                 
mtyp:   for negatives, it is main type in SIMBAD; for the positives, it is 'QSO'                 
otyp:   for negatives, it is other type in SIMBAD; for the positives, it is 'QSO'

## Training sample(QSOs)    

g:      g-band magnitude (AB)         
r:      r-band magnitude (AB)         
z:      z-band magnitude (AB)         
w1:     w1-band magnitude (AB)         
w2:     w2-band magnitude (AB)    
w3:     w3-band magnitude (AB)    
w4:     w4-band magnitude (AB)       
fluxw1w2: defined in eqution 5 in the paper               
fluxgrz: defined in eqution 5 in the paper               
W: magnitude converted by fluxw1w2              
grz: magnitude converted by fluxgrz              
                  
see https://www.legacysurvey.org/dr9/files/#survey-dr9-region-dr16q-v4-fits for other columns.
                        
## Training sample(non-QSOs)         
         
ra:     right ascension (J2000)         
dec:    declination (J2000)         
g:      g-band magnitude (AB)         
r:      r-band magnitude (AB)         
z:      z-band magnitude (AB)         
w1:     w1-band magnitude (AB)         
w2:     w2-band magnitude (AB)                 
mtyp:   main type from SIMBAD;                      
otyp:   other type from SIMBAD;                 
fluxg:  g-band flux (nanomaggies)         
fluxr:  r-band flux (nanomaggies)         
fluxz:  z-band flux (nanomaggies)         
fluxw1: w1-band flux (nanomaggies)         
fluxw2: w2-band flux (nanomaggies)         
