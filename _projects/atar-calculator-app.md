---
layout: page
title: atar calculator app
description: ios app development  
img: assets/img/atar-icon.png
importance: 1
category: fun 
related_publications: true
---

In early March 2020 I had been living in Oxford for about two months but was essentially forced to come back to Australia by the pandemic (absolutely the right choice in hindsight). When I got back to Aus, I was caught up in the first round of hotel quarantine at the Crown hotel and casino in Melbourne. I didn't have much to do, so I decided to teach myself swift by building an iOS app. 

The app itself is pretty straightforward. It allows a user to predict their ATAR (Australian university entry score) based on their grades for each subject. It takes the score, fits them to a bell curve (data is available for previous years on the SACE website), and assigns an ATAR. 

It did better than I expected in that it got around 550 downloads, making about 110 USD in revenue. Unfortunately, it costs about 150 USD a year to list your app on the app store + advertising. I also lost interest in the project basically as soon as I got out of quarantine, so I let the app delist after the year expired. 

The analytics are somewhat interesting, mostly the peak in activity close to the end of the year when final exams are.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/atar-analytics.png" title="atar analytics" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    All time analytics for the app as of 19/01/25
</div>

