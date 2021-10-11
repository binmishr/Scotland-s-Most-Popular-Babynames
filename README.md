# Scotland-s-Most-Popular-Babynames

The details of the codeset and plots are included in the attached Adobe Acrobat reader (.pdf) file in this repository. 
You need to download the same to view the contents. There are referrals to other contents in BLUE colour also to follow.

A Brief Introduction
=====================

Recently seen this great post on Nathan Yau’s FlowingData website which guesses a person’s name based on what the name starts with. It also needs you to select a gender and a decade for when you were born before it can guess. Of course, it isn’t really a guess and is really just based on proportions calculated after restricting the data to what has been selected.

It uses data from the Social Security Administration in America so results more specifically apply to the US. it’d be cool to see how it looks for Scottish data which is available from the National Records of Scotland (NRS). I’ve embedded the Shiny app below into an iframe but you can view the app in it’s own page by going to https://alan-y.shinyapps.io/name_guess. It used a little bit of css to make the iframe responsive (resizes based on the amount of screen/window space available). The app is hosted on shinyapps.io on a free account so if nobody visits it for a while, it will no longer be available (unless I restart it). So apologies if you happen to visit this page further down the line and it’s not working!

The R code I used to download and wrangle the data as well as create the Shiny app is provided further down the page. Hope the app is interesting to some people and my acknowledgements again, to Nathan Yau as this is clearly based off his work.
