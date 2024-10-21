# Introducing Korean fonts.

안녕하세요! 한국 폰트에 관심 있으신가요? 폰트는 디자인과 글의 분위기를 결정짓는 중요한 요소입니다.
특히 웹사이트나 다양한 디자인 프로젝트에서 한글 폰트를 적절히 사용하면, 텍스트의 가독성을 높이고 감각적인 느낌을 더할 수 있어요.
오늘은 여러분께 한국 폰트를 소개해 드릴께요!

<a href="https://fontkor.github.io/fontkor/" target="_blank">[https://fontkor.github.io/fontkor/]</a>

Hello! Are you interested in Korean fonts? Fonts play a crucial role in shaping the design and mood of text. Especially in websites and various design projects, using Korean fonts properly can enhance readability and add a touch of style. Today, I’m excited to introduce you to Korean fonts!

## 폰트 적용 방법

폰트를 적용하는 방식은 2가지 방식이 있습니다.
제일 많이 사용하고 있는 링크 방식입니다. 폰트이름만 적으시면 CSS로 바로 연동이 됩니다.

```html
<link
  rel="stylesheet"
  href="https://fontkor.github.io/fontkor/woff2/[폰트이름]/[폰트이름].css"
/>
```

링크 방식을 사용할 때도 마찬가지 입니다.

```css
@import url("https://fontkor.github.io/fontkor/woff2/[폰트이름]/[폰트이름].css");
```

그리고 원하는 부분에 선언하시면 됩니다.

```html
<span style="font-family: [폰트이름]">나눔바른고딕</span>
```

CSS에서 선언할 때도 같은 방식으로 사용합니다.

```css
.font__list {
  font-family: [폰트이름];
}
```

폰트마다 두꼐가 있습니다.
필요한 두께만 설정하고 싶다면 다음과 같습니다. 아래의 100은 폰트 두께를 말합니다.

```css
@import url("https://fontkor.github.io/fontkor/woff2/[폰트이름]/[폰트이름][100].css");
```

```css
/* sample */
@import url("https://fontkor.github.io/fontkor/woff2/fonts.css"); /* 모든 폰트를 적용할 수 있음. 테스트용 */
@import url("https://fontkor.github.io/fontkor/woff2/MaruBuri/MaruBuri.css"); /* 마루부리 폰트를 적용함[200, 300, 400, 600, 700] */
@import url("https://fontkor.github.io/fontkor/woff2/MaruBuri/MaruBuri200.css"); /* 마루부리 폰트 두께 200만 적용 */
@import url("https://fontkor.github.io/fontkor/woff2/MaruBuri/MaruBuri300.css"); /* 마루부리 폰트 두께 300만 적용 */
@import url("https://fontkor.github.io/fontkor/woff2/MaruBuri/MaruBuri400.css"); /* 마루부리 폰트 두께 400만 적용 */
@import url("https://fontkor.github.io/fontkor/woff2/MaruBuri/MaruBuri600.css"); /* 마루부리 폰트 두께 600만 적용 */
@import url("https://fontkor.github.io/fontkor/woff2/MaruBuri/MaruBuri700.css"); /* 마루부리 폰트 두께 700만 적용 */
```

## 폰트 종류

나눔고딕(NanumGothic) [300, 400, 700, 800]  
나눔고딕에코(NanumGothicEco) [400, 700, 800]  
나눔명조(NanumMyeongjo) [400, 700, 800]  
나눔명조에코(NanumMyeongjoEco) [400, 700, 800]  
나눔명조옛한글(NanumMyeongjoYetHangul) [400]  
나눔바른고딕(NanumBarunGothic) [200, 300, 400, 700]  
나눔바른고딕옛한글(NanumBarunGothicYetHangul) [400]  
나눔바른펜(NanumBarunpen) [400, 700]  
나눔손글씨붓(NanumBrush) [400]  
나눔손글씨펜(NanumPen) [400]  
나눔스퀘어(NanumSquare) [300, 400, 700, 800]  
나눔스퀘어라운드(NanumSquareRound) [300, 400, 700, 800]  
나눔스퀘어네오(NanumSquareNeo) [300, 400, 700, 800, 900]  
D2coding(D2Coding) [400, 700]  
마루부리(MaruBuri) [200, 300, 400, 600, 700]

## 폰트 두께

한국 폰트는 굵기에도 다양한 옵션이 있어서, 텍스트의 느낌을 세밀하게 조정할 수 있어요. 각 굵기는 숫자로 표현되는데요, 폰트를 사용할 때 이 숫자를 조정해 텍스트의 무게감을 바꿀 수 있어요.

Korean fonts offer a wide range of weight options, allowing you to fine-tune the feel of the text. Each weight is represented by a number, and adjusting this number when using fonts can change the overall heaviness and appearance of the text.

- 100: <b>아주 얇은 글자</b>, font-thin
- 200: <b>조금 더 가벼운 글자</b>, font-extralight
- 300: <b>가벼운 느낌의 글자</b>, font-light
- 400: <b>기본 두께</b>, font-normal
- 500: <b>중간 두께</b>, font-medium
- 600: <b>살짝 굵은 글자</b>, font-semibold
- 700: <b>굵은 글자</b>, font-bold
- 800: <b>더 굵은 글자</b>, font-extrabold
- 900: <b>가장 굵은 글자</b> font-black

## 폰트 저작권

폰트를 사용할 때는 꼭 저작권을 확인하는 것이 중요해요! 대부분의 폰트는 무료로 사용할 수 있지만, 상업적 사용이나 배포에는 제한이 있을 수 있거든요.

- 무료 폰트: Google Fonts와 같은 무료 폰트는 개인 프로젝트나 상업적인 용도로도 사용할 수 있지만, 일부는 특정 라이선스 조건을 따를 수 있어요. 꼭 라이선스를 확인하고 사용해 주세요.
- 유료 폰트: 상업적인 목적으로 사용하려면 별도의 라이선스가 필요한 유료 폰트도 있어요. 특히 상업적인 프로젝트에서 폰트를 사용할 때는 저작권 문제가 발생하지 않도록 주의해야 해요.

폰트를 잘 사용하면 디자인을 더 풍부하게 만들어 주지만, 저작권을 지키는 것도 정말 중요한 부분이에요. 안전하게 사용할 수 있도록 라이선스 정보는 항상 꼼꼼히 확인하는 습관을 들여주세요!
