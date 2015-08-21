# Blackjack
Blackjack. All in strict Javascript

This was my first "major" program in any language. It's located at http://www.javascriptisscary.com/blackjack/

This code is intensely sloppy, and not particulary readable. The script is all embedded in the HTML. I'm saving it with
no edits from the original for posterity. I plan on making an updated version of it at some point, however.

I learned javascript through codecademy.com, and working my ass in front of my computer. I was doing about 4 hours a day 
for 3 months. (Though a lot of that time was also spent dabbling in PHP and other things.)

I started the program by making it all through the console, then alert boxes (lol.) I had 0 experience with the DOM so I 
didn't know where to start. Eventually, slowly, I moved it over to the DOM with very basic CSS. My biggest issues, 
beyond working with the DOM, were with calculating mutiple aces in a hand (ie:if you have 3 aces, are they all worth 
one, or is one still worth 11?) and splitting. I ended up only allowing one split due to time constraints of starting 
a course at careerfoundry.com the next day. 

Adding to my time to create this were various little bugs that, because of a lack of experience, it would take me hours 
to realize the issue(s). Learning about "strict mode" and "debugger" obviously helped quite a bit. I remember sitting in 
front of a particular problem for 8 hours, all because I didn't know about strict mode yet, and had forgotten to declare 
"var x =0" and instead declared with "var x;". It kept spitting out "undefined" and I had no idea why. After scouring 
the internet through all sorts of complex loops and recursions and things that had nothing to do with anything, I 
realized on my own that you cannot add a number to an undefined variable. ;)

I ran into many little issues like that, all which taught me a ton. It was a fun experience and I was very happy to 
finally get it out in internet land.

-----------------------

Known issues:

Slow loading cards.

Faceup ace for dealer does not show when asking for insurance (on google chrome.)

No label for chips.

Could be a lot prettier.

Descriptions in the alert box and/or "alert line" can be a bit off. All money is rewarded correctly though.
