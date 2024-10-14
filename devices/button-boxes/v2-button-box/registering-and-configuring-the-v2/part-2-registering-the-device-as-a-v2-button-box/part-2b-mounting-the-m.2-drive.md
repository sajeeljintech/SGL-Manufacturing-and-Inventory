---
description: >-
  Next we will be making sure the device can properly route video files through
  to the M.2 Drive:
---

# 🅱️ Part 2B: Mounting the M.2 Drive

> _<mark style="color:red;">This set of instructions was completed with visual aid of the Scribe.</mark>_

## Connecting via VNC

1\. Click "VNC" in the top right of the device's page in order to remote into the Pi's desktop session and check to see if the M.2 Drive is being detected

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-05/31b5a113-d58b-4b27-a811-a4f52fb640ec/ascreenshot.jpeg?tl\_px=2660,0\&br\_px=4153,840\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=303,70)

2\. Copy the IP Address of the V2 Button Box

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-05/61c5bfa3-27d6-4ab8-9748-9b08ad38839a/ascreenshot.jpeg?tl\_px=2175,839\&br\_px=3668,1679\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=262,139)

3\. Open your VNC application of choice (we use MacOS's built in Screen Sharing" app)

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-05/9063424d-8e69-4de1-a1be-a3684a6da68d/ascreenshot.jpeg?tl\_px=0,1720\&br\_px=1493,2560\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=13,139)

4\. Right-click the "Connect To" text field

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-05/6e3e5705-2852-4a3f-b97c-e4784762f110/ascreenshot.jpeg?tl\_px=2359,506\&br\_px=3852,1346\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=262,139)

5\. Paste the IP Address

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-05/843dbd12-9b7f-477a-8a0a-319b2cc589f0/ascreenshot.jpeg?tl\_px=2222,558\&br\_px=3715,1398\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=262,139)

6\. Click "Connect"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-05/c831302d-b749-4b25-a985-54c4d1a3447f/ascreenshot.jpeg?tl\_px=2675,615\&br\_px=4168,1455\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=262,139)

## Installing GParted

7\. In the VNC Window, open the Terminal which should be located in the top left corner of the Pi's desktop

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-05/5552a0b4-835b-4052-97e3-ac7a3feb4618/ascreenshot.jpeg?tl\_px=691,37\&br\_px=2184,877\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=262,139)

8\. When the black Terminal window appears, type "sudo apt install gparted -y" then press \[\[Enter]] and wait for the application to install GParted

```
sudo apt install gparted -y
```

9\. Type "sudo gparted" then press \[\[Enter]] to run the program

```
sudo gparted
```

## Creating a Partition Table

10\. Click this dropdown in the top right of the GParted window

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-05/b47c7f60-9e36-4fd2-92c5-25f24caf9b98/ascreenshot.jpeg?tl\_px=3956,1252\&br\_px=5449,2092\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=262,139)

11\. Select the larger of the 2 drives and note the name (in this case "/dev/sda")

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-05/dc5301a1-cc5b-4940-b679-b4b872c0f6d5/ascreenshot.jpeg?tl\_px=3973,1326\&br\_px=5466,2166\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=262,139)

12\. Click the "Device" tab at the top of the GParted window and select "Create Partition Table"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-05/1a765c46-3cd0-42c9-83da-184e09ca60fe/ascreenshot.jpeg?tl\_px=3095,1196\&br\_px=4588,2036\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=262,139)

13\. There will be a pop-up to confirm; select "msdos" from the dropdown then click "Apply"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-05/aaef0bc1-03b8-42b1-a21a-13268127f4e2/ascreenshot.jpeg?tl\_px=3990,1836\&br\_px=5483,2676\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=262,139)

14\. Click the "Partition" tab at the top and select "New"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-05/37c92938-5914-4051-b262-f6838cb4cf67/ascreenshot.jpeg?tl\_px=3172,1193\&br\_px=4665,2033\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=262,139)

15\. Once the next pop-up opens, find "File System" dropdown on the right. Scroll down and select "ntfs"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-05/07b8d457-7d0c-48aa-ac55-6500061b15c1/user\_cropped\_screenshot.jpeg?tl\_px=3873,2042\&br\_px=5366,2882\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=262,139)

16\. Click the "Label" text field and enter "video"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-05/efaf9641-b7c6-44be-9658-f6f6303a31d4/ascreenshot.jpeg?tl\_px=3881,1866\&br\_px=5374,2706\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=262,139)

17\. Click "Add"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-05/1d365889-3e90-4f4f-b798-38b02f7643b7/ascreenshot.jpeg?tl\_px=4023,1963\&br\_px=5516,2803\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=262,139)

18\. Click the green check icon to confirm changes

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-05/3f9e6c22-0242-4e5e-87b7-696f06d352f6/ascreenshot.jpeg?tl\_px=3234,1274\&br\_px=4727,2114\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=262,139)

19\. Click "Apply" to apply pending operations

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-05/cbc91909-46fd-436a-9f82-93f4dac27f4c/ascreenshot.jpeg?tl\_px=3911,1821\&br\_px=5404,2661\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=262,139)

20\. Click "Close" when finished

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-05/bf8e9749-be37-4746-8b02-e286bad64869/ascreenshot.jpeg?tl\_px=4037,2042\&br\_px=5530,2882\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=262,139)

21\. Close GParted

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-07-05/793c1e15-a7ea-4e9f-a279-8801ddd539c1/ascreenshot.jpeg?tl\_px=4217,1134\&br\_px=5710,1974\&force\_format=png\&width=560\&wat\_scale=50\&wat=1\&wat\_opacity=0.7\&wat\_gravity=northwest\&wat\_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C\_standard.png\&wat\_pad=262,139)

## Checking the Drive List

22\. Back in the Terminal: type "lsblk" then \[\[Enter]] to list readable drives. If the drive listed is properly mounted to "/media/pi/pivideos", then move onto [Part 2C - Registering the Pi Stack as a V2 Button Box](part-2c-registering-the-pi-stack-as-a-v2.md)

```
lsblk
```

{% content-ref url="part-2c-registering-the-pi-stack-as-a-v2.md" %}
[part-2c-registering-the-pi-stack-as-a-v2.md](part-2c-registering-the-pi-stack-as-a-v2.md)
{% endcontent-ref %}

![A visual on the M.2 drive being properly mounted](<../../../../../.gitbook/assets/Screenshot 2023-07-05 at 4.05.47 PM.png>)
