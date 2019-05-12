# Explanation
This recipe transforms base64-text to ASCII

# Chef Formatted Code
> [
> {"op":"Regular expression","args":["User defined","[a-zA-Z0-9+/=]{30,}",true,true,false,false,false,false,"List matches"]},
> {"op":"From Base64","args":["A-Za-z0-9+/=",true]},
> {"op":"Generic Code Beautify","args":[]}
> ]
