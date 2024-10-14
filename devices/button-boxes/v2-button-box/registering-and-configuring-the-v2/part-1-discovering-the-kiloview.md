---
description: >-
  Before addressing the V2 Pi Stack with the Micro SD Card, we need to configure
  the Kiloview E1-s
---

# 1️ Part 1: Discovering the Kiloview

> _<mark style="color:red;">This set of instructions was completed with visual aid of the Scribe.</mark>_

## Using your Network Manager

1\. Navigate to your Network Manager (we use Cisco Meraki)

2\. Enter your email in the "Email" field

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-05/458d6153-3cb9-4985-9604-427f5a1ebfd2/ascreenshot.jpeg?tl\_px=519,344\&br\_px=2012,1184\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=262,139)

3\. Click the "Next" button

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-05/ffbd92a5-6415-4d77-b073-34762a77a49b/user\_cropped\_screenshot.jpeg?tl\_px=547,442\&br\_px=2040,1282\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=262,139)

4\. Enter your password then click "Log in"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-05/da557c03-ecee-4e00-8f9d-80aa7a086afe/user\_cropped\_screenshot.jpeg?tl\_px=551,478\&br\_px=2044,1318\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=262,139)

5\. Click "Network-wide"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-05/9552f258-5535-4bc4-832e-c167c92a89e3/ascreenshot.jpeg?tl\_px=0,0\&br\_px=1493,840\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=60,102)

6\. Click "Event log"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-05/e34d2859-1011-4865-83ad-6937d01e986f/ascreenshot.jpeg?tl\_px=0,46\&br\_px=1493,886\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=212,139)

7\. Find the most recent DHCP lease that has not been assigned, double-click the IP address in the "Details" column

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-05/03ccddf7-cdb3-431d-995a-759d48a38d5f/user\_cropped\_screenshot.jpeg?tl\_px=1221,514\&br\_px=2714,1354\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=463,139)

## Connecting to the Kiloview

8\. A new browser tab will open prompting you to enter the Kiloview's credentials. The username is "admin" and the password is "admin"

<figure><img src="../../../../.gitbook/assets/Screenshot 2023-07-05 at 12.05.12 PM.png" alt="" width="563"><figcaption></figcaption></figure>

9\. Once you land on the Kiloview's Web Page, double check that there is signal going to the encoder (pictured below)

<figure><img src="../../../../.gitbook/assets/Screenshot 2023-07-05 at 2.22.57 PM.png" alt="" width="563"><figcaption></figcaption></figure>

### Changing the Password

10\. Click "admin" in the top right

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-05/b40548e7-a2b7-4500-981b-8621685eca80/ascreenshot.jpeg?tl\_px=1841,0\&br\_px=3334,840\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=262,22)

11\. Click this password field and enter R0ckS0lidRVSP!

<figure><img src="../../../../.gitbook/assets/Screenshot 2023-07-05 at 2.20.14 PM.png" alt="" width="563"><figcaption></figcaption></figure>

12\. Click "OK"

<figure><img src="../../../../.gitbook/assets/Screenshot 2023-07-05 at 2.20.49 PM.png" alt="" width="563"><figcaption></figcaption></figure>

13\. The password will change, click "OK", then the page will reload. Enter the username "admin" and the new password to continue

<figure><img src="../../../../.gitbook/assets/Screenshot 2023-07-05 at 2.20.56 PM.png" alt="" width="540"><figcaption></figcaption></figure>

### Changing Network Parameters

14\. Click "Network & Service Settings"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-05/9db1eb6b-42d3-4946-80ab-5671411640f2/ascreenshot.jpeg?tl\_px=757,356\&br\_px=2250,1196\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=262,139)

15\. Click "Network Manager"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-05/a8e04404-885b-48ef-9cfc-20642fa23340/ascreenshot.jpeg?tl\_px=591,454\&br\_px=2084,1294\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=262,139)

16\. Click "Configure"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-05/294a209b-d101-4a2e-b202-2525902f7ad2/ascreenshot.jpeg?tl\_px=2095,196\&br\_px=3588,1036\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=262,139)

17\. Click the "Address Resolve" dropdown and select "Manual Set"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-05/1871a391-1b0a-4ffe-a346-11c82f069ef8/ascreenshot.jpeg?tl\_px=1455,250\&br\_px=2948,1090\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=262,139)

18\. Click the "IP Address" field and enter "192.168.133.11"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-05/eeed7acb-2953-40ae-bace-b98dc4591c35/ascreenshot.jpeg?tl\_px=1457,318\&br\_px=2950,1158\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=262,139)

19\. Click the "Net Mask" field and enter "255.255.255.0"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-05/a4743330-f6f1-4fec-bffc-01895cb2d273/ascreenshot.jpeg?tl\_px=1465,398\&br\_px=2958,1238\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=262,139)

20\. Click the "Gateway" field and enter "192.168.133.10"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-05/23310ea8-f19c-4c7b-9ec1-1a47f7111514/ascreenshot.jpeg?tl\_px=1483,468\&br\_px=2976,1308\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=262,139)

21\. Click the "DNS1" field and enter "8.8.8.8"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-05/379e77e3-7d76-4453-b944-02623455aba0/ascreenshot.jpeg?tl\_px=1485,530\&br\_px=2978,1370\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=262,139)

22\. Click the "DNS2" field, enter "8.8.4.4"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-05/1fe1edb7-af4c-425d-ac1d-595ff27409ac/ascreenshot.jpeg?tl\_px=1493,592\&br\_px=2986,1432\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=262,139)

23\. Click "SAVE"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-05/2df2bcbf-c148-4b96-9aaf-b953bb47e059/ascreenshot.jpeg?tl\_px=1559,654\&br\_px=3052,1494\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=262,139)

24\. A window will appear: click "Update network"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-05/b3f49321-3570-4dae-8b81-9149f0adceea/ascreenshot.jpeg?tl\_px=2075,942\&br\_px=3568,1782\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=262,139)

25\. Click "Close", the page will reset and you will no longer be able to access the Kiloview configurator until the V2 Pi Stack has been registered, continue to the next part.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-05/e90b872f-a4fd-4bd0-b7b0-3bfa81bb5ef2/ascreenshot.jpeg?tl\_px=1531,906\&br\_px=3024,1746\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=262,139)

#### [Made with Scribe](https://scribehow.com/shared/How\_to\_Update\_Network\_Manager\_Settings\_in\_Meraki\_\_rTk53qUOR2ePh2lM5oEBDQ)
