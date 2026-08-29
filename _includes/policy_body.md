{% assign policy = include.policy_data %}

# {{ policy.title | replace: '%1$s', 'PhoneTonic' }}

**{{ policy.last_updated_label | replace: '%1$s', policy.last_updated_date }}**

{% for block in policy.blocks %}
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
