
# DIR-860L_REVA_FIRMWARE_hardcode_password

# Firmware:
[DIR-860L_REVA_FIRMWARE_1.08B02.ZIP](https://support.dlink.com/resource/products/DIR-860L/REVA/DIR-860L_REVA_FIRMWARE_1.08B02.ZIP)

# Description:

System initialization, telnetd service started, account and password hard coded.

# Analyse：

Firstly, we can see that the login account is Alphanetworks, and the password is a parameter: image_sign.
![389843926528302](vx_images/412207692970518.png)

Password: "image_sign" is obtained by running the command: cat /etc/config/image_sign. As shown in the figure below.

![38234044756609](vx_images/247026129619054.png)
After executing the command, go to telnet hard code: wrgac03_dlob.hans_dir860

![55553997844254](vx_images/403348452579194.png)




Simulate the launch of the website

![443642910798891](vx_images/4858349149013.png)



Then connect to the website via telnet

![17284674082694](vx_images/154749842324546.png)
