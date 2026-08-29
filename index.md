---
layout: default
title: "PhoneTonic Privacy Policy"
description: "Privacy Policy for the PhoneTonic Android application"
---

# {{ site.data.policy.en.title | replace: '%1$s', 'PhoneTonic' }}

**{{ site.data.policy.en.last_updated_label | replace: '%1$s', site.data.policy.en.last_updated_date }}**

{% for block in site.data.policy.en.blocks %}
{% if block.type == 'section_title' %}
## {{ block.text | replace: '%1$s', 'PhoneTonic' }}
{% elsif block.type == 'subsection_title' %}
### {{ block.text | replace: '%1$s', 'PhoneTonic' }}
{% elsif block.type == 'paragraph' %}
{{ block.text | replace: '%1$s', 'PhoneTonic' }}
{% elsif block.type == 'bullet_list' %}
{% for item in block.items %}
- {{ item | replace: '%1$s', 'PhoneTonic' }}
{% endfor %}
{% elsif block.type == 'email_link' %}
**{{ block.label }}:** [{{ block.email }}](mailto:{{ block.email }})
{% endif %}
{% endfor %}
