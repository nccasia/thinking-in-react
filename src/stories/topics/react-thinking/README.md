# React giải quết vấn đề như thế nào?

## Brief History of React

### Context

#### The web standard evolution

![](https://cmay.vn/wp-content/uploads/2019/02/1-18.jpg)

#### The web hardwares evolution

![](https://deviceatlas.com/sites/deviceatlas.com/files/images/Device%20evolution.JPG)

#### The UX evolution

![](http://mentalmodels.com/i/ui-evolution_reduced.jpg)

## React born to solve problems

![](https://miro.medium.com/max/1908/1*c5R29Xh4icIpQKfEiN9w0A.png)

## React Philosophy

### Virtual DOM

![](https://miro.medium.com/max/700/0*Eh7dka3ImjIf1iPY)

### Composition

#### Composition via React Components

![](https://miro.medium.com/max/700/1*-Ct-gC3L4-WC730W9uFIag.png)
![](https://miro.medium.com/max/700/1*bgkkQiK3mRP7LpTVs1AhFg.png)

#### Composition via React Hooks

![](https://miro.medium.com/max/700/1*5HiQ4yA_IcZN0Rlq64dPGA.png)
![](https://miro.medium.com/max/700/1*9BCt_Z-EffCh5xNV6zBzLw.png)

### Common Abstraction

![](https://i1.wp.com/everyday.codes/wp-content/uploads/2020/10/levels_of_abstraction2.png?resize=680%2C197&ssl=1)

![](http://ar.kapsi.fi/posts/abstractions-in-js/FormProcess.png)

### Functional Programing

### One way data flow

### Single source of truth

![](https://d33wubrfki0l68.cloudfront.net/4271f4d204ab9ca50c9e2bdc8b3fd2168ef1766c/cbc41/assets/images/single-source-of-truth.png)

### Redux

![](https://css-tricks.com/wp-content/uploads/2016/03/redux-article-3-03.svg)

### hooks

![](https://raw.githubusercontent.com/Wavez/react-hooks-lifecycle/master/screenshot.jpg)

![](https://the-guild.dev/medium/bca747b6dd5992e26b78942e8ba4f071.png)

### context

![](https://cmichel.io/you-might-not-need-react-context/react-context-vs-hoc.png)

![](https://1.bp.blogspot.com/-TrhP5bgsnkY/XxyZ0iZj1-I/AAAAAAAAC60/FAGxqxlVtfsxsWfYK8omFZQNKMgROfzQgCLcBGAsYHQ/s542/ozkary-react-component-context-hook.png)

## How React work

![](https://drek4537l1klr.cloudfront.net/thomas/Figures/04fig03_alt.jpg)

![](https://cdn-images-1.medium.com/max/1600/1*PBgAz9U9SrkINPo-n5glgw.gif)

![](https://gblobscdn.gitbook.com/assets%2F-LgMQu802me2gEI8E8bY%2F-LhTzJ4INg_xnDg8TIsk%2F-LhU10tKkR46FfidEKsL%2Fkk1.jpeg?alt=media&token=57f68ab7-2b40-4304-b55f-f7ff3b96a0d4)

![](https://cdn-images-1.medium.com/max/1600/1*T_Q66EkNEhca6TyrvY1xBQ.gif)

### What is Virtual DOM

Trong React, với mỗi DOM object sẽ có một Virtual DOM object tương ứng. Một virtual DOM object là một virtual representation của một DOM object, có thể hiểu nôm na virtual DOM là một bản copy của DOM.

### How React update the DOM

Khi `render()` được gọi, nó không update real DOM, nó thực chất sẽ update lên virtual DOM. Sau đó, compare với một snapshot của old virtual DOM. Nếu có thay đổi React mới update lên Real DOM **chỉ và chỉ** những phần thay đổi. Nếu không thì chả có chuyện gì xảy ra cả.

![](https://raw.githubusercontent.com/nccasia/thinking-in-react/master/src/stories/assets/how-react-update-the-dom.jpg)

Với cách này, nó cũng sẽ giúp tối ưu và hạn chế việc update real DOM không cần thiết.

## References

- [Design Principles
  ](https://reactjs.org/docs/design-principles.html)
- [React is all about composition](https://medium.com/leanjs/react-is-all-about-composition-f9f49dec183c)
- [Thinking in React](https://reactjs.org/docs/thinking-in-react.html)
- [The philosophy of React](https://code.likeagirl.io/the-philosophy-of-react-e2c126c61af3)
- [The Missing Introduction to React](https://medium.com/javascript-scene/the-missing-introduction-to-react-62837cb2fd76)
- [React philosophy](https://reallifeprogramming.com/react-philosophy-e8cdea991599)
- [One Way Data Flow
](https://tkssharma.gitbook.io/react-training/day-01/react-js-3-principles/one-way-data-flow)
