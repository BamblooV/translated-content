---
title: URL
slug: Web/API/URL
tags:
  - API
  - Experimental
  - Expérimental(2)
  - NeedsTranslation
  - TopicStub
  - URL API
translation_of: Web/API/URL
---
<div>{{ApiRef("URL API")}} {{SeeCompatTable}}</div>

<p>La interfaz <strong><code>URL</code></strong> representa a un objeto que provee métodos estáticos para crear objetos URL.</p>

<p>When using a user agent where no constructor has been implemented yet, it is possible to access such an object using the {{domxref("Window.URL")}} properties (prefixed with Webkit-based browser as <code>Window.webkitURL</code>).</p>

<p>{{AvailableInWorkers}}</p>

<h2 id="Properties">Properties</h2>

<dl>
 <dt>{{domxref("URL.href")}}</dt>
 <dd>Is a {{domxref("DOMString")}} containing the whole URL.</dd>
 <dt>{{domxref("URL.protocol")}}</dt>
 <dd>Is a {{domxref("DOMString")}} containing the protocol scheme of the URL, including the final <code>':'</code>.</dd>
 <dt>{{domxref("URL.host")}}</dt>
 <dd>Is a {{domxref("DOMString")}} containing the host, that is the <em>hostname</em>, a <code>':'</code>, and the <em>port</em> of the URL.</dd>
 <dt>{{domxref("URL.hostname")}}</dt>
 <dd>Is a {{domxref("DOMString")}} containing the domain of the URL.</dd>
 <dt>{{domxref("URL.port")}}</dt>
 <dd>Is a {{domxref("DOMString")}} containing the port number of the URL.</dd>
 <dt>{{domxref("URL.pathname")}}</dt>
 <dd>Is a {{domxref("DOMString")}} containing an initial <code>'/'</code> followed by the path of the URL.</dd>
 <dt>{{domxref("URL.search")}}</dt>
 <dd>Is a {{domxref("DOMString")}} containing a <code>'?'</code> followed by the parameters of the URL.</dd>
 <dt>{{domxref("URL.hash")}}</dt>
 <dd>Is a {{domxref("DOMString")}} containing a <code>'#'</code> followed by the fragment identifier of the URL.</dd>
 <dt>{{domxref("URL.username")}}</dt>
 <dd>Is a {{domxref("DOMString")}} containing the username specified before the domain name.</dd>
 <dt>{{domxref("URL.password")}}</dt>
 <dd>Is a {{domxref("DOMString")}} containing the password specified before the domain name.</dd>
 <dt>{{domxref("URL.origin")}} {{readonlyInline}}</dt>
 <dd>Returns a {{domxref("DOMString")}} containing the origin of the URL, that is its scheme, its domain and its port.</dd>
</dl>

<dl>
 <dt>{{domxref("URL.searchParams")}}</dt>
 <dd>Returns a {{domxref("URLSearchParams")}} object allowing to access the GET query arguments contained in the URL.</dd>
</dl>

<h2 id="Constructor">Constructor</h2>

<dl>
 <dt>{{domxref("URL.URL", "URL()")}}</dt>
 <dd>Creates and return a <code>URL</code> object composed from the given parameters.</dd>
</dl>

<h2 id="Methods">Methods</h2>

<p><em>The <code>URL</code> interface implements methods defined in {{domxref("URLUtils")}}.</em></p>

<dl>
 <dt>{{domxref("URLUtils.toString()")}}</dt>
 <dd>Returns a {{domxref("DOMString")}} containing the whole URL. It is a synonym for {{domxref("URLUtils.href")}}, though it can't be used to modify the value.</dd>
</dl>

<h2 id="Static_methods">Static methods</h2>

<dl>
 <dt>{{domxref("URL.createObjectURL()")}}</dt>
 <dd>Returns a {{domxref("DOMString")}} containing a unique blob URL, that is a URL with <code>blob:</code> as its scheme, followed by an opaque string uniquely identifying the object in the browser.</dd>
 <dt>{{domxref("URL.revokeObjectURL()")}}</dt>
 <dd>Revokes an object URL previously created using {{domxref("URL.createObjectURL()")}}.</dd>
</dl>

<h2 id="Specifications">Specifications</h2>

<table class="standard-table">
 <tbody>
  <tr>
   <th scope="col">Specification</th>
   <th scope="col">Status</th>
   <th scope="col">Comment</th>
  </tr>
  <tr>
   <td>{{SpecName('File API', '#creating-revoking', 'URL')}}</td>
   <td>{{Spec2('File API')}}</td>
   <td>Added the static methods <code>URL.createObjectURL()</code> and <code>URL.revokeObjectURL</code><code>()</code>.</td>
  </tr>
  <tr>
   <td>{{SpecName('URL', '#api', 'Node')}}</td>
   <td>{{Spec2('URL')}}</td>
   <td>Initial definition (implements <code>URLUtils</code>).</td>
  </tr>
 </tbody>
</table>

<h2 id="Browser_compatibility">Browser compatibility</h2>

{{Compat("api.URL")}}

<h2 id="See_also">See also</h2>

<ul>
 <li>Property allowing to get such an object: {{domxref("Window.URL")}}.</li>
 <li><a href="/en-US/docs/Components.utils.importGlobalProperties">Components.utils.importGlobalProperties</a></li>
</ul>