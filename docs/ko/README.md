# chzzk-custom-css

[English (영어)](./README.md) | 한국어

이 저장소에 든 제 사용자 지정 CSS 파일은 치지직 채팅창을 브라우저 소스로 OBS에 추가할 때 활용할 수 있습니다. 단, 기본(캔버스) 해상도가 3840 × 2160 (4K UHD)이어야 됩니다.

이 CSS 파일에 이용된 글꼴은 [빅터 모노(Victor Mono)][vm]와 [노토 산(Noto Sans) CJK KR][noto]입니다.
원하시면 자신이 선호하는 글꼴로 바꿔 주세요.

대부분의 요소를 2.5배 확대했습니다.

## 스크린 숏

![제 전체 화면의 스크린 숏. 오른쪽에 사용자 지정이 된 치지직 채팅창이 있습니다.](./chat_4k_uhd.png)

## 이용법

자신의 치지직 채널 채팅창을 브라우저 소스로 OBS에 추가하세요. 이때 [`chat_4k_uhd.css`](./chat_4k_uhd.css)를 해당 브라우저 소스의 사용자 지정 CSS로 설정하시면 됩니다.

치지직 채널과 그 채팅창의 URL은 각각 다음과 같은 꼴로 돼 있습니다.

* 채널: https://chzzk.naver.com/치지직-채널
* 채팅창: https://chzzk.naver.com/live/치지직-채널/chat

예를 들어, 제 치지직 채널과 그 채팅창의 URL은 각각 다음과 같습니다.

* 채널: https://chzzk.naver.com/7b15632e2d0107c85168e0b421aa6439
* 채팅창:
https://chzzk.naver.com/live/7b15632e2d0107c85168e0b421aa6439/chat

## 문서

[오메가T(OmegaT)][omt]를 이용해 영어 문서를 한국어로 번역했습니다. 오메가T 프로젝트는 [`docs`](./docs) 디렉터리에 있습니다. 오메가T로 마크다운 파일을 구문 분석 하려면 [오메가T를 위한 오카피(Okapi) 필터 플러그인][okapi]을 설치해야 됩니다.

`README.md` 파일이 `docs/en` 디렉터리에 있지 않기 때문에, 저는 거기에 이 파일로의 심벌릭 링크를 만들어 놨습니다. 오메가T로 번역 파일을 만들 때마다, 저는 `README.md`의 한국어 번역본을 복사해 `README.ko.md`라는 이름으로 최상위 디렉터리에 넣고 있습니다.

## 이용 허가증

이 저작물은 [자유 이용 저작물](./LICENSE)입니다.

[vm]: https://rubjo.github.io/victor-mono/
[noto]: https://github.com/notofonts/noto-cjk/tree/main/Sans#downloading-noto-sans-cjk
[omt]: https://omegat.org/
[okapi]: https://okapiframework.org/wiki/index.php/Okapi_Filters_Plugin_for_OmegaT
