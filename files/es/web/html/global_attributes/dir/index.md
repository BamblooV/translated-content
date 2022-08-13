---
title: dir
slug: Web/HTML/Global_attributes/dir
tags:
  - Atributos globales
  - HTML
  - Referencia
translation_of: Web/HTML/Global_attributes/dir
original_slug: Web/HTML/Atributos_Globales/dir
browser-compat: html.global_attributes.dir
---
<p class="note">{{HTMLSidebar("Global_attributes")}}</p>

<p>El <a href="/es/docs/Web/HTML/Atributos_Globales">atributo global </a>dir es un atributo enumerado que indica la direccionalidad del texto de los elementos . Puede tener los siguientes valores : </p>

<ul>
 <li><code>ltr ,</code> significa <em>izquierda</em> a <em>derecha</em> y es usado para los lenguajes que son escritos de izquierda a derecha ( como el Inglés ) .</li>
 <li><code>rtl , </code>significa <em>derecha</em> a <em>izquierda</em> y es usado para los lenguajes que son escritos de la derecha a la izquierda (como el árabe ) .</li>
 <li><code>auto , </code>permite al agente usuario decidir . Usa un algoritmo básico mientras parsea los caracteres dentro de un elemento hasta que encuentra un elemento con una direccionalidad fuerte , después aplica esa direccionalidad a todo el elemento .</li>
</ul>

<div class="note">
<p><span style="font-size: 14px; line-height: 21px;"><strong>Notas de uso</strong></span></p>

<p>Este atributo es obligatorio para el elemento  {{ HTMLElement("bdo") }} donde este tiene un significado semántico diferente.</p>

<ul>
 <li>Este atributo no es heredado por el elemento {{ HTMLElement("bdi") }} . Si no se establece , su valor es <code>auto</code> .</li>
 <li>Este atributo puede ser anulado por las propiedades de CSS  {{ cssxref("direction") }} y {{ cssxref("unicode-bidi") }} , si una página CSS está activa y el elemento soporta estas propiedades.</li>
 <li>Mientras la direccionalidad del texto esté semánticamente relacionada con su contenido y no con su presentación , se recomienda que los desarrolladores web usen este atributo en lugar de propiedades de CSS relacionadas ,  cuando sea posible . De esta forma , el texto se mostrará correctamente incluso en un explorador que no soporte CSS o que tenga CSS desactivado .</li>
 <li>El valor <code>auto</code> debe de ser usada para datos con una direccionalidad desconocida , com datos procedentes de la entrada de usuario , eventualmente almacenados en una base de datos .</li>
</ul>
</div>

<h2 id="Especificaciones">Especificaciones</h2>

{{Specifications}}

<h2 id="Compatibilidad_de_Navegadores">Compatibilidad de Navegadores</h2>

{{Compat}}

<h2 id="See_also">See also</h2>

<ul>
 <li><a href="/en-US/docs/Web/HTML/Global_attributes">atributos globales</a></li>
 <li>{{domxref("HTMLElement.dir")}} que refleja este atributo .</li>
</ul>