# 電子公告ための専用ページ

複雑な構造ではなく、シングルページおよび単一htmlファイルでできたもの。

URL: [年度決算報告専用ページ - HYL株式会社](https://hyljp.github.io/ir/)



更新ルール

- PDFファイルのアプロード

  hylwebsite\ir\docに貸借対照表のPFDファイルをアップロードする。

  ファイルのフォーマットは以下通りです。

  HYL_Co_Balance_Sheet_YYYY.pdf

  

- htmlファイルの修正

```html
    <li>
        <h3>第1期 2025年</h3>
        <a href="<a href="doc/HYL_Co_Balance_Sheet_YYYY.pdf">貸借対照表</a>
    </li>
```

  

タイトルとリンクの更新だけで終わる





以上

2025年2月21日