# Replay 7-Zero Build Instructions<br>
Estimated build time: 1-3 hours depending on soldering experience<br>
Here is a build video of the replay-7-zero<br>

https://www.youtube.com/watch?v=gylts5yvYMM


### PARTS LISTING<br>
Case front, mid-frame and back cover plate<br>
6 countersunk screws for the case back plate<br>
12 pan head screws for the PCB and mid-frame<br>
1 LCD plastic protection sheet<br>
1 LCD screen<br>
2 strips of adhisive backed foam padding for LCD screen<br>
1 small square adhisive backed foam padding for speaker<br>
1 directional game pad plastic piece<br>
4 Game buttons for ABXY<br>
2 rubber game pads for the buttons and directions<br>
2 Black plastic Left/Right button covers<br>
3 smaller black plastic buttons for HK (hot key), Start and Select<br>
1 Printed Circuit Board<br>
1 10,000mAh high capacity battery<br>
1 Raspberry Pi Zero 2w single board computer<br>
1 LCD Driver board<br>
2 Black and Red wires with 2mm white connector on end<br>
3 small white 2 pin male 2mm header connectors for wire connectors and battery<br>
1 Speaker<br>
2 Right angle tactile buttons with red tips for Left/Right buttons<br>
3 Black tactile buttons<br>
1 100ohm resistor<br>
1 LED<br>
1 6 pin power switch<br>
1 40 pin header for Raspberry Pi Zero 2w<br>
1 purple audio amp PCB<br>
1 DC-DC voltage converter board<br>
1 USB battery charger PCB<br>
1 1500uF electrolytic capacitor<br>
8 single stand off pins for audio amp, DC-DC converter, and USB charger<br>
2 two pin stand-off pins for the USB charger PCB<br>
2 HDMI connectors for flat ribbon cable<br>
1 Black flat ribbon cable for HDMI connectors<br>
1 SD card with Replay-7-Zero OS installed and ready to play<br>
<br>


### Short note about best practice soldering a Printed Circuit board<br>
When we assemble a pcb, best practice is shortest height part first, followed by the next taller part<br>
Continue this process through the entire build<br>
This ensures a simple build procedure and you aren't fighting keeping parts down flush<br>
Place printed circuit board (PCB) on your table space<br>
Heat iron to correct temp<br>
Tin your iron by applying a small amount of solder directly to the iron<br>
Clean tip, leaving just a light coating of solder on iron tip<br>
### Speaker wire connector<br>
The speaker comes with wire we do not use<br>
Using a utility knife or flat blade screwdriver, scrape off the covering of the connector<br>

<img width="610" height="344" alt="image" src="https://github.com/user-attachments/assets/958e23df-e27e-4931-9dc5-adfae2cf2e74" />


Apply a iron to the exposed wire connector and tab and remove both wires<br>

<img width="684" height="340" alt="image" src="https://github.com/user-attachments/assets/f9b4ff1a-1968-4e45-bdcd-09b58549b256" />


Solder new speaker wire connector to the speaker<br>
Red wire goes to + side and black wire goes to - side<br>

<img width="676" height="320" alt="image" src="https://github.com/user-attachments/assets/9d04a158-f3d4-4ca3-88e0-72f64e3cfc43" />


### Resistor<br>

<img width="62" height="90" alt="Screenshot 2026-05-27 075253" src="https://github.com/user-attachments/assets/0d0740df-33e3-47ac-97a0-382f3f9a11eb" />



Make U shaped bend to the resistor close to the body of the resistor<br>
Place the resistor into the 2 holes of the pcb where labeled<br>
Make sure the resistor is flush with the pcb<br>
While holding the resistor to the pcb, turn over and bend the tabs away from each other<br>

<img width="1784" height="882" alt="20260520_092337" src="https://github.com/user-attachments/assets/cf8d9d5c-feb2-4357-95f2-e52ffb67ebb6" />


