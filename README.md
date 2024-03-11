# chzzk-custom-css

English | [한국어[Korean]](./README-ko.md)

This is the repository for my custom CSS file for a Chzzk chat window
added as a browser source to OBS where the base (canvas) resolution is
3840 × 2160 (4K UHD).

The file uses two fonts: [Victor Mono][vm] and [Noto Sans CJK KR][noto].
Feel free to replace them with the fonts you prefer.

I added a black background with an opacity of 0.9 to each item in the
chat list; the background has rounded corners with a radius of 24
pixels.

I enlarged all elements in the chat, subscription, and donation messages
by a scale factor of 4.

## Screenshot

![A screenshot of my entire screen with a customized Chzzk chat window
on the right](./chat_4k_uhd.png)

## Usage

Add a browser source to OBS whose URL is that of your Chzzk channel's
chat window and custom CSS is [`chat_4k_uhd.css`](./chat_4k_uhd.css).

The URLs of your Chzzk channel and its chat window should have the
following forms, respectively:

* Channel: https://chzzk.naver.com/your-chzzk-channel
* Chat: https://chzzk.naver.com/live/your-chzzk-channel/chat

For example, the URLs of my Chzzk channel and its chat window are as
follows:

* Channel: https://chzzk.naver.com/7b15632e2d0107c85168e0b421aa6439
* Chat:
  https://chzzk.naver.com/live/7b15632e2d0107c85168e0b421aa6439/chat

## Documentation

I use [OmegaT][omt] to translate English documentation into Korean. The OmegaT
project is in the [`docs`](./docs) directory. You need to install the [Okapi
filters plugin for OmegaT][okapi] to make OmegaT parse Markdown files.

## License

This work is in the [public domain](./LICENSE).

[vm]: https://rubjo.github.io/victor-mono/
[noto]: https://github.com/notofonts/noto-cjk/tree/main/Sans#downloading-noto-sans-cjk
[omt]: https://omegat.org/
[okapi]: https://okapiframework.org/wiki/index.php/Okapi_Filters_Plugin_for_OmegaT
