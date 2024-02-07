# Explanation
This recipe takes the encoded powershell command and makes it human-readable. The commandline typically looks like this:

```PowerShell
powershell -NoProfile -NonInteractive -ExecutionPolicy ByPass -EncodedCommand ...
```

Copy the `EncodedCommand` into CyberChef and apply this recipe.

# CyberChef formatted code

```
From_Base64('A-Za-z0-9+/=',true,false)
Remove_null_bytes()
```
