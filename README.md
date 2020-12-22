# NEQAS-results-scraper
[UKNEQAS](https://ukneqas.org.uk/) is a group of providers of external quality assessment (EQA) services for UK clinical laboratories. 

Laboratories submit results that are compared against target values, and a PDF report is provided.

Sometimes, a laboratory may wish to use the results and target values for other purposes (for example, if the EQA samples are analysed as part of a validation of a new method). However, it is not easy to quickly get this information from a PDF file.

The EQA results scraper opens UKNEQAS reports, extracts the distribution, results and target values and returns these values in a Pandas dataframe.

The scraper has been tested with the following [Birmingham Quality](https://birminghamquality.org.uk/) UKNEQAS schemes:
* Newborn British Isles
* Clinical Chemistry
* Immunosuppressants
* Urinary Catecholamines & Metabolites

# Update 21st December 2020
The NEQAS-results-scraper was posted on the [Association for Clinical Biochemistry and Laboratory Medicine (ACB) mailbase on 21st December](https://www.jiscmail.ac.uk/cgi-bin/wa-jisc.exe?A2=ind2012&L=ACB-CLIN-CHEM-GEN&O=D&P=51575)

Shortly afterwards, [UKNEQAS announced](https://www.jiscmail.ac.uk/cgi-bin/wa-jisc.exe?A2=ind2012&L=ACB-CLIN-CHEM-GEN&O=D&P=52983) that they would meet with interested parties with a view to make EQA data more accessible to laboratories.
