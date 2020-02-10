
Installation:
1. install Anacdoda3 in windows 10
2. download the files and put in the local folder c:\data

  Files:
      1) c:/data/archive_device_identifier.json
      2) c:/data/active_device_identifier.json
      3) C:/data/AccessGUDID/device.txt
	#zip file has been attached to the push; extract files into directory /AccessGUDID/
      4) c:/data/active_license.json
      5) c:/data/archive_license.json
      6) c:/data/company.json
      

4. use anacoda Jupyter notebook and open assignment.ipnyb
5. run cell sequentially or you can comibine into one cell

Assignment analysis

1. data is cleansed in catalognumber for white space
2. if there are duplicates they removed by matching company name
3. where it does not match the first one wins

Future work
  1. Fuzzy matching is still pending
  2. In this exercise only catalogNumber is used, versionModelNumber could be used where NAN exist for 
     catalogNumber


 