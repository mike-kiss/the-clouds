## The Clouds!

![Fluffy, illuminated clouds installed above they foyer of a modest apartment. They glow a variety of rainbow colors.](https://raw.githubusercontent.com/mike-kiss/the-clouds/main/the-clouds-installed.png)

A whimsical collection of LED strips, wire, and quilt batting. Originally built as outdoor trail lighting for a summer art festival, it is now permanently installed in the home of one of its creators. 

Fabricated and co-designed by [Ecco Pierce](https://allthingsecco.com/).

![Mike Kissinger and Ecco Pierce The Clouds    2017 Wire, quilt batting, LED strips, buttons, Arduino, speakers, hoodie This award-winning tour de force wowed audiences at the Firefly Arts Festival in 2017 and 2018, where its gentle glow guided guests through treacherous terrain, then blew their minds when it broke into a raucous thunder storm on a semi-random timer. Its interactive button amused, amazed, tantalized, and trolled with shorter animations. After a quite literal debugging, it is now a permanent installation in the Kisszzo Gallery where it continues to provide light and whimsy to all who dare to behold its majesty.](https://raw.githubusercontent.com/mike-kiss/the-clouds/main/the-card.jpg)

### The Technology Stack
- Based on an Arduino Mega.
- Drives 3 WS2811 LED strips (two for two sets of clouds, plus one for the lightning bolts).
- Uses an Adafruit_VS1053 to play sounds.
- Uses an array of relays to provide directional sound by directly switching the signal between speakers. Originally these were 3 battery-operated portable speakers. Currently it runs a single subwoofer and 3 satellite speakers.
- Has a public button that changes animations and color palettes for the default trail lighting. Originally it allowed the public to make it do a small animation (a "trick") every 60 seconds. It will also do the trick animations on a semi-random timer.
- Has a private button that triggers a thunder storm. It will also do the storm animations on a semi-random timer.

![Fluffy, illuminated clouds installed above they foyer of a modest apartment. They glow a soft white.](https://raw.githubusercontent.com/mike-kiss/the-clouds/main/the-clouds-installed-white.png)

### The Materials
- The clouds themselves are welded galvanized steel dressed with two layers of quilt batting.
- The lightning bolts are laser-cut acrylic coated with spray adhesive (except where a few pieces were lost and replaced with pebbled plastic from gallon-size drink containers).
- The public button is set in a 3d printed case. The private button is hot-glued into a pipe wrapped with colorful electrical tape.
- The cables are dressed in split sleeve wire loom.
- The control box and subwoofer are dressed in an old rainbow hoodie.

![An illuminated blue panel hangs on the wall with a bright white button in the center. Below, it connects to a rainbow box with has another device on top of it. The device looks like a rainbow striped detonator button](https://github.com/mike-kiss/the-clouds/blob/main/the-clouds-buttons.jpeg?raw=true)
