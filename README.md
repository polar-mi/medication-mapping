# medication-mapping
This repository holds a sample data on medication related data. It is divided into site specific medication reference data that is not mapped to a terminology server and therefore is missing relevant information like product characteristics. This data can be retrieved using the PZN or ATC code in general. So the data can be used to map the texts to atc/pzn and then enrich the data from the mmi data to create FHIR resources.

## Site-specific Medication Reference Data for Pharmacists in each hospital is collected. The data is structured as follows:

Location | Text | ATC | PZN | ASK | EAN

In generel this data can be mapped using the elaborated procedures and is lateron evaluated by the sites. Measures of data quality should be taken into account. Accuracy and grammatical errors.

## EMA-specific product information
