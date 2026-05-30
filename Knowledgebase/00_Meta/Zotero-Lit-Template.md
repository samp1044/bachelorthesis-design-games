---
title: "{{title}}"
author: {% for creator in creators %}{{creator.firstName}} {{creator.lastName}}{% if not loop.last %}, {% endif %}{% endfor %}
year: {{date | format("YYYY")}}
conference: "{{publicationTitle}}"
citekey: {{citekey}}
---

# {{title}} ({{date | format("YYYY")}})



---
**Verknüpfte Konzepte:**
* 
