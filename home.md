---
title: Inici
date: 2018-10-15 12:55:00 +01:00
permalink: "/"
layout: provisional
---

<div></div>

<section>
  {%- include banner.html -%}
</section>

<div class="container mx-auto">
  <section class="py-12 px-4 text-center">
    <div class="w-full max-w-2xl mx-auto">
      <span class="text-sm font-semibold">Es molt senzill</span>
      <h2 class="text-5xl mt-2 mb-6 leading-tight font-heading">Tria entre 3 caixes</h2>
    </div>
  </section>

  <section class="py-8 px-4">
    <div class="flex flex-wrap -mx-8 text-center">
      <div class="w-full md:w-1/3 p-8 mb-4 md:mb-0">
        <div class="h-48 align-baseline">
          <img class="w-1/4 mx-auto mb-4" src="/assets/images/caixa.png" alt="caixa 4 galetes" />
        </div>
        <h3 class="text-5xl font-heading">La caixeta</h3>
        <h4 class="text-3xl font-heading">6 €</h4>
        <p class="flex-grow mt-4 mb-6 text-gray-500 leading-relaxed">Pots triar entre <strong>4 galetes</strong>.</p>
        <!--<a class="inline-block py-4 px-8 leading-none text-pink-700 bg-pink-100 hover:bg-pink-200 rounded shadow" href="#">Triar aquesta</a>-->
      </div>
      <div class="w-full md:w-1/3 p-8 mb-4 md:mb-0 md:border-l">
        <div class="h-48 align-baseline">
          <img class="w-1/3 mx-auto mb-4" src="/assets/images/caixa.png" alt="caixa 6 galetes" />
        </div>
        <h3 class="text-5xl font-heading">La caixa</h3>
        <h4 class="text-3xl font-heading">8 €</h4>
        <p class="mt-4 mb-6 text-gray-500 leading-relaxed">Pots triar entre <strong>6 galetes</strong>.</p>
        <!--<a class="inline-block py-4 px-8 leading-none text-pink-700 bg-pink-100 hover:bg-pink-200 rounded shadow" href="#">Triar aquesta</a>-->
      </div>
      <div class="w-full md:w-1/3 p-8 mb-4 md:mb-0 md:border-l">
        <div class="h-48 align-baseline">
          <img class="w-1/2 mx-auto mb-4" src="/assets/images/caixa.png" alt="caixa 8 galetes" />
        </div>
        <h3 class="text-5xl font-heading">El caixetó</h3>
        <h4 class="text-3xl font-heading">12 €</h4>
        <p class="mt-4 mb-6 text-gray-500 leading-relaxed">Pots triar entre <strong>8 galetes</strong>.</p>
        <!--<a class="inline-block py-4 px-8 leading-none text-pink-700 bg-pink-100 hover:bg-pink-200 rounded shadow" href="#">Triar aquesta</a>-->
      </div>
    </div>
  </section>

  <section class="py-12 px-4 text-center">
    <div class="w-full max-w-2xl mx-auto">
      <span class="text-sm font-semibold">A continuació...</span>
      <h2 class="text-5xl mt-2 mb-6 leading-tight font-heading">Omple la caixa amb les galetes que més et facin feliç </h2>
    </div>
  </section>

  {%- include cookies.html -%}


  {%- include form.html -%}
</div>