---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header_unsplush_9.jpg 

widget1:
  title: "Recent Articles"
  url: 'http://localhost:4000/blog/'
  text: 'Read our latest blog articles'

widget2:
  title: "Recent Papers"
  url: 'http://localhost:4000/publications/'
  text: 'Follow our latest papers and publications ...'

widget3:
  title: "Current Projects"
  url: 'http://localhost:4000/projects/'
  text: 'Current projects'

# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#
#icallforaction:
#  url: https://tinyletter.com/feeling-responsive
#  text:
#  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---
<hr>
<div>
<h6>The VecLab at KEMRI-Wellcome Trust Research Programme applies computational and statistical methods to sequence data to understand viral transmission and spread </h6>
</div>