Place on table making sure resistor is flush with the pcb<br>
Solder each post and hole so that solder flows to hold and pin but does not make a ball of solder<br>
After both posts are soldered, trim the excess leads with wire cutters<br>

<img width="4572" height="2596" alt="20260520_093002" src="https://github.com/user-attachments/assets/e8b7c474-e3c7-43ff-a0f6-cee7971f7743" />


### USB Battery Charger<br>

<img width="1424" height="1312" alt="20260520_094514" src="https://github.com/user-attachments/assets/57df653a-d516-4476-893b-f4a5c3213236" />


To solder the USB charger, it is best to slightly prop up the pcb off your work table<br>
This will insure that the stand off pins sit straight when soldering down<br>
There are 6 stand off pins that need to go into the pcb, there should be 2 sets of 2<br>
Place them in the pcb where the USB will mount with the longer end facing up<br>

<img width="966" height="1252" alt="20260520_094624" src="https://github.com/user-attachments/assets/35409f30-5e90-4f03-b21d-a116975b2e40" />


Now place the USB Charger board onto the pins so all 6 pins come through the USB board<br>

<img width="1274" height="1658" alt="20260520_094822" src="https://github.com/user-attachments/assets/e334adf2-a49c-4220-8959-12ba2cf04d27" />


The USB Charger should now be resting on the black stand-off of the pins<br>
Solder all 6 pins onto the USB board and trim the excess off<br>

<img width="1344" height="1618" alt="20260520_094935" src="https://github.com/user-attachments/assets/a05a2d4d-cdbc-4e5b-9dc9-c580e2993ea8" />


While holding the USB Charger, turn the pcb over and place on work table<br>
You no longer need prop up the pcb off the table. Be sure the USB board is flush to pcb<br>
Solder one pin to the pcb then flip over and check that the USB is still flush with pcb<br>
Note: If not, you can heat that pin up and push the pcb down<br>
Now solder the remaining pins of the USB Charger<br>

<img width="1298" height="1314" alt="20260520_095140" src="https://github.com/user-attachments/assets/041a1729-8c3a-481d-9002-cf4e34c05a29" />


### Audio Amp<br>

<img width="1848" height="2456" alt="20260520_093127" src="https://github.com/user-attachments/assets/a11d836c-6b17-4f03-8737-8f0a242c4bb8" />


Once again, prop up the pcb off the table slightly so the pins can float straight when installed<br>
Place the yellow 7 pin header in the pcb so the longer pins are facing up<br>
Place 2 single posts into the other end of the pcb for the amp<br>

<img width="1060" height="1160" alt="20260520_093236" src="https://github.com/user-attachments/assets/364a14fc-0fb5-4418-8892-f5bb403ecdf8" />


Place the amp carefully on top of the pins and header so the amp pcb is flush with the stand offs<br>

<img width="1118" height="1238" alt="20260520_093318" src="https://github.com/user-attachments/assets/cceb88ae-2810-4cd7-a614-15f817a01455" />


solder both single pins and the header pins down. Trim extra lead off of pins<br>

<img width="1170" height="1070" alt="20260520_093447" src="https://github.com/user-attachments/assets/77ebcab6-c4cd-4539-83c9-90acf36bc5f3" />

<img width="1506" height="1178" alt="20260520_093535" src="https://github.com/user-attachments/assets/fb27bfe9-101f-474b-a5d9-66dd9ba15b15" />


While holding the amp, turn the board over and place on work table with the amp sitting flush to the pcb<br>
Solder any one pin down and turn the board over to verify the amp is straight and flush<br>
Turn back over and solder the remaining pins<br>

<img width="1848" height="4000" alt="20260520_093723" src="https://github.com/user-attachments/assets/433909d5-3621-4c8c-96c8-18deb1ac6f7d" />


### DC power converter<br>

<img width="1476" height="1542" alt="20260520_093839" src="https://github.com/user-attachments/assets/e2c75e33-885e-4198-84c8-eca13e94e6cf" />


