# Download instructions
Provide download instructions for He&amp;Li, 2022 (submitted to RAA).         
Plase copy and paste the url to the adress bar of browser to start download.                           
Grade-A catalogue: http://paperdata.china-vo.org/zzhe_naoc/LIS+QSO+Candidates/lis_gradeA_qso.csv                      
Grade-B catalogue: http://paperdata.china-vo.org/zzhe_naoc/LIS+QSO+Candidates/lis_gradeB_qso.csv                             
Training sample (QSOs):http://paperdata.china-vo.org/zzhe_naoc/LIS+QSO+Candidates/s1_train.csv                               
Training sample (non-QSOs):http://paperdata.china-vo.org/zzhe_naoc/LIS+QSO+Candidates/s2_train.csv                               
Testing sample (QSOs+non-QSOs): http://paperdata.china-vo.org/zzhe_naoc/LIS+QSO+Candidates/tstset_modified.csv                     

# Description of columns:
         
## Grade-A and Grade-B catalogue:
         
ra:     right ascension (J2000)         
dec:    declination (J2000)         
g:      g-band magnitude (AB)         
r:      r-band magnitude (AB)         
z:      z-band magnitude (AB)         
w1:     w1-band magnitude (AB)         
w2:     w2-band magnitude (AB)         
score:  the probablity of being a QSO that given by RF model         
         
## Testing sample:         
         
ra:     right ascension (J2000)         
dec:    declination (J2000)         
g:      g-band magnitude (AB)         
r:      r-band magnitude (AB)         
z:      z-band magnitude (AB)         
w1:     w1-band magnitude (AB)         
w2:     w2-band magnitude (AB)                 
mtyp:   for negatives, it is main type in SIMBAD; for the positives, it is 'QSO'                 
otyp:   for negatives, it is other type in SIMBAD; for the positives, it is 'QSO'

## Training sample(QSOs):    

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
                        
## Training sample(non-QSOs):         
         
ra:     right ascension (J2000)         
dec:    declination (J2000)         
g:      g-band magnitude (AB)         
r:      r-band magnitude (AB)         
z:      z-band magnitude (AB)         
w1:     w1-band magnitude (AB)         
w2:     w2-band magnitude (AB)                 
mtyp:   for negatives, it is main type in SIMBAD; for the positives, it is 'QSO'                 
otyp:   for negatives, it is other type in SIMBAD; for the positives, it is 'QSO'                 
fluxg:  g-band flux (nanomaggies)         
fluxr:  r-band flux (nanomaggies)         
fluxz:  z-band flux (nanomaggies)         
fluxw1: w1-band flux (nanomaggies)         
fluxw2: w2-band flux (nanomaggies)         
