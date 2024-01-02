# Removing the X-AspNet-Version

If you remove the X-AspNet-Version HTTP header, you are not publicizing which version of ASP.NET you are using.

![image](https://github.com/AdaniKamal/Remediation/assets/44063862/9e6defbd-9049-4a56-8f82-85d911af244a)

## Step-by-step guide

Add the following code to the config file.

> :memo: Code
``` httpRuntime enableVersionHeader="false" ```

![image](https://github.com/AdaniKamal/Remediation/assets/44063862/57c7c831-346e-4a86-a1dc-5bf552fd3f77)

## Related articles

https://doc.sitecore.com/xp/en/developers/92/platform-administration-and-architecture/remove-header-information-from-responses-sent-by-your-website.html
