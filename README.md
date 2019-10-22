# BrickCtl

Playing around with the LEGO® Control+ system.

## What is it?

This is my personal playground for tinkering with the recently introduced LEGO® Control+ system. I recently obtained the
Liebherr excavator set (42100), which features two Bluetooth-controlled SmartHubs and seven motors. Having this hardware
available provides me with the opportunity to learn how to work with Bluetooth in general, as well as to give me a fun
challenge implementing LEGO®'s low-level protocol (which is partially [documented][1], but still should provide plenty of
opportunity to reverse-engineer). If this turns out to be really fun, I may even look into how to support a gamepad and
provide some form of hardware remote for the Liebherr excavator - something that many people are asking for.

## What is it not?

I don't expect this to ever become a finished program, or useful to anyone besides myself. I don't intend to put any
effort into cross-platform support or end-user documentation. I plan to use this project also to explore new
technologies, in particular the upcoming C++20 standard. I develop on a bleeding-edge Gentoo system, and I intend
to make use of very new versions of the toolchain and support libraries, with no respect for backwards compatibility.

Last but not least, I don't expect any outside contributions in the foreseeable future. If this project ever turns out
to be of general interest, and reaches a state of maturity where I would consider opening up and targeting other people,
this might change. Until then, feel free to peruse the code, but don't expect me to make any promises.

## Frequently never-asked questions

* *Q: There are already a bunch of libraries for talking to a variety of LEGOⓇ hardware. Why are you reinventing the wheel?*

  I am aware of several other projects. However, since I want this to be a challenge, I didn't look at them in
  any detail. This project is not about providing a fully-featured tool for others; this is about me playing
  around myself.

* *Q: Do you plan to support any other model than the Liebherr excavator (42100)?*

  The Liebherr currently is the only Control+ set I own. I don't have any plans to support other models. However, I intend
  to design the software in a way that the protocol and device support is decoupled from model-specific code, so it
  should be extensible if need be.

## Disclaimer

LEGO® is a trademark of the LEGO Group of companies which does not sponsor, authorize or endorse this site. The LEGO®
trademark is used in a non-commercial manner following the LEGO Group's [Fair Play Policy][2].

[1]: https://github.com/LEGO/lego-ble-wireless-protocol-docs
[2]: https://www.lego.com/en-us/legal/notices-and-policies/fair-play/
