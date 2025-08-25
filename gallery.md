---
images:
  - slug: "women-in-conversation-1-spirit"
    title: "Women in Conversation 1 - Spirit"

  - slug: "women-in-conversation-II-sentient"
    title: "Women in Conversation II Sentient"

  - slug: "interdepence-I-on-being"
    title: "Interdepence I - On Being"

  - slug: "interdepence II"
    title: "Interdepence II"

  - slug: "its-a-process-interdepence-III"
    title: "It‘s a Process Interdepence III"

  - slug: "focus-a-sense-of-coherence"
    title: "Focus a Sense of Coherence"

  - slug: "kinship-women-in-conversation-III"
    title: "Kinship Women in Conversation III"

  - slug: "mosses-and-waterbears"
    title: "Mosses and Waterbears"

  - slug: "light-language-I"
    title: "Light Language I"

  - slug: "salutogenic-orientation"
    title: "Salutogenic Orientation"

  - slug: "dancers-and-development"
    title: "Dancers and Development"

  - slug: "there-to-be-close-to-her"
    title: "There to be close to her"

  - slug: "cosmic-consciousness"
    title: "Cosmic Consciousness"

  - slug: "day"
    title: "Day"

  - slug: "night"
    title: "Night"
---

# Gallery

{% for image in page.images %}
![{{image.title}}](images/gallery/{{image.slug}}.jpg)
{{ image.title }}

<hr>
{% endfor %}
