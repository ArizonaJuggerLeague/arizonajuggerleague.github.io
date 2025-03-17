---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: HomeBanner1.png
widget1:
  title: "Dust Bowl Masters 2026"
  url: '/dustbowlmasters/'
  image: 'DustBowlPoster2.png'
  text: 'Introducing our premier tournament with a $2000 cash prize, Dust Bowl Masters 2026!<br/>Click here for more information!'
widget2:
  title: "What is Jugger?"
  url: '/aboutjugger/'
  image: 'DustBowlPoster2.png'
  text: 'New to Jugger? Start here!'
widget3:
  title: "About the League"
  url: '/aboutus/'
  image: 'DustBowlPoster1.png'
  text: 'Our mission and purpose as a competitive, Arizona-based Jugger league.'

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
#callforaction:
#  url: https://tinyletter.com/feeling-responsive
#  text: Inform me about new updates and features ›
#  style: alert
permalink: /index.html
---
{% comment %}
<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
{% endcomment %}
