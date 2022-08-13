---
title: Console.trace()
slug: Web/API/Console/trace
translation_of: Web/API/Console/trace
---
<div>{{APIRef("Console API")}}{{Non-standard_header}}</div>

<p>Outputs a stack trace to the <a href="/en-US/docs/Tools/Web_Console">Web Console</a>.</p>

<p>{{AvailableInWorkers}}</p>

<p>Ver <a href="/en-US/docs/Web/API/console#Stack_traces">Stack traces</a> en la documentación de {{domxref("console")}} para detalles y ejemplos.</p>

<h2 id="Sintaxis">Sintaxis</h2>

<pre class="syntaxbox">console.trace();
</pre>

<h2 id="Ejemplo">Ejemplo</h2>

<pre class="brush: js">function foo() {
  function bar() {
    console.trace();
  }
  bar();
}

foo();
</pre>

<p>La siguiente indicador será mostrado en la consola:</p>

<pre>bar
foo
&lt;anonymous&gt;</pre>

<h2 id="Especificaciones">Especificaciones</h2>

<table class="standard-table">
 <thead>
  <tr>
   <th scope="col">Specification</th>
   <th scope="col">Status</th>
   <th scope="col">Comment</th>
  </tr>
 </thead>
 <tbody>
  <tr>
   <td>{{SpecName("Console API", "#consoletraceobject--object-", "console.trace()")}}</td>
   <td>{{Spec2("Console API")}}</td>
   <td>Initial definition</td>
  </tr>
 </tbody>
</table>

<h2 id="Compatibilidad_con_el_navegador">Compatibilidad con el navegador</h2>

{{Compat("api.console.trace")}}

<h2 id="Ver_tambien">Ver tambien</h2>

<ul>
 <li><a class="external" href="http://www.opera.com/dragonfly/documentation/console/">Opera Dragonfly documentation: Console</a></li>
</ul>