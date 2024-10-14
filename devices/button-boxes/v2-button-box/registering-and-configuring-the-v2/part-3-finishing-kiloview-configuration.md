---
description: >-
  To finish configuring the V2 Button Box, we will need to be able to access the
  Kiloview's settings that we routed through the Pi, doing the following:
---

# 3️ Part 3: Finishing Kiloview Configuration

> _<mark style="color:red;">This set of instructions was completed with visual aid of the Scribe.</mark>_

## Configuring the Encorder URL

1\. Once the UI Dashboard has had the connection severed, it should eventually redirect you to the updated UI Dashboard of a V2 Button Box (as seen below). Here we can see that the new V2 Button Box is in need of a reboot and has an HLS Error which can be remedied

![](https://colony-recorder.s3.amazonaws.com/files/2023-07-05/058f9f7a-b448-4a3f-abdd-35f3d1c2133b/stack\_animation.webp)

2\. Navigate back to the V2 Button Box's page in the device list. Scroll down to "Display Configurations" and check "Remote Device Communication"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-05/f9166443-2f98-4120-9776-c695b6481267/user\_cropped\_screenshot.jpeg?tl\_px=195,1231\&br\_px=1688,2071\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=262,139)

3\. Click the "Encoder URL" field and remove what is already in the field with \[\[backspace]] and replace by typing "rtsp://192.168.133.11:554/ch01"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-05/e0c83f58-47b7-449c-8801-876dfe4c98cb/ascreenshot.jpeg?tl\_px=561,1514\&br\_px=2054,2354\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=262,139)

4\. Click the "Submit" button in the bottom right of the "Display Configuration" section and you will be redirected back to the main Device Page. While we search for our device in the backend, reboot the V2 Button Box by flicking the Kiloview's power switch to off then on.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-05/21445320-2683-4508-911b-2bfa9069671f/ascreenshot.jpeg?tl\_px=2660,1756\&br\_px=4153,2596\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=493,139)

5\. In the "Name" field, enter the 4 Digit Device Number (in this case 0307)

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-05/04715d18-0bdb-4f31-ac35-93ee747bff47/ascreenshot.jpeg?tl\_px=197,0\&br\_px=1690,840\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=262,97)

6\. Click on the name of your new V2 Button Box

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-05/69bea1c3-258b-43f1-8958-b2e9061fff37/ascreenshot.jpeg?tl\_px=315,288\&br\_px=1808,1128\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=262,139)

7\. Once in the device's page and the Pi has had some time to reboot; copy and paste one of the V2 Button Box's IP Addresses to another browser tab

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-05/fec95703-4652-4662-b096-18a75e527bb7/ascreenshot.jpeg?tl\_px=2063,566\&br\_px=3556,1406\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=262,139)

8\. You should be directed to the same login page from [Part 1: Discovering the Kiloview](part-1-discovering-the-kiloview.md), enter the Kiloview's _new_ credentials

{% content-ref url="part-1-discovering-the-kiloview.md" %}
[part-1-discovering-the-kiloview.md](part-1-discovering-the-kiloview.md)
{% endcontent-ref %}

<figure><img src="../../../../.gitbook/assets/Screenshot 2023-07-05 at 12.05.12 PM.png" alt="" width="563"><figcaption></figcaption></figure>

## Starting an HLS Service on the Kiloview

9\. Scroll down from the main landing page and click "Add a stream..."

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-05/8632727a-6ea6-4451-a3cd-d4d5ab9e2b24/ascreenshot.jpeg?tl\_px=1091,1566\&br\_px=2584,2406\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=262,139)

10\. Click the "Stream Service" dropdown

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-05/1428c29b-e563-48e7-9afa-84b16d459d36/ascreenshot.jpeg?tl\_px=1397,804\&br\_px=2890,1644\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=262,139)

11\. Find "HLS Service" then click "OK"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-05/72726339-484a-4557-8d15-86024201a954/ascreenshot.jpeg?tl\_px=1673,900\&br\_px=3166,1740\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=262,139)

12\. Click "OK" once finished

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-05/34a55ec5-6504-45aa-9497-a6a29c9a1680/ascreenshot.jpeg?tl\_px=1611,888\&br\_px=3104,1728\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=262,139)

13\. Click on the cog image in the "HLS Service" section for parameters

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-05/2cb022a8-ab38-4738-88a5-f6f9a30bbdd0/user\_cropped\_screenshot.jpeg?tl\_px=1561,1586\&br\_px=3054,2426\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=442,139)

14\. Click this dropdown and select "Yes" to enable the service

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-05/fd2833f5-c3f2-4b47-afd8-0ed1c138d07e/ascreenshot.jpeg?tl\_px=1457,140\&br\_px=2950,980\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=262,139)

15\. Click the "Session ID:" field and remove the "0" from "main0" using \[\[backspace]]

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-05/1d1e12e3-90f0-4b74-923b-9b9eddafe05e/ascreenshot.jpeg?tl\_px=1461,200\&br\_px=2954,1040\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=262,139)

16\. Click the "Segment Size:" field and change the rate from 5000 to 3000

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-05/ed7ddaab-e38f-4bf7-8c25-317f325b71fd/ascreenshot.jpeg?tl\_px=1319,300\&br\_px=2812,1140\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=262,139)

17\. Click "SAVE"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-05/a6e59ba9-16d9-4220-8421-45a457bc6be3/ascreenshot.jpeg?tl\_px=1563,384\&br\_px=3056,1224\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=262,139)

18\. Click "OK" and close this page

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-05/32b1912e-7d81-44a1-bb23-b3ec0bdfb7b4/ascreenshot.jpeg?tl\_px=1607,890\&br\_px=3100,1730\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=262,139)

## Checking for Errors in the Flows

19\. Now that the Kiloview is done being configured, navigate back to the V2 Button Box's device page and click "Flows" in the tabs in the top right and you'll open a new page

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-05/9c4f2751-4342-4dcf-8351-460ac1da26c5/ascreenshot.jpeg?tl\_px=2567,0\&br\_px=4060,840\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=262,67)

20\. Once the new page loads, enter the Red Node username and password from the Showgrounds' 1Password account

<figure><img src="../../../../.gitbook/assets/Screenshot 2023-07-05 at 2.29.48 PM.png" alt="" width="563"><figcaption></figcaption></figure>

21\. One by one make sure all of the Flows have been downloaded. Go through all of the tabs at the top of the page, using the arrow at the end of the row to find the hidden tabs (or use the drop-downs to the right as seen below)

![](https://colony-recorder.s3.amazonaws.com/files/2023-07-05/4fc6f64c-870b-4216-9eab-b7a7dad5707b/stack\_animation.webp)

22\. Click the bug image to navigate to the "Debug" page to double check if there are any active errors. If not, the V2 has been assigned as a Button Box and we are ready to test the needed software and fucntions.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-05/935f543d-4a47-48b1-b599-36b5e14bac5b/ascreenshot.jpeg?tl\_px=2660,0\&br\_px=4153,840\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=456,27)

#### [Made with Scribe](https://scribehow.com/shared/Troubleshooting\_and\_Configuring\_Encoder\_for\_Video\_Streaming\_\_YXDVhimJQeyGxaS8bAD62Q)
