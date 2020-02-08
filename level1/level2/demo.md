---
cats:
  - name: Whiskers
    breed: Persian
  - name: Claude
    breed: Tabby
dogsx:
  - name: Dasher
    breed: Whippet
  - name: Maisey
    breed: Treeing Walker Coonhound
  - name: Ramsey
    breed: Native American Indian Dog
  - name: Oscar
    breed: German Shorthaired Pointer
layout: layout.njk
---

# Pets

## Dogs

{% for dog in dogs %}
{{dog.name}} is a {{dog.breed}}.
{% endfor %}

## Cats

{% for cat in cats %}
{{cat.name}} is a {{cat.breed}}.
{% endfor %}
