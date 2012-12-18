This is an experimental work. Today I saw a thread in the Brazilian community list and it was a request for help and priorization work to support the translation of Firefox OS articles. I decided to give it a try and before any translation work I wanted to see what others were doing. It was a bit scary to see a selection of brazilian contributors jumping to do a translation effort using original English content that I felt not as optimal for translation. The problem with that is that written complexities are scaled when a translator is not an expert in the technical field. 

## The process

Since I am not a native English speaker, the way I was able to detect problems was simply evaluating the end result in Portuguese — looking all technical aspects. So instead fixing contributors translation mistakes, I have decided to invest a bit of time to make the original article more plain and more direct. 

And since I lacked the right English knowledge, my experiment was to ask help from English native speakers using Mechanical Turk. I then became the final reviewer as it turns out I know a bit about Mozilla wording and I also understand the technical subject. The goal of this work was first to test how other crowd sourcin networks can be used to help contributors to gain knowledge and speed as they help open source projects. I also felt that when things are in "high priority" there is a risk in losing quality. It was an experiment to keep many eyes towards contributors work — and to reduce noise. I feel that the supporters from Mechanical Turk were able to give me a great English lesson too — it was pleasant to a point I had to write to one of them asking he/she to become a Mozilla contributor. 

## Summary of the project

### Reviewed article on MDN

https://developer.mozilla.org/en-US/docs/Mozilla/Boot_to_Gecko/Firefox_OS_build_prerequisites

### History of changes incorporated from mturk reviewers 

https://developer.mozilla.org/en-US/docs/Mozilla/Boot_to_Gecko/Firefox_OS_build_prerequisites$compare?to=340425&from=335777

### Assigment Requirement document created in Mechanical turk

I decided to write the task with a bit of a background and each assignment had a prize of 0.50 USD. I paid 5 assigments but have used 3 of them. 

``` 
Review an open-source article for its English content 
 Hi, 

I am a brazilian developer and I was requested to provide a pt-BR (  Brazilian portuguese ) translation to a Mozilla article. When I was  about to translate I noticed that the English content seemed a bit poor.  However, and because English is not my native language, I am now  looking for a support from English writers or native English speaking  citizens to help me out — first to fix the English content. 

Here is the first case I have: 

https://developer.mozilla.org/en-US/docs/Mozilla/Boot_to_Gecko/Firefox_OS_build_prerequisites 

I would like your input about key English mistakes or problems you  see in this writing. Simply pick a part you think is critical and write  down your recommendation or note. 

Summary of task: 

1) Acknowledge the above link / article is understood by you
2) Acknowledge you are a native English speaker and loves your mother language
3) Identify parts of the English text you think are critical and/or can be improved _ pick a few you like and work on it. 
4) Provide your recommendation/note for the identified text areas you think are worth changing. 

```

### Raw Data provided by mturk reviewers 


