# WARNING - I no longer maintain this!
I have merged all useful patches from this into Wineskin from VitorMM > [Upstream](https://github.com/vitor251093/wineskin)
It would be best to use that instead of this, I only uploaded this incase anyone wanted to see the changes I had made.
If you want to submit a patch make sure it's against [Upstream](https://github.com/vitor251093/wineskin) and not this Repo since it's vastly outdated.
Also do not pull-request to my [fork](https://github.com/Gcenx/wineskin) as I already have all patches from that also merged into [Upstream](https://github.com/vitor251093/wineskin)


# Wineskin
Wineskin is a tool used to make ports of Windows software to Mac OS X. 

## About
Ports are in the form of normal Mac application bundle wrappers.  It works like a wrapper around the Windows software, and you can share just the wrappers if you choose. Make ports/wrappers to share with others, make ports of your own open source, free, or commercial software, or just make a port for yourself!  Why install Windows if you don’t need to?

Source: http://wineskin.urgesoftware.com/

## Modifications
As you may have already noticed, this is not the [original Wineskin repository](https://sourceforge.net/p/wineskin/code/ci/master/tree/). This repository includes the "Auto-detect GPU" merge-request from Markus Stoll [Fork Wineskin repository](https://sourceforge.net/u/must21de/wineskin/ci/master/tree/). Also includes additional fixes to make Wineskin work with Wine64 and Wine-Staging/64 correctly when using the required dylibs without breaking Wine or WineskinX11 functionality.

## List of modifications
- The *Auto-detect GPU* fix was taken from an unapplied upstream merge request.
- Unique names for wine-preloader wine64/-preloader processes now like wine.
- *Kill Wineskin Processes* only kills processesfrom current running Wrapper.
-*Screen Options* Changed heading *Override Setting* to *Overrider Settings Requires X11* to avoid confusion
- The first *Advanced* tab (*Tools*) should be much more simple:
    - *Command Line Shell*, renamed to *Command Line (CMD)* to make more sense from a Windows standpoint and moved under *Wine Tools* heading as is not a part of WineSkin's *Utilities* but part of Wine.
    -Moved *Command Line Wine Test* under *Utilities* this is useful to verifiy wine works on your local system and uses the default .wine prefix in the users HOME folder
    -Re-ordered some buttons to make more sense


## License
Keeping the same as the original material, LGPL 2.1 is the license of that project. You can find more details about that in the LICENSE file.

## Credits
Special credits for this version go to doh123, for creating the original Wineskin.
