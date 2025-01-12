# Wilson26

![473014029_970308404527336_7966295988583581471_n](https://github.com/user-attachments/assets/c8661aa6-39ab-48a8-a9b5-c93a5a896aa2)

Wilson26 (work name "speech bubbles") is a **hand wired** 24+2 (12 finger keys and a single thumb key on each side) keyboard. It is my first custom board and first time I hand wired as well. It has room for a quite big thumb key to allow for a constant natural hit on the key. Magnets are used to hold the top and the bottom together, hosting the core piece in between them. Furthermore, I have a metal plate under my desktop mat, making the keyboard stick nicely to the surface and not move around at all.

![473010573_904872761671910_5993000537577480773_n](https://github.com/user-attachments/assets/3483d01d-1c4e-4dd8-b891-cfa4471822bf)

Held in place by magnetic plate:
![472772766_1257146452221999_2719535943537501795_n](https://github.com/user-attachments/assets/ed20e3dc-251f-4ec3-828f-954fe8dc0996)

https://github.com/user-attachments/assets/79317fed-44d1-4464-9065-c3c680b0b202

![472556541_848818513936416_1481843809402186678_n](https://github.com/user-attachments/assets/1e7b5808-f509-417c-8b83-c07ec8926bec)
![472456768_597772769675133_2320854753181551561_n](https://github.com/user-attachments/assets/d48369fb-ca09-4798-a107-47da70ed45bc)
![472414672_1138308854471953_644363828560622730_n](https://github.com/user-attachments/assets/3dc8a996-4241-443d-b0c9-1d1c4074bff9)
![472640176_587801814102372_5305539112194375774_n](https://github.com/user-attachments/assets/8a1a3320-a25f-45ee-a16f-a55a6485759d)
![473277228_447554088428515_8054211697777366360_n](https://github.com/user-attachments/assets/d05c6684-8e71-410e-a874-675597c8c9a5)
![473019889_1144112647115652_5801369336284166013_n](https://github.com/user-attachments/assets/60772948-3ce4-41b8-ac71-930f2022a9e4)

## Hand size and difference between fingers
Every custom keyboard is designed with certain hand specs in mind. I have rather small hands and my index finger is retatively short compared to my middle finger. I also have pinky issues that I struggle with and then my inner most thumb joint cannot bend. Every design aspect in this board has taken these specs into account. On lots of other 3x5 boards or the likes, the thumb cluster is way too close to the alpha keys and it just feels crippled to me when using them as the fingers will have to bend to allow the thumb to reach.

## Component list
- Single unit pcbs: https://keycapsss.com/search?sSearch=KC10133_HMXMx
- Mx hot swap sockets
- smb diodes
- two trrs sockets
- Xiao rp2040
- 12 round magnets of 8x3 mm

## Building

![IMG_1337](https://github.com/user-attachments/assets/3e4f5137-cf87-43e9-a498-8a0810d80b8e)

NOTE: I got a great tip on discord, that it is far easier to solder stuff onto the pcb while they still sit in an array and then break them apart afterwards. The spacing does not allow for one to keep an entire column together as-is, so each square must be solo.
- Print the core stl which is the part that will hold everything electronical
- Solder the diodes onto the pcbs
- Solder the sockets onto the pcbs
- Add the pcbs, sockets and switches to the case so that they hold themselves onto the case
- Solder each row and each col.
- Solder rows and cols onto the mcu
- Press fit the trrs and glue it in afterwards as this press fit cannot hold anything in the long run it turned out :)

## Switches, keycaps and filament used on the pictures
On the pictures I use the followng:
- keychrons black OSA keycaps: https://www.keychron.com/collections/all-keycaps/products/double-shot-pbt-osa-full-set-keycap-set
- Matt black PLA (TODO: name?)
- A black trrs cable with slim neck (needed as I didn't make room for anything wider)
- A black usb-c cable

## Learnings
- Trrs requires a thin neck (blunter from my side, next board should have more spacing)
- All three printable parts need a brim (at least on my printer prusa mk4) to work. This means a little border remains even after the brim is removed.
- In order for the top to fit on the core, sanding was needed as they are too tight.
- The bottom of the case has these legs pointing up to hold the core in place. This makes it annoying to take apart.
- My next board will have a pcb (I hope) unless it will be something keywell.

## Special thanks
I have used way more time experimenting with different keycounts, designs and layouts than I thought I needed to before settling with this. During this I got so much help online from so many people that I can't even remember all of them (sorry).  

A special thanks to Wimads from the Bastardkb and Fingerpunch discord servers. Half of all the tricks I use regularly in onshape is because Wimads took his time (hours and hours) learning me the ins and outs in onshape. He also keeps commenting and giving new angles on design and ideas in general.

Another special thanks to Burfkers (who came up with the name "wilson" for this board among other things). Burfkers is to printers and electronics, what wimads is to onshape; a wizard with an eager to help people online. Most of my know-how about printing I owe to this guy. I also had some qmk challenges that Bufkers helped sort out when creating a layout for this keyboard (dont run qmk with sudo unless you have a keyboard that absolutely requires it, like the moonlander for instance).

When it comes to encouragement to decrease the number of keys in my layout, reeve_. (https://github.com/grassfedreeve), casuanoob and apfel (https://github.com/kilipan) has been of great inspiration and part of the reason I kept trying out new combos until I could actually use them.

A thankyou also goes to all the nice people who gave valuable input on the fingerpunch server during the entire development: reeve_, quappo (https://github.com/rmuraglia/menura-kb/), mayday, bravekarma (https://github.com/caksoylar/keymap-drawer), damselfly, Yingeling (https://zhan.co.nl/), saixos, rafaelromao (https://github.com/rafaelromao/keyboards) and crazymittens (https://docs.google.com/document/d/1714zAB5GvLr3M8TnRpMvAdutThKMioJDGraUgG2VCB4/edit?tab=t.0) are some of them.

I general, Quentin from bastardbk.com and sadekbaroudi from fingerpunch.xyz who both have each their discord server. These two servers are the most beginner friendly environments and the people in there have a very high average level of expertise in every area I have yet come across in this regard.
