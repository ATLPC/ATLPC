{% assign footermenu = site.data.contact.details  %}
{% for item in footermenu %}|**{{ item.field }}**| {{ item.value }}|
{% endfor %}