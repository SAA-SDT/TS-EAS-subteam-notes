#How to update the EAD3 schema

(gather the documentation about using Trang, etc.)

[https://github.com/SAA-SDT/EAD3/blob/master/inprocess/to_make_xsd.txt]

to test issue #499 manually (until we can set up an automated test procedure), here's a reminder to use xmllint like so:

```
xmllint --noout --schema ead3.xsd samples/ead3/EAD3test-xsd.xml
```