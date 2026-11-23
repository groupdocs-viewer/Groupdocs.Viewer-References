---
title: "Metered 클래스"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "사용량 기반(종량제) 라이선스를 관리합니다."
type: docs
url: /ko/python-net/groupdocs.viewer/metered/
is_root: false
weight: 80
---


## Metered class

사용량 기반(종량제) 라이선스를 관리합니다.

Metered 라이선스는 실제 사용량(보통 페이지 또는
문서가 처리된 경우). 공개/비공개 키 쌍을 한 번 설정하십시오
애플리케이션 시작 시; 래퍼가 사용량을 GroupDocs에 보고합니다
백그라운드에서 라이선스 서버에 보고합니다.

Metered 유형은 다음 멤버를 노출합니다:

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [get_consumption_credit](/viewer/python-net/groupdocs.viewer/metered/get_consumption_credit/) | 현재 키에 대한 남은 Metered 크레딧을 반환합니다. |
| [get_consumption_quantity](/viewer/python-net/groupdocs.viewer/metered/get_consumption_quantity/) | 지금까지 사용된 총 Metered 양을 반환합니다. |
| [set_metered_key](/viewer/python-net/groupdocs.viewer/metered/set_metered_key/#public_key-private_key) | 주어진 공개/비공개 키 쌍으로 Metered 청구를 활성화합니다. |

### 참고
* module [`groupdocs.viewer`](/viewer/python-net/groupdocs.viewer/)
