---
title: Science & Environment
date: 2017-08-02 20:43:00 -07:00
layout: post
---

### Actions

Please join our team in taking action to protect our environment and stand up for science!

{% assign curDate = site.time | date: '%s' %}
{% assign sortedActions = (site.categories.action | sort: 'event-end-date') %}
{% assign filteredActions = (site.categories.action | sort: 'event-end-date') %}
{% for post in sortedActions %}
  {% if post.tags contains 'environment' %}
    {% assign postEndDate = post.event-end-date | date: '%s' %}
    {% if postEndDate >= curDate %}
      {% include post-list.html %}
    {% endif %}
  {% endif %}
{% endfor %}

----

### Mission Statement
 
Our mission is to resist the agenda of the Trump administration and promote an agenda that protects the environment and the role of science in society by affecting change through the political system at all levels of government. We care about all aspects of the environment and science, including but not limited to climate change, pollution, science denial, endangered species, and public lands.
 
Our group focuses on actions. We meet, discuss, conduct research, and inform each other always with the aim of coordinating and taking actions that will have maximum impact. Members can influence the focus of our group by taking the initiative to organize actions affecting topics they care about. We believe that actions taken collectively are far more impactful than actions taken individually, and so we believe in a deliberate and efficient process for acting as a group. We maximize our impact by providing clear directions for action to all members of our group and to all Indivisible Berkeley members.
 
----

### Team Information
 
Please check the [calendar page](/calendar) to find the time and location of our next team meeting!
 
Join our email list by sending a blank email to [environment+subscribe@indivisibleberkeley.org][mailtoenv] from the address you wish to subscribe.
 
If you have questions about our team, email [environment+owner@indivisibleberkeley.org][mailtoenvowner].  You can find us in the [#science_environment channel][scienvchannel] in the [IB Slack][ibslack].

----

### Attacks on Environmental Regulations
 
Please see our **[Overview on Environmental Regulations](https://www.indivisibleberkeley.org/environment/environmentalregs/)** for a summary of what's under attack!
 
 
[mailtoenv]: mailto:environment+subscribe@indivisibleberkeley.org
[mailtoenvowner]: mailto:environment+owner@indivisibleberkeley.org
[hsgac]: https://www.hsgac.senate.gov/contact
[feinstein]: https://www.feinstein.senate.gov/public/index.cfm/e-mail-me
[harris]: https://www.harris.senate.gov/content/contact-senator
[lee]: https://lee.house.gov/contact/email-me
[desaulnier]: https://desaulnier.house.gov/contact/email
[calendar]: https://www.indivisibleberkeley.org/calendar
[scienvchannel]: https://indivisible-berkeley.slack.com/messages/science_environment/
[ibslack]: /slack
[findsenator]: https://www.senate.gov/senators/contact/
[findrepresentative]: http://www.house.gov/representatives/find/