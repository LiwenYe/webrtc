# Intel® Collaboration Suite for WebRTC Android SDK

## How to build release package
1. Copy this folder to a clean place.
2. Run `git init` in src, which makes src folder under git control.
3. Run `export GYP_DEFINES="OS=android target_arch=arm"`
4. Run `gclient runhooks`. It will take a long time since it will download large amount of data.
5. Run `ninja -C <folder> libjingle_peerconnection_java`

## References
- [WebRTC development](https://webrtc.org/native-code/development/). (This release uses GYP build. GN is not enabled.)
