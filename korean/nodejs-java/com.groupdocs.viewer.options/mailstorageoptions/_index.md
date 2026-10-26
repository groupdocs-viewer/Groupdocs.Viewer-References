---
title: "MailStorageOptions"
second_title: "Node.js용 GroupDocs.Viewer (Java) API 레퍼런스"
description: "메일 저장소 Lotus Notes MBox 데이터 파일을 렌더링하기 위한 옵션을 제공합니다."
type: docs
weight: 19
url: /ko/nodejs-java/com.groupdocs.viewer.options/mailstorageoptions/
---
**Inheritance:**
java.lang.Object
```
public class MailStorageOptions
```

메일 저장소(Lotus Notes, MBox) 데이터 파일 렌더링 옵션을 제공합니다.

MailStorageOptions 클래스는 GroupDocs.Viewer 구성 요소에서 메일 저장소 데이터 파일(예: Lotus Notes 또는 MBox)의 렌더링을 제어하는 데 사용할 수 있는 다양한 설정 및 매개변수를 캡슐화합니다.

자세한 내용은 [documentation][].

예시 사용법:

```

 MailStorageOptions options = new MailStorageOptions();
 options.setAddressFilter("@gmail.com");
 options.setMaxItems(10);

 final HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 htmlViewOptions.setMailStorageOptions(options);

 try (Viewer viewer = new Viewer("mail.msg")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#specify-rendering-options
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [MailStorageOptions()](#MailStorageOptions--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getTextFilter()](#getTextFilter--) | 메시지를 필터링하는 데 사용되는 키워드를 가져옵니다. |
| [setTextFilter(String textFilter)](#setTextFilter-java.lang.String-) | 메시지를 필터링하는 데 사용되는 키워드를 설정합니다. |
| [getAddressFilter()](#getAddressFilter--) | 보낸 사람 또는 받는 사람으로 메시지를 필터링하는 데 사용되는 이메일 주소를 가져옵니다. |
| [setAddressFilter(String addressFilter)](#setAddressFilter-java.lang.String-) | 보낸 사람 또는 받는 사람으로 메시지를 필터링하는 데 사용되는 이메일 주소를 설정합니다. |
| [getMaxItems()](#getMaxItems--) | 렌더링할 최대 메시지 또는 항목 수를 가져옵니다. |
| [setMaxItems(int maxItems)](#setMaxItems-int-) | 렌더링할 최대 메시지 또는 항목 수를 설정합니다. |
### MailStorageOptions() {#MailStorageOptions--}
```
public MailStorageOptions()
```


### getTextFilter() {#getTextFilter--}
```
public String getTextFilter()
```


메시지를 필터링하는 데 사용되는 키워드를 가져옵니다.

이 속성을 사용하여 제목이나 본문에 특정 텍스트가 포함된 모든 메시지를 렌더링합니다. 코드 예제는 [documentation][]을 참조하십시오.


[documentation]: https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#filter-messages

**Returns:**
java.lang.String - 메시지를 필터링하는 데 사용되는 키워드.
### setTextFilter(String textFilter) {#setTextFilter-java.lang.String-}
```
public void setTextFilter(String textFilter)
```


메시지를 필터링하는 데 사용되는 키워드를 설정합니다.

이 속성을 사용하여 제목이나 본문에 특정 텍스트가 포함된 모든 메시지를 렌더링합니다. 코드 예제는 [documentation][]을 참조하십시오.


[documentation]: https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#filter-messages

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| textFilter | java.lang.String | 메시지를 필터링하는 데 사용되는 키워드. |

### getAddressFilter() {#getAddressFilter--}
```
public String getAddressFilter()
```


보낸 사람 또는 받는 사람으로 메시지를 필터링하는 데 사용되는 이메일 주소를 가져옵니다.

이 속성을 사용하여 발신자\u2019s 또는 수신자\u2019s 주소에 특정 텍스트가 포함된 모든 메시지를 렌더링합니다. 코드 예제는 [documentation][]을 참조하십시오.


[documentation]: https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#filter-messages

**Returns:**
java.lang.String - 메시지를 필터링하는 데 사용되는 이메일 주소.
### setAddressFilter(String addressFilter) {#setAddressFilter-java.lang.String-}
```
public void setAddressFilter(String addressFilter)
```


보낸 사람 또는 받는 사람으로 메시지를 필터링하는 데 사용되는 이메일 주소를 설정합니다.

이 속성을 사용하여 발신자\u2019s 또는 수신자\u2019s 주소에 특정 텍스트가 포함된 모든 메시지를 렌더링합니다. 코드 예제는 [documentation][]을 참조하십시오.


[documentation]: https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#filter-messages

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| addressFilter | java.lang.String | 메시지를 필터링하는 데 사용되는 이메일 주소입니다. |

### getMaxItems() {#getMaxItems--}
```
public int getMaxItems()
```


렌더링할 최대 메시지 또는 항목 수를 가져옵니다.

Lotus Notes 데이터 파일은 크기가 클 수 있으며, 모든 메시지를 가져오는 데 상당한 시간이 걸릴 수 있습니다. 이 설정은 렌더링되는 메시지 또는 항목의 최대 수를 제한합니다.

***Note:** The default value is 0, which means all messages will be rendered.* For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#limit-the-number-of-items-to-render

**Returns:**
int - 렌더링할 메시지 또는 항목의 최대 수입니다.
### setMaxItems(int maxItems) {#setMaxItems-int-}
```
public void setMaxItems(int maxItems)
```


렌더링할 최대 메시지 또는 항목 수를 설정합니다.

Lotus Notes 데이터 파일은 크기가 클 수 있으며, 모든 메시지를 가져오는 데 상당한 시간이 걸릴 수 있습니다. 이 설정은 렌더링되는 메시지 또는 항목의 최대 수를 제한합니다.

***Note:** The default value is 0, which means all messages will be rendered.* For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#limit-the-number-of-items-to-render

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| maxItems | int | 렌더링할 메시지 또는 항목의 최대 수입니다. |

