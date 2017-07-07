# FileMakerDDRXML2JSON
FileMaker DDR XML to JSON conversion

This conversion will have to be run for each database XML dump

such as
```BASh
xsltproc database_fmp12.xml > /tmp/file.json
curl -XPOST "http://localhost:9200/filemakerddr/database" -d@/tmp/file.json
```
