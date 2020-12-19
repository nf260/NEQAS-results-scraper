# NEQAS-results-scraper
UKNEQAS provide external quality assessment (EQA) services for UK clinical laboratories. 

Laboratories submit results that are compared against target values, and a PDF report is provided.

Sometimes, a laboratory may wish to use the results and target values for other purposes (for example, if the EQA samples are analysed as part of a validation of a new method). However, it is not easy to quickly get this information from a PDF file.

The EQA results scraper opens UKNEQAS reports, extracts the distribution, results and target values and returns these values in a Pandas dataframe.

The scraper has been tested with the following Birmingham Quality UKNEQAS schemes:
* Newborn British Isles
* Clinical Chemistry
* Immunosuppressants
* Urinary Catecholamines & Metabolites
