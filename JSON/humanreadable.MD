# Explanation
This recipe allows you to make JSON more human readable.

# Chef Formatted Code
```
Find_/_Replace({'option':'Regex','string':'\''},'"',true,false,true,false)
JSON_Beautify('    ',false)
```
