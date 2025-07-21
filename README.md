# Vpuppr-fork-try-lol
!!! DO NOT USE THIS SOFTWARE!!!

This a fork a Vpuppr. Im currently trying to do something with it so you should never use this. Either its the same as Vpupper or its broken af.
I juped right into this and have no idea what im doing.

So please af of now use the original [Vpupper](https://github.com/virtual-puppet-project/vpuppr/tree/master)

## Original Vpupper README

VTuber software made with Godot.

Godot 4 rewrite in progress.

The Godot 3 version is currently located on the `godot-3` branch.

## Status

General:

- [x] VRM model loading
- [x] Receive tracking data
- [x] Map tracking data onto a VRM model
- [ ] GUI (half-implemented)
- [ ] Save data

Tracking

- [x] [MediaPipe](https://github.com/google/mediapipe)
- [x] [iFacialMocap](https://www.ifacialmocap.com/)
- [x] [MeowFace](https://play.google.com/store/apps/details?id=com.suvidriel.meowface)
- [x] [VTube Studio](https://denchisoft.com/)
- [ ] [OpenSeeFace](https://github.com/emilianavt/OpenSeeFace)
- [ ] [Mouse tracking](https://github.com/virtual-puppet-project/mouse-tracker)
- [ ] [Lip sync](https://github.com/virtual-puppet-project/real-time-lip-sync-gd)

## Building From Source

Prerequisites:

* Godot 4.1.x
* Rust 1.70+
* Python 3.8+ (any 3.x version is probably fine)

Run `setup.sh` to:

* refresh gitsubmodules
* build `libvpuppr`
* copy `libvpuppr`'s `.gdextension` file into the main project

In order to build GDMP, follow the instructions in [that repo](https://github.com/j20001970/GDMP).

## Contributing

Please see [the document about contributing](CONTRIBUTING.md).

Various technical documents are stored under the `docs` directory.
