# smart_beer_taps
ESP based smart beer taps with eInk screens

I am a homebrewer, and a home automation enthusiast.

I use kegs for serving my beers, since I don't fancy filling bottles with all that hassle. I have a tap tower, with three taps. Then I wanted to know how much beer is left in the kegs, as well as what beer is in what tap. That started my project.

The final goal is to have the setup in a keezer, in my outdoor kitchen. Until then, it is temporary setups to make this work. 

For measuring the content of the kegs I did find the following project, that includes all you need to buy, STL files for 3D printing the base and the code to both run and calibrate the scale.

https://github.com/Callwater/Beerkeg-load-cell

Since I will use a keezer, and will have (at least) 3 kegs in there, I do now have the DHT22 sensors in my setup. I will rather use an InkBird ITC-308 with wifi to measure that.

Then for the taphandles, I decided I wanted to use an eInk display to dynamically show what beers are in the kegs and how much is left. I did find some TTGO T5 with a 2.13 inch eInk display included that works perfectly for me. I bought them off Amazon.

The reason for the eInk display is that it will show data even if the device is not powered up. I don't drink beer 24/7, so that makes it possible for me to only update the display during certain times of the week. And then I can run on battery for quite a long time.

