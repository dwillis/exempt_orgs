## IRS Exempt Organization File Converter


### Steps

1. Download Region Files from [irs.gov](http://www.irs.gov/uac/SOI-Tax-Stats-Exempt-Organizations-Business-Master-File-Extract-(EO-BMF))
2. Unzip those files
3. Activate virtualenv, run `pip install -r requirements.txt`
4. Run the following commands:

  `bin/in2csv -f fixed -s ../ffs/us/irs/irs_exempt_org_schema.csv /Users/200025/Downloads/EO1.LST > eo1.csv`
  `bin/in2csv -f fixed -s ../ffs/us/irs/irs_exempt_org_schema.csv /Users/200025/Downloads/EO2.LST > eo2.csv`
  `bin/in2csv -f fixed -s ../ffs/us/irs/irs_exempt_org_schema.csv /Users/200025/Downloads/EO3.LST > eo3.csv`
  `bin/in2csv -f fixed -s ../ffs/us/irs/irs_exempt_org_schema.csv /Users/200025/Downloads/EO4.LST > eo4.csv`
  
