---
layout: post
title:  "마크다운 연습"
date:   2022-02-15 00:21:32 +0900
categories: markdown
---
<android first>

#제목1입니다
##제목2이고요
###제목3입니다
####제목4입니다.
#####제목5입니다.
######제목6입니다.
#######제목7은 없습니다.

제목 1입니다.
====
제목 2입니다.
--

강조----------------------------
==
<em>en</em> 기울여짐
--
<strong>strong</strong> 두껍게
--
<del>del</del> 삭제됨
--
<u>u</u> : 밑줄
--

목록(LIST)------------------------
==

* 리스트
* 리스트2


* 상위 리스트1
  * 하위 리스트1
  * 하위 리스트2
    * 하위의 하위 리스트1
    * 하위의 하위 리스트2
    
```
박스형 코드라인 입니다.
```


문장속 코드 `example code inline` 삽입 예시입니다.

```
문장속 코드 `example code inline` 삽입 예시입니다.
```
`{예시{``}}`

순서가 없는 리스트입니다.
* 리스트1
* 리스트2
* 리스트3

순서가 있는 리스트입니다.
1. 리스트1
   1. 안녕하세요
2. 리스트2
    1. 안녕하세요
    2. ㅇㅇ
1. ㅇㅇ
    * ㅇㅇ
      * ㄹㅇㄹㄹ
리스트3

```
순서가 없는 리스트입니다.
* 리스트1
* 리스트2
* 리스트3

순서가 있는 리스트입니다.
1. 리스트1
   1. 안녕하세요
2. 리스트2
    1. 안녕하세요
    2. ㅇㅇ
1. ㅇㅇ
    * ㅇㅇ
      * ㄹㅇㄹㄹ
리스트3
```


## 링크

* <https://www.github.com>
* [Github](https://www.github.com)


> 인용구입니다.
>>인용구안에 인용구를 사용할 수 있습니다.
```
> 인용구입니다.
>>인용구안에 인용구를 사용할 수 있습니다.
```
## 강조

* 강조 문법 **강조된 부분** 예시입니다.





## 이미지

![예시 이미지]("/assets/images/my_dog_nuri2.jpg')
![예시 이미지]("/assets/images/my_dog_nuri2.jpg")


{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/junhyeok-project
[jekyll-talk]: https://talk.jekyllrb.com/
