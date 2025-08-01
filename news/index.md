---
title: News 
---


# 📰 Newsss
{% assign news_items = site.categories.news | sort: "date" | reverse %}
{% for post in news_items %}
  ... render news ...
{% endfor %}

---

# 🎉 Events
{% assign event_items = site.categories.blog | sort: "date" | reverse %}
{% for post in event_items %}
  ... render event ...
{% endfor %}