Prop the pcb off your work table again and place 4 stand off posts (tall side up) in the holes for the DC power converter<br>
Place the DC converter onto the posts<br>
WARNING: Verify that the direction VIN/VOUT is correct! See PCB markings and DC board markings<br>
Make sure it is as straight as possible resting on the black spacers<br>
Solder all for posts down, then while holding the DC converter, turn the pcb over and place down on the work table<br>

<img width="972" height="2022" alt="20260520_093904" src="https://github.com/user-attachments/assets/00b1d526-7f4a-474b-bdb1-f0bc0af07ffd" />




WARNING: Once again, verify that the direction VIN/VOUT is correct!<br>
Solder one pin down, then turn over and verify the DC converter is flat with only a space for the posts<br>
Turn back over and solder the other 3 posts<br>

<img width="1304" height="1866" alt="20260520_094025" src="https://github.com/user-attachments/assets/a0ca821a-6ccd-4224-ad08-6267cedc86d6" />


### Left/Right game buttons<br>
There are 2 right angle tactile buttons used for Left and Right select control<br>
Place one in the upper corner space and turn the pcb over and lay flat on work table<br>
Solder one of the pins and turn over and double check that the button is flush with pcb<br>
Turn back over and solder the remaining pins<br>
Repeat this for the other button<br>
### LCD Power, Battery and speaker connectors<br>

<img width="1176" height="900" alt="20260520_095814" src="https://github.com/user-attachments/assets/abb19d2b-eed4-4484-a1de-2b769facf4b3" />


There are 3 small white 2mm connectors that must be installed in the correct orientation<br>
Look at pcb part outline and notice the notch and how it matches the connector notch<br>
WARNING: Verify the orientation of the connector matches the pcb drawing. If the part is soldered wrong, you could damage your Replay-7-Zero<br>



Place one in one of the 3 locations and while holding, turn over and carefully set pcb down so that connector is held in place<br>

<img width="2812" height="2404" alt="20260520_095900" src="https://github.com/user-attachments/assets/db3340c8-291e-4f54-a198-d5673202bd1a" />

Quickly solder one pin down. If you take too long, you will melt the connector<br>
Turn pcb over and verify it is flush with pcb. It may be a little skewed, that is ok.<br>
Turn back over and quickly solder the 2nd pin down<br>
Verify the connector is good, then repeat for Battery and LCD Power<br>
### Power Switch<br>

<img width="3652" height="2652" alt="20260521_160427" src="https://github.com/user-attachments/assets/2c0c44b2-8838-4f93-bfa1-6ea6d120b603" />


Place the Large slide switch into the pcb so the post sticks out away from the pcb<br>
Turn the pcb over and lay flat on the work table<br>
Solder one pin on the switch, then turn over pcb and inspect the switch is flush still with pcb<br>

<img width="1848" height="4000" alt="20260521_160527" src="https://github.com/user-attachments/assets/2a50adaa-7e61-4cb8-8729-9c72d8d09bf7" />


Solder the remaining pins down and inspect the switch<br>
NOTE: Make sure it is in the OFF position for testing pcb later<br>
### 40 pin header for RPI Zero 2<br>

<img width="1404" height="1126" alt="20260521_161447" src="https://github.com/user-attachments/assets/77f9366f-9d6b-4bd8-99f2-8c3dbebd5fcb" />


Place the 40 pin header flush onto the pcb with the longer pins pointing up<br>
While holding the header to the pcb, turn the pcb over and lay onto your work table<br>

<img width="1030" height="1640" alt="20260521_161522" src="https://github.com/user-attachments/assets/97d86372-c1ee-4e1d-9670-e8a4a41c95ba" />


Solder one corner pin down to the pcb and then turn over and inspect that the header is flush to pcb<br>
Turn back over and continue soldering the other pins.<br>
NOTE: I like to solder one side, turn the board 180 degrees around and solder the other row<br>
Inspect your part before continuing on<br>
### 1500uF Capacitor<br>

