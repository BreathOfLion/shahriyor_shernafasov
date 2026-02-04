---
layout: list
title: Ideas
subtitle: "My notes, articles, and thoughts."
---

{% assign page = page %}
{% assign page = page | merge: {"collection_to_list": site.ideas | reverse } %}