```
HitId,HitTitle,Annotation,AssignmentId,WorkerId,Status,AcceptTime,SubmitTime,Answer 1
27QH88MQU6L5O82PS5IX24AJW9HUB7,"Review an open-source article for its English content "," ",2SHDOBDDP8PJWH1QNCOMG3Q5F4T3E4,A1T78PV59MJ88L,Approved,"Mon Dec 17 18:24:25 PST 2012","Mon Dec 17 18:33:52 PST 2012","Before you can even get the code, so you can build Firefox OS. You'll need a properly-configured build system. You can currently build on 64-bit Linux distributions and Mac OS X.

Before you download the code you will need a properly configured build system.  You can currently build on 64-bit Linux distributions and Mac OS X.

This is important. Even though we support several phones, some of them are available in multiple variations, and only select variations of them may be supported. In addition, some devices are supported better than others. At this time, the following devices have Firefox OS ports available:

This is important: Even though we support several phones, some of them are available in multiple variations only a few of which may be supported. Additionally, some devices have better support than others. Currently the following devices have Firefox OS ports available:

The tier 2 devices are generally functional and many developers, especially app developers, are using them, so they tend to pick up changes secondarily.

The tier 2 devices are generally functional and many developers, especially app developers, are using them, so they tend to be updated less frequently.

These devices are those for which Firefox OS can be built but are not being actively worked on on a regular basis by core developers, so their reliability and feature set may lag noticeably behind the tier 1 and even tier 2 devices.

These devices are those for which Firefox OS can be built but are not being actively worked on by core developers, so their reliability and feature set may lag noticeably behind the tier 1 and even tier 2 devices.

The only model that works is the i9100; no other variants are officially compatible. (i9100P might work, since the only change is a NFC chip added)
The only model that works is the i9100; no other variants are officially compatible. (i9100P might work, since the only change is an additional NFC chip)",
27QH88MQU6L5O82PS5IX24AJW9HUB7,"Review an open-source article for its English content "," ",2BHC6SK9RJ85OWPCOLDAFPMQUVXS4E,AHF8JUSE0NN87,Approved,"Mon Dec 17 18:12:06 PST 2012","Mon Dec 17 18:49:35 PST 2012","I read and understood the above link. I'm a native English speaker, absolutely love the language, and am great at editing.

I'd change the first sentence at the above link to read as follows:

Before obtaining the code to build Firefox OS, you'll need a properly-configured build system. You can currently build on 64-bit Linux distributions and Mac OS X.

I'd change this sentence accordingly:

Even though we support several phones, some of them are available in multiple variations, and only select variations may be supported.

You might want to consider changing the word 'variations' to the word 'models'.

I would also change this sentence: 'Features will typically arrive, and bugs will be fixed, first for these devices.' to read as follows:

'These devices will typically be the first to receive bug fixes and feature updates.'

The semicolon should be changed to a colon in this sentence:

""There are two emulators available: one emulates ARM code and the other runs everything in x86 code.""

The following sentence has a ton of commas and perhaps parenthesis would read a little bit better:

'Tier 2 devices are generally functional and many developers (especially app developers) are using them, so they tend to pick up changes secondarily.'

I would also reword the following sentence accordingly (It can be split into two sentences since it has two complete ideas):

'Firefox OS can be built for these devices, but they are not being actively worked on on a regular basis by core developers. Their reliability and feature set may lag noticeably behind tier 1 and even tier 2 devices.'


In all instances, it should say '64-bit', or alternatively, '64 bit'. Not '64 bits'. For example:

'An installed 64-bit GNU/Linux distribution (we recommend Ubuntu 12.04).'

RAM should be in all caps.

This sentence: ""Additionally to the steps above needed to fix issues with the 32-bit versions of the libX11.so and libGL.so libraries you will need to specify GCC 4.6 as the default host compiler before building, after having retrieved the sources see here how to do it."" needs fixing. I would reword it as follows:

""In addition to the steps above needed to fix issues with the 32-bit versions of the libX11.so and libGL.so libraries, you will need to specify GCC 4.6 as the default host compiler before building. After having retrieved the sources, see here how to do it.""

The text ""Xcode 4.3.1 (OS X 10.7 ""Lion"") and other newer versions such as 4.4.1+ (that is, Mac OS X10.8 ""Mountain Lion""), won't necessarily bring the required Command Line Utilities."" should be changed as follows:

""Xcode 4.3.1 (OS X 10.7 ""Lion"") and other newer versions such as 4.4.1+ (that is, Mac OS X 10.8 ""Mountain Lion""), won't necessarily include the required Command Line Utilities.""

I would change this: ""Then you need to open a terminal and run this command in the terminal"" to this: ""Then run this command in a new terminal window"" or this if you want to be more verbose: ""Then open a new terminal window and run the above command."" (note: assuming the instructions are referring to the command preceding them)

Everything after that looks pretty good, especially since much of it is terminal commands. Overall, the instructions are really well written and understandable.

",
27QH88MQU6L5O82PS5IX24AJW9HUB7,"Review an open-source article for its English content "," ",2PV95SW6NG1FS0UBXN2YK1F1Y4DHVU,ANQUF4L67Y9QS,Approved,"Mon Dec 17 18:25:28 PST 2012","Mon Dec 17 18:50:27 PST 2012","Hi Marcio...your instincts were correct about this article - there are a couple parts that would read a bit odd to a native American English speaker.  Nothing drastic, but I did make a few punctuation and simple word and phrase changes and feel it flows much better now. The complete text of the page is duplicated below...when you see the same paragraph below the original one, look carefully and you'll spot the changes I recommend.

Good luck on your project, and best regards from a retired teacher.

*********************************

Before you can even get the code, so you can build Firefox OS. You'll need a properly-configured build system. You can currently build on 64-bit Linux distributions and Mac OS X.

Before you can even get the code so you can build Firefox OS, you'll need a properly-configured build system. You can currently build on 64-bit Linux distributions and Mac OS X.

Have a compatible phone or use emulators.

You must have a compatible phone, or use an emulator.

This is important. Even though we support several phones, some of them are available in multiple variations, and only select variations of them may be supported. In addition, some devices are supported better than others. At this time, the following devices have Firefox OS ports available:

This is important: Even though we support several phones, some of them are available in multiple variations, but only select variations of them may be supported. In addition, support for some is better than for others. At this time, the following devices have Firefox OS ports available:

Tier 1

Tier 1 devices are those which are being actively supported as a primary target for development. Features will typically arrive, and bugs will be fixed, first for these devices.

Tier 1 devices are those which are being actively supported as a primary target for development. Features will typically arrive, and bugs will be fixed first for these devices.

Unagi
Unagi is a phone being used as a test and development platform as a low-to-midrange smartphone. Many core Firefox OS developers are working on Unagi.
Otoro
Otoro is a phone being used as a test and development platform as a low-to-midrange smartphone. Many core Firefox OS developers are working on Otoro.
Pandaboard
The Pandaboard is a development board based on the OMAP 4 architecture, used to do development work on mobile platforms.
Emulator (ARM and x86)
There are two emulators available; one emulates ARM code and the other runs everything in x86 code.
Desktop
You can also build a desktop version of Firefox OS; this runs Gecko in a XULRunner application, and you then use the Gaia user experience inside it.
You can, of course, build the desktop client or one of the emulators without a phone.

Tier 2

The tier 2 devices are generally functional and many developers, especially app developers, are using them, so they tend to pick up changes secondarily.

Samsung Nexus S
The known working model numbers of Nexus S devices are GT-I9020A and GT-I9023. Others may work.
Samsung Nexus S 4G
The SPH-D720 is supported as a tier 2 device.

Tier 3

These devices are those for which Firefox OS can be built but are not being actively worked on on a regular basis by core developers, so their reliability and feature set may lag noticeably behind the tier 1 and even tier 2 devices.

These devices are those for which Firefox OS can be built, but are not being actively worked on on a regular basis by core developers. Their reliability and feature set may lag noticeably behind the tier 1 and even tier 2 devices.

Samsung Galaxy S2
The only model that works is the i9100; no other variants are officially compatible. (i9100P might work, since the only change is a NFC chip added)
Samsung Galaxy Nexus
We are not currently aware of any variations that are not compatible.
Important: Only devices running at least Android 4 (aka Ice Cream Sandwich) are supported. If your device is listed above but running an older version of Android, please update it before doing anything.
 

Requirements for Linux

To build on Linux, you'll need to have a system configured with:

An installed 64 bits GNU/Linux distribution (we recommend Ubuntu 12.04).
At least 4 GB of ram/swap space.
At least 20 GB of available hard disk space.
This is more than the bare minimum, but sometimes building fails just because it's missing resources.

An installed 64 bits GNU/Linux distribution (we recommend Ubuntu 12.04).
At least 4 GB of ram/swap space.
At least 20 GB of available hard disk space.
This is more than the bare minimum, but sometimes a builds fails just because it's missing resources.

It's possible to use other distributions, but we recommend Ubuntu 12.04 since it's the most common system people use successfully. Distributions that might not work: 32 bits distros and recent distros ( Ubuntu 12.10, Fedora 17/18, Arch Linux because of gcc 4.7).

You will also need the following tools installed:

autoconf 2.13
bison
bzip2
ccache
curl
flex
gawk
git
gcc / g++ / g++-multilib (4.6.3 or older)
make
OpenGL headers
X11 headers
32-bit ncurses
32-bit zlib
 

64 bits install examples:

Ubuntu 12.04 / Linux Mint 13 / Debian 6

$ sudo apt-get install autoconf2.13 bison bzip2 ccache curl flex gawk gcc g++ g++-multilib git ia32-libs lib32ncurses5-dev lib32z1-dev libgl1-mesa-dev libx11-dev make
When building on 64-bit Ubuntu, you may find that you need to add symlinks for the 32-bit versions of libX11.so and libGL.so:

$ sudo ln -s /usr/lib/i386-linux-gnu/libX11.so.6 /usr/lib/i386-linux-gnu/libX11.so
$ sudo ln -s /usr/lib/i386-linux-gnu/mesa/libGL.so.1 /usr/lib/i386-linux-gnu/libGL.so
Ubuntu 12.10

$ sudo apt-get install autoconf2.13 bison bzip2 ccache curl flex gawk gcc-4.6 g++-4.6 g++-4.6-multilib git ia32-libs lib32ncurses5-dev lib32z1-dev libgl1-mesa-dev libx11-dev make

Additionally to the steps above needed to fix issues with the 32-bit versions of the libX11.so and libGL.so libraries you will need to specify GCC 4.6 as the default host compiler before building, after having retrieved the sources see here how to do it.

In addition to the steps above needed to fix issues with the 32-bit versions of the libX11.so and libGL.so libraries, you will need to specify GCC 4.6 as the default host compiler before building. After having retrieved the sources see here how to do it.

Fedora 16:

$ sudo yum install autoconf213 bison bzip2 ccache curl flex gawk gcc-c++ git glibc-devel glibc-static libstdc++-static libX11-devel make mesa-libGL-devel ncurses-devel patch zlib-devel ncurses-devel.i686 readline-devel.i686 zlib-devel.i686 libX11-devel.i686 mesa-libGL-devel.i686 glibc-devel.i686 libstdc++.i686 libXrandr.i686
Arch Linux (not functional yet):

$ sudo pacman -S --needed alsa-lib autoconf2.13 bison ccache curl firefox flex gcc-multilib git gperf libnotify libxt libx11 mesa multilib-devel wireless_tools yasm lib32-mesa lib32-ncurses lib32-readline lib32-zlib
By default, Arch Linux uses Python3. You'll have to force it to use the old python2:

$ cd /usr/bin

$ sudo ln -fs python2 python
 

Requirements for Mac OS X

To build Firefox OS on Mac OS X, you need to install Xcode, which is available through the Mac App Store. 

Install Command Line Utilities (XCode 4.3.1 and newer)

Xcode 4.3.1 (OS X 10.7 ""Lion"") and other newer versions such as 4.4.1+ (that is, Mac OS X10.8 ""Mountain Lion""), won't necessarily bring the required Command Line Utilities. When you install XCode, make sure to go into Preferences, then the Downloads panel, and install the Command Line Utilities. In addition, make sure you have at least 20 GB of free disk space.

Note: The Firefox OS emulator requires a Core 2 Duo processor or later; that is, a system that is compatible with Mac OS X 10.7 ""Lion."" You do not actually have to be running Lion, you just have to be compatible with it. You can, however, build any Firefox OS build on many older Macs.
Firefox OS Mac Bootstrap

1
curl -fsSL https://raw.github.com/mozilla-b2g/B2G/master/scripts/bootstrap-mac.sh | bash
Then you need to open a terminal and run this command in the terminal; this will pull and run a bootstrap script that makes sure you have all prerequisites met.

This will check to see if you have all the things you need to be able to build the emulator, and will prompt you for permission to install anything you're missing. The items this script will check for and install for you are:

git
gpg
ccache
yasm
autoconf-213
gcc-4.6
homebrew
Xcode

If you have already upgraded to Xcode 4.4+ and get the message that Xcode is outdated, check the Xcode path with:

xcode-select -print-path
If it still points to /Developer you can update the path with:
sudo xcode-select -switch /Applications/Xcode.app
Next to that be sure that you have the Mac OS X 10.6 SDK available at:
/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/
If it cannot be found there you will need to extract and copy it from the Xcode 4.3 DMG file which is available at the Apple Developer portal. You can use the utility Pacifist to extract the 10.6 SDK. Be sure to add a symlink to it to the /Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/ directory.

Mountain Lion

If you are building on OS X 10.8 ""Mountain Lion"" (Xcode 4.4.1 or later) and encounter the following error:

external/qemu/android/skin/trackball.c:130:25: error: 'M_PI' undeclared (first use in this function)
Edit the file: B2G/external/qemu/Makefile.android and add in line 78:
MY_CFLAGS += -DM_PI=3.14159265358979323846264338327950288   #/* B2G_fix: not finding M_PI constant */
If you are on Mountain Lion and you receive an error during the installation of the dependencies via homebrew, such as:
clang: error: unable to execute command: Segmentation fault: 11
... try reinstalling the dependency manually adding the --use-gcc flag, for example:
brew install mpfr --use-gcc
Samsung Galaxy S2

If you plan to build for the Samsung Galaxy S2, you will also need to install heimdall. See Installing heimdall for details. This is not done for you by the bootstrap script!

If you plan to build for the Samsung Galaxy S2, you will also need to install heimdall. See ""Installing heimdall"" for details. This is not done for you by the bootstrap script!

Note: If you have installed the Samsung Kies tool, which is used to manage the contents of many Samsung phones, you will have to remove it before you can flash Firefox OS onto your device. You can use the standard application removal process on Windows; on Mac, the Kies install disk image has a utility to fully remove Kies from your system. Flashing will not work if you have Kies installed. If you forget to remove Kies, the build system will detect it and remind you to uninstall it. Note also that the uninstall tool does not correctly remove the folder ~/Library/Application Support/.FUS, and leaves a reference to a utility there in your user startup items list. You will want to remove these manually.
Note: Mac OS X uses a case insensitive filesystem by default, which will prevent you from building Firefox OS down the road (EDITOR'S NOTE: I have never had a problem with this).  You should create a case sensitive sparse disk image work from within that directory.  To buld the case sensitive disk image:
hdiutil create -type SPARSE -fs 'Case-sensitive Journaled HFS+' -size 40g ~/firefoxos.dmg
Mount the drive with:

open ~/firefoxos.dmg
Change into the mouted drive with:

cd /Volumes/untitled/
Fix libmpc dependency if broken

gcc 4.6 was built with libmpc 0.9; if you then use homebrew to update packages, libmpc gets updated to version 1.0, but homebrew doesn't rebuild gcc 4.6 after the library version changes. So you need to create a symlink to make things work again, like this:

cd /usr/local/lib/
ln -s libmpc.3.dylib libmpc.2.dylib
Optional: Install HAX

Intel provides a special driver that lets the B2G emulator run its code natively on your Mac instead of being emulated, when you're using the x86 emulator. If you wish to use this, you can download and install it. It's not required, but it can improve emulation performance and stability.

Install adb

The build process needs to pull binary blobs from the Android installation on the phone before building B2G (unless you're building the emulator, of course).  For this, you will need adb, the Android Debug Bridge.

To get this, you'll need to install the Android SDK starter package for your platform. Then run their package manager, $SDK_HOME/tools/android, and use the GUI to install ""Android SDK Platform-tools"".

adb will be installed to $SDK_HOME/platform-tools. Be sure to add this directory to your PATH. This can be done by adding the line

PATH=$SDK_HOME/platform-tools:$PATH
replacing $SDK_HOME with the location of the andoird sdk, to your ~/.bashrc or equivalent.  Also, you may wish to run:

adb pull /system <backup target dir>/system
to back up the entire Android system partition on your phone. This will give you a copy of all the binary blobs for Android in case you later delete your B2G tree. Depending on the phone, you may also need to pull the /data and/or /vendor directories:

adb pull /data <backup target dir>/data
adb pull /vendor <backup target dir>/vendor
Install heimdall

Heimdall is a utility for flashing the Samsung Galaxy S2. It's used by the Boot to Gecko flash utility to replace the contents of the phone with Firefox OS, as well as to flash updated versions of B2G and Gaia onto the device. You'll need it if you want to install Firefox OS on a Galaxy S2; it is not needed for any other device. For other devices, we build and use the fastboot utility instead.

Note: Again, it's important to note that this is only required for installing Firefox OS on the Samsung Galaxy S2.
There are two ways to install heimdall:

You can download the code GitHub and build it yourself.
Use a package manager to install it.
On Linux: sudo apt-get install libusb-1.0-0 libusb-1.0-0-dev
On Mac, you can download an installer package and use that.
Configure ccache

The default cache size for ccache is 1GB; the B2G build easily saturates this. You can configure your cache size as follows:

$ ccache --max-size 3GB
Configure the udev rule for your phone

You can get the USB vendor ID by running lsusb now, but typically it's Google's 18d1 or Samsung's 04e8, so adding this line in your /etc/udev/rules.d/51-android.rules would work:

SUBSYSTEM==""usb"", ATTR{idVendor}==""18d1"", MODE=""0666"", GROUP=""plugdev""
Once you've saved the file, and closed it,  make the file readable:

$ sudo chmod a+r /etc/udev/rules.d/51-android.rules
Configure Phone

Before you plug your phone into your USB port, put it USB developer mode. This lets us access the phone for debugging and flashing. To do this, go to the Settings application and navigate to Applications > Development, and turn on the ""USB debugging"" checkbox.

On to the next step

At this point, you should be ready to fetch the Firefox OS code!",
27QH88MQU6L5O82PS5IX24AJW9HUB7,"Review an open-source article for its English content "," ",2OWBLYHVI44OSZRY4C4NJZSDGUXW21,A4USTI6S8ICM9,Approved,"Mon Dec 17 18:30:30 PST 2012","Mon Dec 17 21:46:03 PST 2012","1. yes
2. yes

Additionally to the steps above needed to fix issues with the 32-bit versions of the libX11.so and libGL.so libraries you will need to specify GCC 4.6 as the default host compiler before building, after having retrieved the sources see here how to do it.

That should say ""In addition to..""

also that the uninstall tool does not correctly remove the folder 

that should say ""if the uninstall tool""

",
27QH88MQU6L5O82PS5IX24AJW9HUB7,"Review an open-source article for its English content "," ",2IQ1THV8ER9Y8QUXSQQSR5KHNXVP20,A14U5M64AK4MAR,Approved,"Mon Dec 17 18:29:44 PST 2012","Mon Dec 17 21:49:04 PST 2012","1. yes
2. yes

 To buld the case sensitive disk image

Should read ""to build""

Before you can even get the code, so you can build Firefox OS. You'll need a properly-configured build system. 

This should be one sentence ""Before you can even get the code so you can build Firefox OS, you'll need a properly-configured build system."" for it to make sense

",

```




