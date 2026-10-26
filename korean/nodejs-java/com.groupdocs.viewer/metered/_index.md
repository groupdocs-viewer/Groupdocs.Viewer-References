---
title: "Metered"
second_title: "Node.js용 GroupDocs.Viewer (Java) API 레퍼런스"
description: "GroupDocs.Viewer 구성 요소에 계량식 라이선스를 적용하기 위한 메서드를 제공합니다."
type: docs
weight: 11
url: /ko/nodejs-java/com.groupdocs.viewer/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

GroupDocs.Viewer 구성 요소에 계량식 라이선스를 적용하기 위한 메서드를 제공합니다.

Metered 라이선스는 전통적인 서버당 또는 개발자당 라이선스 대신 처리된 문서 페이지 수를 기준으로 GroupDocs.Viewer 사용량을 동적으로 모니터링하고 제어할 수 있게 해줍니다. 이 유연한 라이선스 모델은 문서 처리 요구 사항이 시간에 따라 변동하거나 사용한 만큼만 비용을 지불하고자 할 때에 적합합니다.

예시 사용법:

```

 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 // Perform document processing operations using GroupDocs.Viewer
 // ...
 
```
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Metered()](#Metered--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | 처리된 메가바이트(MB) 양을 검색합니다. |
| [getConsumptionCredit()](#getConsumptionCredit--) | 소비된 크레딧 수를 검색합니다. |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Metered 키를 사용하여 제품을 활성화합니다. |
### Metered() {#Metered--}
```
public Metered()
```


### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


처리된 메가바이트(MB) 양을 검색합니다.

이 메서드는 구성 요소가 처리한 총 MB 양을 반환합니다.

**Example:**

```

 String publicKey = "Public Key";
 String privateKey = "Private Key";
 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 double mbProcessed = Metered.getConsumptionQuantity();
 
```

**Returns:**
double - 처리된 MB 양.
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```


소비된 크레딧 수를 검색합니다.

이 메서드는 구성 요소가 소비한 총 크레딧 수를 반환합니다.

**Example:**

```

 String publicKey = "Public Key";
 String privateKey = "Private Key";
 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 double creditsConsumed = Metered.getConsumptionCredit();
 
```

**Returns:**
double - 소비된 크레딧 수.
### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public final void setMeteredKey(String publicKey, String privateKey)
```


Metered 키를 사용하여 제품을 활성화합니다.

다음 예제는 Metered 키를 사용하여 제품을 활성화하는 방법을 보여줍니다.

**Example:**

```

 String publicKey = "Public Key";
 String privateKey = "Private Key";
 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 
```

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| publicKey | java.lang.String | 공개 키. |
| privateKey | java.lang.String | 개인 키. |

