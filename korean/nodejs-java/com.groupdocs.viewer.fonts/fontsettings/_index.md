---
title: "FontSettings"
second_title: "Node.js용 GroupDocs.Viewer (Java) API 레퍼런스"
description: "TrueType 글꼴을 찾기 위한 소스와 작업하기 위한 메서드를 제공합니다."
type: docs
weight: 12
url: /ko/nodejs-java/com.groupdocs.viewer.fonts/fontsettings/
---
**Inheritance:**
java.lang.Object
```
public class FontSettings
```

TrueType 글꼴을 찾기 위한 소스와 작업하기 위한 메서드를 제공합니다.

FontSettings 클래스는 TrueType 글꼴을 찾기 위한 소스를 지정하고 관리하는 데 사용됩니다. 이 클래스는 GroupDocs.Viewer API용 글꼴 소스를 추가하고 재설정하는 메서드를 제공합니다.

예시 사용법:

```

 FontSettings.setFontSources(new FolderFontSource("/path/to/fonts/folder", SearchOption.ALL_FOLDERS));
 
```
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [FontSettings()](#FontSettings--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [setFontSources(FontSource[] fontSources)](#setFontSources-com.groupdocs.viewer.fonts.FontSource...-) | 문서를 렌더링할 때 TrueType 글꼴을 찾을 소스를 설정합니다. |
| [resetFontSources()](#resetFontSources--) | 이전에 설정된 글꼴 소스를 재설정합니다. |
### FontSettings() {#FontSettings--}
```
public FontSettings()
```


### setFontSources(FontSource[] fontSources) {#setFontSources-com.groupdocs.viewer.fonts.FontSource...-}
```
public static void setFontSources(FontSource[] fontSources)
```


문서를 렌더링할 때 TrueType 글꼴을 찾을 소스를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fontSources | [FontSource\[\]](../../com.groupdocs.viewer.fonts/fontsource) | 설정할 글꼴 소스입니다. |

### resetFontSources() {#resetFontSources--}
```
public static void resetFontSources()
```


이전에 설정된 글꼴 소스를 재설정합니다.

