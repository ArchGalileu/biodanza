---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
    image: "capa-facebook.png"
    background-color: "#fabb00"
    caption: Por Ana Padilha e Rosely Nunes
    caption_url: http://biodanza.anaerosely.pt/
widget1:
  title: "Quando"
  url: '/aula-1'
  image: widget-1-302x182.jpg
  text: 'A cada quarta-feira pelas 20h30 :) anda, estás convidad@'
widget2:
  title: "Onde"
  url: '/'
  text: 'Rua da Paz 66, 5º piso, Sala 56, 4050-461 Porto - <em>PARQUE PRIVATIVO E GRATUITO</em>'
  video: '<a href="#" data-reveal-id="videoModal"><img src="http://phlow.github.io/feeling-responsive/images/start-video-feeling-responsive-302x182.jpg" width="302" height="182" alt=""/></a>'
widget3:
  title: "Com quem"
  url: '/'
  image: widget-github-303x182.jpg
  text: 'Ana Padilha e Rosely Nunes - Facilitadores de Biodanza em supervisão'
#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#
callforaction:
  url: /contato
  text: Diz-nos se vens dançar conosco :) ›
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/watch?v=XYDZTj2J9Z0" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
