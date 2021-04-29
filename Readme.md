To zip and unzip part files:
https://serverfault.com/questions/760337/how-to-zip-files-with-a-size-limit
zip: zip -r -s 10m archive.zip directory/
unzip:
1. to convert single archive: zip -s 0 split.zip --out unsplit.zip
2. to unzip:  unzip unsplit.zip
