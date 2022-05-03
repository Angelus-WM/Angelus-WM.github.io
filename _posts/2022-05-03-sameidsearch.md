---
title: jQuery 비슷한 ID, Name 찾기
date: 2022-05-03 16:30:00 +09:00
categories: [jQuery]
tags: [jQuery]     # TAG names should always be lowercase
---
안녕하세요. 엔젤루스입니다.  
이번에는 jQuery로 특정 ID, Name을 가지고 있는 요소들을 찾는 방법을 알아보려고 합니다.

## jQuery ID, NAME 검색
``` javascript
//id, name이 test로 시작하는 엘리먼트들 접근
var vId = $("[id^='test']");
var vName = $("[name^='test']");

//id, name이 test로 끝하는 엘리먼트들 접근
var vId = $("[id$='test']");
var vName = $("[name$='test']");
```

다수의 비슷한 ID나 Name으로 컨트롤해야 하는 경우 사용하면 좋을 것 같습니다.  
이상 엔젤루스였습니다.