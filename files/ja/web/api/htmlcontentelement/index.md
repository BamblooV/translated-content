---
title: HTMLContentElement
slug: Web/API/HTMLContentElement
tags:
  - API
  - Deprecated
  - HTML DOM
  - インターフェース
  - リファレンス
translation_of: Web/API/HTMLContentElement
---
<p>{{ APIRef("Web Components") }}</p>

<p>{{Deprecated_header}}</p>

<p><code><strong>HTMLContentElement</strong></code> インターフェースは {{HTMLElement("content")}} HTML要素を表しており、<a href="/ja/docs/Web/Web_Components/Shadow_DOM">Shadow DOM</a> で使用されています。</p>

<h2 id="Properties" name="Properties">プロパティ</h2>

<p><em>このインターフェースは {{domxref("HTMLElement")}} のプロパティを継承してます。</em></p>

<dl>
 <dt>{{domxref("HTMLContentElement.select")}}</dt>
 <dd>{{ htmlattrxref("select", "content") }} というHTMLの属性を反映している {{domxref("DOMString")}} です。その値は、<code>&lt;content&gt;</code> 要素 の代わりに挿入するコンテンツを選択する、カンマで区切られたCSSセレクタのリストです。</dd>
</dl>

<h2 id="メソッド">メソッド</h2>

<p><em>このインターフェースは {{domxref("HTMLElement")}} のメソッドを継承しています。</em></p>

<dl>
 <dt>{{domxref("HTMLContentElement.getDistributedNodes()")}}</dt>
 <dd>この <code>&lt;content&gt;</code> 要素を {{glossary("distributed nodes")}} と関連づける静的な  {{domxref("NodeList")}} を返します。</dd>
</dl>

<h2 id="仕様">仕様</h2>

<p>この機能はどの標準企画によっても定義されていません。</p>

<h2 id="ブラウザ互換性">ブラウザ互換性</h2>



<p>{{Compat("api.HTMLContentElement")}}</p>

<h2 id="参照">参照</h2>

<ul>
 <li>このインターフェースを実装している {{HTMLElement("content")}} HTML 要素</li>
 <li><a href="/ja/docs/Web/Web_Components/Shadow_DOM">Shadow DOM</a></li>
</ul>

<dl>
 <dt> </dt>
</dl>