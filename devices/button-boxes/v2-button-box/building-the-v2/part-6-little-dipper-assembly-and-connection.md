---
description: >-
  To bridge the connection between the V2 Pi Stack and the Door Assembly, We
  will need to install another board that is much simpler. We call this board
  the Little Dipper. Here's how:
---

# 6️ Part 6: Little Dipper Assembly and Connection

## Required Materials

* There are a 2 (3) main parts that we need to assemble in order bridge the Front Button, the Fan Assembly, and the V2 Pi Stack: the _<mark style="color:red;">Pigtail Connector</mark>_, the _<mark style="color:red;">Little Dipper Board</mark>_, and the _<mark style="color:red;">6 Pin Braid Connector</mark>_ (the [Little Dipper ](../../../../custom-hardware/constellation-daughter-boards/little-dipper.md)Assembly in the [Parts List](./#parts-list) includes the Braid Connector).
* As for tools, you will need a small flathead screwdriver and your pair of clippers from the [Tools List](./#tools-list).

{% content-ref url="./" %}
[.](./)
{% endcontent-ref %}

<figure><img src="../../../../.gitbook/assets/IMG_1092 Medium.jpeg" alt="" width="360"><figcaption><p>All needed materials</p></figcaption></figure>

## Possible Preparation

* If not done already, the 6 Pin Braid Connector will easily slot one way into the Little Dipper Board, so start there. You will hear a small click when the Connector is properly installed, making the _<mark style="color:red;">Little Dipper Assembly</mark>_.

<div data-full-width="false">

<figure><img src="../../../../.gitbook/assets/IMG_1093 Medium.jpeg" alt=""><figcaption><p>6 Pin Braid Connector slotting into the Little Dipper Board</p></figcaption></figure>

 

<figure><img src="../../../../.gitbook/assets/IMG_1094 Medium.jpeg" alt=""><figcaption><p>Fully Set Braid Connector, now the Little Dipper Assembly</p></figcaption></figure>

</div>

## Pigtail Connector

* There are a few too many cables on the stock Pigtail Connector, specifically, we do not need to implement the 2 white cables in the middle of the assembly. Begin by removing the spare wires close to the base, being careful not to clip any other cables. You will be left with a Pigtail Connector like the image below.

<div data-full-width="true">

<figure><img src="../../../../.gitbook/assets/IMG_1095 Medium.jpeg" alt=""><figcaption><p>The Pigtail Connector, separated for removal </p></figcaption></figure>

 

<figure><img src="../../../../.gitbook/assets/IMG_1096 Medium.jpeg" alt=""><figcaption><p>Clipping the unused white cables</p></figcaption></figure>

 

<figure><img src="../../../../.gitbook/assets/IMG_1097 Medium.jpeg" alt=""><figcaption><p>A Pigtail Connector after proper preparation</p></figcaption></figure>

</div>

* Cutting the colored Cables to fit into the Little Dipper Assembly is deceptively simple but can be annoying if not done carefully. Pick any cable, in this case <mark style="background-color:green;">Green Cable 3</mark>, and twist the cable cap to tighten the copper wire but try to keep it on to keep the wires tight as we cut them a little under 1/4 of an inch away (as shown below). You will be left with an easy to clean cap and a properly cut <mark style="background-color:green;">Green Cable</mark>.

<div data-full-width="true">

<figure><img src="../../../../.gitbook/assets/IMG_1099 Medium.jpeg" alt=""><figcaption><p>Untwisted, unclipped Green Copper Cable</p></figcaption></figure>

 

<figure><img src="../../../../.gitbook/assets/IMG_1100 Medium.jpeg" alt=""><figcaption><p>Twisting the cap of the Green Cable</p></figcaption></figure>

 

<figure><img src="../../../../.gitbook/assets/IMG_1101 Medium.jpeg" alt=""><figcaption><p>Where to cut in the exposed wire</p></figcaption></figure>

 

<figure><img src="../../../../.gitbook/assets/IMG_1102 Medium.jpeg" alt=""><figcaption><p>On the table before and after</p></figcaption></figure>

</div>

### Correct Little Dipper Cable Order

* There is a **very specific order** to follow when connecting the Pigtail to the Little Dipper Assembly. With the Pigtail Connector laying on the table with the side with <mark style="background-color:red;">Red</mark> and _**Black**_ Cables on top. Place the <mark style="background-color:red;">Red Cable</mark> between <mark style="background-color:green;">Green Cables 1 and 2</mark>, then place the _**Black Cable**_ between the <mark style="background-color:blue;">Blue Cable</mark> and <mark style="background-color:green;">Green Cable 3</mark>. All is shown in the images below.
* The Little Dipper Assembly may need to be facing away from you to get the order correctly and still be able to build without getting confused. It may be easier to lay the Little Dipper Assembly  on its' side to easily access the openings for your colored cables like the example image below.
* Begin by loosening all of the silver flathead screws on the Little Dipper Assembly, allowing the clipped Pigtail cables to set deep into the connector. Once placed, screw in corresponding the flathead screw until the cable does not come out easily. Repeat (preferably from left to right) until all of the Pigtail cables have been well secured.
* There are multiple Green Cables, each one has a different function. Green 1 is ground, Green 2 is for the Front Button's green LED indicator, and Green 3 is power.&#x20;

### _REMEMBER_

> FROM LEFT TO RIGHT:\
> _<mark style="background-color:green;">GREEN 1</mark>, <mark style="background-color:red;">RED</mark>, <mark style="background-color:green;">GREEN 2</mark>, <mark style="background-color:blue;">BLUE</mark>, **BLACK**, <mark style="background-color:green;">GREEN 3</mark>_

<div data-full-width="false">

<figure><img src="../../../../.gitbook/assets/IMG_1103 Medium.jpeg" alt=""><figcaption><p>FROM LEFT TO RIGHT:<br><mark style="background-color:green;">Green 1</mark>, <mark style="background-color:red;">Red</mark>, <mark style="background-color:green;">Green 2</mark>, <mark style="background-color:blue;">Blue</mark>, <em><strong>Black</strong></em>, <mark style="background-color:green;">Green 3</mark></p></figcaption></figure>

 

<figure><img src="../../../../.gitbook/assets/IMG_1104 Medium.jpeg" alt=""><figcaption><p><mark style="background-color:green;">Green 1</mark> and <mark style="background-color:red;">Red</mark> Cables properly seated in order from left to right</p></figcaption></figure>

</div>

<div>

<figure><img src="../../../../.gitbook/assets/IMG_1105 Medium.jpeg" alt=""><figcaption><p>Continuing the proper order, from left to right</p></figcaption></figure>

 

<figure><img src="../../../../.gitbook/assets/IMG_1106 Medium.jpeg" alt=""><figcaption><p>Fully seated and correctly inserted Pigtail Connector, added to the Little Dipper Assembly</p></figcaption></figure>

</div>

## The Little Dipper Assembly

### Connecting the Button and Fan

* This is another easy step as we line up the 4 colored dots on the Front Button with the corresponding colored cables protruding from the Pigtail Connector. It is a snug fit so keep firmly pressing until you hear a small click. Then, wrap the Fan Assembly's cable around the Pigtail Connector and up to the Little Dipper Assembly a few times; terminating at the white JST connector.&#x20;

{% content-ref url="part-4-installing-the-v2-pi-stack-and-cables.md" %}
[part-4-installing-the-v2-pi-stack-and-cables.md](part-4-installing-the-v2-pi-stack-and-cables.md)
{% endcontent-ref %}

<div data-full-width="true">

<figure><img src="../../../../.gitbook/assets/IMG_1107 Medium.jpeg" alt=""><figcaption></figcaption></figure>

 

<figure><img src="../../../../.gitbook/assets/IMG_1108 Medium.jpeg" alt=""><figcaption></figcaption></figure>

 

<figure><img src="../../../../.gitbook/assets/IMG_1109 Medium.jpeg" alt=""><figcaption></figcaption></figure>

 

<figure><img src="../../../../.gitbook/assets/IMG_1110 Medium.jpeg" alt=""><figcaption></figcaption></figure>

</div>

### Connecting to the V2 Pi Stack

* Now, find where you had tucked away the Rainbow Door Cable from [Part 4 - The Rainbow Door Cable](part-4-installing-the-v2-pi-stack-and-cables.md#the-rainbow-door-cable), and connect it to the 6 pin plug on the Little Dipper Assembly

{% content-ref url="part-4-installing-the-v2-pi-stack-and-cables.md" %}
[part-4-installing-the-v2-pi-stack-and-cables.md](part-4-installing-the-v2-pi-stack-and-cables.md)
{% endcontent-ref %}

<div>

<figure><img src="../../../../.gitbook/assets/IMG_1111 Medium.jpeg" alt=""><figcaption><p>Retrieving the Rainbow Door Cable</p></figcaption></figure>

 

<figure><img src="../../../../.gitbook/assets/IMG_1112 Medium.jpeg" alt=""><figcaption><p>Plugging in the Door Cable to the Little Dipper Assembly</p></figcaption></figure>

</div>

### Adhering to the Case

> To note: Although we are in the process of changing how we keep the Little Dipper Assembly is attached to the case, for now we will continue to use a large amount of hot glue to keep it in place.

* Start by placing down the Little Dipper on the case to find the best place to secure the Assembly that accomplishes 2 things: is as close to parallel with the Door Cable's plug on the Big Dipper Board as possible and still allows some slack on all of the attached cables.
* Below is an example of a good place to mark with a small pen, scuff with sandpaper, score with an Exacto Knife, then pour a large amount of hot glue on. There is none in the sample images below, but you will need enough glue to come up and pour on top of the board through the 4 screw holes. This will ensure the Little Dipper Assemble does not get removed by vibration or a fall and will help (but not solve the issue of) heat melting the glue enough that cable train will pull the Assembly from the case.

> To note: In the example images, we do not apply any hot glue since this V2 being built was intended to test other ways the Little Dipper Assembly could be attached to the case.

<div>

<figure><img src="../../../../.gitbook/assets/IMG_1113 Medium.jpeg" alt=""><figcaption><p>An approximate on where to scuff, score, then mark and hot glue the Little Dipper Assembly</p></figcaption></figure>

 

<figure><img src="../../../../.gitbook/assets/IMG_1114 Medium.jpeg" alt=""><figcaption><p> Keeping the Little Dipper Assembly in place while the glue cools</p></figcaption></figure>

</div>

### Completed Little Dipper Assembly

* Here is how the case should look, fully opened, at this part of the build (without hot glue\*):

<figure><img src="../../../../.gitbook/assets/IMG_1115 Medium.jpeg" alt="" width="480"><figcaption><p>A full image of the build thus far (without hot glue*)</p></figcaption></figure>

## Zipping Down Loose Tie

* With the door portion of the manufacturing process complete, you may now zip the Small Zip Tie from [Part 3 - Placing Other Zip Ties](part-3-power-cable-management.md#placing-other-zip-ties) _most_ of the way down, allowing a small gap so the Door Cable can move as the door swings open and closed. Cut away the excess and dispose of all trash properly!

{% content-ref url="part-3-power-cable-management.md" %}
[part-3-power-cable-management.md](part-3-power-cable-management.md)
{% endcontent-ref %}

<div>

<figure><img src="../../../../.gitbook/assets/IMG_1116 Medium.jpeg" alt=""><figcaption><p>The Small Zip Tie, almost fully zipped</p></figcaption></figure>

 

<figure><img src="../../../../.gitbook/assets/IMG_1117 Medium.jpeg" alt=""><figcaption><p>Cutting off the excess tie</p></figcaption></figure>

</div>
