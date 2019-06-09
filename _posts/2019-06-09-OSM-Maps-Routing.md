---
layout:     post
title:      "OSM & Map, Routing Server 구축하기"
subtitle:   "Open Street Map & Map, Routing Server 구축하기"
date:       2019-06-09 00:00:00
author:     "insford"
comments:   true
header-img: "img/post-bg-04.jpg"
tags:		  [OSM, Map, Routing]
categories: [OSM]
---

# What is the OSM?

[OSM](https://ko.wikipedia.org/wiki/%EC%98%A4%ED%94%88%EC%8A%A4%ED%8A%B8%EB%A6%AC%ED%8A%B8%EB%A7%B5)은 Open Street Map의 약자로 2005년 설립된 영국의 비영리기구 오픈스트리트맵 재단이 운영하는 오픈 소스 방식의 참여형 무료 지도 서비스입니다. 비영리인 위키백과를 모델로 하고 있어 누구나 편집하고 활용이 가능합니다.

현재 전 세계적으로 OSM을 사용하는 곳은 굉장히 다양합니다. Map 데이터라는게 굉장히 다양해서 구축하기가 힘들 뿐만 아니라 최신데이터를 유지하는것만 해도 유지비용이 꽤 많이 듭니다. 그로인해 Map을 서비스하는 회사 중 OSM을 사용하는 회사보다 사용하지 않는 회사를 찾는게 더 빠를 정도입니다.

**자체적으로 Map데이터를 수집해서 서비스하고 있는 회사**
- Google Map
- Bing Map(Microsoft)

**OSM을 이용해서 서비스하고 있는 회사 - [참고](https://wiki.openstreetmap.org/wiki/They_are_using_OpenStreetMap)**
- Trip Advisor
- Mapbox
- Apple(일부 지역)

기본적으로 OSM은 [https://www.openstreetmap.org](https://www.openstreetmap.org) 으로 접속하시면 확인이 가능합니다.
기본적인 지도에서부터 자동차, 자전거, 도보길찾기도 가능합니다.

## OSM Stats
[OSM Stats](http://osmstats.neis-one.org)는 OSM데이터가 얼마나 많이 수정되고 있는지를 알려주는 사이트입니다. 해당 사이트에서는 각 국가별 ActiveUser와 각 데이터에 대한 수정개수를 보여줍니다.

![](/img/20190609/osmstats_1.png)
![](/img/20190609/osmstats_2.png)
한국은 2019년 6월 1일 기준 약 55위 Active User가 12명입니다.

![](/img/20190609/osmstats_3.png)

year단위로 보면 거의 매일매일 1~20명의 유저가 지속적으로 데이터를 수정해주고 계십니다. (중간에 그래프가 튀는 구간은 포켓몬고 열풍이었을 시절 - 포켓몬고도 OSM을 이용했었죠)

# Map Server
작성중 ...

# Routing Server
작성중 ...




