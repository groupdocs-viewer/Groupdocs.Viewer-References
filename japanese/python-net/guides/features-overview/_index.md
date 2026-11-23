---
title: "機能概要"
linkTitle: "Features overview"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "GroupDocs.Viewer for Python via .NET を使用して、ドキュメントを HTML、PDF、PNG、または JPEG にレンダリングし、テキストを抽出し、添付ファイルを一覧表示し、回転、順序変更、透かしを適用します。"
type: docs
url: /ja/python-net/guides/features-overview/
is_root: false
weight: 30
---


## Rendering Documents

GroupDocs.Viewer の *rendering* という用語は、ページ境界を保持したファイル形式にドキュメントを変換するプロセスを指します。例えば、3 ページの DOCX ファイルを HTML にレンダリングすると、結果はページごとに 1 つずつ、合計 3 つの HTML ファイルになります。[Developer Guide]() を参照して実行可能な例をご覧ください。

![Rendering diagram](https://docs.groupdocs.com/viewer/python-net/images/getting-started/features-overview/rendering.png)

### Rendering to HTML

HTML にレンダリングすることが最適なケースは次のときです：

- Build a web-based application and display document content inside a browser.
- Allow users to interact with the rendered text — select, copy, or search it.
- View document pages separately.
- Zoom in on a document without quality loss.
- Rotate, reorder, or watermark pages.

GroupDocs.Viewer for Python は、HTML リソース管理モードを 2 つ提供します：

- **HTML with external resources** — stores page resources (CSS, fonts, images) next to the HTML file so common resources are reused across pages. Reduces overall page size and speeds up loading.
- **HTML with embedded resources** — inlines every resource into the HTML file so each page is self-contained. Larger individual files but easier to distribute.

### Rendering to PNG or JPEG

PNG または JPEG にレンダリングすることが最適なケースは次のときです：

- Support any type of application (desktop, web, mobile, CLI).
- Restrict interaction with rendered text — for example, to prevent copying. You can still extract a text layer separately if you want to overlay selectable text on the image.
- View document pages separately.
- Rotate, reorder, or watermark pages.

2 つの画像形式の簡単な比較：

- **PNG** is a lossless raster format that supports full-colour images and transparency. PNG does not expose a quality setting. It is a good choice for line drawings, text, and iconic graphics at small file sizes.
- **JPEG** is a lossy compressed format whose quality can be tuned — lowering the quality removes detail and adds noise, but the file becomes smaller. JPEG is optimal for photographs and any image with a large colour range, and is a common web choice thanks to its compression ratio.

### Rendering to PDF

GroupDocs.Viewer はドキュメントを単一の PDF ファイルにレンダリングします。PDF にレンダリングすることが最適なケースは次のときです：

- Print documents.
- Send documents via email.
- Distribute all pages as a single file rather than a collection of per-page files.

## Retrieving Document Information

GroupDocs.Viewer for Python は、レンダリングせずにソースドキュメントの基本情報（ファイルタイプ、ページ数、座標付きテキストなど）を提供します。[Get Document Info]() を参照してください。

フォーマット固有の情報も利用可能です：

- **Archive** — list of folders contained in the archive.
- **CAD** — list of layers and layouts in a CAD document.
- **Email** — list of folders contained in an Outlook data file.
- **PDF** — a flag that indicates whether document printing is allowed.
- **Project Management** — project start and end dates.

### Text extraction

PNG または JPEG にレンダリングする際に、ドキュメントテキストを抽出することを選択できます。テキストは単語ごとの座標と共に返され、ページ画像上に選択可能なテキストレイヤーを重ねる際に便利です。

## Processing Attachments

GroupDocs.Viewer では、*attachments* はメール添付ファイル、PDF に埋め込まれたファイル、圧縮アーカイブ内の個々のアイテムを指します。

GroupDocs.Viewer を使用すると、一覧表示および保存が可能です：

- Email attachments.
- Files embedded in PDF documents.
- Email messages contained in Outlook and Lotus Notes data files.
- Individual files inside archive containers.

[Processing Attachments]() を参照して実行可能な例をご覧ください。

## Output Transformation

GroupDocs.Viewer for Python には、各レンダリングページを変換するオプションがセットで同梱されています：

- **Rotate pages** — change page orientation when rendering to HTML, JPG, PNG, or PDF.
- **Add a text watermark** — stamp a text watermark on every rendered page.
- **Reorder pages** — render pages in any order you prefer, including when rendering to PDF.

## Caching Results

GroupDocs.Viewer for Python はキャッシュ機能をサポートし、繰り返しのレンダリングを高速化し、アプリケーション全体の負荷を軽減します。

デフォルトでは、キャッシュはローカルディスクに保存されます。Viewer API はサードパーティのストレージ向けに実装できるキャッシュインターフェイスも提供しています — FTP、Amazon S3、Dropbox、Google Drive、Microsoft Azure、Redis、またはその他のバックエンド。
