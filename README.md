# FileMakerDDRXML2JSON
FileMaker DDR XML to JSON conversion

This conversion will have to be run for each database XML dump

such as
```BASh
xsltproc fmpreport2json.xslt databasename_fmp12.xml > /tmp/databasename.json
curl -XPOST "http://localhost:9200/filemakerddr/databasename" -d@/tmp/databasename.json
```
