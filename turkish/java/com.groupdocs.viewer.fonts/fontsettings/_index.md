---
title: "FontSettings"
second_title: "GroupDocs.Viewer Java için API Referansı"
description: "TrueType yazı tiplerini aramak için kaynaklarla çalışmak üzere yöntemler sağlar."
type: docs
weight: 12
url: /tr/java/com.groupdocs.viewer.fonts/fontsettings/
---
**Inheritance:**
java.lang.Object
```
public class FontSettings
```

TrueType yazı tiplerini aramak için kaynaklarla çalışmak üzere yöntemler sağlar.


FontSettings sınıfı, TrueType yazı tiplerini bulmak için kaynakları belirtmek ve yönetmek amacıyla kullanılır.
GroupDocs.Viewer API'si için yazı tipi kaynaklarını ekleme ve sıfırlama yöntemleri sağlar.


Örnek kullanım:

````

 FontSettings.setFontSources(new FolderFontSource("/path/to/fonts/folder", SearchOption.ALL_FOLDERS));
 
````


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [FontSettings()](#FontSettings--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [setFontSources(FontSource[] fontSources)](#setFontSources-com.groupdocs.viewer.fonts.FontSource...-) | Belgeleri işlerken TrueType yazı tiplerini aramak için kaynakları ayarlar. |
|
|  | [resetFontSources()](#resetFontSources--) | Daha önce ayarlanmış yazı tipi kaynaklarını sıfırlar. |
|
### FontSettings() {#FontSettings--}
```
public FontSettings()
```


### setFontSources(FontSource[] fontSources) {#setFontSources-com.groupdocs.viewer.fonts.FontSource...-}
```
public static void setFontSources(FontSource[] fontSources)
```


Belgeleri işlerken TrueType yazı tiplerini aramak için kaynakları ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | fontSources | [FontSource\[\]](../../com.groupdocs.viewer.fonts/fontsource) | Ayarlanacak yazı tipi kaynakları. |
|

### resetFontSources() {#resetFontSources--}
```
public static void resetFontSources()
```


Daha önce ayarlanmış yazı tipi kaynaklarını sıfırlar.


