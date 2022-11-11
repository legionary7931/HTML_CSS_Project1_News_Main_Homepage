# Frontend Mentor - News homepage solution

HTML과 CSS를 사용하여 처음으로 만든 웹페이지다. 문제는 해당 사이트에서 참고하여 가지고 왔다. 조금 더 내가 개발을 더 할 줄 알게 되면 다른 웹사이트를 클론 코딩 할 수 있게 되었으면 좋겠다. (https://www.frontendmentor.io/challenges/news-homepage-H6SWTa1MFl).

## Table of contents

- [개요]
  - [스크린 샷](#screenshot)
- [개발 과정](#my-process)
  - [사용한 기술](#built-with)
  - [배운 것](#what-i-learned)
  - [어려웠던 것](#difficulties)
- [개발자](#author)

### Screenshot

![](./screenshot.png)

## My process

### Built With
- Semantic HTML5 markup
- CSS custom properties
- CSS FlexBox
- Mobile-first workflow(적용 예정)

### What I learned
```
.main{
    height: 630px;
    overflow: hidden;
}

```
```
.main_sidebar{
    float: right;
    background-color: hsl(240, 100%, 5%);
    padding: 40px;
    width: 374px;
    height: 100%;
    margin-left: 40px;
    overflow: hidden;
}

```
한 div가 float되어 있고, 다른 div는 float되어 있지 않는 상태에서, div가 서로의 컨테이너의 width에 꽉 차게 만들고 싶다면 float되지 않은 다른 div에 overflow: hidden을 걸어주어야 한다.

### Difficulties

1. 밑의 사진과 기사가 있는 파트만 flexbox를 사용하고 기타 레이아웃을 잡는데는 float를 사용하였는데, float를 사용하다보니 반응형 웹을 만드는데 어려움이 있었다.

2. float를 사용했더라도 기존에 배웠던대로 layout만을 담당하는 클래스와 component의 내용을 담당하는 클래스를
나누어 마크업 작업을 했으면 반응형 작업하기에도 더 유리
했겠다라는 생각을 했다.

### Useful resources

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.**

## Author

- Website - [Add your name here](https://www.your-site.com)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.**
