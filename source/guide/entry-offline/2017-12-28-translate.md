---
layout: page
title: 다국어 작업하기
type: guide
category: 'Entry Offline'
order: 5
---

엔트리 오프라인에서는 다국어는 js 파일로 관리하고 있습니다. `src/renderer/lang/` 밑에 위치하고 있으며, 각 언어 별로 구성되어 있습니다. 또한, 오브젝트 요소를 구성하는 오브젝트 번역도 있으며 오브젝트 번역은 영문만 지원하고 있습니다.

현재 다국어 파일은 관리 편의상 온라인과 오프라인을 동일하게 공유하고 사용하고 있습니다. 번역의 경우 현재 빌드된 결과물을 사용하고 있어 제 3자가 수정하기 어려운 상황입니다. 현재 이것을 수정하여 보다 쉽게 다국어를 추가 및 수정 할수 있도록 개선 하고 있습니다.