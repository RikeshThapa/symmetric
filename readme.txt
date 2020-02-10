Author: Rikesh Thapa
Date Created: Feb 9th 2020
Last modified: Feb 9th 2020


Installation:
1. install Anacdoda3 in windows 10, no further configs beyond this is required
2. download the files and put in the local folder /

  Files:
    1) Extract AccessGUDID.zip into parent directory subfolder AccessGUDID/:
        - AccessGUDID/device.txt
    2) Extract datasets.zip into parent directory /:
        - archive_device_identifier.json
        - active_device_identifier.json
        - active_license.json
        - archive_license.json
        - company.json
      

4. use anacoda Jupyter notebook and open assignment.ipnyb
5. run cell sequentially or you can comibine into one cell

Assignment analysis

1. data is cleansed in catalognumber for white space
2. if there are duplicates they removed by matching company name
3. where it does not match the first one wins

Future work
  1. Fuzzy matching is still pending
  2. In this exercise only catalogNumber is used, versionModelNumber could be used where NAN exist for catalogNumber
 