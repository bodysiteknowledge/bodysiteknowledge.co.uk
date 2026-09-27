---
images:
  - slug: "women-in-conversation-1-spirit"
    title: "Women in Conversation 1 - Spirit, egg tempera on Fabriano, 2020. 150 x 150 cm"

  - slug: "women-in-conversation-II-sentient"
    title: "Women in Conversation II Sentient, egg tempera on Fabriano, 2021. 150 x 150 cm"

  - slug: "interdependence -I-on-being"
    title: "Interdependence I - On Being, egg tempera on Fabriano, 2020. 150 x 150 cm"

  - slug: "interdependence II"
    title: "Interdependence II, egg tempera on Fabriano, 2021. 150 x 150 cm"

  - slug: "its-a-process-interdependence -III"
    title: "It‘s a Process Interdependence III, egg tempera on Fabriano, 2021. 150 x 150 cm"

  - slug: "focus-a-sense-of-coherence"
    title: "Focus a Sense of Coherence, egg tempera on Fabriano, 2022. 150 x 150 cm"

  - slug: "kinship-women-in-conversation-III"
    title: "Kinship Women in Conversation III, egg tempera on Fabriano, 2022. 150 x 150 cm"

  - slug: "mosses-and-waterbears"
    title: "Mosses and Waterbears, egg tempera on Fabriano, 2021. 150 x 150 cm"

  - slug: "light-language-I"
    title: "Light Language I, egg tempera on Fabriano, 2021. 150 x 150 cm"

  - slug: "salutogenic-orientation"
    title: "Salutogenic Orientation, egg tempera on Fabriano, 2021. 150 x 150 cm"

  - slug: "dancers-and-development"
    title: "Dancers and Development, egg tempera on Fabriano, 2022. 150 x 150 cm"

  - slug: "there-to-be-close-to-her"
    title: "There to be close to her, egg tempera on Fabriano, 2021. 150 x 150 cm"

  - slug: "cosmic-consciousness"
    title: "Cosmic Consciousness, egg tempera on Fabriano, 2022. 150 x 150 cm"

  - slug: "day"
    title: "Day, egg tempera on Fabriano, 2022. 150 x 150 cm"

  - slug: "night"
    title: "Night, egg tempera on Fabriano, 2022. 150 x 150 cm"
---

# Gallery

{% for image in page.images %}
![{{image.title}}](images/gallery/{{image.slug}}.jpg)
{{ image.title }}

<hr>
{% endfor %}
