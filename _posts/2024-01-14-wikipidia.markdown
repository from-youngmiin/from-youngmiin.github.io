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

##### 사용한 프로그램 : 
<pre>
	Front-End(HTML, CSS, Python), 
	Back-end(Django), 
	Data-crawl(web-crawling), 
	DB(DBsqlite3)
</pre>

##### 주요 기능 : 
<pre>

위키백과의 내용은 무수히 많고, 누구나 수정이 가능하다는 특징이 있다. 지도 위에 위키백과를 접목시켜서 다양한 정보를 활용한다.
하지만 위키백과에서는 일정한 규칙을 갖고 있지않고 있기 때문에 1차적으로 선택한 위치의 큰 지역을 잡아서 시각화 한다.

</pre>

***

>첫 web-page

![Image 22](/images/22.jpg)

회원가입을 진행하기 전에는 화면 전화에 대해 lock이 걸리게되어 회원가입을 유도한다.

>회원가입 및 로그인 화면

![Image 24](/images/24.jpg){:style="width:48%; height:300px; display:inline-block; margin: 5px;"}
![Image 25](/images/25.jpg){:style="width:48%; height:300px; display:inline-block; margin: 5px;"}

로그인 회원가입으로 사용자의 정보를 확인할 수 있도록하였고 회원가입의 창에서는 지도가 random으로 보여지도록하여 전세계를 움직일 수 있도록 하였다.

>메인 화면

![Image 26](/images/26.jpg)

로그인 성공한 메인화면에서는 주기능인 검색기능도 가능하고 첫 검색이후에는 검색창이 상단으로 고정되게 설정하였다.

>검색창으로 검색한 화면

![Image 27](/images/27.jpg)

구글Map API를 사용하여 검색의 키워드가 다양하고 선택한 지역의 도로명 주소 중에서 시, 동, 구 의 큰 키워드를 선택해 우측 바에서 키워드의 위키백과 내용이 보여진다.

>검색하지 않고 원하는 곳을 클릭해서 검색한 화면

![Image 28](/images/28.jpg)

첫 검색이 이루어진 이후에는 지도를 움직여서 경계에 있는 위치를 따로 선택가능하고 해당 장소의 주소를 큰 타이틀로 위키백과 내용이 보여진다.

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

