# DHCP-Install


1. From the home page, navigate to 'Add Roles and Features' > 'Next' > 'Server Roles' and select 'DHCP Server.'
<img src="https://i.imgur.com/MhEwIa0.png" height="80%" width="80%"/>

2. Proceed with the installation by clicking 'Next.'
<img src="https://i.imgur.com/yliuVuH.png" height="80%" width="80%"/>

3. Let's set up the scope, which defines the range of available IP addresses. Go to the homepage, click on 'Tools,' and select 'DHCP.'
<img src="https://i.imgur.com/Kq2Apyh.png" height="80%" width="80%"/>

4. You'll notice that the IPv4 and IPv6 icons are red.
<img src="https://i.imgur.com/pRWDyC2.png" height="80%" width="80%"/>

5. Click the drop-down for IPv4, then right-click on it and choose 'New Scope.'
<img src="https://i.imgur.com/EgoJH5N.png" height="80%" width="80%"/>

6. The wizard will open; click 'Next' to enter the scope name. For this lab, we'll name it after the IP ranges we'll be using, which will be 192.168.0.100-200. Click 'Next.'
<img src="https://i.imgur.com/zVKeRfW.png" height="80%" width="80%"/>

7. Manually enter the IP ranges: Start = 192.168.0.100, End = 192.168.0.200, and a length of 24, which sets the subnet mask to 255.255.255.0.
<img src="https://i.imgur.com/cFHsD3t.png" height="80%" width="80%"/>

8. For the lab's sake, skip exclusions and proceed with 'Next.'
<img src="https://i.imgur.com/EaA3scR.png" height="80%" width="80%"/>

9. Keep the lease duration at 8 days or adjust it as needed for your lab.
<img src="https://i.imgur.com/XCdv5ZH.png" height="80%" width="80%"/>

10. Configure the DHCP option now by clicking 'Yes' and then 'Next.'
<img src="https://i.imgur.com/z59mNHB.png" height="80%" width="80%"/>

11. Set the default gateway (the route clients will use to access the internet when connected) to the IP of the DC, which in our case is 192.168.0.1. Type this number in, and be sure to click 'Add' before moving on.
<img src="https://i.imgur.com/UNJAE6h.png" height="80%" width="80%"/>

12. Proceed to the 'Activate Scope' page and click 'Yes.'
<img src="https://i.imgur.com/FO2uP30.png" height="80%" width="80%"/>

13. After the installation wizard finishes, right-click on the DC and authorize your changes.
<img src="https://i.imgur.com/7j1xKav.png" height="80%" width="80%"/>

14. Then right-click again and refresh.
<img src="https://i.imgur.com/6JYlPWf.png" height="80%" width="80%"/>

15. Both IPv4 and IPv6 icons should now display as green, indicating successful configuration."
<img src="https://i.imgur.com/F5q93q4.png" height="80%" width="80%"/>

