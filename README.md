# YoutubeDL

This iOS app uses yt-dlp python module to download videos from YouTube.

- Screen shots

![Screen shot 1](/Images/Screen%20Shot%201.png)
![Screen shot 2](/Images/Screen%20Shot%202.png)
![Screen shot 3](/Images/Screen%20Shot%203.png)
![Screen shot 4](/Images/Screen%20Shot%204.png)

- Video

[![Watch the video](https://img.youtube.com/vi/WdFj7fUnmC0/hqdefault.jpg)](https://youtu.be/WdFj7fUnmC0)

## Warning

This app is NOT AppStore-safe.  Historically AppStore has been removing apps downloading videos from YouTube.  This app will likely be rejected by AppStore.

## Features

- Automatically downloads yt-dlp python module from https://github.com/yt-dlp/yt-dlp/releases/latest
- Download media using URLSession
- Support background download
- Support chunk based download
- Transcode using embedded FFmpeg libraries

## Usage

Run this app in a simulator.

To run on a device:
- Change code sign identity
- Change bundle ID

## Swift Packages

- https://github.com/kewlbear/Python-iOS
- https://github.com/kewlbear/FFmpeg-iOS
- https://github.com/kewlbear/YoutubeDL-iOS

## TODO

- Improve UI/UX
- Improve modularization
- Documentation

## License

MIT

<!-- fastnas2023-support:start -->
## 支持 fastnas2023 / Support

如果你愿意支持 **fastnas2023**，可以通过微信或支付宝自愿打赏。感谢支持！

If you would like to support **fastnas2023**, you can optionally donate via WeChat Pay or Alipay. Thank you!

<p align="center">
  <img src="https://raw.githubusercontent.com/fastnas2023/fastnas2023/9dbfee7325a5e86d89a28c8d1bf95497005f40c7/assets/donate.png" alt="fastnas2023 微信和支付宝打赏码 / WeChat Pay and Alipay donation QR codes" width="700" />
</p>

[GitHub · fastnas2023](https://github.com/fastnas2023)
<!-- fastnas2023-support:end -->