<img width="1202" height="922" alt="20260521_162602" src="https://github.com/user-attachments/assets/df7b000f-ffa6-4684-9ae2-101747834851" />


The large capacitor is polarized meaning there is a positive + and a negative - pin<br>
The positive will be slightly longer, but the negative will have a - on the side of the case<br>
Place the capacitor into the holes of the pcb, then fold it over so it is laying down within the pcb drawing<br>
WARNING: Make sure you have the capacitor installed correctly before soldering down. See image<br>

<img width="1136" height="1094" alt="20260521_162647" src="https://github.com/user-attachments/assets/8cdb935a-622b-4dad-9fa3-904d88b1120e" />


Turn the pcb over and solder the pins down and cut the extra length off<br>
### LED power light (Back side of PCB)<br>

<img width="3996" height="2772" alt="20260521_160135" src="https://github.com/user-attachments/assets/716242b7-4d44-4cf3-ad97-04cdf38b2f6c" />

The LED is soldered on the bottom of the pcb along with 3 tactile buttons<br>
The anode is the + and is longer in length making it easy to identify<br>
Push the anode (longer) pin into the + hole followed by the shorter cathode pin<br>
Push the LED flush onto the pcb, then bend the pins slightly apart to hold the LED in place<br>
NOTE: Make sure the LED is straight and flush so it will all fit in the case correctly<br>

<img width="2740" height="2392" alt="20260521_160251" src="https://github.com/user-attachments/assets/3f7aeca7-3203-447c-895c-11c147a38b26" />


Turn the pcb over and solder both pins down and trim the extra length off<br>
Inspect the LED to ensure it is flush and straight as possible<br>
### VOLTAGE TEST (requires volt meter)<br>
TEST 1<br>
At this point you can connect the battery to the Replay-7-Zero board and make sure nothing is underneath<br>
You can plug in a USB charger and see if the red light comes on on the charger. If not, turn off circuit board, check your work<br> 
TEST 2<br>
For this test, you can unplug the USB charger, then power on the Replay-7-Zero board<br>
The LED should be visible on the bottom side. If so, proceed to the next step<br>
TEST 3<br>
With your volt meter, test that voltage is between 4.7-5.1 volts. If it is within that range, power off, disconnect battery and continue build<br>
If it is lower than 4.7V, with a small flat blade screw driver, turn the screw on the DC controller counter clock wise, just a very little bit and test voltage. Try and get it slightly up to between 4.7V and no more than 5.05V.<br>
If it is higher than 5.1V, turn the screw on the DC controller clock wise, say from 1 oclock to 2 oclock and test voltage again to get it between the acceptable value.<br>
Once the DC voltage is set correctly, turn off the pcb, disconnect that battery.<br>
It is recommended that you put something like a drop of finger nail polish on the screw to keep it from turning. Do not use glue!<br>
### Tactile switches (back side)<br>

<img width="1500" height="798" alt="20260521_161114" src="https://github.com/user-attachments/assets/5e4afb6d-0d42-4a2b-9d31-da10bebb8ed4" />


There are 3 tactile switches that mount on the back side of the board. When you put them in the pcb, you can close the pins together some so it holds onto the pcb better.<br>
Turn the board over and solder one pin, then check to make sure button is flush<br>

<img width="4560" height="2660" alt="20260521_161321" src="https://github.com/user-attachments/assets/ff6376e8-e8f7-4519-8dc9-2588181595a0" />

Solder the remaining pins and repeat for the other 2 buttons<br>
Turn the board over and continue to next step
### Raspberry Pi Zero 2w (rpi)<br>

Place the Raspberry Pi (rpi) onto the pcb with the SD card slot closest to the edge and the chips facing up<br>
place the mid frame brace under the rpi to help support it from sagging<br>
<br>
OPTIONAL: While holding the rpi down, cut the extra length from the top of the pins leaving only a little on top to solder to<br>
<br>
While holding the rpi down flush onto the connector, solder 1 pin down on the corner<br>
Check to make sure the rpi is still flush and level and solder another corner down, check again<br>
Now solder all the remaining pins and check your work so no extra solder flowed onto the rpi<br>

