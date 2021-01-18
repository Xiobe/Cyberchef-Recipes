# Explaination

Microsoft SafeLinks is a technique that is part of [Microsoft's Defender ATP](https://docs.microsoft.com/en-us/microsoft-365/security/office-365-security/atp-safe-links?view=o365-worldwide).

Although very useful idea, since it is rewriting the URLs to go through Microsoft's defense mechanisms it makes the URL's unhandy for incident response sometimes. This is why we wrote a little recipe to extract the actual domain from the URL. If you need the actual URL it is just a matter of toggling the extract domain function.

I don't have actual data from other parts of the world so my recipe is for EMEA but you should be able to adapt it for your region pretty easily.

# Chef Formatted Code
> Split('https://emea01.safelinks.protection.outlook.com/?url=','\\n')
>
> URL_Decode()
>
> Extract_domains(true)
