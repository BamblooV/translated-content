---
title: Document.scripts
slug: Web/API/Document/scripts
translation_of: Web/API/Document/scripts
---
<div>{{APIRef("DOM")}}</div>

<p>Devuelve una lista de elementos {{HTMLElement("script")}} ubicados en el documento. El objeto devuelto es una colección {{domxref("HTMLCollection")}}.</p>

<h2 id="Syntax" name="Syntax">Sintáxis</h2>

<pre class="syntaxbox"><code>var <em>scriptList</em></code> = document.scripts;
</pre>

<p>El objeto <code>scriptList</code> devuelto es una {{domxref("HTMLCollection")}}. Se puede utilizar como un array corriente para acceder a sus elementos.</p>

<h2 id="Ejemplo">Ejemplo</h2>

<p>Este ejemplo busca demostrar la existencia de objetos {{HTMLElement("script")}} en el documento.</p>

<pre class="brush:js">var scripts = document.scripts;

if (scripts.length) {
  alert("This page has scripts!");
}
</pre>

<h2 id="Specification" name="Specification">Compatibilidad de navegadores</h2>

{{Compat("api.Document.scripts")}}

<h2 id="Specification" name="Specification"> </h2>

<h2 id="Specification" name="Specification">Especificaciones</h2>

<ul>
 <li>{{spec("http://www.whatwg.org/specs/web-apps/current-work/multipage/dom.html#dom-document-scripts", "DOM: document scripts")}}</li>
</ul>