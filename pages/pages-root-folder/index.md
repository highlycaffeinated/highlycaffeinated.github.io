---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header_bike_road_horizon.jpg
widget1:
  title: "Blog"
  url: '/blog/'
  image: widget-1-302x182.jpg
  text: "Wherein you'll find my writings, such as ride reports, gear reviews, and random thoughts about whatever's front of mind." 
widget2:
  title: "Photos"
  url: '/photos/'
  image: widget-1-302x182.jpg
  text: "Some of my pictures and links back to the primary sources."
widget3:
  title: "Musings"
  url: '/musings/'
  image: widget-github-303x182.jpg
  text: "Links, quotes, and other shorter form items that have caught my attention."
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
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
