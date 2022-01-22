---
title: 'Feature-Policy: camera'
slug: Web/HTTP/Headers/Feature-Policy/camera
tags:
  - Feature-Policy
  - HTTP
  - リファレンス
  - camera
  - ディレクティブ
  - 機能ポリシー
translation_of: Web/HTTP/Headers/Feature-Policy/camera
---
{{HTTPSidebar}} {{SeeCompatTable}}

<span class="seoSummary">HTTP の {{HTTPHeader("Feature-Policy")}} ヘッダーにおける `camera` ディレクティブは、現在の文書が動画入力機器を使用することを許可するかどうかを制御します。このポリシーが有効であれば、 {{domxref("MediaDevices.getUserMedia()")}} から返却された {{jsxref("Promise")}} が `NotAllowedError` で拒否されます。</span>

## 構文

<pre class="syntaxbox">Feature-Policy: camera &lt;allowlist&gt;;</pre>

 <dt>&lt;allowlist&gt;</dt>
  - : この機能を許可するオリジンのリストです。 [`Feature-Policy`](/ja/docs/Web/HTTP/Headers/Feature-Policy#syntax) を参照してください。

## 仕様書

<table class="standard-table">
 <thead>
  <tr>
   <th scope="col">仕様書</th>
   <th scope="col">状態</th>
   <th scope="col">備考</th>
  </tr>
 </thead>
 <tbody>
  <tr>
   <td>{{SpecName('Feature Policy')}}</td>
   <td>{{Spec2('Feature Policy')}}</td>
   <td>初回定義</td>
  </tr>
 </tbody>
</table>

<h2 id="Browser_compatibility" name="Browser_compatibility">ブラウザーの対応</h2>

{{Compat("http.headers.Feature-Policy.camera")}}

## 関連情報

- {{HTTPHeader("Feature-Policy")}} ヘッダー
- [機能ポリシー](/ja/docs/Web/HTTP/Feature_Policy)
- [機能ポリシーの使用](/ja/docs/Web/HTTP/Feature_Policy/Using_Feature_Policy)