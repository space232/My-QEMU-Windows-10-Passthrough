# My QEMU Windows 10 Passthrough
| This guide details my configuration and setup for GPU passthrough (Using KVM/QEMU)

First things first, I am currently utilising a NVIDIA GeForce GTX 1060 (6GB).
Now, I would upgrade my GPU before doing this, but with the scalper market at the moment, that will not be happening anytime soon.

I would also just like to say that this page's main aim is to get Nested Virtualisation/Hyper-V enabled.

NVIDIA is a ~~awesome~~ terrible  company. You will not be able to use passthrough until... well:
- You ensure your GPU ROM is patched. (some cards may not require this)
- You ensure your GPU is isolated by vfio-pci.
- You ensure that your mental wellbeing is stable enough to follow through several guides just to get it working.

This write up should help you through all of these steps.
Massive credits to snowrii and SomeOrdinaryGamers for making life a little easier.

## Dependencies

!! Linux (I am using Debian for this project) !!
[Debian](https://www.debian.org/)

!! NVIDIA-ROM-DUMP (2) !!
[Download GPU-Z](https://www.techpowerup.com/gpuz/) OR [Locate your ROM](https://www.techpowerup.com/vgabios/)

!! NVIDIA 'Hex Editor' (You can use others, this is the one I used for this project.) !!
[HxD Hex Editor](https://mh-nexus.de/en/hxd/)

## How to Get Started

soon(tm)

## I need support/help! Please?

I do not offer support, I think this should be pretty obvious as to why.
HOWEVER, if you are having issues and you believe my code is responsible:

> Submit a Issue/Pull Request <3
  - [I'd like to submit a issue.](https://github.com/owospace/My-QEMU-Windows-10-Passthrough/issues/new)
  - [I'd like to submit a Pull Request.](https://github.com/owospace/My-QEMU-Windows-10-Passthrough/pulls)
> Discord
  - My Discord is 'space#0002' without the quotes.
> Email
  - My Email Address is 'me@spce.moe' without the quotes.

### Made with <3 by Space.
