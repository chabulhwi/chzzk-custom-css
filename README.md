# chzzk-custom-css

English | [한국어[Korean]](./README.ko.md)

This is the repository for my custom CSS file for a Chzzk chat window
added as a browser source to OBS where the base (canvas) resolution is
3840 × 2160 (4K UHD).

The file uses two fonts: [Victor Mono][vm] and [Noto Sans CJK KR][noto].
Feel free to replace them with the fonts you prefer.

I enlarged most elements by the scale factor of 2.5.

## Screenshot

![A screenshot of my entire screen with a customized Chzzk chat window
on the right](./chat_4k_uhd.png)

## Usage

Add a browser source to OBS whose URL is that of your Chzzk channel's
chat window and custom CSS is [`chat_4k_uhd.css`](./chat_4k_uhd.css).

You can find the URL of your Chzzk chat window in the following link:

* Notification settings: <https://studio.chzzk.naver.com/your-chzzk-channel/notification>

For example, the URL of my Chzzk channel is as follows:

* My Chzzk channel: <https://chzzk.naver.com/7b15632e2d0107c85168e0b421aa6439>

Therefore, I can find the URL of my Chzzk chat window in the following link:

* My notification settings:
  <https://studio.chzzk.naver.com/7b15632e2d0107c85168e0b421aa6439/notification>

## Documentation

I use [OmegaT][omt] to translate English documentation into Korean. The
OmegaT project is in the [`docs`](./docs) directory. You need to install
the [Okapi filters plugin for OmegaT][okapi] to make OmegaT parse
Markdown files.

Since the `README.md` file isn't in the `docs/en` directory, I had to
create a symbolic link to it there. Whenever I use OmegaT to create the
translated file, I copy the Korean translation of `README.md` to the
root directory and rename it `README.ko.md`.

## License

This work is in the [public domain](./LICENSE).

[vm]: https://rubjo.github.io/victor-mono/
[noto]: https://github.com/notofonts/noto-cjk/tree/main/Sans#downloading-noto-sans-cjk
[omt]: https://omegat.org/
[okapi]: https://okapiframework.org/wiki/index.php/Okapi_Filters_Plugin_for_OmegaT
