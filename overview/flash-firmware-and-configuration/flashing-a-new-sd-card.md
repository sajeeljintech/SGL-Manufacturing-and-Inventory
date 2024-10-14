---
description: >-
  All of our Pi based devices will need a Micro SD Card flashed with the newest
  version of our Shrunk Pi Image. Our Flash Image is designed to install
  software on our devices and ready them for our SGL'
cover: ../../.gitbook/assets/Screenshot 2023-06-13 at 12.37.16 PM.png
coverY: 78
---

# 💾 Flashing A New SD Card

> _<mark style="color:red;">This set of instructions was completed with visual aid of the Scribe.</mark>_

* You will need a SD Card Reader (in this instance it is built into a USB Hub), and Micro SD Card. Most of the Micro SD Cards come with a small adapter just in case you may only have regular SD Card Adapter.
* Insert the Micro SD Card into the Reader and follow the steps below:

<div>

<figure><img src="../../.gitbook/assets/IMG_1272 Medium.jpeg" alt=""><figcaption><p>A Micro SD Card Reader, Micro SD Adapter, and Micro SD Card itself</p></figcaption></figure>

 

<figure><img src="../../.gitbook/assets/IMG_1273 Medium.jpeg" alt=""><figcaption><p>Placing the SD Card into the SD Card Reader</p></figcaption></figure>

</div>

1. Open the "BalenaEtcher" desktop application

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-06-13/4d054e8f-1bb7-43b1-a5bb-299efa3335b5/ascreenshot.jpeg?tl\_px=0,1338\&br\_px=1493,2178\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=-4,139)

2. Click the blue button labeled "Flash from file"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-06-13/1b714f73-71ab-4324-8309-c8883411bbf8/ascreenshot.jpeg?tl\_px=1767,1255\&br\_px=3260,2095\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=262,139)

3. Find the newest version of the Shrunk Pi Image (or Yodeck image) in your computer's file system.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-06-13/8743f1e1-f786-4483-95df-183dfd801a1d/ascreenshot.jpeg?tl\_px=1931,1092\&br\_px=3424,1932\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=262,139)

4. Click "Open"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-06-13/f6e60862-0ea4-4118-8dc1-dac814c73017/ascreenshot.jpeg?tl\_px=2986,1667\&br\_px=4479,2507\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=262,139)

5. Click on the next blue button now labeled "Select target"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-06-13/02f99462-2956-4aca-9624-4aec02d92381/ascreenshot.jpeg?tl\_px=2224,1272\&br\_px=3717,2112\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=262,139)

6. In the list, find the SD Card you wish to flash, click on it, then click the blue "Select (1)" button in the bottom right

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-06-13/e3aeeda0-15fa-447d-96b1-df043dc2d308/ascreenshot.jpeg?tl\_px=1889,1173\&br\_px=3382,2013\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=262,139)

7. Click the final blue button labeled "Flash!"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-06-13/718f18fb-1536-4e4e-a21f-0dc219431797/ascreenshot.jpeg?tl\_px=2678,1290\&br\_px=4171,2130\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=262,139)

8. You will need administrator access to make changes. Allow access via entering the admin password on Mac, or giving permissions on Windows. The actual flash process make take some time to finish depending on how fast the SD Card Reader is able to write.

<figure><img src="../../.gitbook/assets/Screenshot 2023-06-13 at 12.37.16 PM.png" alt="" width="563"><figcaption><p>Balena Etcher with a finished flashed Micro SD Card</p></figcaption></figure>

* Once your card is finished, make sure to mark it consistently and keep it separate from empty Micro SD Cards.

> <mark style="color:red;">To note: We use a small Sharpie to permanently add "2</mark>:ballot\_box\_with\_check:<mark style="color:red;">" to the face of the card, designating the card as a 2nd wave of flashed Micro SD Cards. If flashing for a Yodeck: we mark the card with "yd" to indicate Yodeck.</mark>

* Balena Etcher will ask if you want to flash another SD Card. If you are going to be registerering multiple devices at the same time, I would recommend starting the process of another SD Card as you're working on other steps.

#### [Made with Scribe](https://scribehow.com/edit/Using\_Balena\_Etcher\_to\_Flash\_a\_new\_SD\_Card\_\_SBpO1ZghQi-Q5eKpFfSqZg)
