# Explaination
This recipe takes into account that the base64 might be compressed (deflated) and thus we need to inflate it again before we can return it.

# Chef Formated Code
>[
>{"op":"Regular expression","args":["User defined","[a-zA-Z0-9+/=]{30,}",true,true,false,false,false,false,"List matches"]},
>{"op":"From Base64","args":["A-Za-z0-9+/=",true]},
>{"op":"Raw Inflate","args":[0,0,"Adaptive",false,false]},
>{"op":"Generic Code Beautify","args":[]}
>]
