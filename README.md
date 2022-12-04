# Veency

A WIP fork of Saurik's [Veency](http://git.saurik.com/veency.git), as it was no longer maintained, this fork is aimed to provide later iOS support.

## Description

**[Original Depiction](https://cydia.saurik.com/info/veency/)**

If your device has ever been *just* out of reach, this package is for you: you'll never need to touch your iPhone, iPad, or iPod Touch again! Instead, sit back and enjoy the comfort of remotely logging into your phone via VNC. You can view the screen, touch controls, and even push the lock and menu buttons all from the comfort of your desk- or laptop.

To activate, install it and then go to Settings and set a password. When connections come in you will get a notification dialog asking if you want to accept. You can tell whether there are any active clients by way of an icon on the status bar. Just remember: VNC is not a very fast protocol ;P.

The default [Mac OS X Screen Sharing VNC client](http://hints.macworld.com/article.php?story=20071023174751182) is compatible, among many others. The App Store also includes some VNC clients.

(I recommend turning off the cursor in your client, since it causes some graphical artifacts. If you want a cursor, you can use the one that Veency provides. I also recommend using 8-bit color depth as it is much more usable.)

### Controls

 - **left click**: touch screen
 - **middle click**: lock button
 - **right click**: menu button
 - **keyboard**: keyboard ;P

## TODO

 - [ ] iOS11+ support
 - [ ] drop armv6 and armv7 support, add arm64e
 - [ ] use dylibs provided by distros if possible
