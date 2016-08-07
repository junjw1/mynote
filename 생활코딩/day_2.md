# 수업 2일차

## 질문하기

## 생각

## DISQUS
댓글 기능을 가져와서 내 사이트에 추가해보자.

DISQUS : http://disqus.com
  - 회원가입하고 site를 만든다
  - 만든 site에서 settings 탭을 누르고 univesal code를 누른다.
  - 1번 코드를 복사하고 적용할 html에 붙여넣기한다.
![disqus 댓글 기능](disqus댓글기능사용하기.PNG)

## UserLike
아래 코드를 html페이지 </body>위에 붙여 넣는다.
```
 <script type="text/javascript" src="//userlike-cdn-widgets.s3-eu-west-1.amazonaws.com/7718d927ca342ba3a38bc29179506b34498bd2f2942176763f057cb33f9e19f7.js"></script> 
```
우측 하단에 채팅창이 생기고, 사이트 관리자에게 실시간으로 문의할 수 있다. 사이트 관리자는 userlike 홈페이지 내에서 즉답할 수 있다. 

**API 라이브러리 플러그인 서드파티 위젯**

## CSS
![css 문법](css-syntax.PNG)

####selector

*셀렉터 우선순위는 구체적일 수록 높고 포괄적일 수록 낮다.*

id selector : 문서에서 단 한번만 등장한다. (학교에서 학번)
class selector : (학교에서 반)
tag selector : 포괄적이고 정교하지 않은 선택자. 모든 태그를 선택

표현력이 짱! 복잡한 일을 어떻게 이렇게 간결하게 표현할 수 있을까!

#### Box model

각 tag들 마다 기본값을 가지고 있다.
display프로퍼티에 inline이나 block 요소로 인위적으로 설정할 수 있다.

block level element(tag)
- 블럭 레벨

inline level element(tag)
- 인라인 레벨

#### 탈 웹 화
웹을 벗어나 적용 범위가 확장되어 가고 있다. atom 에디터도 html, css, 
크롬 개발자 도구 chromium이라는 플랫폼위에서 크롬 브라우저가 만들어졌음. 그위에서 atom이 만들어졌다. amot menu > view > developer > toggle developer tools를 누르면 크롬개발자도구를 볼 수 있다.(단축키 ctrl + alt + i)

**크롬 개발자 도구 팁**

우측 상단 점 3개를 누르고 show console 하면 하단에 console창 같이 볼 수 있다.

## Atom
코드라인 정렬 - atom beautify

## PHP
```
http://www.clien.net/cs2/bbs/board.php?bo_table=use&wr_id=919870
http://www.clien.net/cs2/bbs/board.php?bo_table=useful&wr_id=253085
http://www.clien.net/cs2/bbs/board.php?bo_table=jirum&wr_id=578889
```
```
http://localhost/1.html
http://localhost/2.html
http://localhost/3.html
```
하나의 php파일로 여러개를

우리는 각 페이지를 표하는 만큼의 html파일을 가지고 있다.

#### 1.html과 1.php의 비교

html에는 php코드가 그냥 표시되고, php는 php코드가 실행된 결과가 나온다.

#### php.ini

php 설정파일 수정하자

opchache_enable = 1 -> 0
display_errors = Off -> On

apache를 껏다 켜자. 아파치에 php가 실행되고 있으므로, php 환경설정 파일이 반영된다.

## impressive
거대 목표만 보고 달려가면
근본적인 것을 배우기 위한 징검다리, 그 스스로 자체가 쓸모있는 것을 놓치기 쉽다.
기초 기본만으로도 많은 것을 할 수 있다.

개발자는 생산자이다. 개인정보를 소중하게 다뤄라

그 누구도 평범하지 않다. 누구나 최고가 될순 없지만 누구나 고유하다.

기능이 많아지면 케어해야할 것들이 많아진다.
완성도를 100%까지 가는 일은 굉장히 힘든일이다.

>선택의 문제

90% 완성도까지 갈 것이냐 100%까지 갈 것이냐
높은 완성도까지 가는 것은 굉장히 노력을 필요로한다. 애플처럼 전세계사람들이 사용할 것이면 완성도에서 타협하지 않아야한다. 그러나 혼자 쓸 것이거나 사용자 범위가 좁아진다면 완성도를 적당한 선에서 타협하는 것이 훨씬 현명할 수 있다.

> 프로그래밍하는 것은 어학연수 온 것과 비슷하다.

언젠가는 한글로 된 자료에 한계를 느낄 것이다. 느껴야한다. 느끼지 않으면 열심히 하지 않은 것이다. 느리더라도 영어를 읽자. 실력으로 꾸준히 축적된다.
영어랑 씨름을 해버리면 빨리 지칠수 있지만... 장기전에 대비하라.

## ID/PW
- disqus.com
  - facebook/ame@nav/eh234
- uploadcare.com
  - github로 로그인 /ju@da/d4
- userlike.com
  - facebook 로그인
