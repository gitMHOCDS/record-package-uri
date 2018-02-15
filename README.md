## Record Package URI
The Ministerio de Hacienda of Paraguay will publish now data about budget and implementation of a contracting process, however, details of the other phases are already been published by the Dirección Nacional de Contrataciones Públicas (DNCP). The record package uri extension is for adding a field to the Hacienda releases to reference where all the other information is published, for this particular OCID, pointing to DNCP's record package (note that in DNCP there is only one record package per OCID containing all the latest information).

##### Example:
```javascript
"releases": 
    [
        {
            "ocid": "ocds-03ad3f-246807",
            "recordPackageURI": "https://www.contrataciones.gov.py:443/datos/api/v2/doc/ocds/record-package/246807
"
            ...
        }
    ]
```