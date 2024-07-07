# 엘리스 디지털 배움체

[배포처 바로가기](https://elice.io/ko/elice/brand#elice_digital_baeum)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `Elice Digital Baeum`입니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/EliceDigitalBaeum/EliceDigitalBaeum.css" type="text/css"/>
```

### CSS `@Import`

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/EliceDigitalBaeum/EliceDigitalBaeum.css');
```

### CSS `@font-face`

```css
@font-face {
    font-family: 'Elice Digital Baeum';
    font-weight: 400;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/EliceDigitalBaeum/EliceDigitalBaeum-Regular.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/EliceDigitalBaeum/EliceDigitalBaeum-Regular.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/EliceDigitalBaeum/EliceDigitalBaeum-Regular.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/EliceDigitalBaeum/EliceDigitalBaeum-Regular.ttf') format('truetype');
}
@font-face {
    font-family: 'Elice Digital Baeum';
    font-weight: 700;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/EliceDigitalBaeum/EliceDigitalBaeum-Bold.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/EliceDigitalBaeum/EliceDigitalBaeum-Bold.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/EliceDigitalBaeum/EliceDigitalBaeum-Bold.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/EliceDigitalBaeum/EliceDigitalBaeum-Bold.ttf') format('truetype');
}
```

&nbsp;

## 다이나믹 서브셋

웹폰트의 최적화를 위해 모던 브라우저에서는 글리프를 여러개로 나누어 필요한 부분만 동적으로 파싱하는 다이나믹 서브셋을 제공합니다. 폰트의 용량이 부담된다면 아래 코드를 사용하는 걸 추천합니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/EliceDigitalBaeum/subsets/EliceDigitalBaeum-dynamic-subset.css" type="text/css"/>
```

### CSS

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/EliceDigitalBaeum/subsets/EliceDigitalBaeum-dynamic-subset.css');
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.



```css
font-family: "Elice Digital Baeum", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
- ‘엘리스 디지털 배움체’의 지적재산권은 엘리스가 보유하고 있습니다.

- ‘엘리스 디지털 배움체’는 무료로 배포하며, Open Font License를 따릅니다.

- 개인 및 기업 사용자를 포함한 모든 사용자에게 무료로 제공되며, 자유롭게 수정/변경하여 영리적/비영리적 목적으로 사용하실 수 있습니다.

- 글꼴 폰트파일(OTT,TTF) 자체를 유상으로 판매하거나 어떠한 형태로든 임의 수정 또는 개작하여 재배포하는 것은 금지하고 있으니 유의 부탁드립니다.

- 문의사항 / contact@elice.io, 070-4633-2017
```
