# portal-for-er605
ER605 External Web Portal Integration This repository contains the custom code designed to work as an external web portal for the TP-Link Omada ER605 router (standalone mode). The solution allows network administrators to redirect clients to a custom captive portal page, handle authentication 
ER605 External Web Portal Integration
This repository contains the custom code designed to work as an external web portal for the TP-Link Omada ER605 router (standalone mode). The solution allows network administrators to redirect clients to a custom captive portal page, handle authentication, and optionally log user access. It is ideal for setups requiring user interaction before granting internet access, such as public Wi-Fi in cafes, hotels, or institutions.

Features:

Fully compatible with TP-Link ER605 (standalone mode)

Supports custom branding

Simple Html-based backend for flexibility

Logs user MAC address, IP, and session info (optional)

Easy to deploy on cloud servers (e.g.,netlify , github , ec2, )

Use Case:
Perfect for deploying guest Wi-Fi with a login or acknowledgment page for compliance, advertising, or access control.







**Things to note** **Important**
*****Log in to your er605 and Make sure its running the latest firmware
*Change lan Ip to 192.168.1.1
*Deploy the portal on web by just downloading the captive portal folder(not whole folder) and deploy using netlify 
*Go to guest resourece and and click on add guest resource from there select url type give  it name and type your url withhout http://or https:// in the begining
*go to user management click on and number of clients being 1024 add user with name being portal and password being 1234
*Go to to authentication setting and type in u'r authentication url in in the authentication url box(eg:https://omadacaptiveportal.netlify.app)(set port to 8443 and idle timeout according to your wish)
*add success url here you can add your own website url or the page that you want to be redirected to for ex (google.com)
*click on save
*make sure your wan is link up 
*thats it your portal will work 
*our portal is the most easiest to use and very easy to use 
*you can manage users with the help of authentication status our captive portal dosent require radius server (which is odten very complicated to setup)
*our portal is free to use
*If you want to change the background  image and logo (u can simply do this by uploading your background image (and make sure that it has the same file name bg.jpg))
*For changing logo (u can simply do this by uploading your logo image (and make sure that it has the same file name logo.jpg))
****
