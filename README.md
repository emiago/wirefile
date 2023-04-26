
<font size="10">Wirefile</font><img src="./wirefile.png"  width="100" height="100">



Cross-platform P2P file/folder transfer.


⚙ **NEEDS MORE WORK, FOR NOW ONLY DEMO!!** ⚙

**NOTE:** *THIS REPO IS USED FOR TRACKING RELEASES*

# About
If you want just to be able to **simply** send **directly** files/folders between devices and avoid any uploading to cloud services just to download, this tool is all about that.

In core, it uses `webrtc` tech to establish **e2e encrypted** connection and transfer data **directly** between your devices.

**Wirefile clients** connect to server only for ***signaling, authentication and some metadata exchange***.

## Features:
- same cross-platform GUI design (mobile as well).
- p2p file transfer
- e2e encryption powered by `webrtc`
- Multifolder sharing and auto file tree updates on file changes.

# Installing latest packages

## Linux (manual)

- Download [wirefile.tar.xz](https://github.com/emiago/wirefile/releases/latest/download/wirefile.tar.xz)
```
tar xf wirefile.tar.xz; 
make user-install
```

## Android (manual)

- Download [wirefile.apk](https://github.com/emiago/wirefile/releases/latest/download/wirefile.apk)
- Allow file media permissions
- Down



# Clients
Metadata is **never** about content of files, but sharing like file tree names makes clients faster exploring.

Wirefile is totally developed in `Go` language.


Same GUI design on all platforms: 

<img src="./gui1.png"  width="350" height="400">





