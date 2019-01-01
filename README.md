# jdfinance

> A Vue.js project!

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).

5-1 首页-抽象组件设计
抽象化思想

抽象出来的东西不能涉及到某一块的业务，比如头部有个下载的具体按钮，我们在设计这个组件的时候，不能只考虑这个下载的按钮，比如它长什么样子，长什么颜色，起了什么类名。这个在抽象组件设计中不应该去考虑的那么具体。要按照大类去分。比如 我这个按钮是不是允许自定义类 是不是允许自定义文本 这才是要考虑的问题

这种抽象组件我们可以默认一个类名 然后允许它传递进来一个类名。

组件里的data 一定要返回一个对象

5-2
emmet

vue-awesome-swiper

npmjs.com

npm install vue-awesome-swiper
去package.json dependencies 里看看安装好没

视频是3.0.6版本


      <swiper-slide>

      </swiper-slide>

import {swiper,swiperSlide} from


先把包引进来 然后我们通过组件去注册一下 这样我们就可以在模板中区使用


      default () {
        return {

        }
      }


default:function(){
return {
}
}
