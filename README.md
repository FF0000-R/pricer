# pricer
Trying to somewhat reverse engineer a Pricer digital price tag in the hope to be able to control its e-ink display, IR transmitter / reciever, and memory. This is mostly just for learning purposes.

---

## Project intoduction.

The Pricer electronic shelf label or digital price tag is a device that is meant to replace traditional price tags in all kinds of shops.
The point of this project is for a complete begginer (me) to understand clearly how this device works, how it is implemented in a system and *try* to interact with the device's firmware, maybe even upload our own.

This project was put in place by a highly inexperimented person, who obviously is **very** open to any input or discussion with anyone who is remotely interested or simply able to help. Contacts (for now) are at robin.e.debroux@gmail.com.

---

## The hardware

###### Description

As previously stated, our device is made by Pricer Solutions. The one in question is a SmartTAG HD – Graphic label. 
Here is the manufacturer's product details:

>* Fully graphic, E-ink displays - paper like
>* 20 000 full memory updates per hour
>* Up to 7 years battery life - easy battery change out
>* Flash ready and NFC
>* Black & White, Red color available - Yellow color soon
>* Four sizes: small, medium, large, tall
>* Dedicated patented freezer label
>* Multiple pages for merchandising and inventory information

The precise model we will be looking at has a 00 x 00 mm screen, it is a black and white dot matrix display made by Weifeng

Here are images of the pcb/display assembly, the whole thing is about 00 mm long by 00 mm wide.  
(*detailed pictures of the pcb and back of the display are below*)

![Photo Documentation](/docs/side-A.JPG)
![Photo Documentation](/docs/side-B.JPG)

Getting your hands on one of them isn't so hard, you can directly ask where you shop, to see if they 
