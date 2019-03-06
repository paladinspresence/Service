# Paladins Presence
Rich Presence is a wonderful way to let people know what you're up to in-game. Paladins, however, doesn't really implement this in the best way. It *could* be a lot better.

### What We Currently Have
<p align="center">
  <img src="https://i.imgur.com/zETz4ol.png"> <img src="https://i.imgur.com/MmCgCUx.png">
</p>

### What Paladins Presence Does
*This is what we believe it should look like*
<p align="center">
  <img src="https://i.imgur.com/Qr2ov5B.png"> <img src="https://i.imgur.com/3NyBPCS.png"> <img src="https://i.imgur.com/snRh3nY.png"> <img src="https://i.imgur.com/tjGbw4u.png">
</p>

## Service Info
Paladins Presence is written as a Windows Service. It runs on boot, and it runs in the background. It takes less than 10mb of memory to run and is easy to install and uninstall, even without the bundled installer. You install the service and forget about it, Paladins Presence will monitor the process list for Paladins, code [here](https://github.com/paladinspresence/Service/blob/master/Presence.cs#L138), and when it's running it will start checking the configured player id against our API to get the status.

It's easy to use, and easy to forget about. Let's make Paladins Rich Presence better than ever, together.
