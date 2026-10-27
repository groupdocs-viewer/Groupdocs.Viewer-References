---
title: "Лицензия"
second_title: "GroupDocs.Viewer для Node.js через Java API Reference"
description: "Предоставляет методы лицензирования компонента и разблокировки его полной функциональности."
type: docs
weight: 10
url: /ru/nodejs-java/com.groupdocs.viewer/license/
---
**Inheritance:**
java.lang.Object
```
public class License
```

Предоставляет методы лицензирования компонента и разблокировки его полной функциональности.

Класс License позволяет вам применить действительную лицензию к компоненту GroupDocs.Viewer, позволяя использовать все функции и убрать любые ограничения оценки.

Пример использования:

```

 License license = new License();
 license.setLicense("path/to/license/file.lic");
 
```
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [License()](#License--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [resetLicense()](#resetLicense--) |  |
| [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) | Лицензирует компонент. |
| [setLicense(Path licensePath)](#setLicense-java.nio.file.Path-) | Лицензирует компонент. |
| [setLicense(String licensePath)](#setLicense-java.lang.String-) | Лицензирует компонент. |
| [setLicense(URL licenseUri)](#setLicense-java.net.URL-) | Лицензирует компонент. |
| [isLicensed()](#isLicensed--) |  |
### License() {#License--}
```
public License()
```


### resetLicense() {#resetLicense--}
```
public static void resetLicense()
```




### setLicense(InputStream licenseStream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream licenseStream)
```


Лицензирует компонент.

Следующий пример демонстрирует, как установить лицензию, передавая InputStream файла лицензии.

Для получения дополнительной информации о лицензировании, пожалуйста, обратитесь к [GroupDocs Licensing FAQ][]. Вы также можете найти подробную информацию о лицензировании GroupDocs.Viewer в документации [Evaluation Limitations and Licensing][].

**Example:**

```

 FileInputStream licenseStream = new FileInputStream("LicenseFile.lic");
 License license = new License();
 license.setLicense(licenseStream);
 
```


[GroupDocs Licensing FAQ]: https://purchase.groupdocs.com/faqs/licensing
[Evaluation Limitations and Licensing]: https://docs.groupdocs.com/display/viewernet/Evaluation+Limitations+and+Licensing+of+GroupDocs.Viewer

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| licenseStream | java.io.InputStream | Поток лицензии. |

### setLicense(Path licensePath) {#setLicense-java.nio.file.Path-}
```
public final void setLicense(Path licensePath)
```


Лицензирует компонент.

Устанавливает лицензию для компонента, используя указанный путь к лицензии.

**Note:** This method should be called before using any functionality of the component.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| licensePath | java.nio.file.Path | Путь к лицензии. |

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String licensePath)
```


Лицензирует компонент.

Этот метод следует вызвать перед использованием любой функциональности.

Пример использования:

```

 String licensePath = "GroupDocs.Viewer.lic";
 License license = new License();
 license.setLicense(licensePath);
 
```

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| licensePath | java.lang.String | Путь к лицензии или URL. |

### setLicense(URL licenseUri) {#setLicense-java.net.URL-}
```
public void setLicense(URL licenseUri)
```


Лицензирует компонент.

Этот метод следует вызвать перед использованием любой функциональности.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| licenseUri | java.net.URL | URI лицензии. |

### isLicensed() {#isLicensed--}
```
public final boolean isLicensed()
```




**Returns:**
boolean
