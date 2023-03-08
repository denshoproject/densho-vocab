# README-topics

Vocabularies are stored in densho-vocab in a particular JSON format, but spreadsheets are the preferred editing format for humans.  The `ddrvocab` command converts between the two formats.  `ddrvocab` is part of the `ddr-cmdln` suite of commands.

IMPORTANT: `ddrvocab csvtojson` depends on having a particular set of columns available.  Here is a sample document:
``` csv
"id","topics"
"title","Topics"
"description","'DDR Topics'"
"id","_title","title","parent_id","weight","created","modified","encyc_urls","description"
"120","Activism and involvement [120]","Activism and involvement","0","0","2014-02-18 17:06:20-08:00","2014-02-18 17:06:20-08:00","/S.I.%20Hayakawa/",""
```
