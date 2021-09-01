---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: RXGPUrig.jpg
widget1:
  title: "Polygon, Ethermine and Payday"
  url: 'https://how-to-mine-crypto.co.uk/PEP'
  image: poly.png
  text: 'Learn what is Polygon and how to use it to reduce Gas fees and get more £/€/$ when it comes to taking profit.'
widget2:
  title: "How to use Hive OS?"
  url: 'https://how-to-mine-crypto.co.uk/hive-os/'
  text: ' In this Post, we will walk you through installing Hive OS on a GPU rig, setting it up, and launching it. Besides, we will make a small overview of the rich functionality of Hive OS that allows us to easily manage both a huge and a small number of our ASICs or GPU rigs, or even single devices.'
  video: '<a href="#" data-reveal-id="videoModal"><img src="https://how-to-mine-crypto.co.uk/images/hiveos-logo.png" width="302" height="182" alt=""/></a>'
widget3:
  title: "Watt Power Supply Should I Use? - Power Supply Guide"
  url: 'https://how-to-mine-crypto.co.uk/power-supply-guide/'
  image: IMG_0009.jpg
  text: 'Deep dive into Power Supplies.. From how to spec a power supply for your rig and what to buy!'
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
  url: https://how-to-mine-crypto.co.uk
  text: Inform me about new updates and features ›
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
    <iframe width="1280" height="720" src="https://www.youtube.com/watch?v=GcBWdyCB-94" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
