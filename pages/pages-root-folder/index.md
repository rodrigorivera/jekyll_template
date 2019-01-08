---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header_mlss-skoltech.jpg
widget1:
  title: "Machine Learning Summer School"
  url: 'http://mlss.cc'
  image: banner_mlss.jpg
  text: 'The Machine Learning Summer School (MLSS) will be held at Skoltech in Moscow, Russia, from Aug. 26 to Sep. 6, 2019. 
  The MLSS presents topics at the core of modern machine learning, from fundamentals to state-of-the-art practice.  
  It is offered mostly to PhD students, but also to researchers and professionals. 
  Its speakers are leading experts in their respective field and/or world-recognized professionals from the industry.' 
widget2:
  title: "Skoltech"
  url: 'http://www.skoltech.ru'
  image: banner_skoltech.jpg
  text: 'Skoltech is a leading research university founded by a collaboration of nine Russian institutions and organizations in collaboration with the Massachusetts Institute of Technology (MIT)'
widget3:
  title: "Moscow"
  url: '/venue/'
  image: banner_moscow.jpg
  text: 'Moscow is the capital and the largest city of Russia. It lies on the river Moskva, in the west of the country. 
  Moscow has a modern infrastructure, but has preserved the look and feel of its historic neighbourhoods. 
  Its landmarks include the Red Square; the Opera House; the Gorky Park; VDNH; and the Tretyakov gallery'

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
  url: /application
  text: Apply now ›
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---
