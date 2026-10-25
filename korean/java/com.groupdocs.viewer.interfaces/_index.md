---
title: "com.groupdocs.viewer.interfaces"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "이 패키지는 출력 문서와 그 리소스를 인스턴스화하고 해제하기 위한 인터페이스를 제공합니다."
type: docs
weight: 17
url: /ko/java/com.groupdocs.viewer.interfaces/
---

이 패키지는 출력 문서와 그 리소스를 인스턴스화하고 해제하기 위한 인터페이스를 제공합니다.


이 인터페이스들은 출력 파일, 페이지 및 HTML 리소스와 관련된 스트림 및 URL의 생성 및 해제를 관리하는 데 사용됩니다.

이 패키지의 주요 인터페이스는 다음과 같습니다:

* [CreateFileStream](../../com.groupdocs.viewer.interfaces/createfilestream) - Represents an interface for instantiating a stream used to write output file data.
* [FileStreamFactory](../../com.groupdocs.viewer.interfaces/filestreamfactory) - Defines methods for instantiating and releasing the output file stream.
* [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) - Releases a stream that was instantiated by a method associated with the CreatePageStream interface.


GroupDocs.Viewer에서 이러한 인터페이스를 사용하고 출력 문서 및 리소스 처리를 사용자 지정하는 방법에 대한 자세한 내용은
다음 [GroupDocs.Viewer Documentation](../https://docs.groupdocs.com/viewer/java/)을 참조하십시오.



## 인터페이스

| 인터페이스 | 설명 |
| --- | --- |
| [CreateFileStream](../com.groupdocs.viewer.interfaces/createfilestream) | 출력 파일 데이터를 쓰는 데 사용되는 스트림을 인스턴스화하는 인터페이스를 나타냅니다. |
| [CreatePageStream](../com.groupdocs.viewer.interfaces/createpagestream) | 출력 페이지 데이터를 쓰는 데 사용되는 스트림을 인스턴스화하는 인터페이스를 나타냅니다. |
| [CreateResourceStream](../com.groupdocs.viewer.interfaces/createresourcestream) | 출력 HTML 리소스 데이터를 쓰는 데 사용되는 스트림을 인스턴스화하는 인터페이스를 나타냅니다. |
| [CreateResourceUrl](../com.groupdocs.viewer.interfaces/createresourceurl) | HTML 리소스에 대한 URL을 생성하는 인터페이스를 나타냅니다. |
| [FileReader](../com.groupdocs.viewer.interfaces/filereader) | 파일 스트림을 읽기 위한 인터페이스를 선언합니다. |
| [FileStreamFactory](../com.groupdocs.viewer.interfaces/filestreamfactory) | 출력 파일 스트림을 인스턴스화하고 해제하는 데 필요한 메서드를 정의합니다. |
| [PageStreamFactory](../com.groupdocs.viewer.interfaces/pagestreamfactory) | 출력 페이지 스트림을 인스턴스화하고 해제하는 데 필요한 메서드를 정의합니다. |
| [ReleaseFileStream](../com.groupdocs.viewer.interfaces/releasefilestream) | CreateFileStream 인터페이스와 연결된 메서드에 의해 인스턴스화된 인터페이스를 해제합니다. |
| [ReleasePageStream](../com.groupdocs.viewer.interfaces/releasepagestream) | CreatePageStream 인터페이스와 연결된 메서드에 의해 인스턴스화된 스트림을 해제합니다. |
| [ReleaseResourceStream](../com.groupdocs.viewer.interfaces/releaseresourcestream) | CreateResourceStream 인터페이스와 연결된 메서드에 의해 인스턴스화된 스트림을 해제합니다. |
| [ResourceStreamFactory](../com.groupdocs.viewer.interfaces/resourcestreamfactory) | 리소스 URL을 생성하고, 출력 HTML 리소스 스트림을 인스턴스화 및 해제하는 데 필요한 메서드를 정의합니다. |
