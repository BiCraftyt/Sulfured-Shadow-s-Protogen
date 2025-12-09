
# My first protogen






## What's all about?
## Description

Here I will post and share all my progress in case someone wants to follow my build :3

## Color Reference

| Components            |  Where to buy in Spain                                                               |
| ----------------- | ------------------------------------------------------------------ |
| RGB LED MATRIX 64*32 Adafruit 4mm Pitch  |  (https://www.digikey.es/en/products/detail/adafruit-industries-llc/2278/7035036)  |
| Raspberry Pi Zero 2W | (https://www.amazon.es/Copy-Raspberry-Pi-Zero-W/dp/B09KLVX4RT/ref=sr_1_1?__mk_es_ES=%C3%85M%C3%85%C5%BD%C3%95%C3%91&s=digital-skills&sr=1-1) |
| Adafruit Hat | (https://www.amazon.es/AdaFruit-RGB-Matrix-Cerebros-Raspberry/dp/B07DNBLXV2/ref=sr_1_1?__mk_es_ES=%C3%85M%C3%85%C5%BD%C3%95%C3%91&s=digital-skills&sr=1-1)) |
|Power Delivery Module Trigger | (https://es.aliexpress.com/item/1005005116710949.html?spm=a2g0o.productlist.main.11.210113b2w0P6aK&algo_pvid=b4460094-e0d3-47d8-bf43-c9929dc90e37&pdp_ext_f=%7B%22order%22%3A%229%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005005116710949%7C_p_origin_prod%3A#nav-description) |
| Filaments; I used PLA for simplicity but PETG works as well | A spanish filament company I reccomend Smart Materials 3D (https://www.smartmaterials3d.com/) PLA Basic |
| Everything used in the base model, it's not mine, it's the Protogen from M16 Studios the Mk3 |(https://www.thingiverse.com/M16_Studios/designs) |
| Visor | Local shop and some tutorials from YouTube (https://www.youtube.com/watch?v=Gx66mS7U2vY, https://www.youtube.com/watch?v=HZ322J9zook) |
| Fur, foam, and other cosmetic stuf is up to you | Not sure what's the best place yet |
| Battery pack | 18650 cells of 3Ah each inside a cheap enclousure, total of 6Ah, for now |
| LEDs used on the side caps, 1M 60 LEDs IP30 | (https://es.aliexpress.com/item/1005008142650081.html?spm=a2g0o.productlist.main.1.47216d98FSaGpa&aem_p4p_detail=2025120902140811934355016105520000159046&algo_pvid=3c16e631-b12f-473b-9fb1-db4729874a4a&pdp_ext_f=%7B%22order%22%3A%2213%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005008142650081%7C_p_origin_prod%3A&search_p4p_id=2025120902140811934355016105520000159046_1) |
| Example Color | ![#00d1a0](https://via.placeholder.com/10/00b48a?text=+) #00d1a0 |
| Example Color | ![#00d1a0](https://via.placeholder.com/10/00b48a?text=+) #00d1a0 |
| Example Color | ![#00d1a0](https://via.placeholder.com/10/00b48a?text=+) #00d1a0 |
| Example Color | ![#00d1a0](https://via.placeholder.com/10/00b48a?text=+) #00d1a0 |
| Example Color | ![#00d1a0](https://via.placeholder.com/10/00b48a?text=+) #00d1a0 |


To change the face expressions you first have to create your own, though I left a demo one.

To execute the desired face you need to be inside of 

"yourusername/rpi-rgb-led-matrix/bindings/python/samples" 

and execute the code

 "sudo python3 image-viewer.py *name_of_your_image.jpg or .png*

## To create your own custom face expressions I recommend using Paint.net

It's basically a free sowftware for Windows that works very well. 

Although anything used for PixelArt should work just fine.
------------------------------
> [!TIP]
>  The resolution needed is 32*64 pixels 

> [!WARNING]  
>  The code is prepared to reescale images to make them fit into the two screens but for best results, use the native resolution.

### To use the file-->
    You need to remember its full name *Example *faceexpression1.png* even the extension matters.

    And go to *replaceWithYourUserName/rpi-rgb-led-matrix/bindings/python/samples* and paste it there. 
    
    Then just execute the code with the previous command *sudo python3 image-viewer.py *yourimageNAME.png* 

##    You are all set!!
