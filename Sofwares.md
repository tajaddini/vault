# The Definitive List of Uselful Software

Table of contents:

| Category        |                                       Link |
| --------------- | -----------------------------------------: |
| Programming     |             [here](#programming-languages) |
| IDE             |                               [here](#ide) |
| Tools           |                             [here](#tools) |
| Drawing         |      [here](#drawing-prototyping-diagrams) |
| Multimedia      |                        [here](#multimedia) |
| E-books and PDF |                   [here](#e-books-and-pdf) |
| Customization   | [here](#customizatoin-and-personalization) |
| Messaging       |                         [here](#messaging) |
| System          |                            [here](#system) |

## Programming

### Python :snake:

![python](./.src/python-icon.png)
![linux](./.src/linux-icon.png)
![windows](./.src/windows-icon.png)
![open-source](./.src/opensource-icon.png)

I need not say anything. Lovely, lovely super versatile and capable language. You can do just about anything with this thing, except maybe hardware description.

![XKCD-python](./.src/xkcd-python.png)

Available on:

- [Python.org](https://www.python.org/)

```python
import opencv
def a(x):
    return x**2
print(a+b)
```

### Conda (Anaconda/Miniconda)

![python](./.src/python-icon.png)
![linux](./.src/linux-icon.png)
![windows](./.src/windows-icon.png)
![open-source](./.src/opensource-icon.png)

Chances are, you're using python more and more and you'll soon come across having a ton of libraries installed on your system which might also have conflicting version requirements or have become obsolete since the last time you had them. Conda offers a robust environment and package management platform as well as a plethora of the most used packages with very installation and update methods. This is a especially a must-have if you're gonna do data science or AI work or want to give [TensorFlow](https://en.wikipedia.org/wiki/TensorFlow) a try.

Available on:

- [Anaconda.com](https://www.anaconda.com/products/individual)

### Github Desktop

![windows](./.src/windows-icon.png)
![open-source](./.src/opensource-icon.png)

Cause I'm lazy and don't wanna mess with git commands on my terminal when I can just push buttons in a fancy GUI.

Available on:

- [GitHub](https://desktop.github.com/)

### Java

![linux](./.src/linux-icon.png)
![windows](./.src/windows-icon.png)
![open-source](./.src/opensource-icon.png)

You'll probably need this at one point or another. You'll have to have JRE on your system if you'd want to run JAR files like [UMLET](#umlet).

[JRE](https://en.wikipedia.org/wiki/Java_virtual_machine) Available on:

- [Oracle](https://www.oracle.com/ca-en/java/technologies/javase-jre8-downloads.html)
- [Java](https://www.java.com/en/download/)
- [Open JDK](https://openjdk.java.net/install/)

[JDK](https://en.wikipedia.org/wiki/Java_Development_Kit) Available on:

- [Oracle](https://www.oracle.com/ca-en/java/technologies/javase-downloads.html)
- [Open JDK](https://openjdk.java.net/)

## IDE

### Visual Studio Code

![linux](./.src/linux-icon.png)
![windows](./.src/windows-icon.png)
![open-source](./.src/opensource-icon.png)

Lightweight and very feature-rich IDE and text editor with tons of extensions and add-ons. Has built-in support for Git as well.

Available on:

- [Visual Studio website](https://code.visualstudio.com/download) (Windows binaries, linux binaries)
- [GitHub](https://github.com/microsoft/vscode) (All the latest builds and releases)
- [Snap](https://snapcraft.io/code) (Linux)

Recommended extensions:

- [Anaconda](https://marketplace.visualstudio.com/items?itemName=ms-python.anaconda-extension-pack)
- [Bracket Colorizer](https://marketplace.visualstudio.com/items?itemName=coenraads.bracket-pair-colorizer-2)
- [Excel Viewer](https://marketplace.visualstudio.com/items?itemName=grapecity.gc-excelviewer)
- [GitHub Markdown Preview](https://marketplace.visualstudio.com/items?itemName=bierner.github-markdown-preview)
- [Jupyter](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter)
- [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)

### Bloodshed's Dev C++

![windows](./.src/windows-icon.png)
![gnu](./.src/gnu-icon.png)

The easist and most straight-forward way to write and run small C/C++ codes on your windows machine. Linux comes with its own GCC C/C++ compilers, but running a `hello world!` program in C is a huge pain on windows. As long as you don't mind its outdated user interface, this has always been more than enough for all my needs. (so far)

Available on:

- [Bloodshed's website](https://www.bloodshed.net/)
- [Source Forge](https://sourceforge.net/projects/orwelldevcpp/)

## Tools

### 7-Zip

![windows](./.src/windows-icon.png)
![open-source](./.src/opensource-icon.png)

Hands-down, the best files archiving tool for windows.

Available on:

- [7-Zip's website](https://www.7-zip.org/download.html)
- [Source Forge](https://sourceforge.net/projects/sevenzip/)
- [Foss Hub](https://www.fosshub.com/7-Zip.html)

### OpenVPN

![android](./.src/android-icon.png)
![linux](./.src/linux-icon.png)
![windows](./.src/windows-icon.png)
![open-source](./.src/opensource-icon.png)

I have to. I love my freedom and want to keep it.

Available on:

- [OpenVPN's website](https://openvpn.net/download-open-vpn/)

### FDM (Free Download Manager)

![linux](./.src/linux-icon.png)
![windows](./.src/windows-icon.png)
![open-source](./.src/opensource-icon.png)

My download manager of choice.

Available on:

- [FDM's website](https://www.freedownloadmanager.org/)

### Microsoft Power Toys

![windows](./.src/windows-icon.png)
![open-source](./.src/opensource-icon.png)

A very nice suite of various utilities and QoL improvements for power users, such as bulk image resizing, markdown previews in windows explorer, and power rename using regex.

Available on:

- [GitHub](https://github.com/microsoft/PowerToys)

### Windows Terminal

![windows](./.src/windows-icon.png)
![open-source](./.src/opensource-icon.png)

Beautiful and feature-rich terminal emulator for windows machines. A step in the right direction for Microsoft. Can be themed and customized to your heart's content.

Available on:

- [GitHub](https://github.com/microsoft/terminal)

Recommended:

- [Powerline](https://docs.microsoft.com/en-us/windows/terminal/tutorials/powerline-setup)
- [My own dotfiles](github)

### Barrier

![linux](./.src/linux-icon.png)
![windows](./.src/windows-icon.png)
![open-source](./.src/opensource-icon.png)

An open source port of synergy, it mimicks a KVM switch. It basically let's you set up a grid of up to 9 different computers (not monitors!) and use and control all of them over the local network using one mouse and kyboard on your main machine.

Available on:

- [GitHub](https://github.com/debauchee/barrier)
- [Source Forge](https://sourceforge.net/projects/barrier.mirror/)

### NoMachine

![linux](./.src/linux-icon.png)
![windows](./.src/windows-icon.png)

Remote desktop control using NX. Very handy for troubleshooting computers in an office environment or accessing and managing your computers in home.

Available on:

- [NoMachine's website](https://www.nomachine.com/)

### Bulk Crap Uninstaller (BCU)

![windows](./.src/windows-icon.png)
![open-source](./.src/opensource-icon.png)

Allows you to remove unwanted programs completely. Has the ability to remove pre-loaded applications and disable protection for _system_ apps as well. You can also trace and remove any left-overs. Also has the ability to do this in batch mode, even in parallel. Has a handy portable version as well.

Available on:

- [BCU's website](https://www.bcuninstaller.com/)
- [GitHub](https://github.com/Klocman/Bulk-Crap-Uninstaller)
- [Source Forge](https://sourceforge.net/projects/bulk-crap-uninstaller/)
- [Foss Hub](https://www.fosshub.com/Bulk-Crap-Uninstaller.html)

### WinDirStat

![windows](./.src/windows-icon.png)
![open-source](./.src/opensource-icon.png)

Disk usage analysis in tree-view mode. Also a nice work-around for hidden folder viruses.

Available on:

- [WinDirStat's website](https://windirstat.net/) (_might be down_)
- [Source Forge](https://sourceforge.net/projects/windirstat/)
- [Foss Hub](https://www.fosshub.com/WinDirStat.html)

### TrID

![windows](./.src/windows-icon.png)
![open-source](./.src/opensource-icon.png)

TrID is an utility designed to identify file types from their binary signatures. You'll need to download the executable as well as the latest file signature database. Just download it and extract it in the same place as the executable.

Available on:

- [Mark0's website](https://mark0.net/soft-trid-e.html)

## Drawing, prototyping, diagrams

### UMLET

![linux](./.src/linux-icon.png)
![windows](./.src/windows-icon.png)
![open-source](./.src/opensource-icon.png)

Written in Java, it is an extremely lightweight yet feature-rich app for all your UML diagram design needs. Can also be adapted to make more complex diagrams and graphics. Has very easy custom shape creation capabilities.

Available on:

- [Umlet's website](https://www.umlet.com/)
- [GitHub](https://github.com/umlet/umlet)

### Draw.IO

![linux](./.src/linux-icon.png)
![windows](./.src/windows-icon.png)
![open-source](./.src/opensource-icon.png)

Make beautiful diagrams to your heart's content.

Available on:

- [Draw.IO](https://www.draw.io/) (Online version)
- [GitHub](https://github.com/jgraph/drawio-desktop)
- [Source Forge]()
- [Foss Hub]()

### Pencil

![linux](./.src/linux-icon.png)
![windows](./.src/windows-icon.png)
![open-source](./.src/opensource-icon.png)

A GUI prototyping tool that does not suck.

Available on:

- [Pencil's website](https://pencil.evolus.vn/)
- [GitHub](https://github.com/evolus/pencil)

## Multimedia

### MPV

![linux](./.src/linux-icon.png)
![windows](./.src/windows-icon.png)
![open-source](./.src/opensource-icon.png)

Lightweight super-fast video and audio player which supports a wide range of file formats, codecs and subtitles. Not as feature-rich as VLC, but then again you really don't need all that on a daily basis.

Available on:

- [MPV's website](https://mpv.io/)
- [GitHub](https://github.com/mpv-player/mpv) (source code)
- [Source Forge](https://sourceforge.net/projects/mpv-player-windows/)

### VLC

![android](./.src/android-icon.png)
![linux](./.src/linux-icon.png)
![windows](./.src/windows-icon.png)
![open-source](./.src/opensource-icon.png)

Probablly the most well-known and fully-featured media player out there. Has network streaming and capture capabilities, makes it a very nice experience for movie streaming. Also has tons of support for various extensions and codecs. Sucks that it's really ugly with an outdated design. Themes are hit-and-miss, because while certainly much better looking than its own skin, they leave tons of features behind.

Available on:

- [Video Lan's website](https://www.videolan.org/vlc/index.html)
- [GitHub](https://github.com/videolan/vlc)
- [Foss Hub](https://www.fosshub.com/VLC-Media-Player.html)
- [Play Store](https://play.google.com/store/apps/details?id=org.videolan.vlc) (Android)
- [F-Droid](https://f-droid.org/en/packages/org.videolan.vlc/) (Android)

### Audacity

![linux](./.src/linux-icon.png)
![windows](./.src/windows-icon.png)
![open-source](./.src/opensource-icon.png)

A nice digital audio editor, recorder, and mixer. Used it a lot for my _Multi Media Systems_ course in university.

Available on:

- [Audacity's website](https://www.audacityteam.org/)
- [GitHub](https://github.com/audacity/audacity)
- [Source Forge](https://sourceforge.net/projects/audacity/)
- [Foss Hub](https://www.fosshub.com/Audacity.html)

### MP3Tag

![windows](./.src/windows-icon.png)

Free metadata editor for audio files written in Java.

Available on:

- [mp3tag's website](https://www.mp3tag.de/en/download.html)

### MediaHuman Lyrics Finder

![windows](./.src/windows-icon.png)

Automatically finds and adds lyrics to your audio files based on thier ID3 tags.

Available on:

- [MediaHuman's website](https://www.mediahuman.com/lyrics-finder/)

### Handbrake

![linux](./.src/linux-icon.png)
![windows](./.src/windows-icon.png)
![open-source](./.src/opensource-icon.png)

A neat video transcoder. Super useful for reducing the size of videos or converting them to codecs playable on TVs.

Available on:

- [Handbrake's website](https://handbrake.fr/)
- [GitHub](https://github.com/HandBrake/HandBrake)

### MP4Tools

![linux](./.src/linux-icon.png)
![windows](./.src/windows-icon.png)
![open-source](./.src/opensource-icon.png)

Join and split MP4 videos.

Available on:

- [mp4joiner's website](https://www.mp4joiner.org/en/)
- [Source Forge](https://sourceforge.net/projects/mp4joiner/)

## E-Books and PDF

### Calibre

![linux](./.src/linux-icon.png)
![windows](./.src/windows-icon.png)
![open-source](./.src/opensource-icon.png)

The go-to place for all your e-book needs. Has built-in editors, viewers and a neat library manager. Can migrate old libraries simply by copying them on the new location. Can fetch the covers and info of books. Also has a handy format convertor. Last but not least, it comes with Amazon Kindle support and can push your books onto the Kindle.

Available on:

- [Calibre's website](https://calibre-ebook.com/)
- [GitHub](https://github.com/kovidgoyal/calibre)
- [Foss Hub](https://www.fosshub.com/Calibre.html)

### Sumatra PDF

![windows](./.src/windows-icon.png)
![open-source](./.src/opensource-icon.png)

Extremely light-weight and fast PDF reader. Does not offer much beyond remembering where you left off and smooth scrolling and good full-screen support. Much better than using browsers.

Available on:

- [Sumatra PDF's website](https://www.sumatrapdfreader.org/free-pdf-reader.html)
- [GitHub](https://github.com/sumatrapdfreader/sumatrapdf)
- [Chocolatey](https://chocolatey.org/packages/sumatrapdf)
- [Foss Hub](https://www.fosshub.com/Sumatra-PDF.html)

### Okular

![linux](./.src/linux-icon.png)
![windows](./.src/windows-icon.png)
![open-source](./.src/opensource-icon.png)

A part of KDE's software suite, Okular is more than just a document viewer. While [Sumatra](#sumatra-pdf) is a nice daily driver, okular can annotate documents. It is definitely heavier than Sumatra though. (~110mb vs 10mb)

Available on:

- [Okular's website](https://okular.kde.org/download.php)
- [GitHub](https://github.com/KDE/okular)
- [Microsoft Store](https://www.microsoft.com/store/apps/9N41MSQ1WNM8) (Windows only)

### PDFedit

![linux](./.src/linux-icon.png)
![windows](./.src/windows-icon.png)
![open-source](./.src/opensource-icon.png)

A complete PDF viewer and editor tool. Can add/remove/extract text and images from the files and can work with annotations. Lightweight and dependable. While it's very powerful for its use, the GUI is far from nice and needs improvements. I use it as a last resource for editing/annotations.

Available on:

- [PDFedit's website](http://pdfedit.cz/en/download.html)
- [Source Forge](http://sourceforge.net/projects/pdfedit)

### PDFsam Basic

![windows](./.src/windows-icon.png)
![open-source](./.src/opensource-icon.png)

Allows you to merge, split, rotate, mix and extract pages from PDF files. It's a bit pushy with its paid version, and also wants to push other software into your system. But if you contain it, it gets the job done.

Available on:

- [PDFsam's website](https://pdfsam.org/download-pdfsam-basic/)
- [FossHub](https://www.fosshub.com/PDFsam.html)

### jpeg2pdf

![windows](./.src/windows-icon.png)
![open-source](./.src/opensource-icon.png)

A commandline tool for converting and combining JPG image files into PDF files.

Available on:

- [Source Forge](https://sourceforge.net/projects/jpeg2pdf/)

## Customizatoin and personalization

### Lively Wallpaper

![windows](./.src/windows-icon.png)
![open-source](./.src/opensource-icon.png)

A low-impact tool for having videos or parallax scenes as your desktop wallpaper.

- [Lively Wallpaper's website](https://rocksdanister.github.io/lively/)
- [GitHub](https://github.com/rocksdanister/lively)
- [Microsoft Store](https://www.microsoft.com/en-us/p/lively-wallpaper) (This version has less features and is less frequently updated)

### TaskbarX

![windows](./.src/windows-icon.png)
![open-source](./.src/opensource-icon.png)

TaskbarX gives you control over the position of your taskbar icons. It's like a dock. It's also very easy on the CPU.

Available on:

- [GitHub](https://github.com/ChrisAnd1998/TaskbarX)

## Messaging

### Telegram

![android](./.src/android-icon.png)
![linux](./.src/linux-icon.png)
![windows](./.src/windows-icon.png)
![open-source](./.src/opensource-icon.png)

Fast, very feature-rich and mostly secure messagin platform.

Available on:

- [Telegram's website](https://desktop.telegram.org/)
- [Play Store](https://play.google.com/store/apps/details?id=org.telegram.messenger) (Android)

## System

### Open Razer

![linux](./.src/linux-icon.png)
![open-source](./.src/opensource-icon.png)

Daemons and drivers for controlling Razer products' RGB effects and calibration and configuration. Written in python, this is the most reliable solution I've found so far.

Available on:

- [GitHub](https://openrazer.github.io/)

---

### template

![android](./.src/android-icon.png)
![linux](./.src/linux-icon.png)
![windows](./.src/windows-icon.png)
![open-source](./.src/opensource-icon.png)

description goes here.

Available on:

- ['s website]()
- [GitHub]()
- [Source Forge]()
- [Foss Hub]()
