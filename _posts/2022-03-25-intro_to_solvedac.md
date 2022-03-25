---
tags: contest
date: 2022-03-25 12:00 +0900
title: "solved.ac에 대한 (짧은) 소개!"
categories: almight
author: wbjeon2k
---
### TL;DR
[solved.ac](https://solved.ac)는 [백준 온라인 저지(BOJ)](https://acmicpc.net)와 연동이 되는 서비스이다.  
**문제의 난이도**를 볼 수 있으며, solved.ac기준 플래티넘 이상의 개인 티어를 달성하면 난이도 투표에 참여할 수 있다.  
**태그**를 통해 문제를 알고리즘 유형별로 검색할 수 있다.  
**클래스**를 통해 난이도 별 추천 문제들을 풀어볼 수 있다.  

### solved.ac의 탄생 배경 
[백준 온라인 저지(BOJ)](https://acmicpc.net)는 국내 알고리즘 트레이닝 사이트 중 보유하고 있는 문제가 가장 많으며,  
아주 많은 종류의 언어를 지원하고 게시판, 문제집, 그룹, 블로그 등 다양한 기능을 제공하기로 유명합니다.  
지원하는 문제의 양과 지원하는 언어의 종류는 전세계 알고리즘 사이트들 중에서도 손 꼽히게 많은 편입니다.  
풍부한 문제와 기능, 거기에 깔끔한 UI까지 지원 되어서 많은 사람들이 애용하고 있습니다.  

이러한 백준에도 한 가지 단점이 있었는데, 백준 온라인 저지의 문제들에는 난이도 표기가 없었습니다.(*※2021년 초에 solved.ac 티어 연동이 되기 전까지*)  
다양한 문제를 풀어 보고 싶더라도 난이도를 가늠하기 어려워 무슨 문제를 풀어야 할지 판단하기 곤란했었습니다.  
푼 사람 수를 보거나, 분류된 알고리즘으로 대충 난이도를 추정할 수 있었지만 이는 별로 좋은 방법은 아니었습니다.  

알고리즘분류-맞힌사람 정렬의 허점을 보여주는 예시가 [1014번 컨닝](https://www.acmicpc.net/problem/1014) 문제와 [2595번 배수](https://www.acmicpc.net/problem/2595) 문제 입니다.  
  
2019년 당시 1014번 컨닝 문제는 알고리즘 분류에서 **DP** 를 선택하고, 맞힌 사람이 많은 순으로 정렬했을 때 첫 페이지에 있었습니다.  
그 당시 컨닝 문제와 비슷한 위치에 붙어있던 문제들은 [11053 가장 긴 증가하는 부분 수열](https://www.acmicpc.net/problem/11053) 등의 DP 기본 예제 문제들 이었습니다.  
컨닝 문제는 **플래티넘4** 이고, 11053번 문제는 **실버2** 임을 감안한다면 난이도 정렬에 큰 문제가 있었음을 알 수 있습니다.  

비슷한 예시로 [2595번 배수](https://www.acmicpc.net/problem/2595) 문제는 **플래티넘1** 의 난이도 임이 후에 밝혀졌지만,  
오랫동안 **BFS** 알고리즘 분류의 첫 페이지에 군림 하여 실버 수준의 문제들과 함께 있었습니다.  

**solved.ac**는 이런 백준의 단점을 보완하는 서비스입니다. 이 서비스는 백준 문제의 난이도를 보고, 유저의 개인 티어도 볼 수 있습니다.  

### 주요기능 - 문제 티어

**BOJ 문제들의 난이도를 볼 수 있는 기능입니다.**  
각 문제들의 난이도는 개인 티어 플래티넘 이상의 유저들 중, 그 문제를 해결 한 사람들이 투표를 하여 매겨집니다.  
난이도를 매기는 가이드라인은 solved.ac 안에 자세히 제시 되어 있습니다. [링크](https://solved.ac/guideline)  
가장 중요한 세 가지 요소는 아래와 같습니다.  

- 문제를 가장 쉽게 풀었을 때 등장하는 알고리즘의 난이도
- 필요한 알고리즘들을 알고 있다고 가정할 때 문제의 이론적인 솔루션을 생각하기까지의 난이도
- 그 솔루션을 코드로 구현하는 난이도

[solved.ac 문제-레벨](https://solved.ac/problems/level) 에서 난이도 별로 정렬된 문제들을 확인할 수 있습니다.  

### 주요기능 - 문제 태그

**BOJ 문제들의 알고리즘 유형을 볼 수 있는 기능입니다.**  
각 문제들의 알고리즘 유형을 볼 수 있는 기능입니다.  
각 문제에는 알고리즘 유형별로 미리 만들어진 **태그** 들을 붙일 수 있습니다.  
많은 사람들의 투표 결과로 인해 태그들이 충분히 모이면, 해당 문제의 공식 태그로 등재됩니다.  

알고리즘 태그별로 문제들을 검색 할 수 있습니다.  
[문제-태그](https://solved.ac/problems/tags) 를 통해 볼 수도 있고, 후술할 **검색 연산자** 기능을 통해서도 할 수 있습니다.  

### 주요기능 - 클래스

**난이도 별 추천 문제들을 볼 수 있는 기능입니다.**  
가장 낮은 클래스 1 부터 가장 높은 클래스 10 까지, 알고리즘 난이도 별로 엄선된 표준 유형 문제들을 풀어볼 수 있습니다.  
각 알고리즘 유형을 대표하는 문제들로 구성 되어있습니다.  
특정 클래스의 문제들을 20개 이상 해결하면 해당 클래스를 이수했다는 solved.ac 프로필 뱃지를 획득하게 됩니다.  

### 주요기능 - 개인 티어

해결한 문제들을 난이도 내림차순으로 정렬하여,  
그 중 상위 난이도 N개 문제의 난이도를 바탕으로 개인 티어를 매깁니다.  
문제를 많이 푸는것도 좋지만, 점점 더 어려운 문제에 도전하면서 티어를 높여보아요!  

단체 티어도 존재합니다. 현재 2022-03-25 현재 UNIST는 48등에 있네요.  
UNIST의 티어를 올릴 수 있도록 열심히 해봅시다!  

### 주요기능 - 검색 연산자

solved.ac 검색 창은 검색연산자 기능을 지원합니다.  
검색연산자의 예시는 [Google Search Operator](https://www.twinword.co.kr/blog/search-operator-complete-list/) 등을 참고 할 수 있습니다.  

검색 연산자를 쓰면 검색하고자 하는 문제의 조건을 더 구체적으로 정할 수 있습니다!  
전부 소개하기엔 꽤나 어려운(*귀찮은?*) 기능이기에, 감을 잡을 수 있는 예시를 몇 개 남깁니다.  

BFS 태그가 달린 문제들 중 난이도가 골드5 ~ 플래티넘1 이면서 wbjeon2k 가 해결하지 않은 문제들:  
```
tag:bfs tier:g5..p1 -solved_by:wbjeon2k
```

DP 태그와 BFS 태그가 **같이(AND)** 달린 문제들
```
tag:bfs & tag:dp
```

DP 태그 **또는(OR)** BFS 태그가 달린 문제들
```
tag:bfs | tag:dp
```

자세한 내용은 [검색](https://solved.ac/search) 탭에 있습니다.  

### 보너스 기능들

1. 랜덤 검색:  
solved.ac 검색 창에서 검색 연산자를 통해 조건을 설정한 후,  
**alt+Enter** 를 통해 조건을 만족하는 문제들 중 아무거나 하나로 바로 이동할 수 있습니다.  
2. 시프트마음대로:  
1번과 비슷한 기능이지만, 조건을 만족하는 문제들을 랜덤 순서대로 섞어서 보여주는 기능입니다.  
3. 프로필 뱃지, 프로필 배경:  
특정 클래스를 이수하거나 뱃지를 주는 대회에 참여하면 얻을 수 있습니다.