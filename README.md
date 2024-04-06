# XSS in WonderCMS 3.4.3 (SETTINGS -> MENU)
**Software link:** WonderCMS 3.4.3 [https://www.wondercms.com/download]

**@author:** Antonio Díaz.

**Description:** Cross-site scripting (XSS) vulnerability in MENU of the SETTINGS section of WonderCMS 3.4.3 allow attackers to execute arbitrary web scripts or HTML via a crafted payload injected into several fields: 'WEBSITE TITLE', 'Page keywords' and/or 'Page description'.

## PoC
### WEBSITE TITLE
1. Enter to MENU of the SETTINGS section in the webpage and in 'WEBSITE TITLE' set the payload:

![image](https://github.com/adiapera/xss_menu_page_wondercms_3.4.3/assets/165512291/9a0188b1-76c8-4f98-9e07-19cf0d79a420)
or
![image](https://github.com/adiapera/xss_menu_page_wondercms_3.4.3/assets/165512291/2c951098-61d9-4139-9ddb-2b99b02e3801)

2. Click anywhere outside the parameter box to save:

![image](https://github.com/adiapera/xss_menu_page_wondercms_3.4.3/assets/165512291/23008249-261a-4b17-8252-1d7b92e42198)
![image](https://github.com/adiapera/xss_menu_page_wondercms_3.4.3/assets/165512291/016133b6-1425-4834-8dbd-8a155d934527)
or
![image](https://github.com/adiapera/xss_menu_page_wondercms_3.4.3/assets/165512291/5973d173-d05e-46f1-8ba9-d23d6661108e)
![image](https://github.com/adiapera/xss_menu_page_wondercms_3.4.3/assets/165512291/d1abb48b-6502-4b33-9a9f-b31a2240b30b)



 
