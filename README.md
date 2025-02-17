# 서평원 꺾깍체

[배포처 바로가기](https://slei.seoul.kr/introduce/brand/typeface.do)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `SLEI Gothic`입니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/SLEIGothic/SLEIGothic.css" type="text/css"/>
```

### CSS `@Import`

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/SLEIGothic/SLEIGothic.css');
```

### CSS `@font-face`

```css
@font-face {
  font-family: 'SLEI Gothic';
  font-weight: normal;
  font-style: normal;
  font-display: swap;
  src: url('https://cdn.jsdelivr.net/gh/fonts-archive/SLEIGothic/SLEIGothic.woff2') format('woff2'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/SLEIGothic/SLEIGothic.woff') format('woff'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/SLEIGothic/SLEIGothic.otf') format('opentype'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/SLEIGothic/SLEIGothic.ttf') format('truetype');
}
```

&nbsp;

## 다이나믹 서브셋

웹폰트의 최적화를 위해 모던 브라우저에서는 글리프를 여러개로 나누어 필요한 부분만 동적으로 파싱하는 다이나믹 서브셋을 제공합니다. 폰트의 용량이 부담된다면 아래 코드를 사용하는 걸 추천합니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/SLEIGothic/subsets/SLEIGothic-dynamic-subset.css" type="text/css"/>
```

### CSS

```css
@import url("https://cdn.jsdelivr.net/gh/fonts-archive/SLEIGothic/subsets/SLEIGothic-dynamic-subset.css");
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.

```css
font-family: "SLEI Gothic", -apple-system, BlinkMacSystemFont, "Segoe UI",Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
서평원 꺾깎체의 지적 재산권은 서울특별시평생교육진흥원에 있으나, 오픈 라이선스로 자유롭게 수정하고 재배포 할 수 있습니다. 서체의 개발은 한글 디자인 및 폰트 기술 전문 회사 <이도타입>에서 맡았습니다.
```
