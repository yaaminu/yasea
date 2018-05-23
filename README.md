Yet Another Stream Encoder for Android
======================================

[![Android Arsenal](https://img.shields.io/badge/Android%20Arsenal-yasea-green.svg?style=true)](https://android-arsenal.com/details/1/3481)

**Yasea** is an Android streaming client. It encodes YUV and PCM data from
camera and microphone to H.264/AAC, encapsulates in FLV and transmits over RTMP.

Branch
------

[non-gpuimage](https://github.com/begeekmyfriend/yasea/tree/non-gpuimage) for demo without GPUImage module.

[android-16](https://github.com/begeekmyfriend/yasea/tree/android-16) for Android API 16+.

[aac-hev2](https://github.com/begeekmyfriend/yasea/tree/aac-hev2) for Youtube live broadcast that is not compatible with conventional flash media players.

Feature
-------

- [x] Android mini API 21.
- [x] H.264/AAC hard encoding.
- [x] H.264 soft encoding.
- [x] RTMP streaming with state callback handler.
- [x] Portrait and landscape dynamic orientation.
- [x] Front and back cameras hot switch.
- [x] Recording to MP4 while streaming.
- [x] Beautiful filters with GPUImage.
- [x] Acoustic echo cancellation and automatic gain control support.

Test
----

You may build your own private RTMP server [srs](https://github.com/ossrs/srs/tree/2.0release).
Remember to modify the URL by yourself. Have fun!

**NOTE** if you feel high latency, please check your bandwidth limits and player buffering.

Acknowledgements
----------------


- [srs-sea](https://github.com/ossrs/srs-sea)
- [SimpleRtmp](https://github.com/faucamp/SimpleRtmp)
- [MagicCamera](https://github.com/wuhaoyu1990/MagicCamera)
- [x264](http://www.videolan.org/developers/x264.html)
- [mp4parser](https://android.googlesource.com/platform/external/mp4parser)

