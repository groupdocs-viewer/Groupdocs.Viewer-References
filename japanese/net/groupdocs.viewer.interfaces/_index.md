---
title: "GroupDocs.Viewer.Interfaces"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "この名前空間は、出力ドキュメントとそのリソースをインスタンス化および解放するためのインターフェイスを提供します。"
type: docs
weight: 60
url: /ja/net/groupdocs.viewer.interfaces/
---

この名前空間は、出力ドキュメントとそのリソースをインスタンス化および解放するためのインターフェイスを提供します。

## クラス

| クラス | 説明 |
| --- | --- |
| [CreateFileStream](./createfilestream) | 出力ファイルデータを書き込むために使用されるストリームをインスタンス化するメソッドを表します。 |
| [CreatePageStream](./createpagestream) | 出力ページデータを書き込むために使用されるストリームをインスタンス化するメソッドを表します。 |
| [CreateResourceStream](./createresourcestream) | 出力HTMLリソースデータを書き込むために使用されるストリームをインスタンス化するメソッドを表します。 |
| [CreateResourceUrl](./createresourceurl) | HTMLリソースのURLを作成するメソッドを表します。 |
| [ReleaseFileStream](./releasefilestream) | [`CreateFileStream`](../groupdocs.viewer.interfaces/createfilestream) デリゲートに関連付けられたメソッドによってインスタンス化されたストリームを解放します。 |
| [ReleasePageStream](./releasepagestream) | [`CreatePageStream`](../groupdocs.viewer.interfaces/createpagestream) デリゲートに関連付けられたメソッドによってインスタンス化されたストリームを解放します。 |
| [ReleaseResourceStream](./releaseresourcestream) | [`CreateResourceStream`](../groupdocs.viewer.interfaces/createresourcestream) デリゲートに関連付けられたメソッドによってインスタンス化されたストリームを解放します。 |
## インターフェイス

| インターフェイス | 説明 |
| --- | --- |
| [IFileStreamFactory](./ifilestreamfactory) | 出力ファイルストリームのインスタンス化と解放に必要なメソッドを定義します。 |
| [IPageStreamFactory](./ipagestreamfactory) | 出力ページストリームのインスタンス化と解放に必要なメソッドを定義します。 |
| [IResourceStreamFactory](./iresourcestreamfactory) | リソースURLの作成、出力HTMLリソースストリームのインスタンス化と解放に必要なメソッドを定義します。 |

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
