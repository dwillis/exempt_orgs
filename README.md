## IRS Exempt Organization File Converter

This uses csvkit's in2csv utility to parse the fixed-width files listing tax-exempt organizations from the IRS into CSVs.

### Steps

1. Download Region Files from [irs.gov](http://tinyurl.com/cenu7sd)
2. Unzip those files
3. Clone [ffs](https://github.com/onyxfish/ffs) someplace
4. Clone this repo some other place
5. cd into this repo, create and activate virtualenv, run `pip install -r requirements.txt`
6. Run the following commands:

  `bin/in2csv -f fixed -s /path_to/irs_exempt_org_schema.csv /path_to/EO1.LST > eo1.csv`
  `bin/in2csv -f fixed -s /path_to/irs_exempt_org_schema.csv /path_to/EO2.LST > eo2.csv`
  `bin/in2csv -f fixed -s /path_to/irs_exempt_org_schema.csv /path_to/EO3.LST > eo3.csv`
  `bin/in2csv -f fixed -s /path_to/irs_exempt_org_schema.csv /path_to/EO4.LST > eo4.csv`
  
