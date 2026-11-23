---
title: "기능 개요"
linkTitle: "Features overview"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: ".NET을 통해 Python용 GroupDocs.Viewer를 사용하여 문서를 HTML, PDF, PNG 또는 JPEG로 렌더링하고, 텍스트를 추출하며, 첨부 파일을 나열하고, 회전, 순서 변경 및 워터마크를 적용합니다."
type: docs
url: /ko/python-net/guides/features-overview/
is_root: false
weight: 30
---


## Rendering Documents

GroupDocs.Viewer에서 *rendering*이라는 용어는 페이지 경계를 유지하는 파일 형식으로 문서를 변환하는 과정을 설명합니다. 예를 들어, 3페이지 DOCX 파일을 HTML로 렌더링하면 결과는 페이지당 하나씩 총 세 개의 HTML 파일이 됩니다. 실행 가능한 예제는 [Developer Guide]()를 참조하십시오.

![Rendering diagram](https://docs.groupdocs.com/viewer/python-net/images/getting-started/features-overview/rendering.png)

### Rendering to HTML

HTML로 렌더링하는 것이 다음과 같은 경우에 가장 적합합니다:

- Build a web-based application and display document content inside a browser.
- Allow users to interact with the rendered text — select, copy, or search it.
- View document pages separately.
- Zoom in on a document without quality loss.
- Rotate, reorder, or watermark pages.

Python용 GroupDocs.Viewer는 두 가지 HTML 리소스 관리 모드를 제공합니다:

- **HTML with external resources** — stores page resources (CSS, fonts, images) next to the HTML file so common resources are reused across pages. Reduces overall page size and speeds up loading.
- **HTML with embedded resources** — inlines every resource into the HTML file so each page is self-contained. Larger individual files but easier to distribute.

### Rendering to PNG or JPEG

PNG 또는 JPEG로 렌더링하는 것이 다음과 같은 경우에 가장 적합합니다:

- Support any type of application (desktop, web, mobile, CLI).
- Restrict interaction with rendered text — for example, to prevent copying. You can still extract a text layer separately if you want to overlay selectable text on the image.
- View document pages separately.
- Rotate, reorder, or watermark pages.

두 이미지 형식에 대한 간단한 비교:

- **PNG** is a lossless raster format that supports full-colour images and transparency. PNG does not expose a quality setting. It is a good choice for line drawings, text, and iconic graphics at small file sizes.
- **JPEG** is a lossy compressed format whose quality can be tuned — lowering the quality removes detail and adds noise, but the file becomes smaller. JPEG is optimal for photographs and any image with a large colour range, and is a common web choice thanks to its compression ratio.

### Rendering to PDF

GroupDocs.Viewer는 문서를 단일 PDF 파일로 렌더링합니다. PDF로 렌더링하는 것이 다음과 같은 경우에 가장 적합합니다:

- Print documents.
- Send documents via email.
- Distribute all pages as a single file rather than a collection of per-page files.

## Retrieving Document Information

Python용 GroupDocs.Viewer는 렌더링 없이도 원본 문서에 대한 기본 정보(파일 유형, 페이지 수, 좌표가 포함된 텍스트 등)를 제공합니다. 자세한 내용은 [Get Document Info]()를 참조하십시오.

형식별 정보도 제공됩니다:

- **Archive** — list of folders contained in the archive.
- **CAD** — list of layers and layouts in a CAD document.
- **Email** — list of folders contained in an Outlook data file.
- **PDF** — a flag that indicates whether document printing is allowed.
- **Project Management** — project start and end dates.

### Text extraction

PNG 또는 JPEG로 렌더링할 때 문서 텍스트를 추출하도록 선택할 수 있습니다. 텍스트는 단어별 좌표와 함께 반환되며, 페이지 이미지 위에 선택 가능한 텍스트 레이어를 오버레이할 때 유용합니다.

## Processing Attachments

GroupDocs.Viewer에서 *attachments*는 이메일 첨부 파일, PDF에 포함된 파일 및 압축된 아카이브 내부의 개별 항목을 포함합니다.

GroupDocs.Viewer를 사용하면 다음을 나열하고 저장할 수 있습니다:

- Email attachments.
- Files embedded in PDF documents.
- Email messages contained in Outlook and Lotus Notes data files.
- Individual files inside archive containers.

실행 가능한 예제는 [Processing Attachments]()를 참조하십시오.

## Output Transformation

Python용 GroupDocs.Viewer는 각 렌더링된 페이지를 변환하기 위한 옵션 세트를 제공합니다:

- **Rotate pages** — change page orientation when rendering to HTML, JPG, PNG, or PDF.
- **Add a text watermark** — stamp a text watermark on every rendered page.
- **Reorder pages** — render pages in any order you prefer, including when rendering to PDF.

## Caching Results

Python용 GroupDocs.Viewer는 캐싱을 지원하여 반복 렌더링을 가속화하고 애플리케이션의 전체 부하를 줄입니다.

기본적으로 캐시는 로컬 디스크에 저장됩니다. 뷰어 API는 또한 서드파티 저장소(FTP, Amazon S3, Dropbox, Google Drive, Microsoft Azure, Redis 또는 기타 백엔드)를 위해 구현할 수 있는 캐시 인터페이스를 제공합니다.
