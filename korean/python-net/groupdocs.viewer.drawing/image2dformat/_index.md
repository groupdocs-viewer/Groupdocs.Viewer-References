---
title: "Image2DFormat 클래스"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "가장 일반적인 2D 이미지 형식을 나타내며, 래스터 및 벡터 형식을 모두 지원합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.drawing/image2dformat/
is_root: false
weight: 60
---


## Image2DFormat class

가장 일반적인 2D 이미지 형식을 나타내며, 래스터 및 벡터 형식을 모두 지원합니다.

Image2DFormat 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/__init__/) |  |

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/equals/#other) | 이 인스턴스가 지정된 [`Image2DFormat`](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/) 인스턴스와 동일한지 여부를 결정합니다. |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/equals/#obj) | 이 인스턴스가 지정된 객체와 같은지 여부를 결정합니다. 해당 객체는 다른 [`Image2DFormat`](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/) 인스턴스로 가정됩니다. |
| [equals_image_2d_format](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/equals_image_2d_format/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/equals_object/) |  |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/get_hash_code/) | 이 특정 인스턴스에 대한 불변 숫자인 해시 코드를 반환합니다. |
| [parse_from_filename_with_extension](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/parse_from_filename_with_extension/#filename) | 지정된 파일 이름에서 추출한 파일 확장자에 해당하는 Image2DFormat 값을 반환합니다. |
| [parse_from_mime](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/parse_from_mime/#mime_code) | 지정된 MIME 코드에 해당하는 [`Image2DFormat`](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/) 값을 반환합니다. |
| [to_string](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/to_string/) | [`Image2DFormat.name`](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/name/) 속성을 반환합니다. |

### 속성
| 속성 | 설명 |
| :- | :- |
| [file_extension](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/file_extension/) | 특정 이미지 유형의 파일 확장자(앞에 점 문자 없이)를 소문자로 표시합니다. |
| [is_vector](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/is_vector/) | 형식은 벡터(`True`) 또는 래스터(`False`)입니다. |
| [mime_code](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/mime_code/) | 특정 이미지 유형의 MIME 코드를 문자열로 나타냅니다. Undefined 유형의 경우 문자열 'unsefined'를 반환합니다. |
| [name](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/name/) | 이 이미지 형식의 공식 이름입니다. |

### 필드
| 필드 | 설명 |
| :- | :- |
| [UNDEFINED](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/undefined/) | 정의되지 않은 이미지 유형 - 일반적으로 발생하지 않아야 하는 특수 값 |
| [JPEG](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/jpeg/) | JPEG 이미지 유형 |
| [PNG](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/png/) | PNG 이미지 유형 |
| [BMP](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/bmp/) | BMP 이미지 유형 |
| [GIF](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/gif/) | GIF 이미지 유형 |
| [ICON](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/icon/) | ICON 이미지 유형 |
| [SVG](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/svg/) | SVG 벡터 이미지 유형 |
| [WMF](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/wmf/) | WMF (Windows MetaFile) 벡터 이미지 유형 |
| [EMF](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/emf/) | EMF (Enhanced MetaFile) 벡터 이미지 유형 |
| [TIFF](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/tiff/) | TIFF (Tagged Image File Format) 래스터 이미지 유형 |

### 참고
* module [`groupdocs.viewer.drawing`](/viewer/python-net/groupdocs.viewer.drawing/)