### Video Driver board power connector<br>


<img width="1848" height="4000" alt="20260521_170459" src="https://github.com/user-attachments/assets/78df6a12-b5e8-4fe7-80c1-cdd8200c144b" />

The video driver board needs a power connector wire soldered to the pcb<br>
There is a set of 6 holes on the side of the pcb and the 2 top and bottom are for the red wire and the black wire<br>
You can turn the pcb over onto the bottom and read 5V and GND for the 2 holes<br>
Push the end of one wire through the correct hole and solder down that wire<br>
Solder the other wire into the other holes so both wires match the pitcher above<br>

### Connect the video driver to the LCD<br>
Lay the LCD facing up on the table, and the video driver pcb just at the end of the flat cable<br>
Lift the black tab of the connector on the pcb so that you can insert the cable into the connector<br>
It opens like a door so it will swing upwards<br>
The pins on the flat cable will be upwards so you can see the metal pins of the cable<br>
When the cable is seated as far in as it can go, close the connector by folding it back down<br>

### Assembling the Replay-7-Zero<br>
For easier assembly, find something to lift the case up off the table slightly but still supported<br>
Place the case so the front is on the table and the bottom of the case is close to you<br>
Make sure none of the button or controllers are blocked so they can fit into the case<br>
Peel off the protector sheets from the plastic cover that goes before the LCD screen<br>
You may need to wipe it down with rubbing alcohol before placing in the case to be sure it is free of debris<br>
Next, peel off the screen protector from the LCD then place the screen into the case with the cable and driver board laying towards the bottom out of the case<br>
Place the speaker into the speaker holder area facing down towards the table with the cable facing to the edge<br>
Peel the backing from the small square foam pad and place it on the speaker<br>
This prevents the speaker from contacting the CPU<br>
Peel and place the 2 long foam strips on the LCD so they are evenly spread apart preventing the LCD and PCB from touching<br>
Next, place the direction plastic into the right side, any direction will work<br>
Place the rubber button over the direction pad and you will see 4 small tabs that go into the rubber<br>
Place the START SEL black buttons into the 2 holes below the direction pad<br>
See image below for orientation<br>

<img width="1644" height="2268" alt="20260523_211118" src="https://github.com/user-attachments/assets/b4d24487-6483-46cb-aec7-0e6aacbc5450" />

Place the 4 buttons A,B,X,Y into their holes. These are keyed so there is a large tab and a small tab so they won't rotate<br>
Place the other rubbon button over the 4 plastic buttons and lock into place with the 4 small pins<br>
Place the HK "Hot Key" black button into the hole below the rubbon button<br>

<img width="1434" height="1938" alt="20260523_211115" src="https://github.com/user-attachments/assets/4b2178bc-69ef-4ba1-8e05-8c34fae79360" />

### Left/Right Game buttons<br>

Place the Left/Right black plastic buttons onto the red push buttons on the top edge of the PCB<br>

### Place the main board into the case starting with the top edge at an angle<br>
WARNING: Be careful of the on/off switch, it is fragile and can break easily<br>
ALSO: Do not put the SD card into the Raspberry Pi until it is mounted into the case later<br>

<img width="3132" height="1702" alt="20260525_114222" src="https://github.com/user-attachments/assets/f109d392-967c-4efa-ab55-b00630612373" />

### Secure the mainboard to the case with the 8 screws<br>
There are a total of 8 screws around both the direction pad and the A,B,X,Y buttons<br>
There are 4 other holes that are used for the mid-frame, we will mount that later<br>
While holding down the PCB<br>
Screw one in most of the way, leaving the board loose for adjustment<br>
Screw in another screw on the other side most of the way down<br>
Repeat for all 8 screws, once all 8 are in, carefully tighten until just snug <br>
WARNING: If you over tighten the screws, you could break the case post<br>
See image below for how the PCB should look when mounted<br>

