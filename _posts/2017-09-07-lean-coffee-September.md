---
layout: post
title: "Lean Coffee - September"
categories: events leancoffee
event:
  facebook-id: 
  eventbrite-id: lean-coffee-september-2017-tickets-37829901253
  date: 2017-09-21
  time: 7:00 AM to 8:30 AM

  presenter:
    name: 
    title: 
    bio:

  location:
    name: Machine Shed Restaurant 
    address: 11151 Hickman Road
    citystatezip: Urbandale, IA 50322
    instructions: 

  description: 
  slides: 

---
**{{page.event.date | date: "%A, %B %-d, %Y" }} from
 {{page.event.time}}**
{% if page.event.slides %}
  **Download the slides:**
  [{{page.event.slides}}](p/{{page.event.slides}})
{% endif %}

**Location**  
{{page.event.location.name}}  
{{page.event.location.address}}  
{{page.event.location.citystatezip}}  

{% if page.event.location.instructions %}
  *Additional instructions*: 
  {{page.event.location.instructions}}
{% endif %}

{% if page.event.eventbrite-id %}
<a class="btn" title="EventBrite Registration"  href="http://www.eventbrite.com/e/{{page.event.eventbrite-id}}" target="_blank" data-eventdate="{{page.event.date | date: '%D'}}">Register on EventBrite</a>
{% endif %}

**Description**  
 The format of this meeting is simple:

  - Show up
  - Order breakfast (optional)
  - Suggest topics
  - Vote on topics
  - Discuss topics with the most votes

I hope to see you there!

{{page.event.description | markdownify}}

{% if page.event.eventbrite-id %}
<a class="btn" title="EventBrite Registration" href="http://www.eventbrite.com/e/{{page.event.eventbrite-id}}" target="_blank">Register on EventBrite</a>
{% endif %}
