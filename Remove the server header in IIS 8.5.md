# Remove the server header in IIS 8.5

## Problem

**Server Header are exposing the IIS version**

![image](https://github.com/AdaniKamal/Remediation/assets/44063862/7493e573-8187-4fa6-9d16-9ebda1c72373)

## Solution
**Step-by-steps to Remove the Server Header in IIS 8.5**

1. Open the IIS Manager
2. Click on the icon for URL Rewrite

![image](https://github.com/AdaniKamal/Remediation/assets/44063862/81f60607-a0e5-47f7-947f-84fe175ddd47)

3. Right-click into the outbound section to open the context menu
4. Select Add Rule(s)

![image](https://github.com/AdaniKamal/Remediation/assets/44063862/2224049d-54dc-47d3-8ad0-150dc1a843d0)

5. Select Blank rule from the Outbound rules section

![image](https://github.com/AdaniKamal/Remediation/assets/44063862/a390bf74-9723-4f63-8b6c-40e8edf9cb72)

6. Fill the rules

![image](https://github.com/AdaniKamal/Remediation/assets/44063862/17092a36-6ec6-4635-a923-ed364cf6af4d)

| Number   |  Value     |
| ------------- | ------------- |
| 1             | Remove Server Header |
| 2             | Server Variable (select from menu) |
| 3             | RESPONSE_SERVER |
| 4             | .* |
| 5             | Rewrite (select from menu) |
| 6             | Make sure that value is empty |
| 7             | Apply |

7. Click "OK" to save the changes.

8. Restart the IIS service.
