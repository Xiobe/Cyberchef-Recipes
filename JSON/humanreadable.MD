# JSON Human readable
When I need to go through lenghty JSON files, I sometimes need to beautify them. Cyberchef allows this without any issue.

```
Find_/_Replace({'option':'Regex','string':'\''},'"',true,false,true,false)
JSON_Beautify('    ',false)
```
