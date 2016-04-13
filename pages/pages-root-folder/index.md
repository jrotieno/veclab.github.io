---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: kilifi-1.jpg
  title: VECLab

widget3:
  title: "More about us"
  url: '/about/'
  text: 'Who we are!'

widget2:
  title: "Peer reviewed papers"
  url: '/publications/'
  text: 'Read our recent articles'

widget1:
  title: "Projects and Studies"
  url: '/projects/'
  text: 'Our projects & studies'

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

{% include alert warning="This website is work in progress!" %}
<h1>Virus Epidemiology and Control Research Group</h1>

</div>

We are based at the <strong>KEMRI-Wellcome Trust Research Programme</strong> in Kenya and we conduct intensive and long-term surveillance of viral pathogens. We apply a range of approaches that include; molecular, immunological, bioinformatics, social, electronic, and modelling tools.
<hr>
