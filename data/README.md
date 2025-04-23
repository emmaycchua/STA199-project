Project Presentation Link: https://youtu.be/OeYogJOotpc

## Dataset 1: `lemurs_2019`

Data dictionary courtesy of the Duke Lemur Center Database (2019).

- `Taxon`: In most cases, the taxonomic code is comprised of the first letter of the genus and the first three letters of the species; if taxonomic designation is a subspecies, comprised of the first letter of genus, species, and subspecies, and hybrids are indicated by the first three letters of the genus.  See table 1 for details.
- `DLC_ID`: Unique specimen identification number assigned by the DLC at accession of animal.
- `Hybrid`: Hybrid status of the lemur. N=not a hybrid.  S=species hybrid.  B=subspecies hybrid.  If sire is one of multiple possible and animal could be a hybrid, it is designated a hybrid.
- `Sex`: M=male.  F=Female.  ND=Not determined
- `Name`: House name:  Animal name assigned at DLC
- `Current_Resident`: Whether or not the animal currently lives in the DLC colony.
- `StudBook`: Regional or global unique Studbook ID among captive individuals of that species; assigned by AZA studbook keeper.  Not all individuals have studbook numbers in this data record.
- `DOB`: Date of birth
- `Birth_Month`: Month of birth
- `Estimated_DOB`: Whether or not the date of birth is an estimate.  Y=estimated to the nearest year, M to the nearest month, and D to the nearest day.  If there is a number after the letter code, that indicates to the Nth value of the code.  U=unknown.  If there is no entry in this field, DOB is not an estimate.
- `Birth_Type`: Whether the animal was captive-born (CB), wild-born (WB) or of unknown birth type (UNK)
- `Birth_Institution`: Name or ISIS abbreviation of institution where animal was born.  Duke Prim=DLC.  For wild caught animals, birth institution = country of origin, if known.
- `Litter_Size`: Number of infants in the litter the focal animal was born into (including focal animal).  Only indicated where verifiable (born at DLC).  A missing value indicates that the litter size is unknown.
- `Expected_Gestation_d`: Expected gestation length with values based on DLC observations and reports from the literature, in days.
- `Estimated_Concep`: Date of estimated conception calculated as (DOB-Expected_Gestation)
- `Concep_Month`: Month of estimated conception as identified from Estimated_Concep
- `Dam_ID`: The Specimen ID of female parent. DLC unique ID preferred if there is one.  Local ID of another ISIS-reporting institution if knEstown and no DLC number exists.  “Wild” indicates dam of wild-caught individual.  "Unk" or no data indicates dam is unknown.
- `Dam_Name`: House name of female parent (at DLC)
- `Dam_Taxon`: Taxon of female parent
- `Dam_DOB`: Date of birth of female parent. If female parent is wild caught or of unknown origin, this date is an estimate.
- `Dam_AgeAtConcep_y`: Estimated age of female parent at conception of focal animal in years ((Estimated_Concep-Dam_DOB)/365)
- `Sire_ID`: Specimen ID of male parent: DLC number preferred if there is one.  Local ID of another ISIS-reporting institution if known and no DLC number exists.  “Wild” indicates sire of wild-caught individual. “MULT” indicates multiple possible sires.  A following number indicates number of possibilities (e.g. MULT2).  “Unk” or no data indicates unknown sire and may include cases of multiple possible sires.
- `Sire_Name`: House name of male parent (at DLC)
- `Sire_Taxon`: Taxon of male parent
- `Sire_AgeAtConcep_y`: Estimated age of male parent at conception of focal animal in years ((Estimated_Concep-Dam_DOB)/365)
- `DOD`: Date of death, missing indicates animal is either alive or status is unknown
- `AgeAtDeath_y`: Age of animal at verifiable date of death, in years ((DOD-DOD)/365).  Missing indicates animal is either alive or status is unknown.
- `AgeOfLiving_y`: Verifiable living age of DLC-owned animals and/or current residents at DLC on loan, in years as of the date the datafile was updated ((date of last update-DOB)/365).  Missing indicates animal is either dead or status is unknown.
- `AgeLastVerified_y`: Age of animal at most recent date a non-DLC owned, non-current resident animal was verifiably alive, in years.  Dates were obtained from ISIS as entered by other institutions (dates of live weight or animal transfer) or via direct communication from other animal facilities. ((DateLastVerified-DOB)/365).  Missing indicates animal is known to be dead or alive.
- `AgeMax_LiveOrDead_y`: The animal's age from any of the three age categories (each individual must have a value in one of the three) indicating the maximum age the animal could have achieved as of the date the datafile was updated.
- `N_known_offspring`: Number of offspring the individual is known to have produced.  There may be additional offspring for this individual if they were born at another institution or if this individual is a possible, rather than known, parent.
...

## Dataset 2: `jobs_gender`

- `year`: Year
- `occupation`: Specific job/career
- `major_category`: Broad category of occupation
- `minor_category`: Fine category of occupation
- `total_workers`: Total estimated full-time workers > 16 years old
- `workers_male`: Estimated MALE full-time workers > 16 years old
- `workers_female`:	Estimated FEMALE full-time workers > 16 years old
- `percent_female`:	The percent of females for specific occupation
- `total_earnings`: Total estimated median earnings for full-time workers > 16 years old
- `total_earnings_male`: Estimated MALE median earnings for full-time workers > 16 years old
- `total_earnings_female`: Estimated FEMALE median earnings for full-time workers > 16 years old
- `wage_percent_of_male`: Female wages as percent of male wages - NA for occupations with small sample size
...
