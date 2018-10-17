---
title: Under construction
date: 2018-10-15 12:55:00 +01:00
permalink: "/"
layout: provisional
---
{% for item in site.serveis %}
  <div class="row justify-content-lg-between align-items-lg-center py-5">
    <div class="col">
        {% capture thecycle %}{% cycle 'odd', 'even' %}{% endcapture %}
          {% if thecycle == 'odd' %}
          <div class="box box-pink">
            <h3 class="font-playfair">{{ item.title }}</h3>
            {{ item.content }}
            <div class="box-square box-square-right"></div>
          </div>
          {% else %}
            <div class="box box-blue">
              <h3 class="font-playfair">{{ item.title }}</h3>
              {{ item.content }}
              <div class="box-square box-square-left"></div>
            </div>
          {% endif %}
    </div>
  </div>
{% endfor %}