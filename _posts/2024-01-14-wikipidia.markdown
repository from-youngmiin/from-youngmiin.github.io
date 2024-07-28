---
layout: post
title: '[개발]GoogleMap API에 위키백과사전 정보를 보여줄 수 있는 WEB'
image: 20.jpg 
date: 2024-01-14 12:00:00
tags:
categories: guide
---
##### 소개 : Instagram 사진정보를 이용하여 서울, 경기 지역 사람들에게 관광지를 추천해주는 어플리케이션을 제작

##### 개발기간 : 2023.10 ~ 2023.12
<div style="text-align: center;">
  <img src="/images/23.jpg" alt="Image 23" />
</div>

<br>
##### 맡은 임무 : UI파트 (5인으로 구성하여 UI, DB, 시각화, 크롤링, 서버로 나누어 활동)

##### 사용한 프로그램 : Front-End(HTML, CSS, Python), Back-end(Django), Data-crawl(web-crawling), DB(DBsqlite3)

##### 주요 기능 : 


위키백과의 내용은 무수히 많다. 누구나 작성할 수 있고 ,,,,,,,,,,

***

>첫 web-page

![Image 22](/images/22.jpg)

>회원가입 및 로그인 화면

![Image 24](/images/24.jpg){:style="width:48%; height:300px; display:inline-block; margin: 5px;"}
![Image 25](/images/25.jpg){:style="width:48%; height:300px; display:inline-block; margin: 5px;"}


>메인 화면

![Image 26](/images/26.jpg)

>검색창으로 검색한 화면

![Image 27](/images/27.jpg)

>검색하지 않고 원하는 곳을 클릭해서 검색한 화면

![Image 28](/images/28.jpg)

>이슈


#### Headings by default:

# H1 For example
## H2 For example
### H3 For example
#### H4 For example
##### H5 For example
###### H6 For example

#### Lists

###### Ordered list example:

1. Poutine drinking vinegar bitters.
2. Coloring book distillery fanny pack.
3. Venmo biodiesel gentrify enamel pin meditation.
4. Jean shorts shaman listicle pickled portland.
5. Salvia mumblecore brunch iPhone migas.

###### Unordered list example:

* Bitters semiotics vice thundercats synth.
* Literally cred narwhal bitters wayfarers.
* Kale chips chartreuse paleo tbh street art marfa.
* Mlkshk polaroid sriracha brooklyn.
* Pug you probably haven't heard of them air plant man bun.

{% highlight markdown %}
1. Order list item 1
2. Order list item 1

* Unordered list item 1
* Unordered list item 2
{% endhighlight %}


{% highlight js %}
  $('.top').click(function () {
    $('html, body').stop().animate({ scrollTop: 0 }, 'slow', 'swing');
  });
  $(window).scroll(function () {
    if ($(this).scrollTop() > $(window).height()) {
      $('.top').addClass("top-active");
    } else {
      $('.top').removeClass("top-active");
    };
  });
{% endhighlight %}

