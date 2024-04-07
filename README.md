# XSS in WonderCMS 3.4.3 (SETTINGS -> MENU)
**Software link:** WonderCMS 3.4.3 [https://www.wondercms.com/download]

**@author:** Antonio Díaz.

**Description:** Cross-site scripting (XSS) vulnerability in MENU of the SETTINGS section of WonderCMS 3.4.3 allow attackers to execute arbitrary web scripts or HTML via a crafted payload injected into two fields: 'WEBSITE TITLE' and/or 'MENU'.

## PoC
### WEBSITE TITLE
1. Enter to MENU of the SETTINGS section in the webpage and in 'WEBSITE TITLE' set the payload:

![image](https://github.com/adiapera/xss_menu_page_wondercms_3.4.3/assets/165512291/9a0188b1-76c8-4f98-9e07-19cf0d79a420)

2. Click anywhere outside the parameter box to save:

![image](https://github.com/adiapera/xss_menu_page_wondercms_3.4.3/assets/165512291/23008249-261a-4b17-8252-1d7b92e42198)
![image](https://github.com/adiapera/xss_menu_page_wondercms_3.4.3/assets/165512291/016133b6-1425-4834-8dbd-8a155d934527)


### MENU
1. Enter to MENU of the SETTINGS section in the webpage and in any 'MENU' parameter set the payload:

![image](https://github.com/adiapera/xss_menu_page_wondercms_3.4.3/assets/165512291/caf6eb26-dd25-412a-8c94-d56a6fbd8fa4)

or

![image](https://github.com/adiapera/xss_menu_page_wondercms_3.4.3/assets/165512291/7e2e17fd-a9a4-4eca-abe5-34238e8627b5)

2. Click anywhere outside the parameter box to save:

![image](https://github.com/adiapera/xss_menu_page_wondercms_3.4.3/assets/165512291/feac9950-f2f4-481c-a42b-3bddb8411843)
![image](https://github.com/adiapera/xss_menu_page_wondercms_3.4.3/assets/165512291/65055777-4166-48af-b878-2c36a0cff566)

or

![image](https://github.com/adiapera/xss_menu_page_wondercms_3.4.3/assets/165512291/1f8585d5-caa6-4bb5-ad3c-0395c5c225a1)
![image](https://github.com/adiapera/xss_menu_page_wondercms_3.4.3/assets/165512291/5c182cfc-78f6-452d-8562-976c48ee014e)






 
