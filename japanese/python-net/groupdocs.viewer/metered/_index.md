---
title: "Metered クラス"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "従量課金（使用量に応じた支払い）ライセンスを管理します。"
type: docs
url: /ja/python-net/groupdocs.viewer/metered/
is_root: false
weight: 80
---


## Metered class

従量課金（使用量に応じた支払い）ライセンスを管理します。

Metered ライセンスは実際の使用量に基づいて課金されます（通常はページまたは
処理されたドキュメント）。公開/秘密鍵ペアは一度だけ設定します
アプリケーションの起動時に；ラッパーは使用状況を GroupDocs に報告します
バックグラウンドでライセンスサーバーへ。

Metered 型は次のメンバーを公開します：

### メソッド
| メソッド | 説明 |
| :- | :- |
| [get_consumption_credit](/viewer/python-net/groupdocs.viewer/metered/get_consumption_credit/) | 現在のキーに対する残りのメータークレジットを返します。 |
| [get_consumption_quantity](/viewer/python-net/groupdocs.viewer/metered/get_consumption_quantity/) | これまでに消費された総メーター量を返します。 |
| [set_metered_key](/viewer/python-net/groupdocs.viewer/metered/set_metered_key/#public_key-private_key) | 指定された公開/秘密鍵ペアでメーター課金を有効にします。 |

### 参照
* module [`groupdocs.viewer`](/viewer/python-net/groupdocs.viewer/)
