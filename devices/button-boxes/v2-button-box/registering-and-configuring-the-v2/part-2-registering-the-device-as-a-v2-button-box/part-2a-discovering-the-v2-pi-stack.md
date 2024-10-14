---
description: >-
  To start registering a V2 Pi Stack as a V2 Button Box, you will first need to
  find the Raspberry Pi on your network. Here is how:
---

# 🅰️ Part 2A: Discovering the V2 Pi Stack

> _<mark style="color:red;">This set of instructions was completed with visual aid of the Scribe.</mark>_

## Re-inserting the Pi Stack's Cables

* In order to begin the process of discovering the V2 Pi Stack, you will need to turn the Kiloview off and insert a Flashed Micro SD Card into the Pi.
* Then remove the live ethernet cable from the Kiloview and insert it into the Pi Stack's Ethernet Adapter.

<div data-full-width="true">

<figure><img src="../../../../../.gitbook/assets/IMG_1424 Medium.jpeg" alt=""><figcaption><p>Turning off the Kiloview</p></figcaption></figure>

 

<figure><img src="../../../../../.gitbook/assets/IMG_1423 Medium.jpeg" alt=""><figcaption><p>Inserting the Flashed Micro SD Card</p></figcaption></figure>

 

<figure><img src="../../../../../.gitbook/assets/IMG_1425 Medium.jpeg" alt=""><figcaption><p>Unplugging the live network from the Kiloview</p></figcaption></figure>

 

<figure><img src="../../../../../.gitbook/assets/IMG_1427 Medium.jpeg" alt=""><figcaption><p>Inserting the live ethernet cable into the Pi Stack's Ethernet Adapter</p></figcaption></figure>

</div>

* Next, take the 1ft Ethernet Cable you had set aside from Part 1 - Discovering the Kiloview and replace it into the Kiloview's ethernet port. Then re-insert in the V2 Pi Stack's USB-C Power Cable into the back of the Kiloview. You should be left with a Button Box that looks something like the image below:

<div data-full-width="true">

<figure><img src="../../../../../.gitbook/assets/IMG_1428 Medium.jpeg" alt=""><figcaption><p>Plugging in the 1ft Ethernet Cable</p></figcaption></figure>

 

<figure><img src="../../../../../.gitbook/assets/IMG_1429 Medium.jpeg" alt=""><figcaption><p>Resetting the USB-C Power Cable</p></figcaption></figure>

</div>

### Turning on the V2 Pi Stack&#x20;

* Finally, switch on the Kiloview and take note of a few things:
  * The LED indicators are on for the Ethernet Adapter, Raspberry Pi, M.2 Drive Card, Kiloview and Kiloview's Ethernet Port.
  * The 5V Fan begins spinning without any strange noises.
  * There is no smoke or strange smells.
* Once the V2 Pi Stack is on, move onto the next step:

<div data-full-width="true">

<figure><img src="../../../../../.gitbook/assets/IMG_1431 Medium.jpeg" alt=""><figcaption><p>Turning on the Kiloview, and so the V2 Pi Stack</p></figcaption></figure>

 

<figure><img src="../../../../../.gitbook/assets/IMG_1432 Medium.jpeg" alt=""><figcaption><p>Both of the indicator LED's working on both the Ethernet Adapter and the Pi</p></figcaption></figure>

 

<figure><img src="../../../../../.gitbook/assets/IMG_1433 Medium.jpeg" alt=""><figcaption><p>The 5V Fan spinning up</p></figcaption></figure>

 

<figure><img src="../../../../../.gitbook/assets/IMG_1434 Medium.jpeg" alt=""><figcaption><p>Indicator LEDs working on the Kiloview</p></figcaption></figure>

</div>

## Navigating the Showground's Device List

* To begin, navigate back to your Network Manager (we use [Cisco Meraki](https://meraki.cisco.com/))

1\. Reload the "Event log" page to find new DHCP Leases

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-05/c198dc9a-622d-4bed-b253-8668a2ae5c57/ascreenshot.jpeg?tl\_px=0,38\&br\_px=1493,878\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=219,139)

2\. Find the most recent "raspberrypi" with a new DHCP Lease, take note of the IP addresses that are published for reference later

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-05/ec4f6bb7-e39b-4bc0-b8e4-5b4887c221fe/user\_cropped\_screenshot.jpeg?tl\_px=552,171\&br\_px=2045,1011\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=501,139)

3\. Navigate to https://www.showgroundslive.com/admin

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-05/ac885959-9e46-4e76-b496-fed758b845ae/ascreenshot.jpeg?tl\_px=1247,38\&br\_px=2740,878\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=262,139)

4\. Enter your email address and password, then click "Login"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-05/0f720665-348c-4569-b92c-1d2222f0b216/user\_cropped\_screenshot.jpeg?tl\_px=1679,254\&br\_px=3172,1094\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=262,139)

5\. Click "Show Administration" dropdown from the tabs on the left

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-05/c9ffdd32-6c2c-4b15-8596-af8820623fe6/ascreenshot.jpeg?tl\_px=0,210\&br\_px=1493,1050\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=64,139)

6\. Click "Devices", this is where we list the devices connected to our backend via _<mark style="color:red;">Remote.It</mark>_

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-05/7c9d00a3-26cc-4293-baaa-ec8a8df21093/ascreenshot.jpeg?tl\_px=0,524\&br\_px=1493,1364\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=55,139)

### Finding the New Device

7\. Click the "Name" field.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-05/c6766bff-64aa-4b5e-b1e5-15d835ba597e/ascreenshot.jpeg?tl\_px=61,0\&br\_px=1554,840\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=262,96)

8\. Make sure all filters are deselected or set to default

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-05/1fa3aee4-4122-4a38-ac38-e137ffba2a65/ascreenshot.jpeg?tl\_px=519,76\&br\_px=2012,916\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=262,139)

9\. Click the "Name" field and type "rasp" (for raspberrypi) and press \[\[Enter]]

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-05/a78d5b66-1bd8-4980-ae4e-13627c7a9071/ascreenshot.jpeg?tl\_px=0,0\&br\_px=1493,840\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=257,98)

10\. Listed out should be all devices registered to our Remote.It with the name "raspberrypi". Here we have an online Pi with the type "SD Card Boot Image" and the same IP Address (as noted from Step 3 above) which means this is the correct device

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-05/284ab3e6-969f-4df3-943b-3b102be92bf0/user\_cropped\_screenshot.jpeg?tl\_px=778,601\&br\_px=2271,1441\&force\_format=png\&width=560)

11\. Right-click "raspberrypi" and open the page in a new tab, then move onto [Part 2B - Mounting the M.2 Drive](part-2b-mounting-the-m.2-drive.md)

{% content-ref url="part-2b-mounting-the-m.2-drive.md" %}
[part-2b-mounting-the-m.2-drive.md](part-2b-mounting-the-m.2-drive.md)
{% endcontent-ref %}

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-05/892463b3-0bec-4efa-89f9-cc71a2013a57/ascreenshot.jpeg?tl\_px=507,284\&br\_px=2000,1124\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=262,139)