<img width="2754" height="1440" alt="20260525_114602" src="https://github.com/user-attachments/assets/a23048cc-7132-4153-8377-45c47e10d7a4" />

### Install the Mid-Frame above the PCB<br>

<img width="3662" height="1848" alt="20260523_211908" src="https://github.com/user-attachments/assets/63ec195b-0329-4d48-90f8-0208ae6fb934" />


Install the mid-frame so it slides slightly under the Raspberry Pi and the 4 holes line up with the PCB<br>
Install the 4 screws in the same manner that you did for the 8 other screws. Do not over tighten<br>
Make sure the screw near the Raspberry Pi is all the way down so it can not touch the HDMI cable we will install shortly<br>

### HDMI Cable assembly<br>
There are 2 connectors and one short flat ribbon cable<br>
Each side of the cable has pins exposed at the end<br>
On one connector, open the retaining tab and slide the cable pins DOWN into the connector<br>
Lock the cable connector down by closing the tab<br>
Repeat exactly for the other side, with the pins facing down on these connectors<br>
Plug one end of the HDMI cable into the Video Driver board and let the board hang down still<br>

### Plug the speaker into the speaker connector on the PCB as shown below<br>

<img width="2582" height="1406" alt="20260523_211938" src="https://github.com/user-attachments/assets/df836983-605d-4285-9fa0-ab513b65c30d" />

### Install the Video Driver Board onto the Mid-Frame<br>

<img width="3074" height="1584" alt="20260523_212014" src="https://github.com/user-attachments/assets/d523408e-e8eb-49e1-99f3-3f876d533bf2" />

Carefully lay the video driver board with a 90 degree fold into the pins of the mid frame as shown above<br>
WARNING: Do not crease the flat ribbon cable or it could damage the LCD<br>
Plug the power wire into the PCB near the USB connector<br>
Plug the other end of the HDMI cable into the Raspberry Pi. Use caution or you may unclasp the HDMI flat ribbon cable when installing<br>

<img width="1630" height="1814" alt="20260525_120330" src="https://github.com/user-attachments/assets/4cef77ca-0599-45f7-9250-4c07b3b031b3" />

### Install the Battery<br>
Install the battery so the text on the battery is facing down and the cable is near the slot in the mid-frame<br>
WARNING: For next step, make sure the power switch on the Replay-7-Zero is turned off<br>
Plug the battery into the battery connector on the PCB<br>
Your Replay-7-Zero should now look like the image below<br>

<img width="4000" height="1848" alt="20260525_120243" src="https://github.com/user-attachments/assets/42ab66ae-f7ac-4adf-9ad3-ff070dc81ff4" />

### Install the SD card into the Raspberry Pi SD card slot<br>
Install the card as shown in the picture below<br>

<img width="1630" height="1814" alt="20260525_120330" src="https://github.com/user-attachments/assets/c1807b9b-29ff-48f6-a7fe-f942bafe7467" />


### Install the back cover plate<br>
The back cover plate is formed so it will fit snug onto the front when placed correctly. If upside down, it won't fit right<br>
It's easier to install one of the middle countersunk screws into one of the middle screw locations first while holding the case down<br>
Repeat for all 6 screws and you have the case closed<br>

### Power up and test your Replay-7-Zero<br>
When you power up your Replay-7-Zero you will see and HDMI message showing the LCD screen has powered up correctly<br>
The screen may go blank and maybe flash for a bit, but eventually you should see the Recalbox OS logo appear<br>
NOTE: IF YOU DO NOT SEE THE RECALBOX LOGO AFTER 30 SECONDS, TURN OFF THE MACHINE, OPEN UP AND CHECK YOUR HDMI CONNECTORS<br>
Once the Replay fully boots up, you should see the console system options and hear the Recalbox menu music playing<br>
You can now start your gaming adventure!<br>
