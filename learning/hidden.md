---
layout: default
title: col(hidden)
permalink: /learning/hidden/
---

<div id="css">
  <div class="dn-browser">
    <div class="dn-browser-header">
      <div class="dn-browser-button">
        <div class="wrap xl-auto">
          <div class="col"><div class="dn-browser-button__circle"></div></div>
          <div class="col"><div class="dn-browser-button__circle"></div></div>
          <div class="col"><div class="dn-browser-button__circle"></div></div>
        </div>
      </div>
      <div class="dn-style--title">
        col(<span>hidden</span>) (css)
      </div>
      <a href="/" class="dn-logo"><img src="/img/flexiblegs-logo-white.png" alt=""></a>
    </div>
    <div class="dn-browser-body">
      <div class="dn-browser-body__pre">
        <pre class="is-not-compiled"><div class="dn-tag dn-tag--gray dn-tag--top dn-tag--button">view compiled</div><div class="dn-tag dn-tag--gray dn-tag--bottom">html</div><!--
          -->&lt;div class="wrap"&gt;<br/><!--
          -->  &lt;div class="col xl-1-3"&gt;01&lt;/div&gt;<br/><!--
          -->  &lt;div class="col xl-1-3"&gt;02&lt;/div&gt;<br/><!--
          -->  &lt;div class="col xl-1-3 <span>xl-hidden</span>"&gt;03&lt;/div&gt;<br/><!--
          -->&lt;/div&gt;<!--
        --></pre>
        <pre class="is-compiled"><div class="dn-tag dn-tag--black dn-tag--top dn-tag--button">close</div><!--
          --><span>wrap > col(hidden)</span><br/><!--
          -->  display: none;<!--
        --></pre>
      </div>
      <div class="dn-browser-body__item">
        <div class="wrap dn-style--wrap">
          <div class="col xl-1-3"><div class="dn-style--col">01</div></div>
          <div class="col xl-1-3"><div class="dn-style--col">02</div></div>
          <div class="col xl-1-3 xl-hidden"><div class="dn-style--col">03</div></div>
        </div>
      </div>
      <div class="dn-browser-footer">
        <div class="wrap xl-gutter-24 xl-outside-24 xl-right xl-auto">
          <div class="col">
            <a href="http://codepen.io/dnomak/pen/xGQMzy?editors=110" class="dn-button dn-button--link dn-button--right">
              http://codepen.io/dnomak/pen/xGQMzy
            </a>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
