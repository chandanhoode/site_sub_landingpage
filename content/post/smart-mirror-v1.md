+++
categories = ["DIY","Project"]
date = "2017-01-11T22:25:32-04:00"
tags = ["raspberrypi"]
title = "Smart Mirror v1.0"
affiliatelink =  "/img/assemble_1.jpg"
desc = "this is my firt project"
+++
<img src="/img/exported-2184.jpg" width="740px">
{{< figure title="Raspberry Pi 3, connected and powered on" >}}


A couple of years ago, while browsing reddit, I stumbled upon a DIY post where the author described how he had built a smart mirror, a mirror that displays content, using Raspberry Pi and an old monitor. The idea about a mirror being more than just a mirror sounded cool and innovative so I decided to someday try and build one myself.


After a lot of procrastination, I finally pushed myself to start this project and build my own smart mirror. This project is also my first big electronic DIY project, if you discount the damaged digital watches and the pimped-up RC cars. In this post, I am going to describe how I went about this project.


I started by asking myself how I wanted the end product to be. I wanted it to be slightly big which meant I had to use a bigger monitor and a bigger two-way mirror. I wanted it to have a minimalistic yet sturdy wooden frame. I also wanted to make it modular so that I could take it apart and put it back together easily.
 

Here are the list of items that I used for this project along with their approximate prices
 

	1. Old 22" monitor
	2. Poplar wood 1.5" x 1.5" x 8' (about $10)
	3. Two-way mirror 12" x 24" ($100)
	4. Raspberry Pi 3 Kit ($69)

Here are the tools I used


	1. Table saw
	2. Circular saw
	3. Corner clamps
	4. Chisel
	5. Wood glue
	6. Sand paper
	7. Danish oil
	

After considerable research, I ordered the [Raspberry Pi 3 Complete Starter kit from Canakit](https://www.amazon.com/CanaKit-Raspberry-Complete-Starter-Kit/dp/B01C6Q2GSY/ref=sr_1_3?ie=UTF8&qid=1507492124&sr=8-3&keywords=canakit+pi+3), which comes with a Micro SD card preloaded with NOOBS, a case, a charger and of course the Pi3. I chose this kit because I didn’t want the hassle of ordering each part separately. The first thing I did once I received it was to install the MagicMirror2 software by following the instructions provided [here](https://github.com/MichMich/MagicMirror).

MagicMirror2 is an open source modular smart mirror platform which contains some default modules like Clock, Calendar, Current Weather, Weather Forecast, News Feed and Compliments. With this platform installed you can either choose to install any of the various modules developed by the MagicMirror community or write one of your own module. My first goal was get the basic mirror working so with this set up, I moved on to the next part.
 

<img src="/img/pi_1.jpg" width="740px">
{{< figure title="Raspberry Pi 3, connected and powered on" >}}

For the display, I needed a two-way mirror and a monitor. I decided to use an old 22-inch monitor that I had. I had to strip the monitor of its stand and its outer bezel. Now I needed a two-way mirror about the size of the monitor that would reflect light on one side and also allow light to pass through on the other side, similar to the ones shown in interrogation scenes in movies. 

There were two options to go with. The cheaper acrylic option, which I didn’t go with because I read that it tends to distort the image over time. The other costlier option was an actual two-way glass mirror which I went with. After having a few calls to the local glass companies around my area, I decided it was cheaper to order it from Amazon and ordered the following 12x24 inch mirror. [Link here](https://www.amazon.com/Two-Way-Glass-Mirror-Surveillance/dp/B01MSAZ3PN/ref=sr_1_2?ie=UTF8&qid=1502661529&sr=8-2&keywords=two+way+glass+mirror). It was expensive but was well worth it. It fit the monitor almost perfectly on the shorter side and was about 3 inches too long in height which I was okay with.


<img src="/img/assemble_2.jpg" width="740px">
{{< figure title="Mirror fits monitor almost perfectly." >}}


Moving on to the last step - woodworking

Not many people know that I love woodworking and had always wanted to work with wood but had never gotten a chance, until now. Usually people who build photo frames or frames for mirrors build the frame in two parts and then glue them together. The visible thin outer frame and the thicker frame to hold the components at the back. I wanted a single frame which required an L shaped cut to (each side of) the wood. Knowing next to nothing about the different types of wood, I told my frame requirements to a friend who suggested that I go with the 1.5in x 1.5in x 8ft poplar wooden bar.


<img src="/img/assemble_1.jpg" height="500px">
{{< figure title="Before the edges were cut." >}}


I spent about a week trying to envision the sort of cut I would need to build the type of frame I wanted.


<img src="/img/3d_model.jpg" width="360px" height="320px">    <img src="/img/3d_model_2.jpg" width="360px" height="320px">
{{< figure title="Sample 3D model before and after cut. RED=parts to be cut, BLUE=front view, DARK GREY=side view" >}}


<img src="/img/measurements_1.jpg" width="740px">
{{< figure title="Front view measurements. Shaded region needs to be cut." >}}




<img src="/img/measurements_2.jpg" width="360px" height="500px">   <img src="/img/measurements_3.jpg" width="360px" height="500px">
{{< figure title="Back view. Shaded region needs to be cut." >}}


Once I did that, my coworker who a mini table saw helped me cut the wood to my requirements. We also cut the edges to 45 degrees to form the mitered corner, which is required to join them together. It required quite a bit of sanding (coarse grit) and chiseling to make sure that the corners aligned properly and that it could hold the glass and the monitor at the back.





<img src="/img/assemble_3.jpg" height="500px">
{{< figure title="Making sure everything fits, pre-gluing." >}}



After the corners aligned perfectly, I glued the sides using gorilla glue and frame clamps and left it to dry for 24 hours. Be sure to verify multiple times that the corners are properly aligned as there is no going back once they are glued together.



<img src="/img/gluing_1.jpg" width="350px" height="500px"> <img src="/img/gluing_2.jpg" width="350px" height="500px">
{{< figure title="Glued and held." >}}


Once the glue dried, I used sand paper (finer grit) to sand the corners and edges and make it ready for polishing. I decided to go with the natural look of poplar hence used a double coat of Danish oil for the polish. It brought out the light stains but still maintained the light brown color of the wood.



<img src="/img/assemble_4.jpg" height="500px">
{{< figure title="Making sure everything fits, pre-gluing." >}}


With the frame done, I needed something to hold the mirror and monitor inside the frame without falling out. For this, I used some thin scrap wooden sheets which acted like a supporting bar and was held to the frame using flat corner irons and screws.
I taped the Pi case to the back of the monitor and made the other connections (HDMI, power etc.). And that’s it, the mirror has now become smart.


<img src="/img/back_view.jpg" height="500px">
{{< figure title="Back view with support." >}}



<img src="/img/exported-2184.jpg" width="740px">
{{< figure title="Raspberry Pi 3, connected and powered on" >}}


A big shoutout to the entire [MagicMirror community](https://forum.magicmirror.builders/) who help answer questions, debug issues and develop new modules, without whom this project would not have been possible. Now with the basic version working, I have some ideas for the next version like voice activated home automation using Alexa (asking mirror to dim the lights, controlling thermostat etc.), personal tickers for stock market and crypto markets, mail/message notifications etc. Keep follwing this site for more details.




 
