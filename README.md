# DoneGEKI
Finally, a (soon to be) completed, documented guide for an O.N.G.E.K.I. controller. Yes, ironic, since this isn't actually done

I started this project because I had the wonderful opportunity to play on an ONGEKI machine and fell in love. I immediately started looking up DIY guides to make a controller... However, much to my dismay, NONE of the guides were finished, fully documented, or even guides. I went on a wild goose chase to acquire the files and knowledge I've provided here. I'm tired of poorly written, terribly documented, unfinished guides that explain nothing. This guide will make sure that doesn't happen again.

I would like to say one more thing: a lot of the stuff I am documenting and providing here isn't mine, but made by other people. I am only making sense of all of it. Thank you to the Cons&Stuff Discord for all the help and material. 

### Note: 
As you may notice, I'm still building this con troller, so I haven't solved all the problems/added everything.

# Requirements
- Access to a 3D printer
- Access to basic workshop tools
    - Screwdrivers
    - Soldering iron
- A PC with Arduino installed (google it)
- Internet access (to download what you need)

# Parts List
## Lever parts (from [toxicmango's design](https://github.com/toxikmango/Ongeki-Lever))  
### A note: I'm using a modified version of this design in order to fit cheaper parts.
- 2x [608 skateboard bearings](https://smile.amazon.com/gp/product/B07R7PR72H)(8mm ID, 22mm OD, 7mm thick) 
- [Dielectric grease](https://smile.amazon.com/gp/product/B000AL2RI2) or other equivalent lubrication
    - Do not use WD-40. That will damage plastic.
### The following parts are better obtained at a hardware store.
- 1x 5/16" fully threaded bolt (5.5-6" long) 
- 1x 5/16" fully threaded bolt (about 3.75"-4" long) 
- 4x 5/16" nylock nuts
- 4x m3 bolts and nuts (35mm long) 
- ?x m3 bolts/#6 screws (3/4'' ?)


## Controller electronics parts

- 6x [ISTMALL 60mm 65g Square Buttons](https://istmall.co.kr/us/goods/goods_view.php?goodsNo=1009992342)
    - Main gameplay buttons. It's worth putting money here. These are the cheap kind, 65g. The cab uses 100g.
    - For other options, see the [cons wiki](https://rhythm-cons.wiki/w/Buttons)
- 2x [30mm Buttons](https://smile.amazon.com/dp/B07WQSMY8B)
    - Start buttons. Official cab uses 30mm square buttons, no LED. You are crazy if you are sinking money into these.
    - Any button will do, really. 
- 1x [Potentiometer](https://smile.amazon.com/dp/B00MCK7JMS)
    - These only really come in bulk. Consider splitting the cost and ordering with other people.
- 1x [Sparkfun Pro Micro](https://www.amazon.com/ATmega32U4-Micro-USB-Development-Compatible-ATmega328/dp/B07PHK8SMR/)
    - Rather widely available. Better found at Micro Center or equivalent hobby electronics shop. Clones are ok too.

## Controller Body Parts
to do

## Assembly and How-To
From here, assembly and stuff will be pretty complex. I will divide assembly into several sections. Aim to have all of the `/hardware` assembly/preparation done before beginning to go through `/software`. If you're having trouble preparing any of the materials, I may have provided more details in the relevant assembly section. 

