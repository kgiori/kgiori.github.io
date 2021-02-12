## Shared Technology Information

Below I share tidbits of useful technology. I like giving workshops to help people get started building their own technology solutions, especially those that incorporate open software and hardware. Ask me if you have ideas for groups who would appreciate a live workshop. The benefits of open source collaboration are immense, which is why I've always been a fan of FOSS, open hardware, and open 'silicon' approaches. We all stand on the shoulders of other brilliant women and men.

### MicroBlocks

http://microblocks.fun - 
Free and open source software for physical computing that is just plain faster and easier than anything else I've tried. The IDE is blocks-based but the blocks actually run as byte code on the microcontroller. It supports many libraries, including one to easily build your own WebThings out of any of the supported 32-bit MCU boards. Unlike Snap4Arduino, these MicroBlocks programs run even after you disconnect the board from your computer. This is not just for kids!

Tutorials: http://microblocks.fun/learn <br>
Wiki: https://wiki.microblocks.fun <br>
Hour of code: https://gpblocks.org/hourOfCode2018/microbitIntro/

### WebThings (spun out from Mozilla)

https://webthings.io (formerly https://iot.mozilla.org) - 
I run the WebtThings Gateway on a Raspberry Pi 4 to power my own private smart home. This fully open and community supported project helps to bring IoT devices to the web, in a private, secure, and interoperable manner. (Note I am biased as I used to work on this project at Mozilla, leading advocacy, expanding industry and strategic relationships, and bringing it to educators via the MicroBlocks WebThings library.)

### Snap! and Snap4Arduino

https://snap.berkeley.edu/ and 
http://snap4arduino.rocks/ - 
Snap<i>!</i> is also an amazing programming environment, but interaction is focused on the computing platform you are doing the development on (e.g. a laptop). It runs in a browser. It goes beyond Scratch -- as far as your imagination in first class programming constructs. 
Snap4Arduino lets you tie the UI of your computer with the real world of microcontroller boards that can run Arduino and Standard Firmata. Like MicroBlocks, it is a superb way to engage in programmable interaction with the physical world. However, it does require that the microcontroller remain tethered to the computer.

### PlatformIO

https://platformio.org - 
When I'm not programming in blocks, I prefer to use PlatformIO to program any MCU hardware, especially those that support the Arduino framework. In fact, the way I build and upload the MicroBlocks virtual machine (VM) onto several niche microcontroller boards is using the extremely veratile PlatformIO tool. I wish all semiconductor (chip) makers would support a PlatformIO build environment and examples for their products!

Enjoy!
