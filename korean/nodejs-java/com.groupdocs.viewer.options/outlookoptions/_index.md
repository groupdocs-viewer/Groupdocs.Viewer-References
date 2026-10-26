---
title: "OutlookOptions"
second_title: "Node.js용 GroupDocs.Viewer (Java) API 레퍼런스"
description: "Outlook 데이터 파일 렌더링 옵션을 제공합니다."
type: docs
weight: 20
url: /ko/nodejs-java/com.groupdocs.viewer.options/outlookoptions/
---
**Inheritance:**
java.lang.Object
```
public class OutlookOptions
```

Outlook 데이터 파일 렌더링 옵션을 제공합니다.

OutlookOptions 클래스는 GroupDocs.Viewer 구성 요소에서 Outlook 데이터 파일(PST 또는 OST 파일 등)의 렌더링을 제어하는 데 사용할 수 있는 다양한 설정 및 매개변수를 캡슐화합니다.

자세한 내용은 [documentation][].

예시 사용법:

```

 OutlookOptions options = new OutlookOptions();
 options.setAddressFilter("@gmail.com");
 options.setFolder("folderName");

 final HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 htmlViewOptions.setOutlookOptions(options);

 try (Viewer viewer = new Viewer("mail.pst")) {
   viewer.view(htmlViewOptions);
   // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#specify-rendering-options
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [OutlookOptions()](#OutlookOptions--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getFolder()](#getFolder--) | 렌더링할 폴더의 이름을 가져옵니다. |
| [setFolder(String value)](#setFolder-java.lang.String-) | 렌더링할 폴더의 이름을 설정합니다. |
| [getTextFilter()](#getTextFilter--) | 메시지를 필터링하는 데 사용되는 키워드를 가져옵니다. |
| [setTextFilter(String value)](#setTextFilter-java.lang.String-) | 메시지를 필터링하는 데 사용되는 키워드를 가져옵니다. |
| [getAddressFilter()](#getAddressFilter--) | 보낸 사람 또는 받는 사람으로 메시지를 필터링하는 데 사용되는 이메일 주소를 가져옵니다. |
| [setAddressFilter(String value)](#setAddressFilter-java.lang.String-) | 보낸 사람 또는 받는 사람으로 메시지를 필터링하는 데 사용되는 이메일 주소를 설정합니다. |
| [getMaxItemsInFolder()](#getMaxItemsInFolder--) | 하나의 폴더에서 렌더링할 수 있는 최대 메시지 또는 항목 수를 가져옵니다. |
| [setMaxItemsInFolder(int value)](#setMaxItemsInFolder-int-) | 하나의 폴더에서 렌더링할 수 있는 최대 메시지 또는 항목 수를 설정합니다. |
### OutlookOptions() {#OutlookOptions--}
```
public OutlookOptions()
```


### getFolder() {#getFolder--}
```
public final String getFolder()
```


렌더링할 폴더의 이름을 가져옵니다. 렌더링할 폴더의 이름(예: Inbox, Sent Item, Deleted Items 등).

Outlook 데이터 파일을 렌더링할 때, GroupDocs.Viewer는 파일에 포함된 모든 폴더(중첩 폴더 포함)의 메시지를 렌더링합니다. 이 속성을 사용하여 특정 폴더의 항목을 렌더링하십시오. 코드 예제는 이 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#render-a-specific-folder

**Returns:**
java.lang.String - 렌더링할 폴더의 이름.
### setFolder(String value) {#setFolder-java.lang.String-}
```
public final void setFolder(String value)
```


렌더링할 폴더의 이름을 설정합니다. 렌더링할 폴더의 이름(예: Inbox, Sent Item 또는 Deleted Items).

Outlook 데이터 파일을 렌더링할 때, GroupDocs.Viewer는 파일에 포함된 모든 폴더(중첩 폴더 포함)의 메시지를 렌더링합니다. 이 속성을 사용하여 특정 폴더의 항목을 렌더링하십시오. 코드 예제는 이 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#render-a-specific-folder

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String | 렌더링할 폴더의 이름. |

### getTextFilter() {#getTextFilter--}
```
public final String getTextFilter()
```


메시지를 필터링하는 데 사용되는 키워드를 가져옵니다.

이 속성을 사용하여 제목이나 본문에 특정 텍스트가 포함된 모든 메시지를 렌더링합니다. 코드 예제는 [documentation][]을 참조하십시오.


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#filter-messages

**Returns:**
java.lang.String - 키워드.
### setTextFilter(String value) {#setTextFilter-java.lang.String-}
```
public final void setTextFilter(String value)
```


메시지를 필터링하는 데 사용되는 키워드를 가져옵니다.

이 속성을 사용하여 제목이나 본문에 특정 텍스트가 포함된 모든 메시지를 렌더링합니다. 코드 예제는 [documentation][]을 참조하십시오.


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#filter-messages

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String | 키워드. |

### getAddressFilter() {#getAddressFilter--}
```
public final String getAddressFilter()
```


보낸 사람 또는 받는 사람으로 메시지를 필터링하는 데 사용되는 이메일 주소를 가져옵니다.

이 속성을 사용하여 보낸 사람\ufffd 또는 받는 사람\ufffd 주소에 특정 텍스트가 포함된 모든 메시지를 렌더링합니다. 코드 예제는 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#filter-messages

**Returns:**
java.lang.String - 메시지를 필터링하는 데 사용되는 이메일 주소.
### setAddressFilter(String value) {#setAddressFilter-java.lang.String-}
```
public final void setAddressFilter(String value)
```


보낸 사람 또는 받는 사람으로 메시지를 필터링하는 데 사용되는 이메일 주소를 설정합니다.

이 속성을 사용하여 보낸 사람\ufffd 또는 받는 사람\ufffd 주소에 특정 텍스트가 포함된 모든 메시지를 렌더링합니다. 코드 예제는 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#filter-messages

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String | 메시지를 필터링하는 데 사용되는 이메일 주소. |

### getMaxItemsInFolder() {#getMaxItemsInFolder--}
```
public final int getMaxItemsInFolder()
```


하나의 폴더에서 렌더링할 수 있는 최대 메시지 또는 항목 수를 가져옵니다.

Outlook 데이터 파일은 크기가 클 수 있으며 모든 메시지를 검색하는 데 상당한 시간이 걸릴 수 있습니다. 이 설정은 렌더링되는 메시지 또는 항목(예: 연락처 및 작업)의 최대 수를 제한합니다. 기본값은 50입니다. 값을 0으로 설정하면 모든 메시지를 렌더링합니다. 코드 예제는 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#limit-the-number-of-folder-items-to-render

**Returns:**
int - 하나의 폴더에서 렌더링될 수 있는 메시지 또는 항목의 최대 수.
### setMaxItemsInFolder(int value) {#setMaxItemsInFolder-int-}
```
public final void setMaxItemsInFolder(int value)
```


하나의 폴더에서 렌더링할 수 있는 최대 메시지 또는 항목 수를 설정합니다.

Outlook 데이터 파일은 크기가 클 수 있으며 모든 메시지를 검색하는 데 상당한 시간이 걸릴 수 있습니다. 이 설정은 렌더링되는 메시지 또는 항목(예: 연락처 및 작업)의 최대 수를 제한합니다. 기본값은 50입니다. 값을 0으로 설정하면 모든 메시지를 렌더링합니다. 코드 예제는 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#limit-the-number-of-folder-items-to-render

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int | 하나의 폴더에서 렌더링될 수 있는 메시지 또는 항목의 최대 수. |

