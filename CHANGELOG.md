# Changelog

## [5.0.0](https://github.com/tomaszzmuda/Xabe.FFmpeg/pull/339) - Unreleased
- A lot of code improvements and simplifications
- Automated tests are using docker now to set up RTSP server
- Change GetScreenCapture to AddDesktopStream
- Added more tests related to RTSP
- Remove obsolete methods
- Add SetInputFormat ("-f"), SetStreamLoop ("-stream_loop"), and UseNativeInputRead ("-re" flag) to IAudioStream
- Add SetInputFormat ("-f"), SetStreamLoop ("-stream_loop"), and UseNativeInputRead ("-re" flag) to IVideoStream
- Add SetStreamLoop ("-stream_loop"), and UseNativeInputRead ("-re" flag) to ISubtitleStream
- UseMultiThread(true) is using max 16 threads due to compatibility reasons
- Fix bug with RTSP streams when FFmpeg stucks

## 4.4.1 - 2021-05-11

- [Upgrade test project .NET Core version to 3.1](https://github.com/tomaszzmuda/Xabe.FFmpeg/pull/353)
- Handle special characters in paths [PullRequest#350](https://github.com/tomaszzmuda/Xabe.FFmpeg/pull/350) [PullRequest#351](https://github.com/tomaszzmuda/Xabe.FFmpeg/pull/351)
- [Create directory for output file if it not exists](https://github.com/tomaszzmuda/Xabe.FFmpeg/pull/351/files)
- [Extend GetScreenCapture by offset and size](https://github.com/tomaszzmuda/Xabe.FFmpeg/pull/325)
- [Tests clean up their temp files from now](https://github.com/tomaszzmuda/Xabe.FFmpeg/pull/326)
- [License moved to official Xabe.FFmpeg site](https://github.com/tomaszzmuda/Xabe.FFmpeg/pull/342/files)
- [Change few missleading comments](https://github.com/tomaszzmuda/Xabe.FFmpeg/pull/348/files)
- [Added a few more tests](https://github.com/tomaszzmuda/Xabe.FFmpeg/pull/349/files)

## 4.4.0 - 2020-12-09