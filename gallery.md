---
images:
  - slug: "women-in-conversation-1-spirit"
    title: "Women in Conversation 1 - Spirit, egg tempera on Fabriano, 2020"

  - slug: "women-in-conversation-II-sentient"
    title: "Women in Conversation II Sentient, egg tempera on Fabriano, 2021"

  - slug: "interdepence-I-on-being"
    title: "Interdepence I - On Being, egg tempera on Fabriano, 2020"

  - slug: "interdepence II"
    title: "Interdepence II, egg tempera on Fabriano, 2021"

  - slug: "its-a-process-interdepence-III"
    title: "It‘s a Process Interdepence III, egg tempera on Fabriano, 2021"

  - slug: "focus-a-sense-of-coherence"
    title: "Focus a Sense of Coherence, egg tempera on Fabriano, 2022"

  - slug: "kinship-women-in-conversation-III"
    title: "Kinship Women in Conversation III, egg tempera on Fabriano, 2022"

  - slug: "mosses-and-waterbears"
    title: "Mosses and Waterbears, egg tempera on Fabriano, 2021"

  - slug: "light-language-I"
    title: "Light Language I, egg tempera on Fabriano, 2021"

  - slug: "salutogenic-orientation"
    title: "Salutogenic Orientation, egg tempera on Fabriano, 2021"

  - slug: "dancers-and-development"
    title: "Dancers and Development, egg tempera on Fabriano, 2022"

  - slug: "there-to-be-close-to-her"
    title: "There to be close to her, egg tempera on Fabriano, 2021"

  - slug: "cosmic-consciousness"
    title: "Cosmic Consciousness, egg tempera on Fabriano, 2022"

  - slug: "day"
    title: "Day, egg tempera on Fabriano, 2022"

  - slug: "night"
    title: "Night, egg tempera on Fabriano, 2022"
---

# Gallery

{% for image in page.images %}
![{{image.title}}](images/gallery/{{image.slug}}.jpg)
{{ image.title }}

<hr>
{% endfor %}
