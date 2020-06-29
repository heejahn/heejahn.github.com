---
title: "GitHub 블로그 만들기"
excerpt: "Jekyllㅇ르 통해 GitHub 블로그 설치"
comments: true

categories:
  - GitHub
last_modified_at: 2020-06-29
---
# 목적
GitHub에 올리는 프로젝트 과정, 진행하며 느낀 점, 맞닥뜨린 문제 및 해결 방법을 적기 위해 생성

인터넷에 잘 설명된 글이 많아 모든 파트를 자세히 쓰기 보다 내가 겪었던 진행 상황을 적음

# 설치
1. Repository 생성
GitHub에서 내 아이디.github.io라는 이름의 repository를 만든다. 나는 .io 대신 .com을 사용해도 된다 해서 .com으로 지었다.
* 그런데 나중에 블로그 링크를 쓸 때 확장자를 .com으로 쓰면 404 페이지가 떴다. 거기선 .io로 써줘야 한다.
* repository 주소를 clone한 걸 보면 확장자는 무조건 .io로 고정되는 것 같다.

만들어진 repository 주소를 복사해 원하는 디렉토리에 clone 한다.
나는 git bash를 사용했다.
'
$ git clone https://github.com/heejahn/heejahn.github.io.git
'

2. 테마 고르기
지킬 테마 사이트에서 선택한다. 

해당 사이트에 무료로 받을 수 있는 테마가 수두룩하게 있다.
최종 선택은 minimal-mistake로 했다.
내가 선택할 당시엔 Now가 제일 fork가 많이 되었다. 하지만 Now를 적용해도 다른 테마를 추가로 적용해야 한다고 들었고 구글에서 가장 많이 언급되어 문제가 생겼을 때 해결하기 수월해 보여 선택했다.

좀 있다 추가. 잠깐 나갔다 와야 함.
