---
title: "com.groupdocs.viewer.interfaces"
second_title: "GroupDocs.Viewer for Java API リファレンス"
description: "このパッケージは、出力文書とそのリソースをインスタンス化および解放するためのインターフェイスを提供します。"
type: docs
weight: 17
url: /ja/java/com.groupdocs.viewer.interfaces/
---

このパッケージは、出力文書とそのリソースをインスタンス化および解放するためのインターフェイスを提供します。


これらのインターフェイスは、出力ファイル、ページ、HTML リソースに関連するストリームと URL の作成および解放を管理するために使用されます。

このパッケージの主なインターフェイスは次のとおりです：

* [CreateFileStream](../../com.groupdocs.viewer.interfaces/createfilestream) - Represents an interface for instantiating a stream used to write output file data.
* [FileStreamFactory](../../com.groupdocs.viewer.interfaces/filestreamfactory) - Defines methods for instantiating and releasing the output file stream.
* [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) - Releases a stream that was instantiated by a method associated with the CreatePageStream interface.


これらのインターフェイスの使用方法や GroupDocs.Viewer の出力ドキュメントとリソース処理のカスタマイズに関する詳細は、
以下の [GroupDocs.Viewer Documentation](../https://docs.groupdocs.com/viewer/java/) を参照してください。



## インターフェイス

| インターフェイス | 説明 |
| --- | --- |
| [CreateFileStream](../com.groupdocs.viewer.interfaces/createfilestream) | 出力ファイルデータの書き込みに使用されるストリームを生成するインターフェイスを表します。 |
| [CreatePageStream](../com.groupdocs.viewer.interfaces/createpagestream) | 出力ページデータの書き込みに使用されるストリームを生成するインターフェイスを表します。 |
| [CreateResourceStream](../com.groupdocs.viewer.interfaces/createresourcestream) | 出力 HTML リソースデータの書き込みに使用されるストリームを生成するインターフェイスを表します。 |
| [CreateResourceUrl](../com.groupdocs.viewer.interfaces/createresourceurl) | HTML リソースの URL を作成するインターフェイスを表します。 |
| [FileReader](../com.groupdocs.viewer.interfaces/filereader) | ファイルストリームを読み取るためのインターフェイスを宣言します。 |
| [FileStreamFactory](../com.groupdocs.viewer.interfaces/filestreamfactory) | 出力ファイルストリームの生成と解放に必要なメソッドを定義します。 |
| [PageStreamFactory](../com.groupdocs.viewer.interfaces/pagestreamfactory) | 出力ページストリームの生成と解放に必要なメソッドを定義します。 |
| [ReleaseFileStream](../com.groupdocs.viewer.interfaces/releasefilestream) | CreateFileStream インターフェイスに関連付けられたメソッドによって生成されたインターフェイスを解放します。 |
| [ReleasePageStream](../com.groupdocs.viewer.interfaces/releasepagestream) | CreatePageStream インターフェイスに関連付けられたメソッドによって生成されたストリームを解放します。 |
| [ReleaseResourceStream](../com.groupdocs.viewer.interfaces/releaseresourcestream) | CreateResourceStream インターフェイスに関連付けられたメソッドによって生成されたストリームを解放します。 |
| [ResourceStreamFactory](../com.groupdocs.viewer.interfaces/resourcestreamfactory) | リソース URL の作成、出力 HTML リソースストリームの生成および解放に必要なメソッドを定義します。 |
