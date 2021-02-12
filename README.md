Below I share tidbits of useful technology. I like giving workshops to help people get started building their own technology solutions, especially those that incorporate open software and hardware. Ask me if you have ideas for groups who would appreciate a live workshop. The benefits of open source collaboration are immense, which is why I've always been a fan of free and open source software (FOSS), open hardware, and open 'silicon' approaches. We all stand on the shoulders of other brilliant women and men.

# [TechWomen](https://techwomen.org) Emerging Leaders and Fellows
Here are ideas to improve STEM learning in your community.

## Recommended Hardware 
* [MicroBlocks Activity Kit](https://www.okdo.com/us/p/okdo-microblocks-classroom-activity-kit/) or [BBC micro:bit](https://microbit.org/buy/) and accessories (key components: micro:bit, piezo or other speaker, NeoPixel LEDs)
* Other electronics: small batteries, LEDs, resistors, alligator clips

## Recommended Software 
* [MicroBlocks IDE](http://microblocks.fun/) - free [download](http://microblocks.fun/download) or [run from within Chrome browser](http://microblocks.fun/mbrun)
* [User Guide](https://wiki.microblocks.fun/ide)
* [Blocks Reference](https://wiki.microblocks.fun/reference_manual)
* [Libraries](https://wiki.microblocks.fun/libraries)
  
## Learning Content
[MicroBlocks Activity Card](http://microblocks.fun/learn) lessons and videos supporting the [Kit](https://wiki.microblocks.fun/en/kits/okdoactivitykitmicrobit).
1. Use Buttons to Control LEDs <br> Make LED Animations <br> [lesson](https://wiki.microblocks.fun/card_1_buttons_led_display.pdf) - [video](https://youtu.be/Pu1jFMuyDpE)
2. Display Messages by Scrolling Text <br> Create a Magic 8-Ball <br> [lesson](https://wiki.microblocks.fun/card_2_scrolling_magic_8-ball.pdf) - [video](https://youtu.be/igRhAvRpAqI)
3. Radio Communications <br> Do Text Messaging Using Only 2 Buttons! <br> [lesson](https://wiki.microblocks.fun/card_3_radio_texting.pdf) - [video 1](https://youtu.be/o3Mly7wOMOM) - [video 2](https://youtu.be/0ISMFgFI-kY)
4. Creating Sounds <br> Play the Tune Happy Birthday <br> [lesson](https://wiki.microblocks.fun/card_4_sound_music-small.pdf) - [video](https://youtu.be/wUXRA6ddepI)
5. Light up LEDs in Many Colors <br> Here Comes an Ambulance <br> [lesson](https://wiki.microblocks.fun/card_5_colorful_leds_ambulance.pdf) - [video](https://youtu.be/HMQY5n7dhsc)
6. Read Electronic Sensors <br> Graph Sensor Values to See the Big Picture <br> [lesson](https://wiki.microblocks.fun/card_6_sensors_graphing-small.pdf) - [video 1](https://youtu.be/t-X5qIZYqhY) - [video 2](https://youtu.be/Zh-b2QMKRnM)
7. Count Your Steps <br> Alert! Alert! Backpack Security Monitor and Alarm <br> [lesson](https://wiki.microblocks.fun/card_7_step_counter_motion.pdf) - [video](https://youtu.be/KIOewCLBb3U)
8. Be a Scientist and Collect Data <br> Remote Data Logging Using the Radio <br> [lesson](https://wiki.microblocks.fun/card_8_data_logging.pdf) - [video](https://youtu.be/ZBU6l-4XjQw)
9. Make a Game <br> Play the Simon (Memory) Game <br> [lesson](https://wiki.microblocks.fun/card_9_games_simon-small.pdf) - [video](https://youtu.be/oKuQvBGw41o)
10. Turn a Flashlight into a Remote Control <br> Play Flashlight Tag <br> [lesson](https://wiki.microblocks.fun/card_10_flashlight_remote_tag.pdf) - [video](https://youtu.be/AhnheX1g_nU) - [long video](https://youtu.be/VMPMrNIcQtw) <br>
Or follow this [playlist of all the videos](https://youtube.com/playlist?list=PLHsB9Dgp_QuN00KnVoIxXSjtI0U8CxHw6).

## Introduction to Electronics
* [Electronics reference](https://wiki.microblocks.fun/electronics/working_with_electronics) -- can use batteries for power instead of micro:bit to light LEDs
* [Electronics projects](https://wiki.microblocks.fun/en/electronics) -- check back as there will be more projects added

# Technology References

## [MicroBlocks](http://microblocks.fun)
Free and open source software for physical computing that is just plain faster and easier than anything else I've tried. The IDE is blocks-based but the blocks actually run as byte code on the microcontroller. It supports many libraries, including one to easily build your own WebThings out of any of the supported 32-bit MCU boards. Unlike Snap4Arduino, these MicroBlocks programs run even after you disconnect the board from your computer. This is not just for kids!

[Tutorials](http://microblocks.fun/learn) - [Wiki](https://wiki.microblocks.fun) - [Hour of code](https://gpblocks.org/hourOfCode2018/microbitIntro)

## [WebThings](https://webthings.io)
WebThings was spun out from [Mozilla IoT](https://iot.mozilla.org) in December 2020. I run the WebThings Gateway on a Raspberry Pi 4 to power my own private smart home. I can use my voice (locally and privately) to control things. I love the convenience of putting things on automated schedules. This fully open and community supported project helps to bring IoT devices to the web, in a private, secure, and interoperable manner. (Note I am biased as I used to work on this project at Mozilla, leading advocacy, expanding industry and strategic relationships, and bringing it to educators via the MicroBlocks WebThings library.)

## [Snap!](https://snap.berkeley.edu)
Snap<i>!</i> is also an amazing programming environment, but interaction is focused on the computing platform you are doing the development on (e.g. a laptop). It runs in a browser. It goes beyond Scratch -- as far as your imagination can go with first class programming constructs. 

## [Snap4Arduino](http://snap4arduino.rocks)
Snap4Arduino lets you tie the UI of your computer with the real world of microcontroller boards that can run Arduino and Standard Firmata. Like MicroBlocks, it is a superb way to engage in programmable interaction with the physical world. However, it does require that the microcontroller remain tethered to the computer.

## [PlatformIO](https://platformio.org)
When I'm not programming in blocks, I prefer to use PlatformIO to program any MCU hardware, especially those that support the Arduino framework. In fact, the way I build and upload the MicroBlocks virtual machine (VM) onto several niche microcontroller boards is using the extremely veratile PlatformIO tool. I wish all semiconductor (chip) makers would support a PlatformIO build environment and examples for their products!

Enjoy!
