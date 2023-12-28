# Removing the X-Powered-By

If you remove the X-Powered-By HTTP header, you are not publicizing which version of ASP.NET you are using.

<br>

## Step-by-step guide
Add the following code to the config file.


<img src="https://github.com/AdaniKamal/Remediation/assets/44063862/32113ece-0072-4731-beb9-98e83e47db08" width=50% height=50%>

<br><br>

> :memo: Code
``` remove name="X-Powered-By" ```

<br> 

![image](https://github.com/AdaniKamal/Remediation/assets/44063862/191de550-f9a9-49b3-9301-07470b4d7fb2)

<br> 
<b> Related articles </b>
<br> 
- https://doc.sitecore.com/xp/en/developers/92/platform-administration-and-architecture/remove-header-information-from-responses-sent-by-your-website.html
