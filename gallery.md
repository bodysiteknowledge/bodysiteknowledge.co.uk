---
images:
  - slug: "women-in-conversation-1-spirit"
    title: "Women in Conversation 1 - Spirit, 2020"

  - slug: "women-in-conversation-II-sentient"
    title: "Women in Conversation II Sentient, 2021"

  - slug: "interdepence-I-on-being"
    title: "Interdepence I - On Being, 2020"

  - slug: "interdepence II"
    title: "Interdepence II, 2021"

  - slug: "its-a-process-interdepence-III"
    title: "It‘s a Process Interdepence III, 2021"

  - slug: "focus-a-sense-of-coherence"
    title: "Focus a Sense of Coherence, 2022"

  - slug: "kinship-women-in-conversation-III"
    title: "Kinship Women in Conversation III, 2022"

  - slug: "mosses-and-waterbears"
    title: "Mosses and Waterbears, 2021"

  - slug: "light-language-I"
    title: "Light Language I, 2021"

  - slug: "salutogenic-orientation"
    title: "Salutogenic Orientation, 2021"

  - slug: "dancers-and-development"
    title: "Dancers and Development, 2022"

  - slug: "there-to-be-close-to-her"
    title: "There to be close to her, 2021"

  - slug: "cosmic-consciousness"
    title: "Cosmic Consciousness, 2022"

  - slug: "day"
    title: "Day, 2022"

  - slug: "night"
    title: "Night, 2022"
---

# Gallery

{% for image in page.images %}
![{{image.title}}](images/gallery/{{image.slug}}.jpg)
{{ image.title }}

<hr>
{% endfor %}
